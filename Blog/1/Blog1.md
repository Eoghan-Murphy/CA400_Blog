# Blog 1 - Getting the ball rolling again

2020 has been strange, a lot happened but at the same time it was a sort of hibernation. I started the year, trying to make the most of my academic deferral by travelling to southeast Asia. When I got back around the start of march the world was experiencing a global pandemic, and nothing's really changed since. I'd like to say I took all that extra free time to formulate a solid project idea, but in reality, I only tried out a few random ideas, not really spending more than a week on each. I did however have the time to improve my 3D modelling skills, game development skills and networking skills. I also had the time for them to rust over again. That's why I thought it would be important to start again, and document my process in this blog. 

### Idea for prototype

For my 4th year project, I'm leaning towards a networked game built in Unity. I think it's feasible but want to check by developing a small prototype,  a first person "game" where multiple players can move around and interact with physics objects. If I can do this, I should be able to make my actual idea a reality. 

### Early Design

Normally I'd just start writing code wildly, and throwing everything together, but I wanted to be able to reuse some of this code for my actual project. I decided to start by developing some UML class diagrams for the prototype. Mainly classes for the player and the logic to do with controlling them.

![UML Diagram describing classes to do with controlling the player](C:\Users\Eoghan\Desktop\Project\Blog\1\playerUML.png)

My UML skills were a bit rusty, but it helped tremendously, I had forgotten how helpful it is to have any sort of design documents prepared. In far less time then I expected, I had working first person controls, in a primitive environment.

![gif showing first person gameplay](C:\Users\Eoghan\Desktop\Project\Blog\1\firstperson.gif)

### Interactable Items

Next I wanted to add interactable items. I decided on simple physics based objects that the player can lift up (creatively named 'Liftables'...) and items which play an animation when interacted with (I'm still working on this as Unity's default animation tools don't want to cooperate). The UML diagram for this step was very simplistic:

![UML class diagram for Interactable class](C:\Users\Eoghan\Desktop\Project\Blog\1\interactable.png)

And here's the what it looked like implemented:

![interactable](C:\Users\Eoghan\Desktop\Project\Blog\1\interactable.gif)

### What's Next

My progress so far isn't anything to brag about, but it was invaluable in getting me back into shape. Now I'll move onto getting the prototype networked, and will see if my project idea is viable.

