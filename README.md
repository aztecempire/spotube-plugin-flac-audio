# Spotube FLAC Audio Plugin

An audio source plugin for [Spotube](https://spotube.cc) that downloads and streams music in **FLAC lossless** and **MP3 320kbps** via flacdownloader.com.

## Features

- Search songs by title
- **FLAC** streaming (lossless, 1411 kbps)
- **MP3** streaming (lossy, 320 kbps)
- Spotube plugin format (`.smplug`)

## Installation

1. Download the `plugin.smplug` file from [Releases](https://github.com/aztecempire/spotube-plugin-flac-audio/releases)
2. Open Spotube → Settings → Plugins → Install plugin
3. Select the downloaded `.smplug` file
4. The plugin will appear as an available audio source

## Build from source

**Requirements:**
- [Dart SDK](https://dart.dev/get-dart)
- Hetu Script (`dart pub global activate hetu`)

```bash
git clone https://github.com/aztecempire/spotube-plugin-flac-audio.git
cd spotube-plugin-flac-audio
make compile
make archive
```

The packaged plugin will be at `build/plugin.smplug`.

## Disclaimer

**THIS SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT.**

Use this plugin **at your own risk**. The developer is not responsible for:

- Any use made of this software
- Compliance with applicable intellectual property and copyright laws in your jurisdiction
- Any claims, damages, or losses arising from the use of this plugin
- The availability or legality of the flacdownloader.com service

This plugin is for **educational and research purposes only**. It should not be used to infringe copyright. Check your local laws before using this software.

**We are not affiliated, endorsed, or sponsored by** Deezer, flacdownloader.com, Spotube, or any other mentioned entity.

## License

[MIT](LICENSE)
