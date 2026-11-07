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
* Using rect() will make a rectangle which I used to make the grass. using"pos()" will tell the game where you want the position will be.
* I used "text()" to write the word hospital on the building, and I added a black border around the building and I liked how it looked, "outline(2, BLACK)". I used the position, size, and color codes to make everything look realistic.




<!-- 
* Links you used today (websites, videos, etc)
* Things you tried, progress you made, etc
* Challenges, a-ha moments, etc
* Questions you still have
* What you're going to try next
-->
