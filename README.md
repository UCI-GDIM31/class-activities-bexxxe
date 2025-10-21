# in-class-activities
## Devlogs
### W1
Hello world!

### W2
r, g, b are floats becuase they are on a 0.0 to 1 scale.
Bounce is a int because it is a whole number and not a fraction like float.
In Step 8, I didn't add a float and was struggling on how to make it work, but I learned from a TA that the float defines the brightness as a fraction and makes it work.

### W3
Question 2. We input one integer for friendship, and the other is a boolean for the secret, which depends on the relationship status. We use strings to output a response. 1. Classes are like a toolbox, and the components are the tools. Methods refer to the functions each tool performs, and members refer to the various uses and situations for which the tools can be applied. 2. The GetColorMultiplier method creates a multiplier that will be used to
make the balls brighter each time they bounce

### W4
Table 9: In line 5 "[SerializeField] private float _moveSpeed = 1.0f;" is the line asking to be descriped. Its a member variable of cat movement, its setting how fast the cat can move while also making it so that we can tune the movement speeds in unity. Line 22, "float translation = Input.GetAxis("Vertical") * _moveSpeed * Time.deltaTime;" is a float, we are getting input from the player then translates the object based on the movement and moving it based on frames. Line 25 is " transform.Translate(0, 0, translation);" this calls the component to move based on the value of translation. For the colider activity I did everything as stated on the canvas, I put the rigidbody on the Cat and Ball only because there were supossed to interact and colide. I didnt add it on the goal and checked the "is trigger" because the ball was supposed to go through the goal not be stopped by it.

## Open-Source Assets
### W1
- Animals: https://assetstore.unity.com/packages/3d/characters/animals/animals-free-animated-low-poly-3d-models-260727 
- Low-poly environment: https://assetstore.unity.com/packages/3d/environments/landscapes/low-poly-simple-nature-pack-162153 
