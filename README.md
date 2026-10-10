# datasource-anim-female-doll-retargeting

A game-engine project that retargets dance and walk animations onto a set of humanoid avatars, the female doll among them.

## What it is for

It holds the avatar models, the animation clips, the bone maps from each skeleton to a shared humanoid profile, and scenes that play a retargeted clip on each avatar. Eight editor add-ons are git submodules; the rest, the avatar format importer among them, are vendored files.

## Build and run

```sh
git submodule update --init addons
```

`animation_retargeting_demo/art/ANIM_perfume` is a submodule path with no `.gitmodules` entry, so a bare `git submodule update --init` stops on it; initialise `addons` by name.

Then open `project.godot` in the engine's editor.

## Licence

MIT. See [LICENSE](LICENSE).
