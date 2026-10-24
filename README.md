<div align="center">
  <h1>Hello, I'm Psycho Rosse</h1>
  <p><b>Rust Developer · Game Engine Developer</b></p>
  <p>Building a modular 3D game engine from scratch in Rust.</p>
</div>

## 🔭 What I'm Working On

**[Kodanu](https://github.com/PsychoRosse/kodanu)** is my personal project: a modular 3D game engine written in Rust, built around a custom ECS architecture and a `wgpu`-based rendering system.

I'm developing the engine as a collection of independent, interconnected crates, with a focus on modular architecture, explicit data flow, and control over the underlying systems.

### Core Systems

- **Rendering:** A `wgpu`-based renderer with perspective cameras, directional lighting, materials, depth testing, MSAA, and GPU instancing.
- **ECS Architecture:** A custom Entity Component System with queries, component access, change-detection filters, resources, plugins, and staged system execution.
- **Engine Runtime:** Application lifecycle, window management, input handling, time management, and fixed- and variable-timestep scheduling.
- **Physics:** Integration with `rapier3d` for 3D physics simulation, rigid bodies, colliders, and spatial queries.
- **Mathematics:** Custom math library, **Plam**, providing vectors, quaternions, matrices, and 3D transformation operations.
- **Graphics & World Systems:** Cameras, transforms, typed asset handles, and UI components.
- **Extensibility:** A plugin-based architecture that allows engine features and game logic to be organized into separate modules.

<div align="center">
  <img src="https://img.shields.io/badge/Rust-000000?style=for-the-badge&logo=rust&logoColor=white" alt="Rust" />
  <img src="https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black" alt="Linux" />
  <img src="https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white" alt="Git" />
</div>

### 🎯 My Focus

I'm interested in low-level systems programming, game engine architecture, real-time rendering, ECS design, and building reusable tools in Rust.

Rather than relying entirely on an existing engine, I'm building Kodanu to understand and control how its core systems fit together, from the application runtime and entity management to rendering and physics integration.

**[Explore Kodanu on GitHub](https://github.com/PsychoRosse/kodanu)**

Many thanks to [MihailRis](https://github.com/MihailRis).
