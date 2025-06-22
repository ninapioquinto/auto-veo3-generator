# Auto Veo 3 Generator

This automation blueprint integrates Anthropic’s Claude AI with Airtable and FAL’s Veo 3 video generation API to create cinematic short video scenes from storytelling prompts. All fully automated through n8n.

---

##  Overview

The **Auto Veo 3 Generator** is designed to:
- Automatically generate immersive, first-person cinematic prompts.
- Use Claude AI to create raw, documentary-style storytelling scenes.
- Submit prompts to FAL’s Veo 3 video engine for video generation.
- Store and update prompt and output data within Airtable.
- Seamlessly manage the workflow using n8n's no-code automation engine.

---

##  Use Case

This flow is perfect for:
- AI-generated storytelling content pipelines
- Creators looking to automate scene ideation and generation
- Visual prototyping for cinematic ideas
- Batch content creation for reels, TikToks, or short films
- Research or experimentation with prompt-to-video automation

---

##  Integrations

- **Anthropic Claude 3.7 Sonnet (via n8n LangChain node)**
- **Airtable (Prompt Storage + Output Logging)**
- **FAL Veo 3 API (Text-to-Video Generation)**
- **n8n (Automation Orchestration)**

---

##  Features

- Cinematic storytelling prompt generation
- Claude AI system message customization
- Airtable contact table integration
- Auto-scheduling via `Schedule Trigger`
- Real-time video generation via FAL Veo 3 API
- Output handling and Airtable updates
- Smart delay with `Wait` node until video is ready
- No-code, fully visual flow via n8n

---

##  File Contents

- `Auto-Veo3-Generator.json`

---

##  Setup Notes

1. **Claude API Access**: Make sure you have valid Anthropic API credentials.
2. **FAL Account**: Get a FAL API key and ensure your endpoint is correct (`/fal-ai/veo3`).
3. **Airtable**: Create a table with fields: `Prompt`, `Status`, and `Final Output`.
4. **Import to n8n**:
   - Go to your n8n instance.
   - Import the `Auto Veo 3 Generator.json` file.
   - Connect your credentials: Claude, Airtable, and HTTP Auth for FAL.
5. **Schedule the Flow** as needed using the `Schedule Trigger` node.

---

##  Created by Nina Pioquinto

Automation Systems Engineer  
Helping creators and teams build smart, scalable content systems using AI automation and visual workflows.

> Let’s build your custom system
