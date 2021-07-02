# Making A Unity Game
My project is building a Unity Game from Scratch!

| **Engineer** | **School** | **Area of Interest** | **9** |
|:--:|:--:|:--:|:--:|
| Eric Chen | Palo Alto High School | Electrical Engineering | Incoming Sophmore

![Headstone Image](https://bluestampengineering.com/wp-content/uploads/2016/05/improve.jpg)
  
# Final Milestone
My final milestone was to make a background, end the game when the robot touches an enemy bomb, and make a GameOver scene to transfer the scene after the robot has been hit by a bomb. I also changed how high the robot can jump, where the enemy bomber spawns, and when the platforms move. When I made the collision script, I had to use OnCollision2D instead of OnCollision because it was a 2D game, and if you didn't you would get errors. I also used setactive, which made an object active or not active. I used this this to pause the actions of my robot when it was hit by an enemy bomber.I then used SceneManager.LoadScene("") to load the game over scene.
)
[![Third Milestone](https://res.cloudinary.com/marcomontalbano/image/upload/v1625245196/video_to_markdown/images/youtube--HgCicNDgtKA-c05b58ac6eb4c4700831b2b3070cd403.jpg)](https://youtu.be/HgCicNDgtKA "Third Milestone"){:target="_blank" rel="noopener"}

# Second Milestone
My Second Milestone for my project was to make import components of an infinite runner game. I learned how to create an infinite ground so my main character wouldn't fall off, and I changed the infinite platforms so there were more of them. I then started working on the enemy and the enemy movements. I learned how to move the enemy towards the user when the game is started by checking how far the distance was between the user and checking if the enemy needed to move left or right. I used this to make the enemy always move to the user, so it could chase it forever. I then created how the enemy drops bombs from the top. I used Time.deltaTime to do it. Last but not least, I created the animations for the bomb to explode. It would delete after the animation happened.

[![Second Milestone](https://res.cloudinary.com/marcomontalbano/image/upload/v1625245021/video_to_markdown/images/youtube--PpinHj2AXRA-c05b58ac6eb4c4700831b2b3070cd403.jpg)](https://youtu.be/PpinHj2AXRA "Second Milestone"){:target="_blank" rel="noopener"}
# First Milestone
  
My first milestone was setting up Unity, learning the basics of scripting with C# and adding components and objects in Unity. I learned how to set variables by using a making an public variable, and I learned how I could use them to create other things, such as making game objects. I learned how to add objects in the Unity game so I could script something with them. The first object I created was a floor, and I was taught how to add a component called a Box Collider 2D, which detecs if another object "collides" or runs into it. I used this knowledge to create another object with a robot sprite. I used the component Physics 2D and Box Collider 2D to make my robot object fall onto the ground instead of falling right through the ground object. I then learned the two functions Unity gives you at the start, void start and void update. Void start only runs at the start of script, but void update runs every single frame. I used this information to learn how to move my sprite robot from left to right by calling the velocity of the sprite and changing it by multiplying. I then created an input for loop to check if the Spacebar was pressed so I could implement the jump for my game. The last thing I did for this milestone was implementing prehabs and instanciating them. Instanciating something in C# means to create a copy of it, which is extremely useful for infinite platforms and scenarios in a game. Overall, this milestone I learned the basics of Unity Scripting and learned how to implement that knowledge to make certain things.


[![First Milestone](https://res.cloudinary.com/marcomontalbano/image/upload/v1625244288/video_to_markdown/images/youtube--24N3mv7mrO8-c05b58ac6eb4c4700831b2b3070cd403.jpg)](https://youtu.be/24N3mv7mrO8 "First Milestone"){:target="_blank" rel="noopener"}
