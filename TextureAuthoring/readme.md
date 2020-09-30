# Texture Authoring

## The process here is:

* Upscale the original textures with waifu2x or other related AI upscalers to longest side 4096
* Process upscaled textures with ShaderMap 4 and manually tweak normals and other related things as needed
* Optimize and fix up the sections of the maps associated with each texture in 3D a modeling program and export just that object to FBX
* Apply the textures to each 3D model with Substance Painter and export the packed texture maps to PNG files and the 3D mesh to GLTF
* Import assets into UE4

## Packed Texture Types

When I first started this I just was using:

* Base Color Map
* Specular (R) Roughness (G) Metallic (B)
* Normal Map
* Height (R) Displacement (G) Ambient Occlusion (B)

But after some time, I realized that I don't really use that last map at all. The file name convention stays the same but now it's just a Height Map. I haven't redone every model's textures yet so some still are a packed version. I did this change also so I could experiment with POM materials but I'm abandoning that idea for the most part now.
