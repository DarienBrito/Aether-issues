# Aether — Issue Tracker

This repository is the public issue tracker for **Aether**, a shared memory audio bridge plugin for DAWs and TouchDesigner.

Aether is a VST3 (Windows) / AudioUnit (macOS) plugin that streams real-time audio from your DAW to TouchDesigner via shared memory. Drop it on any track and your audio is instantly available as a Shared Mem In CHOP.

## Reporting a bug

Please use the **Bug Report** template and include:

- Your OS, DAW, and TouchDesigner version
- The Aether version you're using
- Steps to reproduce the issue
- Any relevant screenshots or logs

## Requesting a feature

Use the **Feature Request** template to suggest improvements. Describe the problem you're solving and how you imagine it working.

## Quick setup reference

1. Install the plugin to your system's VST3 or AudioUnit folder
2. Load **Aether** as an audio effect on any track in your DAW
3. Set a **stream name** (or keep `default`)
4. In TouchDesigner, add a **Shared Mem In CHOP** and set **Segment Name** to match
5. Play audio — it appears in TD instantly

| Setting | Options | Default |
|---------|---------|---------|
| Stream  | Any name | `default` |
| Buffer  | 512 / 1024 / 2048 frames | 512 |
| Channel | Stereo / Mono L / Mono R / Mono Mix | Stereo |

## Links

- [Get Aether](https://darienbrito.gumroad.com/l/aether) (Gumroad)

## Note

This repository contains no source code. It exists solely for community bug reports and feature requests.
