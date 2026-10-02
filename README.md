<p align="center">
  <a href="https://awesome.re"><img alt="awesome" src="https://awesome.re/badge.svg" /></a>
</p>

# Awesome glTF
A curated list of awesome Graphics Library Transmission Format (glTF) resources and projects. These are hand-picked resources and projects that I find awesome.

Curated by [@askender43](https://twitter.com/askender43) and ...
Pull Requests are welcome!

## Contents
- [What is glTF?](#what-is-glTF)
- [Libraries & Tools](#libraries--tools)
  - [Loaders & SDKs](#loaders--sdks)
  - [Optimization & Compression](#optimization--compression)
  - [Converters](#converters)
  - [Engines & Engine Integrations](#engines--engine-integrations)
  - [Viewers](#viewers)
- [Sample Assets](#sample-assets)
- [Learning](#learning)
- [References](#references)
- [Integrations](#integrations)

## What is glTF?
### Non-Technical Explanation
- A standard file format for three-dimensional scenes and models. [glTF - Wikipedia](https://en.wikipedia.org/wiki/GlTF)
- [What is glTF?](https://www.khronos.org/gltf/)

### Technical Explanation
* TODO

## Libraries & Tools
* [glTF Github Repository](https://github.com/KhronosGroup/glTF) - The main repository for the glTF project.
- [glTF-Validator](https://github.com/KhronosGroup/glTF-Validator)
- [glTF Viewer](https://gltf-viewer.donmccurdy.com/)
- [glTF Report](https://gltf.report/)
- [official Khronos glTF 2.0 Sample Viewer](https://github.com/KhronosGroup/glTF-Sample-Viewer)
- [Super GLB Viewer](https://jessyleite.dev/super-glb-viewer/) - View, inspect, edit, compare and optimize GLB/glTF 3D models - multi-engine (Three.js, Babylon.js, PlayCanvas, Unity).
- [Super GLB Viewer for VS Code](https://marketplace.visualstudio.com/items?itemName=JessyLeite.super-glb-viewer)
- [iMeshh glTF Viewer](https://imeshh.com/tools/gltf-viewer) - Free, in-browser glTF/GLB viewer with a path-traced photoreal preview mode.
- [pyrender: Easy-to-use glTF 2.0-compliant OpenGL renderer for visualization of 3D scenes.](https://github.com/mmatl/pyrender)
- [VS-Code extension support editing glTF files](https://github.com/AnalyticalGraphicsInc/gltf-vscode)
- [A minimal, engine-agnostic JavaScript glTF Loader](https://github.com/shrekshao/minimal-gltf-loader)

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

### Optimization & Compression
- [meshoptimizer](https://github.com/zeux/meshoptimizer) - Mesh optimization library that makes meshes smaller and faster to render.
- [Draco](https://github.com/google/draco) - Library for compressing and decompressing 3D geometric meshes and point clouds.
- [glTF-Pipeline](https://github.com/CesiumGS/gltf-pipeline) - Content pipeline tools for optimizing glTF assets.

### Converters
- [FBX2glTF](https://github.com/facebookincubator/FBX2glTF) - Command-line tool for converting FBX assets to glTF.
- [OBJ2GLTF](https://github.com/CesiumGS/obj2gltf) - Convert OBJ assets to glTF.
- [glTF-Blender-IO](https://github.com/KhronosGroup/glTF-Blender-IO) - Blender glTF 2.0 importer and exporter.
- [assimp](https://github.com/assimp/assimp) - Open Asset Import Library; loads 40+ 3D file formats, including glTF.

### Engines & Engine Integrations
- [UnityGLTF](https://github.com/KhronosGroup/UnityGLTF) - Runtime glTF 2.0 Loader for Unity3D.
- [glTFast](https://github.com/atteneder/glTFast) - Efficient glTF 3D import/export package for Unity.
- [GLTFUtility](https://github.com/Siccity/GLTFUtility) - Simple GLTF importer for Unity.
- [UniVRM](https://github.com/vrm-c/UniVRM) - glTF-based VRM format implementation for Unity.
- [three-vrm](https://github.com/pixiv/three-vrm) - Use VRM (built on glTF) with three.js.

### Viewers
- [F3D](https://github.com/f3d-app/f3d) - Fast and minimalist 3D viewer supporting glTF.

## Sample Assets
- [glTF Sample Assets](https://github.com/KhronosGroup/glTF-Sample-Assets) - An assortment of assets that demonstrate features and capabilities of the glTF format.
- [glTF Sample Models (archived)](https://github.com/KhronosGroupArchives/glTF-Sample-Models) - The original glTF sample model collection.

## Learning
- [glTF Tutorials](https://github.com/KhronosGroup/glTF-Tutorials) - Official Khronos glTF tutorials.

## References
* [Everything You Need to Know About glTF Files](https://www.marxentlabs.com/gltf-files/)
* [Why we should all support glTF 2.0 as THE standard asset exchange format for game engines](https://godotengine.org/article/we-should-all-use-gltf-20-export-3d-assets-game-engines/)
* [glTF: Everything You Need to Know](https://www.threekit.com/blog/gltf-everything-you-need-to-know)
- [glTF (GL Transmission Format) - Sketchfab](https://sketchfab.com/features/gltf)
- [glTF™ 2.0 Specification](https://registry.khronos.org/glTF/specs/2.0/glTF-2.0.html)

## Related Projects
- [Awesome Blender](https://github.com/agmmnn/awesome-blender)
- [Awesome Godot](https://github.com/godotengine/awesome-godot)
