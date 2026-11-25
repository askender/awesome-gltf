<h1 align="center">Awesome glTF <a href="https://awesome.re"><img alt="awesome" src="https://awesome.re/badge.svg" /></a></h1>

The GL Transmission Format (glTF) is an open standard by the Khronos Group for transmitting and loading 3D models and scenes.

Curated by [@askender](https://github.com/askender). Pull requests are welcome — see [contributing.md](contributing.md).

## Contents
- [What is glTF](#what-is-gltf)
- [Libraries & Tools](#libraries--tools)
  - [Validation](#validation)
  - [Viewers](#viewers)
  - [Editor Plugins](#editor-plugins)
  - [Loaders & SDKs](#loaders--sdks)
  - [Optimization & Compression](#optimization--compression)
  - [Converters](#converters)
  - [Engines & Engine Integrations](#engines--engine-integrations)
- [Sample Assets](#sample-assets)
- [Learning](#learning)
- [References](#references)
- [Related Projects](#related-projects)

## What is glTF
### Non-Technical Explanation
- A standard file format for three-dimensional scenes and models, often called the "JPEG of 3D" ([glTF - Wikipedia](https://en.wikipedia.org/wiki/GlTF))
- [What is glTF?](https://www.khronos.org/gltf/) - Official introduction from Khronos.

### Technical Explanation
glTF 2.0 describes a full scene — geometry, PBR materials, animations and the node hierarchy — as JSON, with mesh and animation data in binary buffers and textures as images. An asset ships either as a `.gltf` JSON file plus external buffers and textures, or packed into a single binary `.glb` container. The format is extensible through registered extensions such as `KHR_draco_mesh_compression` and `KHR_materials_variants`.

## Libraries & Tools
- [glTF GitHub Repository](https://github.com/KhronosGroup/glTF) - The main repository for the glTF project.

### Validation
- [glTF-Validator](https://github.com/KhronosGroup/glTF-Validator) - Official Khronos validator for glTF 2.0, available as a library and an online service.
- [CharpstAR GLB Validator](https://charpstar.co/tools/glb-validator) - Free, in-browser check of a GLB against the 3D model rules of Amazon, Shopify, Google and iPhone AR, with fixes that output a new GLB and USDZ. Nothing is uploaded.

### Viewers
- [glTF Viewer](https://gltf-viewer.donmccurdy.com/) - Drag-and-drop glTF/GLB viewer in the browser, by Don McCurdy.
- [glTF Report](https://gltf.report/) - View, inspect, edit, validate and compress glTF/GLB models in the browser.
- [glTF 2.0 Sample Viewer](https://github.com/KhronosGroup/glTF-Sample-Viewer) - Official Khronos reference viewer for glTF 2.0.
- [Super GLB Viewer](https://jessyleite.dev/super-glb-viewer/) - View, inspect, edit, compare and optimize GLB/glTF 3D models - multi-engine (Three.js, Babylon.js, PlayCanvas, Unity).
- [iMeshh glTF Viewer](https://imeshh.com/tools/gltf-viewer) - Free, in-browser glTF/GLB viewer with a path-traced photoreal preview mode.
- [3D House Planner Material Editor](https://www.3dhouseplanner.com/index2.php) - Free, in-browser glTF/GLB viewer and material editor: inspect models, edit PBR materials and textures, and export GLB. No login required.
- [F3D](https://github.com/f3d-app/f3d) - Fast and minimalist desktop 3D viewer supporting glTF.

### Editor Plugins
- [glTF Tools for VS Code](https://github.com/AnalyticalGraphicsInc/gltf-vscode) - VS Code extension for viewing and editing glTF files.
- [Super GLB Viewer for VS Code](https://marketplace.visualstudio.com/items?itemName=JessyLeite.super-glb-viewer) - Super GLB Viewer as a VS Code extension.

### Loaders & SDKs
- [model-viewer](https://github.com/google/model-viewer) - Easily display interactive 3D models on the web and in AR with a single web component.
- [tinygltf](https://github.com/syoyo/tinygltf) - Header-only C11 glTF 2.0 library.
- [cgltf](https://github.com/jkuhlmann/cgltf) - Single-file glTF 2.0 loader and writer written in C99.
- [fastgltf](https://github.com/spnda/fastgltf) - Modern C++17/C++20 glTF 2.0 library focused on speed, correctness, and usability.
- [glTF-SDK](https://github.com/microsoft/glTF-SDK) - Microsoft's C++ Software Development Kit for glTF.
- [gltf (Rust)](https://github.com/gltf-rs/gltf) - A crate for loading glTF 2.0 in Rust.
- [SharpGLTF](https://github.com/vpenades/SharpGLTF) - glTF reader and writer for .NET Standard.
- [glTF-Transform](https://github.com/donmccurdy/glTF-Transform) - glTF 2.0 SDK for JavaScript and TypeScript, on Web and Node.js.
- [gltfjsx](https://github.com/pmndrs/gltfjsx) - Turns GLTFs into JSX components for react-three-fiber.
- [minimal-gltf-loader](https://github.com/shrekshao/minimal-gltf-loader) - A minimal, engine-agnostic JavaScript glTF loader.
- [pyrender](https://github.com/mmatl/pyrender) - Easy-to-use Python OpenGL renderer for visualizing glTF 2.0 scenes.

### Optimization & Compression
- [meshoptimizer](https://github.com/zeux/meshoptimizer) - Mesh optimization library that makes meshes smaller and faster to render.
- [Draco](https://github.com/google/draco) - Library for compressing and decompressing 3D geometric meshes and point clouds.
- [glTF-Pipeline](https://github.com/CesiumGS/gltf-pipeline) - Content pipeline tools for optimizing glTF assets.
- [CharpstAR GLB Compressor](https://charpstar.co/tools/compress-glb) - Free, in-browser GLB/glTF compression with Draco or Meshopt geometry and resized WebP textures, with a before/after comparison view. Nothing is uploaded.
- [Mint GLB Texture Compressor](https://mint.gg/glb-texture-compressor) - Free, in-browser tool that resizes the textures inside a GLB and re-encodes them as WebP or AVIF to shrink file size. No signup, nothing uploaded.

### Converters
- [FBX2glTF](https://github.com/facebookincubator/FBX2glTF) - Command-line tool for converting FBX assets to glTF.
- [OBJ2GLTF](https://github.com/CesiumGS/obj2gltf) - Convert OBJ assets to glTF.
- [glTF-Blender-IO](https://github.com/KhronosGroup/glTF-Blender-IO) - Blender glTF 2.0 importer and exporter.
- [assimp](https://github.com/assimp/assimp) - Open Asset Import Library; loads 40+ 3D file formats, including glTF.
- [Shapeweld FBX to VRM](https://shapeweld.com/tools/fbx-to-vrm) - Browser tool that converts a rigged FBX, GLB or glTF to VRM, the glTF-based avatar format, and maps the skeleton to the VRM humanoid.
- [Unity Asset Exporter](https://extractunitypackage.com) - Free in-browser tool that opens .unitypackage files and exports textured glTF/GLB (and VRM for humanoid avatars). Files stay local.
- [CharpstAR Free 3D Product Renders](https://charpstar.co/tools/free-product-renders) - Upload a GLB and get studio renders from four angles, on white and as transparent PNGs, plus a 360 turntable video, sent by email. Free, no watermark.

### Engines & Engine Integrations
- [UnityGLTF](https://github.com/KhronosGroup/UnityGLTF) - Runtime glTF 2.0 Loader for Unity3D.
- [glTFast](https://github.com/atteneder/glTFast) - Efficient glTF 3D import/export package for Unity.
- [GLTFUtility](https://github.com/Siccity/GLTFUtility) - Simple GLTF importer for Unity.
- [UniVRM](https://github.com/vrm-c/UniVRM) - glTF-based VRM format implementation for Unity.
- [three-vrm](https://github.com/pixiv/three-vrm) - Use VRM (built on glTF) with three.js.

## Sample Assets
- [glTF Sample Assets](https://github.com/KhronosGroup/glTF-Sample-Assets) - An assortment of assets that demonstrate features and capabilities of the glTF format.
- [SceneCrate CC0 GLB Scene Packs](https://scenecrate.com/free-3d-game-assets) - Nine self-contained binary glTF 2.0 (GLB) game scenes in two LOD tiers with SHA-256 checksums, JSON colliders, and local Three.js viewers under CC0 1.0.

## Learning
- [glTF Tutorials](https://github.com/KhronosGroup/glTF-Tutorials) - Official Khronos glTF tutorials.

## References
- [glTF™ 2.0 Specification](https://registry.khronos.org/glTF/specs/2.0/glTF-2.0.html) - The official glTF 2.0 specification.
- [glTF Extension Support Matrix](https://digitalgarden.si/tools/gltf-extension-support-matrix/) - Source-linked matrix of glTF extension support across Three.js, Babylon.js, model-viewer, glTFast, Godot and Blender.
- [Everything You Need to Know About glTF Files](https://www.marxentlabs.com/gltf-files/) - Introductory overview of the glTF and GLB file formats.
- [Why we should all support glTF 2.0 as THE standard asset exchange format for game engines](https://godotengine.org/article/we-should-all-use-gltf-20-export-3d-assets-game-engines/) - Godot's case for glTF 2.0 as the standard asset exchange format.
- [glTF: Everything You Need to Know](https://www.threekit.com/blog/gltf-everything-you-need-to-know) - A broad introduction to glTF for product visualization.
- [glTF (GL Transmission Format) - Sketchfab](https://sketchfab.com/features/gltf) - Sketchfab's overview of glTF support and use cases.

## Related Projects
- [Awesome Blender](https://github.com/agmmnn/awesome-blender) - Curated list of awesome Blender resources.
- [Awesome Godot](https://github.com/godotengine/awesome-godot) - Curated list of awesome Godot engine resources.
