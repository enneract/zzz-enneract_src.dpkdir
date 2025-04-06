# zzz-enneract_src.dpkdir

Experimental new assets for [Unvanquished](https://github.com/Unvanquished).

## Features

- Improved chaingun shading. Finished and sent upstream in [this PR](https://github.com/UnvanquishedAssets/res-weapons_src.dpkdir/pull/34). I'm keeping ambient occlusion maps here in extras/ for future use.

- Improved rocket pods. New sounds, particle effects, etc.

## Testing

Clone the repository and symlink it to `~/.local/share/unvanquished/pkg`. Start the game with `-set fs_extrapaks zzz-enneract'.

For servers, you can grab a `.dpk` from [dl.zittrig.eu](http://dl.zittrig.eu/pkg/).

## Licensing

GPL 3.0 (see `LICENSE`) applies to all source code that might appear in this repository. This includes any shell/Python scripts and patches to Unvanquished. This does not apply to asset text files (`*.cfg`, `*.shader`, `*.particle`, etc.).

Unless specifically listed below, all asset files are derived from [UnvanquishedAssets](https://github.com/UnvanquishedAssets), are licensed accordingly, and I take no extra credit for any modifications.

File                                   | Source                                                               | License
---------------------------------------|----------------------------------------------------------------------|---------
`sound/weapons/rocketpod/flash0.opus`  | [freesound.org](https://freesound.org/people/qubodup/sounds/182794/) | CC0
`sound/weapons/rocketpod/flash1.opus`  | [freesound.org](https://freesound.org/people/qubodup/sounds/182794/) | CC0
`sound/weapons/rocketpod/flash2.opus`  | [freesound.org](https://freesound.org/people/qubodup/sounds/182794/) | CC0
`sound/weapons/rocketpod/missile.opus` | [freesound.org](https://freesound.org/people/qubodup/sounds/182794/) | CC0

License links:

- [CC0](https://creativecommons.org/public-domain/cc0/)
