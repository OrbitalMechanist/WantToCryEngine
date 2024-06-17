#  WantToCryEngine
## iOS + OpenGL ES

Game.cpp is where you should program the game itself.
Swift just initializes the whole thing and passes in input events.
Use GameBridge to call Game event functions from Swift.

My priority for now is filling the basic requirements for a course. Once that's
done, I'll try to optimize and refactor some things, such as better encapsulation.

Now featuring the worst physics you have ever seen!

Textures are using texture image units for now, and probably forever.
Arrays aren't really worth the hassle of having to have all the textures
be the same size for the purposes of this project.
Maybe I'll optimize things a little if I can get around to it, but for now
the priority is filling the basic requirements.

Ease of use was very important when developing this engine. Some stuff is
less efficient than it could be because I wanted an inexperienced
user to make the final game without too much trouble.
