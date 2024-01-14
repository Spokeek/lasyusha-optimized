# Lasyusha Project Optimised

This project is a trial to use NDMF module to bring an avatar asset to an optimized step only with modular tools.

This is based on the NDMF modular framework.
<https://github.com/bdunderscore/ndmf>

## Requirements

When cloning this avatar, you will need a few items for it to work.

- The original avatar project from Keenoo at <https://keenooshop.booth.pm/items/4825073>

- The listed dependencies of the project (a popup will ask you to install them on the first load of the project)
  - NDMF Framework <https://github.com/bdunderscore/ndmf>
  - LILToon <https://github.com/lilxyzw/lilToon>
  - Gesture Manager <https://github.com/BlackStartx/VRC-Gesture-Manager>
  - Dread HierarchyPlus <https://github.com/Dreadrith/DreadScripts>
  - Tex Trans Tool <https://github.com/ReinaS-64892/TexTransTool>
  - Modular Avatar <https://github.com/bdunderscore/modular-avatar>
  - Anatawa12 Avatar Optimizer <https://github.com/anatawa12/AvatarOptimizer>
  - Anatawa12 Gists Tools <https://github.com/anatawa12/unity-gist-pack>

- Some optional dependencies
  - NDMF LOD EDITOR <https://github.com/hitsub/ndmf-mantis-lod-editor>

## Project Structure

All of the assets are in the `Assets/Spokeek/Lasyusha` Folder.

Please note that those are my version of the optimisation strategy. For example it removes the availablility to use the original toogles.

You will find:

### A Base prefab

This is only a reference to the main Lasyusha Prefab.

This is the original one that you want to edit if you want to add some items or change the materials

### A Optimized Base prefab

This is the first one where the work is done.

It incudes lots of settings associated with NDMF modules to optimize the avatar at runtime.

### C1, C2, C3 prefabs

Those are made based on the three avatar version provided by Keenoo and includes optimization options to use them in an optimized version.

### Improvements

#### Stability

For now most of my changes are done quick and dirty way.
I would need to make this more stable and closer to the original prefabs

#### Performance rank

I would want all C1,C2,C3 prefabs to be poor at minimum

#### Quest Support

It would be great to have modular prefabs for Quest as well.
