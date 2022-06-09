# Computer graphics in Game development course

This repo contains a template for Computer graphics in Game development labs (summer 2022)

# Chernakov Ivan BS21-05
## Rasterization lab results
- Cube.obj renders correctly
- Z_test.obj renders correctly
- Fixed problem with Reaching the resource.
- Tried to use some 3D models, but every time it didn't work. Maybe the files were too big or some other problems with transporting files. Every model was Free to Use Licensed*
- I have left "debug" sout's, do not think it is necessary to delete them as amount of vertices is an always required info. Added debug from last time.

## Pre-requirements

- Version control: [Git](https://git-scm.com/)
- C++ compiler: **MSVS**, Clang, GCC
- Build automation: [CMake](https://cmake.org/download/)
- C++ IDE: [Visual Studio Community](https://visualstudio.microsoft.com/downloads/), [CLion](https://www.jetbrains.com/clion/)
- DirectX related: [Windows SDK](https://developer.microsoft.com/en-us/windows/downloads/windows-sdk/)

## How to build the solution

Use `git clone --recursive` to clone the repo with submodules or run `git submodule update --init --recursive` after the first clone.

Go to the project folder and run the next command:

```sh
mkdir Build
cd Build
cmake .. -A x64
```

## Third-party tools and data

- [STB](https://github.com/nothings/stb) by Sean Barrett (Public Domain)
- [Linalg.h](https://github.com/sgorsten/linalg) by Sterling Orsten (The Unlicense)
- [Tinyobjloader](https://github.com/syoyo/tinyobjloader) by Syoyo Fujita (MIT License)
- [Cxxopts](https://github.com/jarro2783/cxxopts) by jarro2783 (MIT License)
- [Cornell Box models](https://casual-effects.com/g3d/data10/index.html#) by Morgan McGuire (CC BY 3.0 License)
- [Cube model](https://casual-effects.com/g3d/data10/index.html#) by Morgan McGuire (CC BY 3.0 License)
- [Dabrovic Sponza](https://casual-effects.com/g3d/data10/index.html#) by Marko Dabrovic (CC BY-NC)
