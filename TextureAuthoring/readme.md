# Texture Authoring

## The process here is:

* Upscale the original textures with waifu2x or other related AI upscaler to longest side 1024
* Process upscaled textures with ShaderMap 4 and manually tweak normals and other related things as needed
* Optimize and fix up the sections of the maps associated with each texture in 3D a modeling program
* Apply the textures to each 3D model with Substance Painter and export the packed texture maps
* Optimize the textures exported from ShaderMap 4 and Substance Painter to 95 quality 4:2:0 jpeg for color and packed textures and 95 quality 4:4:4 jpeg for normal maps (to save space)
* Import assets into UE4
