# Third-party notices — Scene 01

The built bundle (dist/assets/*.js) includes **three.js 0.187.0** (npm `three`), including the GLTFLoader addon, under the MIT License:

```
The MIT License

Copyright © 2010-2026 three.js authors

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in
all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN
THE SOFTWARE.
```

## meshoptimizer (bundled inside three.js `examples/jsm/libs`, used by MeshletDrawingPipeline)

meshopt_clusterizer / meshopt_simplifier (meshoptimizer 1.1), MIT License:

```
Copyright (C) 2016-2026, by Arseny Kapoulkine (arseny.kapoulkine@gmail.com)

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in
all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN
THE SOFTWARE.
```

## mrdoob — Codevember 2026 #05 "Moss" (adapted shader code)

`src/surfaces.ts` adapts `reliefNormal` and the mineral/lichen `rockSurface` field from
https://github.com/mrdoob/codevember-2026 (05/geology.js), MIT License:

```
MIT License

Copyright (c) 2026 mrdoob

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in
all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN
THE SOFTWARE.
```

## Technique references (no code copied)

- Shuffle Legend grass (`shared-food/games/shuffle-legend/src/world/GpuGrass.ts`, read-only, same owner): root-to-tip colour, dry/straw blades, gust sheen and sun-through-tip glow re-implemented in `src/world.ts`.
- leoawen/fluffytree-threejs (MIT, © 2025 Leonardo Soares Gonçalves): sun-gradient canopy principle, re-implemented in TSL.

## Textures

`textures/*.webp` (bark, ground, moss, metal albedo) were generated for this project by Aggy with the
Black Forest Labs FLUX.2 image model on 6 Nov 2026; project-owned, no third-party asset licence.
Provenance: `public/textures/README.md`.

No other third-party code, fonts, models, audio or screenshots ship in the build.
Build-only tools (not shipped): Vite 8.3.6, TypeScript 7.0.2, Vitest 5.1.0, @types/three 0.187.0, Blender 4.5.14 LTS (authoring only).
