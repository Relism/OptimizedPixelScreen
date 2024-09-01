# OptimizedPixelScreen

![Showcase](https://raw.githubusercontent.com/Relism/OptimizedPixelScreen/main/assets/showcase.gif)

OptimizedPixelScreen is a Minecraft plugin/mod designed to run on Bukkit and its forks, as well as Fabric. It is a platform-independent video-to-Minecraft animation converter that utilizes a pixel-differential algorithm to efficiently store and play animations. The focus is on minimizing filesystem space usage and reducing computational power during playback.

## Features

- **Pixel-Differential Algorithm:** Only stores the changed pixels between frames, drastically reducing resource requirements.
- **.ops Filetype:** Uses a proprietary `.ops` filetype, designed for optimized storage and playback of Minecraft animations.
- **Converter and Reader:** Convert videos to the `.ops` format and play any `.ops` file directly in Minecraft.

## How It Works

1. **Conversion:** OptimizedPixelScreen analyzes each frame of the video and identifies pixels that have changed from the previous frame. Only these changes are stored in the `.ops` file.
2. **Playback:** During playback, the reader reconstructs each frame by applying the stored pixel differences, ensuring smooth and efficient animation rendering in Minecraft.

## To-Do List

- [ ] Implement a GUI for easier file conversion in-game.
- [ ] Add support for additional video formats.
- [ ] Improve the pixel-differential algorithm for better compression rates.
- [ ] Optimize playback performance for low-end devices.
- [ ] Add error handling for unsupported video formats.
- [ ] Implement batch conversion functionality.
- [ ] Make actual documentation lol.
- [ ] Add compatibility with a wider range of Minecraft versions.