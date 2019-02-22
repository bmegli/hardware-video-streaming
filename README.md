# hardware-video-streaming meta repository

This repository groups libraries, programs and examples related to video streaming.

## Before diving in

If you have no specific needs use gstreamer or FFmpeg command line streaming.

## Repositories
 
### [HVD Hardware Video Decoder](https://github.com/bmegli/hardware-video-decoder)

Multiple technologies hardware decoding wrapped in a simple zero-copy interface to FFmpeg.

### [HVE Hardware Video Encoder](https://github.com/bmegli/hardware-video-encoder)

VAAPI hardware encoding wrapped in a simple zero-copy interface to FFmpeg.

### [MLSP Minimal Latency Streaming Protocol](https://github.com/bmegli/minimal-latency-streaming-protocol)

A simple zero buffering UDP blaster.

### [NHVD Network Hardware Video Decoder](https://github.com/bmegli/network-hardware-video-decoder)

Network hardware decoder on top of [HVD](https://github.com/bmegli/hardware-video-decoder) and [MLSP](https://github.com/bmegli/minimal-latency-streaming-protocol).

### [NHVE Network Hardware Video Encoder](https://github.com/bmegli/network-hardware-video-encoder)

Network hardware encoder on top of [HVE](https://github.com/bmegli/hardware-video-encoder) and [MLSP](https://github.com/bmegli/minimal-latency-streaming-protocol) wrapped in a simple zero-copy interface.

### [realsense-ir-to-vaapi-h264](https://github.com/bmegli/realsense-ir-to-vaapi-h264)

Example of Realsense camera infrared stream H.264 encoding with [HVE](https://github.com/bmegli/hardware-video-encoder).

### [realsense-network-hardware-video-encoder](https://github.com/bmegli/realsense-network-hardware-video-encoder)

Example of Realsense camera color/infraed H.264 network streaming with [NHVE](https://github.com/bmegli/network-hardware-video-encoder).

### [unity-network-hardware-video-decoder](https://github.com/bmegli/unity-network-hardware-video-decoder)

Unity rendering example of [NHVD](https://github.com/bmegli/network-hardware-video-decoder) hardware decoded H.264 network stream.

## Additional information

The top level solution built on top of libraries forms:
- 100 ms order latency Realsense Camera to Unity WiFi streaming
- measured between LattePanda Alpha and i7-7820HK laptop
