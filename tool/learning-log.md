# Tool Learning Log

## Tool: **Kaboom/VUE**

## Project: **Game/studyguide**

---

### 10/19/26:
#### Learning Kaboom 

So we have started to learn our tool that we have picked. I picked Kaboom and now it time to learn it. I don't know where to start so first I'm going to look at some examples that are on the website.

##### Links
GitHub of Kaboom -> https://github.com/replit/kaboom?tab=readme-ov-file#notice <br>
link to playground -> (https://kaboomjs.com/play?example=add<br>

    * I made a separate file in my tools folder so I can test out some code from the website.

    * I learned "setGravity()" can be used to make the character go down from the top of your screen, and depending on what number you put it is how fast or slow it will go down the screen. 

    * There is a playground in Kaboom where there is 4 characters and each time you click run, its in a different position in the output but the code doesn't change. 

This adds a rectangle, which I think can be used as an obstacle for the game I will make.
```
add([
    pos(80, 120),
    rect(20, 40),
    outline(4),
    area(),
])
```
Adding a circle 
```
add([
    pos(80, 120),
    circle(16),
])
```

I watched a video from the channel `ourcade`, and I watched the video `5 tips for getting started with Kaboom.js`. Here are some things I learned.

**Creating game objects**
* Use `k.add()` to create objects
* Add components to decide what the object looks like and what it can do
*    `k.pos()`- where the object is
*    `k.rect()`- makes a rectangle
*    `k.spite()`- gives the object an image
*    `k.body()`- lets gravity affect the object
*    `k.solid()`- stops objects from passing through each other.
*    

**Making objects collide**
* Make a player fall using gravity
* You can create a floor for the player to land on
* Use `k.body()` to make the player fall
* Use `k.solid()` to stop the player from falling through the floor

**Adding animations**
* Learning how to load images into the game
* Use `k.loadSprite()` to load a sprite sheet (an image containing many smaller images).
* Choose which images to use for your animations
* Use `player.play("run")` to make your character run.
* Make the character face left or right
* Play the idle animation when the character stops moving.

**Creating game levels**
* Build a level using rows of letters and symbols
* You have to tell kaboom what each symbol means
* For example = could mean a floor tile
* Use `k.addLevel()` to create the level.
* Add floors, platforms, and a player.
* Make the player move left and right and jump.
* Make the camera follow the player as they move.



### 11/7/26:
* So first I made a new file in my ide called, kaboom.html, and what i made is pretty simple and basic.
* I made a blue background with grass, sun, and tree. with a pink character with eyes.
* Now i'm going to figure out how to add a body / build a body for my character.

* I made the body for the character and it looks okay.  now i'm going to try and add a hospital because for the game i want to make. the patient is going to leave the hospital and try to safely get home, and avoid obstacles.

* I like doing my code in Jsbin because i find it easier because I don't have to switch back and forth between tabs.
* So I have added my hospital and I really like how it turned out, at first I was gonna do only 4 windows but it felt empty, so then I changed the layout and I added six.

* First for the background, I used width , height, and background to put the setting, for how wide the screen is and how tall the screen is.
* Using `rect()` will make a rectangle which I used to make the grass. using "`pos()`" will tell the game where you want the position will be.
* I used "`text()`" to write the word hospital on the building, and I added a black border around the building and I liked how it looked, "`outline(2, BLACK)`". I used the position, size, and color codes to make everything look realistic.

### **Beach Scene**

#### My inspiration
I really miss the summer so, I wanted to create a relaxing scene with blue skies, ocean water, and golden sand to represent the summer. I added a sun to represent the sunny weather and a palm tree to give it a tropical vibe. I also added an umbrella because it makes it look more realistic. I made this at my beach.html file.

#### HOw I made it
##### Background
* I set the width to 2040 pixels and the height to 800 pixels. I made it bigger than my scene from before because I wanted it to fully fit my chromebook.
* I used the `background: [100, 190, 255]` to make the sky  be a light blue.
##### Sand
* I used add() to add the sand to the screen.
* Then I used `rect(2040, 830)`, to make a rectangle that stretches across the bottom, and then I used `pos(0, 370)`, to place it at the bottom of the screen.
##### Ocean
* For the ocean I also used a rectangle, `rect(2040, 235)`, and a nice ocean color, `color(30, 140, 220)`,.
* I use this to choose which colors I want. [RGB Color](https://rgbcolorpicker.com/)
##### Sun
* For the sun I used, `circle(35)`
* Then I used `pos(1200, 65)`, to place it near the top-right corner.
* Set the color to yellow using `color(255, 220, 50)`.
##### Tree
* I used `rect(25, 110)` to create the tree trunk.
* I used  `pos(100, 440)`  to position the trunk, then I used `color(140, 90, 45)` to make it brown.

* Then I used, `circle(45)` to create the palm tree's leaves. Then after I used `pos(112, 420)`, to put the leaves on top of the tree trunk.


   * While doing this I came across an issue because in the code I first put the top of the tree and then I put the body of the tree. Which made the tree look weird, because you could see the body of the tree on top of the leaves.

   * Then after I realized that in JavaScript  the order you put things matter. So I switched it up and put the body of the tree first then the leaves.
  
##### Umbrella
* I used `circle(45)` to create the top of the umbrella.

   * Then I used  `pos(330, 440)`, to put it on top of the sand.
* I made the color pink using `color(255, 80, 100)`
* I used rect(8, 75) to create the umbrella pole.
   *  I set the position to `pos(326, 480)`, for it to be right on top of the sand and look like an umbrella while touching the top.

##### What I practiced

|Code |Output|
| --- | --- |
|  add() | adds objects to the screen|
|  rect() | makes a rectangle|
|  circle() | makes a circle|
|  pos() | controls the position|
|  color() | changing colors|
|  text() | adds words to the screen|



<!-- 
* Links you used today (websites, videos, etc)
* Things you tried, progress you made, etc
* Challenges, a-ha moments, etc
* Questions you still have
* What you're going to try next
-->
