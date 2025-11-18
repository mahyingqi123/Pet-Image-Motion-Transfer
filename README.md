# Pet Image Motion Transfer Video Generator

## Overview

This tool generates videos from pet images using motion transfer technology, enabling users to create videos of their pets moving in specific ways without recording them directly. The ultimate goal is to project these videos into hologram boxes to create pet holograms.

It's also a tryout project to run a model on online platform like colab/kaggle to offload my laptop's resources.

## Project Components

The initial implementation is split into three main parts:

### 1. Comprehensive Pet Image Generator

- Generate a comprehensive pet image from multiple source images
- Most motion transfer models require a single, well-composed input image
- Single-image inputs often lack sufficient detail due to varying poses and angles
- Handles hidden or partially visible parts of the pet

### 2. Motion Transfer Video Generator

- **Core functionality**: Takes a pet image and motion reference video to generate animated output
- Currently exploring the **animate-x model** for implementation
- Transfers motion patterns from reference videos to the pet image

### 3. Background Removal

- Removes backgrounds from generated videos
- Creates transparent/black backgrounds suitable for hologram projection
- Ensures realistic hologram display quality

## Future Improvements

- End-to-end model capable of generating pet holograms directly from multiple images
- Web interface for easy access and improved user experience
- Additional motion libraries for try outs

## License

See [LICENSE](LICENSE) for details.
