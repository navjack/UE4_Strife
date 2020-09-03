# UE4_Strife

Yeah this is just me remaking or porting or just doing the maps from the game Strife in UE4.

My main goal is just to have all the map geometry and textures and lighting done. I'll attempt to bring the sprite work in by converting them to 3D geometry with MagicaVoxel.

This will be RTX & DLSS 2.0 featured.

## Status:

* Early development.

## To-Do:

* Still getting the workflow down for things.
* Redo each map by taking each section of each map that is associated with a single texture and further splitting them into smaller 3D geometry objects and fixing the UVs.

## More info

Check the texture authoring folder for more information on how I'm going about that.

## Requirements

### For Editing

If you want to open the project all you need is the latest version of UE4. Although on my end I'm using a fork of the engine with DLSS 2.0 built in the project still works on the normal release of the engine.

### For Playing

If you want to play a build of the game I will have one of those on here once a single level is fully textured and modeled and lit. Spec wise I will try and have it aim for 30fps 1080p with TAA and 60fps 1080p with DLSS Quality mode on a RTX 2070 Super. This will be with ray-traced global illumination, ambient occlusion, reflections, transparency, and shadows.
