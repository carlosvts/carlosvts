<h1 align="center">carlosvts</h1>

<p align="center">
  Systems programmer building the perception and reasoning layers for embodied intelligence.<br/>
  CS student at UFLA — from memory allocators and emulators to perception and interaction pipelines for robots.
</p>

<p align="center">
  <img src="https://img.shields.io/badge/C-000000?style=for-the-badge&logo=c&logoColor=white"/>
  <img src="https://img.shields.io/badge/C++-000000?style=for-the-badge&logo=c%2B%2B&logoColor=white"/>
  <img src="https://img.shields.io/badge/Python-000000?style=for-the-badge&logo=python&logoColor=white"/>
  <img src="https://img.shields.io/badge/OpenCV-000000?style=for-the-badge&logo=opencv&logoColor=white"/>
  <img src="https://img.shields.io/badge/Ollama-000000?style=for-the-badge&logo=ollama&logoColor=white"/>
  <img src="https://img.shields.io/badge/MediaPipe-000000?style=for-the-badge"/>
  <img src="https://img.shields.io/badge/Linux-000000?style=for-the-badge&logo=linux&logoColor=white"/>
  <img src="https://img.shields.io/badge/POSIX-000000?style=for-the-badge"/>
</p>

<p align="center">
  carlosvtsdev@gmail.com · carlosvts@proton.me · <a href="https://carlosvts.github.io/">carlosvts.github.io</a><br/>
  C/C++ (modern C++) · Python · OpenCV/MediaPipe · Ollama (local LLMs/VLMs) · POSIX/Linux · Git
</p>

---

## Human-Robot Interaction & Embodied AI — current focus

**[attention-aware-toy](https://github.com/carlosvts/attention-aware-toy)**
An experimental attention-gated perception pipeline for HRI. OpenCV/MediaPipe estimate sustained human attention from head pose and gaze; when attention holds, locally-run models (via Ollama) generate a contextual response. Includes custom telemetry for latency/CPU/RAM/VRAM and an explicit responsible-use policy. A testbed for perception-to-behavior pipelines aimed at future deployment on social robots.

**Areas of active exploration:** attention and engagement estimation, perception-to-behavior pipelines, local/edge inference for vision-language models, resource-aware real-time AI, human-centered design constraints for social robots.

---

## Systems Foundations

**[lain](https://github.com/carlosvts/lain)**
A personal Unix laboratory — reimplementations of coreutils and libc functionality, process management, and POSIX interface experiments.

**[malloc implementation](https://github.com/carlosvts/malloc-implementation)**
A custom heap manager built from scratch in C++: doubly-linked free lists, coalescing, fragmentation analysis, and direct interaction with the Linux kernel via `sbrk`.

**[input multiplexer](https://github.com/carlosvts/input-multiplexer)**
Event-driven terminal input handling and file-descriptor multiplexing.

**[lain-audio](https://github.com/carlosvts/lain-audio)**
A small C audio library for visualizing `.wav` files as amplitude bars, built within the `lain` ecosystem.

---

## Graphics, Vision & Simulation

**[raw image processor](https://github.com/carlosvts/raw-image-processor)**
Zero-dependency manual BMP parsing and convolution-based filtering — Sobel edge detection, Gaussian blur, pixel-level convolution.

**[raytracing](https://github.com/carlosvts/raytracing)**
CPU ray tracing covering geometric intersection testing and lighting models.

**[sandbox game](https://github.com/carlosvts/sandbox-game)**
A real-time particle physics sandbox with custom cellular automata — fluid, thermal, and biological interactions implemented in C++ with Raylib.

**[fractals](https://github.com/carlosvts/fractals)**
Fractal trees and Mandelbrot set exploration, procedural mathematical visualization.

---

## Emulation

**[CHIP-8 emulator](https://github.com/carlosvts/chip8)**
A CHIP-8 virtual machine in C using SDL2 — fetch-decode-execute cycle, big-endian opcode handling, timer synchronization, and display rendering.

---

## Networking

**[http server (C++)](https://github.com/carlosvts/http-server-cpp)**
A multithreaded HTTP server — socket programming, request parsing, and thread-per-connection handling, following Beej's Guide to Network Programming.

---

## Education

**B.Sc. Computer Science — UFLA (Federal University of Lavras)**

**CS50x — Introduction to Computer Science**
C programming · memory management · data structures · algorithms · systems fundamentals

**CS50AI — Introduction to Artificial Intelligence**
Search algorithms · knowledge representation · probabilistic inference · optimization · machine learning fundamentals

---

<p align="center">
  <img src="https://github-readme-stats.zcy.dev/api?username=carlosvts&show_icons=true&theme=transparent&hide_border=true" height="160"/>
  <img height="180em" src="https://readme-stats-fork.vercel.app/api/top-langs/?username=carlosvts&layout=compact&hide_border=true&bg_color=00000000&title_color=58A6FF&text_color=C9D1D9&exclude_repo=carlosvts.github.io,InfraCompjr,Portfolio-de-Qualidade&hide=javascript"/>
</p>
