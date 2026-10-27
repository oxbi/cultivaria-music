# cultivaria-music

Music library for a private Minecraft modpack (the Cultivaria port). It is not a mod and not for redistribution.

The library is one resource pack, `cultivaria-music.zip` (507 songs, OGG Vorbis 112 kbps), attached to the
[releases](../../releases) of this repo. It is not stored in git history.

The pack's updater downloads it once into `config/paxi/resourcepacks/` and checks its sha256 on later runs.
If this download is unreachable the pack still works; the in-game boombox just shows an empty list.
