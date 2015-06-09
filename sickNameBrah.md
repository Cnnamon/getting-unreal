##Blueprint remindes

###Getting an object (actor)

_Select actor, right click in blueprint section_

###Proximity - Use volume (the area).
###No simultanous stuff, just sequential.
###Delays possible.

##Optimization reminders

###Turn off smooth render

###Important commands
stat Unit - displays rendering information  <br />
stat UnitGraph - self explanatory <br />
stat fps - self explanatory <br />
profilegpu - get a rundown of whats taking how much time <br />
stat startfile - get a "record" of the game. stat stopfile - to end it <br />
for more commands and detailed info: https://docs.unrealengine.com/latest/INT/Engine/Performance/StatCommands/index.html <br />

###Graph tips
if the game render time jumps along with everything else - the game code is lagging <br />
whatever is closest to the frame time, thats the bottleneck <br />

###Session profiler - used to examine recordings and determine which part isn't doing so well
