# Texture Authoring

## The process here is:

* Upscale the original textures with waifu2x or other related AI upscalers to longest side 4096
* Process upscaled textures with ShaderMap 4 and manually tweak normals and other related things as needed
* Optimize and fix up the sections of the maps associated with each texture in 3D a modeling program and export just that object to FBX
* Apply the textures to each 3D model with Substance Painter and export the packed texture maps to PNG files and the 3D mesh to GLTF
* Import assets into UE4
