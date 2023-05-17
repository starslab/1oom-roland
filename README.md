# 1oom-roland
Roland MT-32 music packs for 1oom!

These are 1oom compatible PBX files that replace the mostly-awful MIDI music with the original less-awful MT-32 musics as rendered by MUNT in Super-CM-32L mode.

Learn more about 1oom, an open-source Master of Orion engine re-implementation, here:
* https://gitlab.com/Tapani_/1oom
* https://github.com/1oom-fork/1oom

There are two files in this distribution:
* roland_music_normal.pbx
* roland_music_reverb.pbx

The \_reverb file was recorded with a Front Panel 8/10 reverb setting. Some people will like this. Some will not. You can preview both music packs at the following YouTube playlists:
* https://www.youtube.com/playlist?list=PLQfcsYP5T4-Ezqrluq_F-oCa0epgYAyxI
* https://www.youtube.com/playlist?list=PLQfcsYP5T4-GxYYMR7mCl-cd3dYy1GLxv

The very limited testing I've done has indicated the game randomly crashes with one of these packs active, but I haven't been testing long and I don't know if it's crashing because of the music or something else.
There's an issue on 1oom-fork here: https://github.com/1oom-fork/1oom/issues/12 - If you have either a positive or negative experience, feedback would be appreciated!

Additionally, 1oom does not currently loop musics that are provided in digital formats like this. So the Main Menu, GNN News, and race diplomacy musics will play twice and stop. This is also being investigated at the issue above. If you are familiar with the coding required to implement Ogg LOOPSTART metadata support, such as found in RPGMaker and SDL_Mixer2, please drop a comment on that issue!

Installation is fairly straightforward. Drop the music packs into your 1oom directory, then edit the shortcut you launch the game from (If you don't use a shortcut, you're going to want to start), adding `-file roland_music_normal.pbx` or `-file roland_music_reverb.pbx` as appropriate.
