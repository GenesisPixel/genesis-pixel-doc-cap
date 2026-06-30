<img src="/svg/svg-8.png" width="40" /> <img src="/svg/svg-1.png" width="40" /> <img src="/svg/svg-2.png" width="40" /> <img src="/svg/svg-4.png" width="40" />

# GenesisPixel Documentation

A comprehensive educational documentation covering modern CSS animations, 3D graphics with Three.js, and shader programming. This project serves as a structured learning path for developers who want to master interactive web experiences.

## Core Purpose

Modern web development demands mastery of visual effects and user interactions. DOC-CAPITULOS bridges the gap between theoretical knowledge and practical implementation by providing:

- **Progressive Learning**: Carefully structured modules that guide you from foundational CSS concepts to advanced shader programming.
- **Hands-on Exercises**: Practical exercises at the end of each lesson to reinforce learning.
- **Real-world Applications**: Case studies and projects that apply skills to production-ready scenarios.

## Learning Modules

The documentation is organized into six comprehensive chapters:

### Chapter 1 – Keyframes

Master the art of CSS animations from the ground up. This chapter covers everything from basic `@keyframes` syntax to complex animation sequences, timing functions, and optimization techniques.

**Topics include:**
- `@keyframes` syntax and timeline
- Animation properties: name, duration, timing function, delay
- Iteration count, direction, fill mode, and play state
- Shorthand animation property
- Multiple keyframes and advanced sequences

### Chapter 2 – CSS Transform

Explore 2D and 3D transformations to create dynamic visual effects. Learn how to move, scale, rotate, and skew elements with hardware-accelerated performance.

**Topics include:**
- `translate`, `translateX`, `translateY`
- `scale`, `rotate`, `skew`
- `transform-origin` and multiple transforms
- 3D transforms: `rotateX`, `rotateY`, `translateZ`, `scale3D`
- Perspective and depth effects

### Chapter 3 – CSS Transitions

Understand the nuances of smooth state transitions for enhanced user experience. Learn when and how to apply transitions for hover effects, form inputs, and component interactions.

**Topics include:**
- `transition-property`, `transition-duration`, `transition-timing-function`
- `transition-delay` and shorthand syntax
- Hover interactions and focus states
- Performance optimization
- Microinteractions and design systems

### Chapter 4 – Interactions

Learn best practices for creating engaging user interfaces through interactive elements. Understand feedback systems, loading states, and consistent interaction patterns.

**Topics include:**
- Microinteractions and UI feedback
- Component states: default, hover, active, focus, disabled
- Loading states: spinners, skeletons, loaders
- Success and error feedback
- Modals, dropdowns, tooltips, and form validation

### Chapter 5 – Three.js

Dive into 3D graphics programming with Three.js. Create immersive 3D experiences for the web with cameras, lights, materials, and animations.

**Topics include:**
- Scene setup and rendering
- Cameras: PerspectiveCamera, OrthographicCamera
- Geometries and materials
- Lighting and shadows
- Textures and models (GLTF)
- Camera controls and user interaction
- Production optimization

### Chapter 6 – Shaders

Master GPU programming with GLSL shaders. Create procedural effects, visual distortions, and interactive graphics that run directly on the graphics card.

**Topics include:**
- GLSL syntax and structure
- Vertex and Fragment shaders
- Uniforms and Varyings
- UV coordinates and textures
- Procedural noise and gradients
- Interactive and animated effects
- Integration with Three.js

## Technical Architecture

This project is built using modern web standards:

- **Framework**: [Astro](https://astro.build/) - Optimized for content-driven documentation sites
- **Language**: TypeScript - Ensures type safety and robust code structure
- **Styling**: Vanilla CSS - Demonstrates core CSS concepts without abstraction overhead
- **3D Graphics**: [Three.js](https://threejs.org/) - Industry-standard WebGL library
- **Shader Language**: GLSL - GPU programming for visual effects

## Development Setup

To run this project locally:

1. **Clone the repository**:
   ```bash
   git clone https://github.com/GenesisPixel/doc-capitulos.git
   cd doc-capitulos
   ```

2. **Install dependencies**:
   ```bash
   npm install
   ```

3. **Start the development server**:
   ```bash
   npm run dev
   ```

## Project Structure

```
DOC-CAPITULOS/
├── Keyframes.md          # Chapter 1: CSS Animation Keyframes
├── Transform.md          # Chapter 2: CSS Transformations
├── Transitions.md        # Chapter 3: CSS Transitions
├── Interactions.md       # Chapter 4: UI Interactions
├── Three.js.md           # Chapter 5: 3D Graphics with Three.js
├── Shaders.md            # Chapter 6: GLSL Shader Programming
└── README.md             # Project documentation
```

## Learning Path

We recommend following the chapters in order:

1. **Keyframes** → Foundation of CSS animations
2. **Transform** → Hardware-accelerated visual effects
3. **Transitions** → Smooth state changes
4. **Interactions** → Real-world UI patterns
5. **Three.js** → 3D graphics programming
6. **Shaders** → GPU-powered visual effects

Each chapter contains 15 structured lessons with practical exercises, culminating in a final project that combines all concepts learned.

## Contributing

Contributions are welcome to improve learning content and examples. Please ensure contributions align with the educational focus and coding standards.

1. Fork the repository
2. Create a new branch for your feature or fix
3. Commit your changes following [Conventional Commits](https://www.conventionalcommits.org/)
4. Push to your branch and open a Pull Request

## License

This project is licensed under the MIT License - see the LICENSE file for details.
