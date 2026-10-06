<h1 align="center">carlosvts</h1>

<p align="center">
  Undergraduate Research Fellow in Human-Robot Interaction.<br/>
  Social robots in healthcare, built on a systems programming foundation.
</p>

<p align="center">
  CS @ UFLA · carlosvtsdev@gmail.com · <a href="https://carlosvts.github.io/">carlosvts.github.io</a>
</p>

---

## Research

My research is on **social robots in healthcare**: how robots can perceive human engagement and respond appropriately in care-related contexts, running on local/edge hardware where privacy and latency matter.

- Attention and engagement estimation
- Perception-to-behavior pipelines
- Local inference for vision-language models
- Resource-aware, real-time AI
- Human-centered and ethical design constraints for social robots

**Affiliations:** Undergraduate Research Fellow, UFLA · NEURON robotics study group

---

## Selected work

**[attention-aware-toy](https://github.com/carlosvts/attention-aware-toy)**
Attention-gated perception pipeline for HRI. OpenCV/MediaPipe estimate sustained attention from head pose and gaze; when it holds, local models (Ollama) generate a contextual response. Includes latency/CPU/RAM/VRAM telemetry and an explicit responsible-use policy.

**[go2-api](https://github.com/carlosvts/go2-api)**
HTTP API that owns and multiplexes the single WebRTC connection to a Unitree Go2 quadruped, so other services (voice, chat) can control the robot through simple REST calls: posture, gestures, locomotion and status. Built for the NEURON group at UFLA; real-time WebSocket streams are planned.

**[sar-review-pipeline](https://github.com/carlosvts/sar-review-pipeline)**
RAG pipeline to automate snowballing in systematic literature reviews.

---

## Technical foundation

Systems programming is where I learned to reason about memory, latency and hardware limits, which is what makes local, real-time perception on robots tractable.

- **[malloc](https://github.com/carlosvts/malloc-implementation)**: heap manager in C++ (free lists, coalescing, `sbrk`)
- **[lain](https://github.com/carlosvts/lain)**: Unix lab; coreutils/libc reimplementations, POSIX experiments
- **[chip8](https://github.com/carlosvts/chip8)**: CHIP-8 emulator in C with SDL2
- **[http-server-cpp](https://github.com/carlosvts/http-server-cpp)**: multithreaded HTTP server
- **[raytracing](https://github.com/carlosvts/raytracing)** · **[raw-image-processor](https://github.com/carlosvts/raw-image-processor)** · **[sandbox-game](https://github.com/carlosvts/sandbox-game)** · **[fractals](https://github.com/carlosvts/fractals)**

---

**Languages:** Python · C · C++
**Exploring:** Rust
**Tools:** OpenCV · MediaPipe · Ollama · FastAPI · Docker · Networking · Linux/POSIX · Git
