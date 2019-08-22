<!--- REVISED -->
# Lab 1.4: Sprites in Action

In this lab, you will use costumes and movement to create simple SNAP animations. You will also use broadcast and receive blocks to trigger actions in sprites.

Before you get started on this lab, be sure to preview the Student Notes for this lesson!

## Minimum Viable Product: Run, Spot, Run!

1a) In a SNAP project, click on the Costumes tab. Then, click on the file menu and choose the "Costumes" option. 

|![Illustration of the Costumes tab, File menu, and Costumes option](Costumes_tab.PNG)|

1b) Import the costumes "dog2-a" and "dog2-b".

![IIllustration of how to import a costume. In this picture, the "Dog2 a" costume has already been imported. The user is about to import the "Dog 2b" costume](dog_costumes.png)

2) Add code so that the sprite changes to the next costume each time the left arrow key is pressed. 

3) Add code so that the sprite does the following when you press the left arrow key:
  - Faces to the left
  - Moves 10 steps forward 
  > *Hint: The rotation buttons in the Costumes tab toolbar can be used to control how a sprite rotates!

4) Add code so that if the dog reaches the edge of the stage, it bounces.
  >*Hint: You will need one of the blocks in the "Motion" category for this!

5) Right click on the script you created and choose the "Duplicate" option. This should create a second script that is identical to the script you created in step #2-5.

6) Modify the new script so the sprite faces right and moves to the right when you press the right arrow key.

## Version 1. Here be Dragons!

7) Create a new sprite. Following the same steps as in part 1a and 1b, import the costumes "dragon1-a" and "dragon1-b"

8) Write a script to make the sprite appear to breathe fire when the 'f' key is pressed.  The sprite should switch to the "fire-breathing" costume for a few seconds, then switch back to the "normal" costume.

9) Modify your code so that the dragon "attacks" the mouse pointer when the 'f' key is pressed. When the 'f' key is pressed, the dragon should take the following actions in order:

-   Make sure it is in the "normal" costume
-   Point at the mouse pointer
-   Glide to the mouse pointer's position
-   Change to the "fire-breathing" costume
-   Pause to breathe fire
-   Change back to the "normal" costume

## Version 2. Run Away!

10) Add another sprite to your program.  (This sprite can have any costume you choose.)

11) Write a script to make this new sprite point away from the dragon and move when the 'r' key is pressed.  (You'll need more than one block to do this.)

12) Modify your code so that instead of moving when the 'r' key is pressed, the new sprite moves when the dragon "attacks."  The "fleeing" sprite should move when the dragon starts breathing fire.

13) Add a second sprite that runs away from the dragon as well.

## Grading Scheme/Rubric

| **Lab 1.4 Criteria**                              |                |
| ------------------------------------------------- | -------------- |
| 2.2 Dragon breathes fire                          | 0.25 points    |
| 2.3 Dragon attacks mouse pointer correctly        | 0.75 points    |
| 3.2 A sprite runs away from dragon                | 0.25 points    |
| 3.3 Sprite runs away when dragon breathes fire    | 0.5 points     |
| 3.4 Another sprite runs away too                  | 0.25 points    |
| **PROJECT TOTAL**                                 | **2.0 points** |
