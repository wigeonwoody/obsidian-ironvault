*This note's text is taken directly from 'The complete guide to Solo Roleplaying With AI' from Oracle RPG (oraclerpg.com).*
```table-of-contents
title: Contents
style: nestedList # TOC style (nestedList|nestedOrderedList|inlineFirstLevel)
minLevel: 1 # Include headings from the specified level
maxLevel: 6 # Include headings up to the specified level
include: 
exclude: 
includeLinks: true # Make headings clickable
hideWhenEmpty: false # Hide TOC if no headings are found
debugInConsole: false # Print debug info in Obsidian console
```

## Solo play outline
Free-form solo games are extremely varied, because of their procedural nature. Due to solo roleplaying's unpredictability, there are many possible stories that can emerge. However, the solo games in this guide generally follow the same basic pattern:

- **The player prompts AI to create a text-based virtual world.** The player uses the campaign prompts in this guide to create an interactive text adventure created by AI.
- **The player interacts with the world created by AI.** AI roleplaying games act like virtual worlds made form text. You can interact with this virtual world by telling the AI what you want to do. The AI will then respond to your actions.
- **The player uses their rulebooks as an engine for gameplay.** Rulebooks and supplements provide the framework for what you can and cannot do in the game. Your core rulebooks not only provide the rules for combat, but also tell you how to use your character's skills during play.

# The Basics
AI is the most revolutionary tool for solo roleplaying. It is by far the most versatile and can generate endless content for an adventure. It's also fairly easy to set up.

The role of AI in solo play is to:
- Provide interactive descriptions of what the player experiences in-game.
- Enable conversations with NPCs.
- Generate environments to explore.
- Tie everything together to create plot.

## Important things to remember about AI roleplaying

***The AI uses a question and answer format***
This means that in order for the AI to work correctly, you must always ask it a clear question or ask it to describe something to you. If you don't ask the AI a question, it may act on your character's behalf during a scene. Whenever you take an action in the game, ask the AI for a description. Common questions to ask the AI include "What do I see?", "What does she say to me?", "What does it look like?", or "Describe it to me". ==Always ask a question or request a description; this cannot be stressed enough.== The only exception is during dialogue.

***Be as clear as possible***
Whenever you ask questions from the AI or engage in dialogue, be as clear and unambiguous as possible. When talking to NPCs, direct your conversations at them. Clearly indicate who you are talking to during dialogue to prevent misunderstandings. Whenever possible, use the correct punctuation during the dialogue to show you're talking to an NPC.

***The AI makes mistakes***
Due to AI token reference limits as well as other factors, the AI may make tiny mistakes during a game. This is a broader issue in AI design that also impacts roleplaying.

***Practice caution when instructing the AI or using suggested replies***
The AI is quite easy to break with the wrong instructions. Even seemingly minor changes in a prompt or custom instruction can have unintended effects. Whenever the AI behaves strangely, make sure your custom instructions are typed correctly and that the prompt you're using is clearly worded. Furthermore, be cautious of AI's suggested replies. These are not always the best option and can break the game if used incorrectly.

***Don't use the AI to generate loot***
AI is not precise enough to generate loot in a satisfying way. Whenever you need to buy an item, loot an opponent, or receive a quest reward, refer to the other tables in your campaign's rulebook instead of relying on the AI. The only exception to this rule is for quest items.

# Prompts
In this final part of the guide, a prompt template that you can mod, hack, and adapt to the campaign setting of your choice has been included. To use this template, create a new note in the `Copilot/Prompts` folder and fill in the ==highlighted== fields with the resources that the AI should reference when creating your text adventure, then use the `/` key in the Copilot Prompt field to select your new prompt.

For best results, use novels, lore-heavy video games, and well-known television/streaming series. These types of entertainment often contain high quality writing that the AI can emulate. The more information that's available for the AI to reference, the better.

Choosing a campaign setting is only one part of the AI roleplaying, the other part is telling the AI how to write the adventure in an entertaining way. The simplest method is to tell the AI to emulate a famous author in your campaign setting's genre. For example, you can tell the AI to write your fantasy adventure in the style of Robert E. Howard, or J.R.R. Tolkein.



## Managing AI's memory during a playthrough
At the time of this writing, ChatGPT 4.1 can reference around 20,000-25,000 worlds before the context is truncated and the AI begins to forget details about your adventure. As the adventure continues, the AI will forget more and more details resulting in errors that harm the playing experience. To counteract this, the player needs to be mindful of this limitation and play around it. There are three useful strategies for managing memory.

1. **Don't use the AI to administrate the rules**
   Administrating the rules of your TTRPG should be done externally by the player, not the AI. This prevents the AI from consuming memory that can be used for worldbuilding.
2. **Refresh the AI's memory at regular intervals**
   Use the following prompt at regular intervals to "save" your game. When this prompt is entered into the chat box, the AI will create a summary of everything that happened to you, as well as all the important NPCs you've met. this synopsis keeps the important details of your adventure in the AI's memory thereby effectively saving your game. After the AI has created the summary, you can continue normally.

   > Create an accurate, detailed summary of everything that has happened thus far as well as all the characters I have met.

3. **Use AI's memorization feature**
   To save specific details, use the AI's memorization feature. This method can be used alongside memory refreshing to assist AI in remembering the finer details in your adventure. If something important happens, tell the AI to remember that detail and it will remember it. Examples include:
   - "Remember this conversation."
   - "Remember this character."
   - "Remember this event."

---

# Campaign Prompt Template

> Assume the role of an expert ==Insert Genre== writer that specializes in interactive fiction, as well as the story line, quests, characters and character description, locations, descriptions, groups and organizations, stories, events, and magical objects/technology of ==Insert My Campaign Setting==. The adventure takes place in ==Insert My Campaign Setting's location==.
> Describe everything that follows in the present tense, in response to what I type, while strictly and accurately adhering to the established lore, descriptions, monsters and enemies, events and magical objects/technology of ==Insert Campaign Setting==, and written in the descriptive style of ==Insert Author==. Provide names for characters, locations, groups and organizations, events, and magical objects/technology. Characters should always use dialogue, enclosed in quotation marks when speaking, addressing, or interacting with me, written in the conversational style of ==Insert Author==. Do not type, compose, dictate, influence, script, generate, control, or describe what I am doing, saying, acting, behaving, thinking, feeling, experiencing, or any other aspect concerning me throughout the entire adventure, scenario, story, location, quest, mission, scene, event, description, dialogue, and conversation. Keep all responses to 80 words or less.
> Begin when I tell you to start.