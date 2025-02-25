# ELLMPEG: Command Pools for FFmpeg and VVenC

## Overview

In our paper titled *ELLMPEG: Towards a Simple and Energy-Efficient FFmpeg-Like Video Processing Tool with LLMs*, we utilized the power of **GPT-4o** to generate command pools for evaluating **ELLMPEG**. Given the absence of an existing dataset, we created two diverse command pools of queries and responses. This repository contains the generated command pools for both FFmpeg and VVenC.

## Command Pools

### FFmpeg Command Pool

- **Total Queries:** 100
- This command pool includes a variety of queries categorized based on common multimedia processing tasks, ensuring thorough coverage of real-world applications. Queries are grouped into distinct categories, including:
  - **Video Processing**: Codec change, manipulation (resize, crop), compression, filters (watermark, blurring)
  - **Audio Processing**: Manipulation (speed change), Effects (echo, equalize)
  - **Image Processing**: Format support, sequence handling
  - **Streaming and Broadcasting**: Streaming (to YouTube), broadcasting (DASH manifest)
  - **Metadata Handling**
  - **Advanced Features**: Concatenation and splitting, analysis tools (media information), complex operations (processing multiple input files)
  - **Optimization**: Resource management, hardware acceleration
  - **Special Features**: Testing and debugging, screen capture
  - **System Integration**: Batch processing, command line usage

### VVenC Command Pool

- **Total Queries:** 50
- Similar to the FFmpeg command pool, this collection includes various queries tailored for the VVenC tool, categorized for ease of use and comprehensive coverage.
  - **Basic Encoding**: Codec change, bitrate settings
  - **Optimization**: Hardware acceleration, speed optimization
  - **Compression**: Bitrate control, compression efficiency
  - **Advanced Encoding**: rate control, custom encoding settings
  - **Intra, Inter Prediction, Motion Estimation**
  - **Fine-tuning Encoding**: Encoder parameters, pre-processing (scale, resize)
  - **Compatibility and Interoperability**: Format support, metadata handling
  - **Debugging and Analysis**: Log output, bitstream analysis
  - **System Integration**: Batch processing, command line usage
  - **Two-pass Encoding** 
## Files

- [ffmpeg_queries.csv](./ffmpeg_queries.csv): Contains the command pool for FFmpeg.
- [vVenc_queries.csv](./VVenC_queries.csv): Contains the command pool for VVenC.

## Usage

The command pools in this repository are publicly available to ensure reproducibility and support further research in energy-efficient video processing tools. You can use these command pools to evaluate and enhance your own implementations or for comparative studies.

## License

This project is licensed under the MIT License - see the [LICENSE](./LICENSE) file for details.

## Citation

If you use this dataset or reference this work in your research, please cite our paper as follows:

@inproceedings{azimi2025ellmpeg,
  author = {Zoha Azimi, Reza Farahani, Radu Prodan, CHristian Timmerer},
  title = {ELLMPEG: Towards a Simple and Energy-Efficient FFmpeg-Like Video Processing Tool with LLMs},
  booktitle = {Proceedings of [Conference Name]},
  year = {2025},
  note = {Under Review}
}
