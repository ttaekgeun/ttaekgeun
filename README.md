# Taekgeun You

Graphics researcher and rendering system developer focused on **mobile ray tracing**, **real-time global illumination**, and **Vulkan-based GPU rendering systems**.

My work focuses on implementing practical rendering systems for performance-constrained environments, especially mobile GPUs. I am interested in Vulkan ray tracing, ray query, DDGI, hybrid rendering, CUDA/Vulkan interoperability, and real-time graphics performance profiling.

---

## Research Interests

- Mobile ray tracing
- Real-time global illumination
- Dynamic Diffuse Global Illumination, DDGI
- Vulkan ray tracing pipeline
- Vulkan ray query
- Hybrid rendering
- Deferred rendering
- Path tracing
- 3D Gaussian rendering
- GPU-driven rendering
- CUDA/Vulkan interoperability
- Real-time rendering performance profiling

---

## Selected Projects

### PIKA

[PIKA](https://github.com/ttaekgeun/PIKA) is a Vulkan-based renderer for mobile ray tracing and DDGI-based global illumination.

It was developed to implement and evaluate ray tracing and global illumination techniques in performance-constrained mobile environments. PIKA supports multiple rendering paths, including deferred rasterization, full ray tracing, hybrid ray tracing, ray query-based rendering, DDGI, and path tracing.

Main topics:

- Mobile-oriented Vulkan renderer
- Vulkan ray tracing pipeline
- Vulkan ray query
- Deferred rasterization renderer
- Full ray tracing, FRT
- Full ray query, FRQ
- Hybrid ray tracing, HRT
- Hybrid ray query, HRQ
- DDGI-based global illumination
- Adaptive probe update budget
- Probe importance metric
- Runtime renderer switching through UI

---

### Shadow Edge Selective Ray Tracing

[Shadow Edge Selective Ray Tracing](https://github.com/ttaekgeun/ShadowEdgeSelectiveRayTracing) is a Vulkan-based rendering project that improves shadow quality by applying ray tracing selectively to shadow edge regions generated from shadow maps.

Instead of tracing rays across the entire screen, this project detects shadow boundary regions and applies ray tracing only where shadow artifacts are most visible.

Main topics:

- Hybrid shadow rendering
- Shadow map edge detection
- Selective ray tracing
- Vulkan-CUDA interoperability
- CUDA-based image processing
- Sobel filtering
- GPU resource sharing between Vulkan and CUDA
- Shadow quality improvement with reduced ray tracing workload

---

### 3DGVRT

[3DGVRT](https://github.com/sebbang99/3DGVRT), or **3D Gaussian Vulkan Ray Tracing**, is a Vulkan-based research renderer for experimenting with ray tracing approaches for 3D Gaussian rendering.

The project includes full ray tracing and hybrid rendering paths for 3D Gaussian rendering. It explores Vulkan ray tracing, Vulkan compute preprocessing, and hybrid graphics/ray tracing pipeline design.

Main topics:

- 3D Gaussian rendering
- Vulkan ray tracing pipeline
- Vulkan compute pipeline
- Ray query-style rendering path
- Hybrid Vulkan rendering
- Gaussian enclosing preprocessing
- Particle rendering pass
- Mobile execution experiments
- 3DGS / 3DGRT comparison experiments

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
- OpenGL deferred rendering
- Deferred renderer optimization
- NVIDIA OptiX ray tracing
- Shader programming
- C++ graphics programming
- CUDA and GLSL-based rendering components

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
- Vulkan Ray Tracing Pipeline
- Vulkan Ray Query
- OpenGL
- NVIDIA OptiX
- CUDA

### Rendering Techniques

- Deferred rendering
- Full ray tracing
- Hybrid ray tracing
- Whitted-style ray tracing
- Path tracing
- DDGI
- Shadow mapping
- Selective ray tracing
- Probe-based global illumination
- 3D Gaussian rendering

### GPU Programming

- GLSL shader programming
- CUDA kernel programming
- Vulkan compute pipeline
- GPU image processing
- GPU synchronization
- External memory and semaphore sharing
- Parallel sorting and probe prioritization
- Ray tracing pipeline construction
- Acceleration structure management

### Asset and Scene Handling

- glTF scene loading
- Custom scene configuration files
- Camera keyframe configuration
- DDGI volume configuration
- Research-oriented rendering assets

---

## Publications

### Journal Article

**Performance Profiling of Vulkan-based Ray Tracing Renderers on Mobile Platforms**  
Taekgeun You, Sungho Yoon, Sehee Jo, Woong Seo, and Insung Ihm  
*Journal of the Korea Computer Graphics Society*, Vol. 31, No. 3, pp. 171–181, July 2025

This paper presents a Vulkan-based mobile ray tracing renderer and analyzes its performance on mobile platforms. The renderer compares full ray tracing and rasterization-based hybrid ray tracing architectures, and evaluates both Vulkan ray tracing pipeline and ray query implementations. It also proposes an adaptive light attenuation function to reduce shadow ray shading cost in multi-light scenes.

[Paper](http://journal.cg-korea.org/archive/view_article?pid=jkcgs-31-3-171)

### Master's Thesis

**Development and Performance Profiling of a Mobile Ray Tracing System Supporting Global Illumination**  
Taekgeun You  
Graduate School of Sogang University, Seoul, Korea, 2026

---

### I3D 2026 Poster

**Mobile-DDGI: Lightweight Probe-Based Global Illumination via Adaptive Budget Allocation**  
T. You, W. Seo, D. Han, and I. Ihm  
2026 ACM SIGGRAPH Symposium on Interactive 3D Graphics and Games, I3D '26 Posters, San Francisco, U.S.A., May 2026

---

## References and Influences

My work is influenced by research and engineering work on:

- Dynamic Diffuse Global Illumination
- RTXGI / DDGI
- Adaptive Dynamic Global Illumination
- Ubisoft's real-time ray tracing and global illumination techniques
- Sascha Willems' Vulkan examples
- Vulkan-based GPU sorting and rendering utilities
- 3D Gaussian Splatting and ray tracing-based Gaussian rendering

---

## Contact

- GitHub: [@ttaekgeun](https://github.com/ttaekgeun)
- Email: taekgeun9025@gmail.com
- Affiliation: Sogang University
