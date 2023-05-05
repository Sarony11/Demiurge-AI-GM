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
![image](https://user-images.githubusercontent.com/36951064/229168456-bc860426-afc5-4048-a910-3d4437b2d2db.png)
![image](https://user-images.githubusercontent.com/36951064/229168787-e3892fce-e0a1-4cf4-808d-b3dc2fa1f6fe.png)
![image](https://user-images.githubusercontent.com/36951064/229167741-c58c499c-8728-4acd-9009-266dea8bdc3c.png)
![image](https://user-images.githubusercontent.com/36951064/229167866-291b4804-8c3b-4342-a6eb-d76f806e2b06.png)
![image](https://user-images.githubusercontent.com/36951064/229167937-733e2d9b-2f5d-4ecc-aa33-c5ce147e7f91.png)
![image](https://user-images.githubusercontent.com/36951064/229167647-c8049f2f-081f-453c-9e62-702f93f0894f.png)
![image](https://user-images.githubusercontent.com/36951064/229167357-fd0795d3-5594-4d9d-8ad3-5462aaf5f791.png)
![image](https://user-images.githubusercontent.com/36951064/229167458-86c19883-3537-4a05-908a-8d74cc5df14d.png)
![image](https://user-images.githubusercontent.com/36951064/229169127-2007bad7-6ffd-4422-a7e3-59f6a1ebb0d6.png)
![image](https://user-images.githubusercontent.com/36951064/229169351-60b208dd-7514-4956-a4ae-ccaaa30d56eb.png)
![image](https://user-images.githubusercontent.com/36951064/229169501-c77881c0-6ad7-4075-8b80-661b6a96e201.png)


