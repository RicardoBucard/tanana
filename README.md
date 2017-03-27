Tananã
======

> Software to learn/practice music scores. It's pronouced like "*tah-nah-naan*" É só um trabalho da faculdade, mas pode ficar bem legal.

![https://ci.appveyor.com/api/projects/status/github/graciano/tanana?svg=true](https://ci.appveyor.com/api/projects/status/github/graciano/tanana?svg=true)
  
 ![print](http://i.imgur.com/FYmVeXm.png?2)


### Project motivation

Most of the musicians I know are kind of "*semi iletrate*" in music scores. Myself included. We can read and play music, but not in an efficient way. This project was made so people like that can practice it. Most of music software today is either too professional for that, or the UX is just painful. I think the exception would be *[flat.io](http://flat.io)*, but their goal is not to be an educational software like **Tananã**.

## Project status and milestones

Currently it doesn't work quite well. It just reads a [Music XML](http://usermanuals.musicxml.com/MusicXML/MusicXML.htm#Tutorial.htm%3FTocPath%3DMusicXML%25203.0%2520Tutorial%7C_____0) file and tries to make a music score (like a bazillion other projects already do). [Here is a video](https://drive.google.com/file/d/0BzCvf4xDDyNpWHpveDlud05FRlU/view?usp=sharing) with a demonstration of what the project can do right now. In the future this will be useful to practice music score reading. [Github milestones](https://github.com/graciano/tanana/milestones) are keeping track of what will be implemented, and I'm *dreaming* with having a player that checks if you are playing the score correctly in you MIDI keyboard, for example.

## This project is using:

 - [yarn](https://code.facebook.com/posts/1840075619545360) (*if you know your npm, this will be easy*)
 - [gulp](http://gulpjs.com/)
 - [electron](http://electron.atom.io)
 - [VexFlow](https://github.com/0xfe/vexflow) *to create an svg music score*

All of those dependencies, unless vezflow, must be installed globally in npm.

### Yeah, cool, but after I clone the repo, what do I do?

 - `git clone git@github.com:graciano/tanana.git && cd tanana`
 - `make` # and then, read instructions ;)
 
 **warning**: the build script in the makefile is deprecated
## License
BSD-4-Clause License, aka the first license of BSD. (It's small and in the file [LICENSE.md](LICENSE.md), read it and be happy)
