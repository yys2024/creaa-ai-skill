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

---

# Creaa AI - OpenClaw 技能

通过 [Creaa](https://creaa.ai) API，在终端中直接生成和编辑 AI 图片、生成 AI 视频。

## 功能

- **AI 生图**: 支持 5 个图片模型 (Seedream 4.5、Nano Banana 2/Pro、GPT Image 1.5、Z-Image Turbo)
- **AI 图片编辑**: 单图编辑和多图合成
- **AI 视频生成**: 文生视频和图生视频，支持 8 个视频模型 (Veo 3.1、Seedance 2.0、Sora 2 Pro、Kling 3.0 等)

## 安装

### OpenClaw 用户

下载 `SKILL.md` 到技能目录：

```bash
mkdir -p ~/.openclaw/skills/creaa-ai
curl -o ~/.openclaw/skills/creaa-ai/SKILL.md https://raw.githubusercontent.com/yys2024/creaa-ai-skill/main/SKILL.md
```

或 clone 本仓库：

```bash
git clone https://github.com/yys2024/creaa-ai-skill.git ~/.openclaw/skills/creaa-ai
```

### 配置

1. 在 https://creaa.ai/profile -> API Keys 获取 API Key
2. 设置环境变量：
   ```bash
   export CREAA_API_KEY="ck_你的API密钥"
   ```

## 使用

安装完成后，在 OpenClaw 中使用 `/creaa-ai` 命令即可生成图片和视频。

## 链接

- 官网: https://creaa.ai
- 充值积分: https://creaa.ai/pricing
