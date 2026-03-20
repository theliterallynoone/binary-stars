hi, so i learnt this through chatgpt 
(and no, i didnt vibe code it)

so heres little things i picked up that are helpful 

Step 0: Forget stars. Think “moving dots”
Before gravity, before physics—just learn:
👉 how to move a point on screen
Step 1: Understand position + velocity
Right now:
x, y = position
the +1, +0.5 = velocity
So motion =
👉 new position = old position + velocity
Step 2: Add acceleration (tiny physics entry)
Now instead of constant velocity, we let it change.
Step 3: Replace “downward gravity” with “toward a point”
Instead of pulling down, we pull toward a point (like a star).
Let’s say the star is at (0,0)
Now it curves → orbit-ish behavior 

how do i make both points pull each other?
Core idea (super simple)
Earlier you had:
1 moving object
1 fixed point (center)
Now:
👉 BOTH are moving
👉 BOTH pull each other
🧩 Step 1: Two positions, two velocities
which means that we'll now have two sets
Step 2: Distance between them
This part is SAME logic as before
Step 3: Direction of force
This gives direction from star1 → star2
Step 4: Apply force BOTH ways
Here’s the key 
👉 Star 1 is pulled toward Star 2
👉 Star 2 is pulled toward Star 1
So accelerations are opposite
also notice the minus sign = opposite direction
Step 5: Update velocities
Step 6: Update positions
Step 7: put it all together-
👉 Two objects
👉 Mutually attracting
👉 Orbiting each other

Mini intuition trick
Think of it like:
invisible spring pulling them together
but sideways velocity keeps them from crashing
Boom → orbit

and now i animate it
YAY, I DID IT (SIMPLE ORBITS THO)

okay cool so i have now added-
Visual glow: colored stars, glowing trails, starry background
Real physics upgrade: unequal masses → asymmetric orbit (WAY more realistic)
Supernova moment: collision detection, explosion effect, stars turn bright white
Inspiral effect-
slow energy loss → spiral → BOOM

okay so update- what i’ve built right now is basically a springy chaos system, not a clean orbital system (yet)
ive accidentally built atoms or smthn revolving each other and themselves in orbit
wait i think its the physics-

next up- them merging in a black hole