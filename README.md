# Araz: Voice

**Talk to Araz. It answers.**

Araz: Voice is a free, client-side add-on for **[Araz (The Anomaly)](https://www.curseforge.com/minecraft/mc-mods/araz-the-anomaly)**, the Minecraft horror mod whose creature learns how you play. With this add-on you can speak to it with your microphone or in chat, and it speaks back.

## Download

Get the jar for your loader and Minecraft version from **[Releases](https://github.com/SpicesFire/ArazVoice/releases)** and put it in your `mods` folder next to Araz.

| Loader | Minecraft | File |
|---|---|---|
| Fabric | 26.3, 26.1.2, 1.21.10, 1.20.1 | `araz_voice-fabric-<mc>-<version>.jar` |
| Forge | 26.3, 1.20.1 | `araz_voice-forge-<mc>-<version>.jar` |
| NeoForge | 26.3, 1.21.1 | `araz_voice-neoforge-<mc>-<version>.jar` |

Also available on [CurseForge](https://www.curseforge.com/minecraft/mc-mods/araz-voice) and on the [Araz website](https://spicesfire.com/araz/#voice).

## Requirements
- **Araz (The Anomaly)** 1.0.0-beta.3 or newer
- **Fabric API** on Fabric
- **Client only**: install it on your own computer. Servers only need Araz.
- A microphone is optional; you can also type with `/arazvoice <message>`.

## How it works
- **Open mic:** just talk, no key to hold. Or hold **Y** to talk, or type.
- **With your own Groq or Gemini key** (both have free tiers), or a local **Ollama**, an AI model answers in character. It remembers you, comments on what it saw you do and can act: come closer, play a prank, put out your lights, leave, or attack.
- **Without a key** it answers with its own recorded lines.
- Settings: `/arazvoice`.

## Privacy
- Without a key nothing leaves your computer.
- With a key, what you say goes only to the service you chose (Groq, Google Gemini or ElevenLabs), with your key. With Ollama it stays on your computer.
- Keys are stored only in your local `config/araz_voice.json`. Audio is never written to disk.

## Links
- Araz website and guides: https://spicesfire.com/araz/
- Discord (bug reports, sightings): https://discord.gg/utuKpP7XCa

Made by SpicesFire. License: CC0-1.0.
