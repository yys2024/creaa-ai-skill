# Creaa AI - OpenClaw Skill

Generate and edit AI images, plus generate AI videos directly from your terminal using the [Creaa](https://creaa.ai) API.

## Features

- **Image Generation**: Text-to-image with 5 AI models (Seedream 4.5, Nano Banana 2/Pro, GPT Image 1.5, Z-Image Turbo)
- **Image Editing**: Single-image edit and multi-image composition
- **Video Generation**: Text-to-video and image-to-video with 8 AI models (Veo 3.1, Seedance 2.0, Sora 2 Pro, Kling 3.0, and more)

## Installation

### For OpenClaw users

Copy the `SKILL.md` file into your skills directory:

```bash
mkdir -p ~/.openclaw/skills/creaa-ai
curl -o ~/.openclaw/skills/creaa-ai/SKILL.md https://raw.githubusercontent.com/yys2024/creaa-ai-skill/main/SKILL.md
```

Or clone this repo:

```bash
git clone https://github.com/yys2024/creaa-ai-skill.git ~/.openclaw/skills/creaa-ai
```

### Setup

1. Get your API key at: https://creaa.ai/profile -> API Keys
2. Set the environment variable:
   ```bash
   export CREAA_API_KEY="ck_your_api_key_here"
   ```

## Usage

Once installed, use the `/creaa-ai` command in OpenClaw to generate images and videos.

## Links

- Website: https://creaa.ai
- API Credits: https://creaa.ai/pricing
