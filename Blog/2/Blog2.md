# Getting the prototype online

To ensure that my project idea was viable I wanted to first make a networked prototype, a simple first person game where players can interact with objects and have everything tracked over a network. I got to work researching Unity multiplayer solutions and came across the third party Unity Server Client Networking API, Mirror.

### Few bumps in the road

Luckily my core design from my first blog post didn't really need to change, I just had to adapt it to use a few premade Mirror classes. All the calls to move the players just had to be passed through the server to all connected clients. However being relatively niche, Mirror only has a handful of tutorials online so I had to delve deep into the documentation whenever something wasn't working, which happened a lot. Unity has a tendency to require you to do a lot in the GUI inspector. This can be an issue when you've scoured your code trying to fix a bug only to realize you ticked a box somewhere in the inspector 3 hours ago to test out a functionality of a built in component.

### Results

Everything mostly just worked in the end, once I was more familiar with the library adapting my prototype to allow for multiple players wasn't too hard (Notice I'm controlling both players here, but I have tested it over a network with another player):

![quick demonstratin of a second player picking up a physics object](C:\Users\Eoghan\Desktop\Project\Blog\2\ezgif-7-0c70abadabe2.gif)

There's still a bit of lag and noticeable stuttering, but I believe I can fix this with a bit more work.

### Future Plans

This simple prototype proves a networked game is feasible. Next I'd like to experiment with Lua scripting to make a small prototype that can me modded with user scripts. 

