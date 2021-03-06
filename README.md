## Technobear's Orac virtual modular 


Orac is a virtual modular based on Pure Data , utilising externals (KontrolRack/KontrolModule) from my MEC projects.

Its is designed to be easy to use on lightweight computing platforms, and provides features such as Presets and Midi Learn.

As well as being flexible for users, its is designed to be is for 'Module Patchers' to create new modules, and thus extend the ecosystem.


### Videos
A couple of views have been made, which help show Orac , and how to use it.

https://youtu.be/-m8p9E-WGWE
https://youtu.be/raTvethmcqc
https://youtu.be/ilHzy4mNu3w
https://youtu.be/Z1fYYE622Iw


### Platforms
The code is cross-platform, and I run it on the Organelle, Raspeberry PI and Bela.
(also for development purposes I run it on macOS)
Currently, Ive released only on Organelle, but this is just because I want to add a 'web interface' before releasing on rPI and Bela... 
(its on its way ;) )

### Building
This projects contains the Pure Data aspects of Orac, as mentioned above it utilises MEC
MEC can be found/built here : https://github.com/TheTechnobear/MEC
MI externals (used in some modules) can be found here: https://github.com/TheTechnobear/Mi4Pd

### Release
I release 'builds' of Orac on PatchStorage.com


### Contribution
This is an open source project, and Im happy if others would like to collaborate/extend etc.
Generally Id recommend contacting me first, so we can co-ordinate efforts, but Im also willing to review Pull Requests.


### Credits:
Id like to extend  thanks to open source developers who make these kinds of projects possible, 
and special thanks to Critter and Guitari for open sourcing their wonderful patches which I have 'modularised', similarly Id extend the same thanks to Mutable Instruments whos code I have used to create PD externals for use in Modules in Orac.

### Project Structure
This is still in flux, until I release on all platforms

Currently, Ive placed different platforms in different directories, this is so I can have differnt external (binary) builds stored, and also some modules are not applicable to all platforms
Organelle, is usually the latest verions of modules etc, so consider this 'the base'

This is all very likely to change, once Ive release for rPI/Bela, when these will be combined, and I suspect I'll create build/installer scripts to gather relevant things together for each platform.

Its also possible that the modules will be moved into a seperate directory (again, once an installer script is written)

so If you want to change something, probably the Organelle diectory is the right place, but again easier to discuss with me ;) 



Happy Patching 

Mark Harris aka TheTechnobear
