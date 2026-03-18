# Chronicle Engine

> "Give any creator the tools to build worlds in Unreal Engine 5 that were previously only possible for teams with years of experience and million-dollar budgets."

## What is Chronicle Engine?

Chronicle Engine is an AI-powered pipeline that lets anyone build professional, walkable Unreal Engine 5 environments using plain English — no coding required, no technical background needed.

You describe what you want. Chronicle Engine builds it inside UE5 in real time.

**"Build me a dark fantasy war room"** → walls, floor, war table, fireplace, and weapon rack appear in Unreal Engine 5 automatically.

## How It Works

1. **You describe** what you want in natural language
2. **Chronicle Engine** processes your request through a fine-tuned AI model trained specifically on UE5 knowledge
3. **Unreal Engine 5** builds it in real time through a direct socket connection

## Key Features

- **Natural language to UE5** — describe any environment, it gets built
- **Custom fine-tuned model** — trained on 3,375+ UE5 Blueprint instruction pairs
- **Image to UE5** — upload a reference image and Chronicle Engine builds it
- **Style vocabulary system** — Dark Fantasy, Medieval, Sci-Fi, Cyberpunk themes
- **Compounding intelligence** — every build session improves the model
- **No coding required** — built by a non-developer, for non-developers

## Who It's For

- Indie game developers who want to build faster
- Filmmakers and storytellers who want UE5 environments without the learning curve
- Educators and architects exploring real-time 3D visualization
- Anyone with a creative vision who has been locked out of UE5 by technical barriers

## Tech Stack

- **MCP Server** — custom Python server connecting Claude Desktop to UE5
- **UE5 Socket Listener** — Python script running inside Unreal Engine 5.7
- **Fine-tuned Llama 3.1 8B** — deployed on Together AI (chronicle-blueprint-v1)
- **Claude Vision** — image interpretation layer for reference image input

## Status

Functional alpha — actively building The Ledger, a dark fantasy D&D companion app, as the primary test environment.

## Open Source

Chronicle Engine is committed to open source release under MIT license. The MCP server, socket listener, training data pipeline, and style vocabulary system will all be publicly available for the UE5 community.

## Origin

This project started because someone wanted to play D&D online and couldn't find a game that felt right. One thing led to another. Now it controls Unreal Engine 5 with plain English.

Built entirely with AI tools by a solo developer with zero coding experience.

---

*"Not all legends are born. Some are written."*
