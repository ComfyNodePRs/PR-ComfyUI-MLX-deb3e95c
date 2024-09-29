# ComfyUI MLX Nodes

Faster image generation for ComfyUI users on Mac with Apple silicon

## Installation

1. First, install the DiffusionKit library:

```bash
conda create -n comfy_mlx python=3.11 -y
conda activate comfy_mlx
cd /path/to/your_folder
git clone https://github.com/argmaxinc/DiffusionKit
cd DiffusionKit
pip install -e .
```

2. Install the MLX nodes:
 - In ComfyUI, Manager > Install via Git URL > https://github.com/thoddnn/ComfyUI-MLX.git

## Getting Started

A basic workflow is provided to help you start experimenting with the nodes.

## Why ComfyUI MLX Nodes?

I started building these nodes because image generation from Flux models was taking too much time on my MacBook. After discovering DiffusionKit on X (Twitter), which showcased great performance for image generation on Apple Silicon, I decided to create a quick port of the library.

The goal is to collaborate with other contributors to build a full suite of ComfyUI custom nodes optimized for Apple Silicon.

This will allow ComfyUI users on MacOS to perform faster image/video generation, upscaling, inpainting, and more.

## Future Plans

- SDXL models support
- Loading models from local file 
- Build more MLX based node for common workflows including Controlnet, IP adapter etc
- Add support for more ML models and techniques
- Add sampler and scheduler method 

## License

ComfyUI MLX Nodes is released under the MIT License. See [LICENSE](LICENSE) for more details.

## Acknowledgements

- [DiffusionKit](https://github.com/argmaxinc/DiffusionKit)

## Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

## Support

If you encounter any problems or have any questions, please open an issue in this repository.