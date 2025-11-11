# in-class-activities
## Devlogs
### W1
When the camera is removed from the rest of the children of the cat the camera is now stuck in a singular spot while the player can still move the cat around.

### W2
1. The r, g, and b variables are floats because they represent a color value that isn't defined by integers alone, but by fractions. So we must identify them as floats instead of integers.

2. The _bounce variable is an integer because a "bounce" cannot be done in fractions like a float. Instead we use integer because it uses solely whole numbers for descrbing how many bounces the ball has done.

3. The error message I received said "colon expected" which helped me figure out that I needed to add a colon to make the line of code a statement and be able to run in unity.

### W3
1. Our table is number #3 and we concluded that the return type would be a bool type and that would mean the parameters are setup as false, and so if the player misses the beat it stays false until the player does hit the beat, then it will become true.

2. Components are like concerts, making classes the perfomance itself while member variables are the specific artists playing in the perfomacne which leaves the methods as the instruments being used to make the music for the performance.

3. I believe the balls get really bright when they bounce too much because the rgb used to color them gets too high, and most likely gets so bright that it turns white since it is most likely something to do with saturation when the colors are changing.

### W4
1. Table 3: Line 5 declares a private void as a way to keep the code within it's own class and not have other classes change it. It also uses SerializeField to be able to view and change the class within Unity's inspector window. Line 22 is declaring the translation variable to equal the player's vertical input to be mutliplied by _movespeed and Time.deltaTime. Line 25 is declaring transform as a way to store the position of the cat while calling the translate method, and then the method is calling the translation variable to act only for the z axis.
2. The solution we came up with for the collider activity was giving the rigid body to both the cat and ball so that they could both interact with each other physically. Then, we gave the goal the ontrigger so that the ball could still go through the goal without colliding with the box, but at the same time it is being detected by the box collider.
3. We had to fix the size of the capsule collider to make it so that the cat wouldn't be floating in the air, because before the collider was a huge sphere but we fixed it to more properly fit the shape of the cat.

### W5
1. I had a question about what positiveinfinity and negativeinfinity do in the vector script provided by Unity. I learned that they put a gameobject at the very edge of a plane and it makes the object not visible at all but still accessible. You wouldn't use this in your actual game but more so to find the distances between objects in your scene since the object with positive/negativeinfinity would be the farthest object in the scene.

2. The member variable we want to define is the GameObject we want the deer to track because we should still be able to adjust it. The only method we want for this class is the Start() method which tells the deer to start moving as soon as the game begins running. This method should have the deer utilize the navmeshagent and setdestination so that it will be moved to a specific target which in this case would be the mushroom.

### W6
1. The Category I was assigned was Unity Coding.
[Week 6 Class Activity: Class Resource Guide](https://docs.google.com/document/d/12M9ND9VMCNH2GKoPRBsCeOYkleAXUMs-frSjHPjas9A/edit?tab=t.vdnl7cv1xpid)

2. Plan: The member variables we need are movement speed and the cat's position through a transform variable. Then for the two methods we make the bat chase the player/cat by making a translate method to move the bat towards the player and then the other method should stop the bat from moving so we would transform the bat's position to it's own position which would stop the bat altogether.

### W7
1. I planned the outline for the UI elements for our game. [Week 7 Activity 1: Designing a game engineering plan](https://docs.google.com/document/d/1yZqnc3GyaietJAPdXlV0iO8EaXxBU-2bWMjaaw1TMe4/edit?tab=t.0)

2. The issue in Step 2 was the line of code was trying to use transform.position when you should be using transform.Translate with the movement float in order to have the muskrat move forwards and backwards.

## Open-Source Assets
### W1
- Animals: https://assetstore.unity.com/packages/3d/characters/animals/animals-free-animated-low-poly-3d-models-260727 
- Low-poly environment: https://assetstore.unity.com/packages/3d/environments/landscapes/low-poly-simple-nature-pack-162153 