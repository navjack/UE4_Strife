# UE4_Strife

Yeah this is just [me](https://twitter.com/Jack_Mangano) remaking or porting or just doing the maps from the game [Strife](https://en.wikipedia.org/wiki/Strife_(1996_video_game)) in UE4.

My main goal is just to have all the map geometry and textures and lighting done. I'll attempt to bring the sprite work in by converting them to 3D geometry with MagicaVoxel.

This will be RTX & DLSS 2.0 featured.

# This is the last push i'll be putting on github. project too big and maintaining it VIA git is just no. i'll be working locally still though.

## Video Previews

[Most Recent Video](https://www.youtube.com/watch?v=nCg0tfOpabU)

## Status:

* Early development.

## To-Do:

* Still getting the work-flow down for things.
* Redo each map by taking each section of each map that is associated with a single texture and further splitting them into smaller 3D geometry objects and fixing the UVs.

## More info

Check the texture authoring folder for more information on how I'm going about that.

## Requirements

### To Acquire the Files

Just git clone or download by clicking on Code and Download ZIP. I'd advise against using the built in UE4 Git stuff, I don't use it.

### For Editing

If you want to open the project all you need is the latest version of UE4. Although on my end I'm using a fork of the engine with DLSS 2.0 built in - the project still works on the normal release of the engine and you can use that if you want to mess around with things.

### For Playing

If you want to play a build of the game I will have one of those on here once a single level is fully textured and modeled and lit. Spec wise I will try and have it aim for 30 FPS 1080p with TAA and 60 FPS 1080p with DLSS Quality mode on a RTX 2070 Super. This will be with ray-traced global illumination, ambient occlusion, reflections, transparency, and shadows.
