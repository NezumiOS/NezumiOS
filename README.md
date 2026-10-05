# NezumiOS

NezumiOS is an Ubuntu-based Linux distribution focused on local AI,
AI companions, automation, and containerized AI workloads.

## Goals

- Provide a reproducible Ubuntu-based installation.
- Make local AI workloads easy to install and manage.
- Use Docker for application and workload isolation.
- Integrate AI companions as a first-class part of the user experience.
- Support local AI tools such as Ollama, OpenClaw, ComfyUI and other workloads.
- Keep the underlying Linux system accessible and usable without the companion.
- Allow community-created companions to be distributed independently.

## Architecture

NezumiOS separates the operating system from AI workloads.

The host system is responsible for:

- Linux kernel and base system
- Hardware support
- NVIDIA drivers
- Networking
- Storage
- Docker
- System-level services

AI applications and workloads run primarily as containers.

## Project status

Early development.

The project is currently focused on creating a reproducible installation
and bootstrap process from a clean Ubuntu installation.
