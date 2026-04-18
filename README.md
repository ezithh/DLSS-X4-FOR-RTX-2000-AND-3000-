Frame Generation Mod for RTX 2000 / 3000 (x3 / x4)
Description

This is an experimental mod that enables enhanced Frame Generation (up to x3 or x4) on NVIDIA RTX 2000 and RTX 3000 series GPUs.

Unlike official DLSS 3 Frame Generation (limited to RTX 4000 series), this project explores an alternative approach to frame interpolation in order to improve perceived smoothness on older hardware.

This is an experimental / proof-of-concept project and is not affiliated with NVIDIA.

How it works

The mod uses a custom frame interpolation pipeline that:

Generates intermediate frames between rendered frames
Improves frame pacing for smoother motion
Optimizes GPU workload distribution for older RTX architectures

The goal is to increase perceived FPS without requiring DLSS 3 hardware features.

Improvements and fixes

Compared to earlier versions, this release includes major improvements:

Reduced input latency
Significantly reduced ghosting artifacts
Improved frame stability and pacing
Better interpolation accuracy in fast motion scenes
General performance optimizations
Compatibility

Tested on:

RTX 2000 series (Turing)
RTX 3000 series (Ampere)

Performance may vary depending on:

Game engine
GPU load
V-Sync / frame limiter settings
Limitations
Some visual artifacts may still occur in fast-paced scenes
Latency can still vary depending on configuration
Not equivalent to native DLSS 3 Frame Generation
Results differ per game

Installation

Download the latest release
Copy files into the game directory
Select frame generation mode (x3 / x4)

Notes

This project is intended for experimentation and research into frame generation techniques on unsupported hardware. It aims to explore what is possible beyond official hardware restrictions.

Disclaimer

Not affiliated with NVIDIA.
