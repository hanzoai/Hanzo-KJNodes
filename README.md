# Hanzo-KJNodes

A grab-bag of general-purpose ComfyUI nodes — masking, image and latent helpers, batch and curve utilities.

This is a Hanzo-maintained fork of [kijai/ComfyUI-KJNodes](https://github.com/kijai/ComfyUI-KJNodes), pinned so the ComfyUI node packs we
run together stay on versions we have tested together.

## Install

```bash
cd ComfyUI/custom_nodes
git clone https://github.com/hanzoai/Hanzo-KJNodes
cd Hanzo-KJNodes
[ -f requirements.txt ] && pip install -r requirements.txt
```

Restart ComfyUI. The nodes appear in the node menu under the categories upstream defines.

## Docs

Node reference and usage are upstream's — see [kijai/ComfyUI-KJNodes](https://github.com/kijai/ComfyUI-KJNodes). Nothing about the nodes
themselves is changed here.

## Contributing

Improvements to the nodes belong upstream: open them against
[kijai/ComfyUI-KJNodes](https://github.com/kijai/ComfyUI-KJNodes), and this fork picks them up on the next sync. Open an issue here only
for something specific to the fork.

## License

Upstream's; see the licence file in this repository.
