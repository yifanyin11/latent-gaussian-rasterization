# Latent Gaussian Rasterizer
This is a modified version of the differentiable 3D Gaussian rasterizer from "3D Gaussian Splatting for Real-Time Rendering of Radiance Fields" (Kerbl et al.).

## Modifications

- Spherical harmonics match e3nn now.
- Return alpha mask and depth, and allow gradients through them
- Optional rasterization of high-dimensional features and stop gradient through features to all structural Gaussian parameters
