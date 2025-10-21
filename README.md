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

## Open-Source Assets
### W1
- Animals: https://assetstore.unity.com/packages/3d/characters/animals/animals-free-animated-low-poly-3d-models-260727 
- Low-poly environment: https://assetstore.unity.com/packages/3d/environments/landscapes/low-poly-simple-nature-pack-162153 