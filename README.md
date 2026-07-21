# Taekgeun You

Graphics engineer focused on **real-time rendering**.

My work focuses on implementing practical rendering systems for performance-constrained environments, especially mobile GPUs.
I am interested in real-time rendering techniques, including rasterization, ray tracing, global illumination, and performance profiling of real-time graphics systems.

You can find my CV and portfolio here.

[[CV](./Files/CV_Taekgeun_You.pdf)] [[Portfolio(Korean)](./Files/Portfolio_Taekgeun_You(Korean).pdf)]

---

## Research Interests

- Rasterization/Ray tracing/Hybrid Rendering
- Mobile rendeinrg
- Global illumination
- 3D Gaussian rendering
- Physically Based Rendering (PBR)
- Game engine

---

## Selected Projects

### PIKA

[PIKA](https://github.com/ttaekgeun/PIKA) is a Vulkan-based renderer for mobile ray tracing and DDGI-based global illumination.

It was developed to implement and evaluate ray tracing and global illumination techniques in performance-constrained mobile environments. PIKA supports multiple rendering paths, including deferred rasterization, full ray tracing, hybrid ray tracing, ray query-based rendering, DDGI, and path tracing.

Main topics:

- Mobile-oriented Vulkan renderer
- Vulkan ray tracing pipeline/ray query
- Deferred rasterization renderer
- DDGI-based global illumination

---

### Shadow Edge Selective Ray Tracing

[Shadow Edge Selective Ray Tracing](https://github.com/ttaekgeun/ShadowEdgeSelectiveRayTracing) is a Vulkan-based rendering project that improves shadow quality by applying ray tracing selectively to shadow edge regions generated from shadow maps.

Instead of tracing rays across the entire screen, this project detects shadow boundary regions and applies ray tracing only where shadow artifacts are most visible.

Main topics:

- Hybrid shadow rendering
- Shadow map edge detection and selective ray tracing
- Vulkan-CUDA interoperability
- CUDA-based sobel filtering

---

### 3DGVRT

[3DGVRT](https://github.com/sebbang99/3DGVRT), or **3D Gaussian Vulkan Ray Tracing**, is a Vulkan-based research renderer for experimenting with ray tracing approaches for 3D Gaussian rendering.

The project includes full ray tracing and hybrid rendering paths for 3D Gaussian rendering. It explores Vulkan ray tracing, Vulkan compute preprocessing, and hybrid graphics/ray tracing pipeline design.

Main topics:

- 3D Gaussian rendering
- Vulkan ray tracing pipeline/compute pipeline
- Mobile execution experiments

Representative components:

| Component | Description |
|---|---|
| Vulkan Full Ray Tracing | Full Vulkan ray tracing path for 3D Gaussian rendering. |
| Gaussian Enclosing Pass | Preprocessing pass executed with a Vulkan compute pipeline. |
| Particle Rendering Pass | Per-frame rendering pass using Vulkan ray tracing or compute-based execution. |
| Vulkan Hybrid Renderer | Hybrid renderer using a graphics geometry pass and a ray tracing lighting pass. |

---

### Real Time Rendering Projects

[RealTimeRendering](https://github.com/ttaekgeun/RealTimeRendering) is a collection of real-time rendering coursework projects developed for CSE6449.

This repository includes rendering implementations ranging from CPU-based ray tracing to OpenGL deferred rendering optimization and OptiX-based ray tracing.

Main topics:

- CPU ray tracing
- OpenGL deferred renderer optimization using stencil pass
- NVIDIA OptiX ray tracing

Representative projects:

| Project | Description |
|---|---|
| HW1: CPU Ray Tracer | CPU-based ray tracing implementation. |
| HW3: OpenGL Deferred Renderer Optimization | OpenGL deferred rendering project focused on rendering optimization. |
| HW4: OptiX Ray Tracer | Ray tracing renderer implemented using NVIDIA OptiX. |

---

## Technical Stack

### Graphics APIs

- Vulkan
- OpenGL
- NVIDIA OptiX
- CUDA

### Rendering Techniques

- Deferred rendering
- Ray tracing/Hybrid rendering
- DDGI
- 3D Gaussian rendering

---

## Publications

### Journal Article

**Performance Profiling of Vulkan-based Ray Tracing Renderers on Mobile Platforms**  
Taekgeun You, Sungho Yoon, Sehee Jo, Woong Seo, and Insung Ihm  
*Journal of the Korea Computer Graphics Society*, Vol. 31, No. 3, pp. 171–181, July 2025

This paper presents a Vulkan-based mobile ray tracing renderer and analyzes its performance on mobile platforms. The renderer compares full ray tracing and rasterization-based hybrid ray tracing architectures, and evaluates both Vulkan ray tracing pipeline and ray query implementations. It also proposes an adaptive light attenuation function to reduce shadow ray shading cost in multi-light scenes.
 [[Paper](http://journal.cg-korea.org/archive/view_article?pid=jkcgs-31-3-171)]

### Master's Thesis

**Development and Performance Profiling of a Mobile Ray Tracing System Supporting Global Illumination**  
Taekgeun You  
Graduate School of Sogang University, Seoul, Korea, 2026
 [[Paper](http://www.dcollection.net/handler/sogang/000000082452)]

---

### I3D 2026 Poster

**Mobile-DDGI: Lightweight Probe-Based Global Illumination via Adaptive Budget Allocation**  
T. You, W. Seo, D. Han, and I. Ihm  
2026 ACM SIGGRAPH Symposium on Interactive 3D Graphics and Games, I3D '26 Posters, San Francisco, U.S.A., May 2026 (Best Poster Award)
 [[Paper](https://dl.acm.org/doi/10.1145/3807895.3807920)]

---

## Contact

- GitHub: [@ttaekgeun](https://github.com/ttaekgeun)
- Email: taekgeun9025@gmail.com
- Affiliation: Sogang University
