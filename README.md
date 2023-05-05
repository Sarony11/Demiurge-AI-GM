# Demiurge: Your personalized AI GM!

Unlock the potential of GPT-4 with Demiurge AI GM, a customizable prompt that delivers personalized RPG experiences for users who want to enjoy of rich solo-narrative experiences.

The original idea es from [@yupiop12](https://twitter.com/yupiop12) and this is [Mr. Ranedeer AI Tutor](https://github.com/JushBJJ/Mr.-Ranedeer-AI-Tutor) was his first idea which I encourage to follow because it is amazing.

## Table of Contents
- [Demiurge: Your personalized AI GM!](#demiurge-your-personalized-ai-gm)
  - [Table of Contents](#table-of-contents)
  - [Why Demiurge AI GM?](#why-mr-demiurge-ai-gm)
  - [Requirements and Compatibility](#requirements-and-compatibility)
    - [Recommended](#recommended)
    - [Not Recommended](#not-recommended)
  - [Quick Start Guide](#quick-start-guide)
- [Prompt Formats](#prompt-formats)
- [AI GM Personalization Options](#ai-gm-personalization-options)
  - [Commands](#commands)
  - [Detailed Documentation](#detailed-documentation)
- [Actual Challenges to Overcome](#actual-challenges-to-overcome)
- [Screenshots](#screenshots)

## Why Demiurge AI GM?

Demiurge AI GM allows you to:
- Adjust the duration of your RPG campaign to match your needs.
- Customize the setting, plot, protagonist arc and RPG system
- Create the ultimate AI GM tailored just for you

## Requirements and Compatibility

### Recommended
- ChatGPT Plus Subscription with GPT-4 or above models.

### Not Recommended
- Default and Legacy GPT-3.5
- GPT-4 API (It will be costly)

*Note: The compatibility with plugins for this prompt is currently unknown.

## Quick Start Guide

1. Visit [ChatGPT](https://chat.openai.com/chat)
2. Select the GPT-4 (or above) model
3. Copy and paste the contents of [demiurge-ai-gm.yaml](https://raw.githubusercontent.com/Sarony11/Demiurge-AI-GM/main/demiurge-ai-gm.yaml) into the prompt
4. Let Demiurge guide you through the configuration process
5. Start enjoying from a customized RPG solo-experience!

# Prompt Formats
Originally, Mr.-Ranedeer-AI-Tutor was written in `json` format. I have preffered to focus only on `yaml` format which costs ~1.4x less than the `json` format.

JSON Format: `4,267` tokens

YAML Format: `2,988` tokens

# AI GM Personalization Options

This section outlines the various configuration options available to students using the AI GM. These options can be modified to customize the learning experience.

| Configuration | Options | 
|---|---|
| Setting | Forgotten Realms<br>Eberron<br>Vampire The Masquerade<br>Shadowrun<br>Call of Cthulhu<br>Warhammer Fantasy Roleplay<br>Star Wars<br>Cyberpunk 2020<br>Legend of the Five Rings<br>
| Plot Styles | Horror, Intrigue, Survival, Investigation, Personal, Exploration, Court, Dungeon Crawl, Adventure, Mistery |
| Protagonist Arcs | Positive Arc, Negative Arc, Flat Arc, Disillusionment Arc, Fall and Redemption Arc, Transformation Arc |
| Narrative Styles | Comedic, Dark, Epic, Noir, Pulp, Romantic, Surreal, Tragic |
| RPG Systems* | Fate Core System, Powered by the Apocalypse, Forged in the Dark, Gumshoe, Narrative Dice System, Storyteller System, Amber Diceless, Amberian Nights |
| Duration | One-Shot, Short-Term, Medium-Term, Long-Term, Open-Ended|
*Working in progress

## Commands

The AI GM supports the following commands:

- `/test`: Request a test to assess your knowledge and understanding.
- `/config`: Update your AI GM configuration/preferences.
- `/create`: Create a full RPG campaign based on your preferences.
- `/character`: Starts a process to create a relevant character for the RPG campaign.
- `/search`: Search for specific information (*requires plugins*).
- `/start`: Start the RPG campaign.
- `/stop`: Stop the RPG campaign plan.
- `/continue`: Continue the output if it was cut.

*The search command requires plugins.


## Detailed Documentation

Find detailed documentation for Demiurge AI GM in the [docs.md](https://raw.githubusercontent.com/Sarony11/Demiurge-AI-GM/main/docs.md) file.

# Actual Challenges to Overcome
- **4001 token limit:** to increase the prompt. At this moment, it is needed to remove some options from the configuration to be inside this limit and paste the prompt directly on ChatGPT.
- **RPG system functionality not working:** For now all test have shown that there is not consistency on RPG system implementation. Prompt has to be improved for that.
- **Character creation:** Although some kind of character creation process is implemented though `/character` it is not enough consistent, but trying to improve it I faced 4001 token limit.

# Screenshots


