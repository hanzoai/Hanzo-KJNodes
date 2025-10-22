# Hanzo-KJNodes

**Core utilities for the Hanzo ecosystem**

Part of [Hanzo Painter](https://github.com/hanzoai/painter) - AI-powered watermark removal and video inpainting platform.

[![Upstream](https://img.shields.io/badge/upstream-kijai%2FComfyUI-KJNodes-blue)](https://github.com/kijai/ComfyUI-KJNodes)
[![Hanzo AI](https://img.shields.io/badge/Hanzo-AI-orange)](https://hanzo.ai)

## About

Hanzo-KJNodes is a Hanzo-maintained fork of kijai/ComfyUI-KJNodes, providing Core utilities for video processing. This fork is part of the Hanzo ComfyUI ecosystem, ensuring tested compatibility and seamless integration with other Hanzo custom nodes.

## Installation

### As Part of Hanzo Painter (Recommended)

```bash
git clone git@github.com:hanzoai/painter.git
cd painter
make setup  # Automatically installs all Hanzo nodes
```

### Standalone Installation

```bash
cd ComfyUI/custom_nodes
git clone git@github.com:hanzoai/Hanzo-KJNodes.git
cd Hanzo-KJNodes
pip install -r requirements.txt  # If requirements.txt exists
```

## Hanzo ComfyUI Ecosystem

Hanzo-KJNodes is part of a curated stack of ComfyUI nodes maintained by Hanzo AI. All nodes work together seamlessly and are tested as a unified stack.

| Node | Purpose |
|------|---------|
| [Hanzo-DiffuEraser](https://github.com/hanzoai/Hanzo-DiffuEraser) | Content-aware inpainting |
| [Hanzo-VideoHelper](https://github.com/hanzoai/Hanzo-VideoHelper) | Video I/O suite |
| [Hanzo-EasyUse](https://github.com/hanzoai/Hanzo-EasyUse) | Workflow utilities |
| [Hanzo-KJNodes](https://github.com/hanzoai/Hanzo-KJNodes) | Core utilities |
| [Hanzo-LayerStyle](https://github.com/hanzoai/Hanzo-LayerStyle) | Layer compositing |
| [Hanzo-MLX](https://github.com/hanzoai/Hanzo-MLX) | Apple Silicon acceleration |

## Upstream

This is a Hanzo-maintained fork of [kijai/ComfyUI-KJNodes](https://github.com/kijai/ComfyUI-KJNodes).

- **Upstream Sync**: Regularly updated from original repository
- **Hanzo Enhancements**: Custom improvements for Hanzo ecosystem
- **Tested Compatibility**: Verified to work with other Hanzo nodes

## Contributing

### To Hanzo Fork
For Hanzo-specific features:
1. Fork this repository
2. Create a feature branch
3. Submit a PR to `hanzoai/Hanzo-KJNodes`

### To Upstream
For general improvements:
1. Submit PRs to [kijai/ComfyUI-KJNodes](https://github.com/kijai/ComfyUI-KJNodes)
2. Hanzo fork will sync these improvements

## About Hanzo AI

Part of the [Hanzo AI](https://hanzo.ai) ecosystem:

- **hanzo.ai** - Core AI infrastructure platform
- **hanzo.io** - Business solutions
- **hanzo.network** - Decentralized compute marketplace

---

Made with ❤️ by [Hanzo AI](https://hanzo.ai)
