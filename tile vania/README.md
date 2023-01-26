﻿# Complete Unity Developer - Section 6 - TileVania

This is the [Complete Unity Developer](http://gdev.tv/cudgithub) - one of the most successful e-learning courses on the internet! Completely re-worked from scratch with brand-new projects and our latest teaching techniques. You will benefit from the fact we have already taught over 360,336 students game development, many shipping commercial games as a result.

You're welcome to download, fork or do whatever else legal with all the files! The real value is in our huge, high-quality online tutorials that accompany this repo. You can check out the course here: [Complete Unity Developer](http://gdev.tv/cudgithub)

## In This Section
Build a Speulnky-like level in under one minute using a procedural Tilemap smart brush that you build yourself! (Section REF: TV_CUD)

## How To Build / Compile
This is a Unity project. If you're familiar with source control, then "clone this repo". Otherwise download the contents, and navigate to `Assets > Levels` then open any `.unity` file.

This branch is the course branch, each commit corresponds to a lecture in the course. The current state is our latest progress.

## Lecture List
Here are the lectures of the course for this section...


### 1 Welcome To TileVania ###

**In this video (objectives)…**

1. We'll be taking on Tilemap.
2. A note about where this section fits within the course.

**After watching (learning outcomes)…**

Explain to a fellow student roughly what we're building, and why this is awesome stuff to know.


### 2 TileVania Game Design ###

**In this video (objectives)…**

1. Be clear on the core game design for this section.
2. Understand the creative options that each student has for making this game their own.

**After watching (learning outcomes)…**

Explain to a fellow student the design of what we'll be building and to start exploring options for creativity.


### 3 Slicing Sprite Sheets ###

**In this video (objectives)…**

1. Import sprite sheets to be used for our platformer.
2. Use the automatic or slice-by-grid options in Unity to slice our sprite sheet into individual sprite images for our game.

**After watching (learning outcomes)…**

Be capable of slicing sprite sheets to make individual assets.


### 4 Intro To Unity Tilemap ###

**In this video (objectives)…**

1. Create multiple tile map layers.
2. Build multiple tile palettes.
3. Paint a simple level.

**After watching (learning outcomes)…**

Able to import a sprite sheet, slice it up, create tile palettes and paint a simple level layout.


### 5 Unity Rule Tiles ###

**In this video (objectives)…**

1. Download the Unity 2D asset.
2. Create rule tile rules.
3. Paint additional platforms using rule tile.

**After watching (learning outcomes)…**

Create a rule tile and set up the logic for its rules.


### 6 Create Player Idle Animation ###

**In this video (objectives)…**

1. Create player idle animation clip from sprite sheet.
2. Add animation to Animator Controller.
3. Add Sprite Renderer and Animator to Player character.

**After watching (learning outcomes)…**

Created 4 frames of 2d character idle animation which plays automatically when the game plays.


### 7 Animation States & Transitions ###

**In this video (objectives)…**

1. Create animation clips for run and climb.
2. Add animation states for each animation clip type.
3. Add bool parameters to switch between animation states.
4. Add transitions between the animation states.

**After watching (learning outcomes)…**

Able to construct an animation state machine with transitions and triggers.


### 8 Implement 2D Collision ###

**In this video (objectives)…**

1. Add RigidBody and collision to the player.
2. Set up composite collision on our environment.

**After watching (learning outcomes)…**

Drop our player from a height and have it land on the platform.


### 9 Maximize Learning Value ###

**In this video (objectives)…**

1. Context for the gameplay functionality we are about to create.
2. The best way to learn and become better at being a programmer.

**After watching (learning outcomes)…**

Understand how to get even more value from this course in terms of your learning and skills.


### 10 Move Player Horizontally ###

**In this video (objectives)…**

1. Create Player class.
2. Import CrossPlatformInput.
3. Move the player's RigidBody horizontally.

**After watching (learning outcomes)…**

Move the player horizontally using CrossPlatformInput.


### 11 Flip Character Sprite ###

**In this video (objectives)…**

1. Introduce Mathf.Abs and Mathf.Sign.
2. Pseudocode for flipping character sprite.
3. Flip character sprite based upon player having horizontal velocity.

**After watching (learning outcomes)…**

Flip the player character's sprite whenever the character has horizontal velocity.


### 11b Instructor Hangout 6.1 ###

**In this video (objectives)…**

1. We discuss the difference between caching and calculating.
2. Why did we set up the flip sprite the way we did rather than starting with an isFacingRight bool.
3. Ben makes a bad joke at the end of the video.

**After watching (learning outcomes)…**

Greater understanding of the cache versus calculate options we have.


### 12 Animation State In Code ###

**In this video (objectives)…**

1. Use code to set the animation transition bool.
2. Make the player transition to the running animation when the running transition condition is called in our script.

**After watching (learning outcomes)…**

Make the player's run animation state be triggered from code.


### 13 Jumpy Jumpy ###

**In this video (objectives)…**

1. Revise how velocity is being applied to our player's RigidBody.
2. Add a positive y velocity to cause the player to jump.
3. Tune the global gravity and player jump speed to give the right feel for our game.

**After watching (learning outcomes)…**

Make your player jump and fall in a way which feels good to play.


### 14 Jump if IsTouchingLayers ###

**In this video (objectives)…**

1. Review how layers work as a way to apply the same functionality to many GameObjects.
2. Implement IsTouchingLayers for our collision check.
3. Only allow the player to jump if he is touching the ground.

**After watching (learning outcomes)…**

Make the player jump only when touching the ground layer.


### 15 Climb Ladder ###

**In this video (objectives)…**

1. Create ladder tile.
2. Set up the climb tilemap, sorting layer and collision layer.
3. Transition to climb state if player is touching ladder.
4. Move player's y velocity when input is received.

**After watching (learning outcomes)…**

Move the player up and down on a ladder with appropriate climbing animation state.


### 16 Climb Ladder Tweaks ###

**In this video (objectives)…**

1. Fix bug where player does not transition out of climb state.
2. Change gravity while on ladder to stop player sliding back down.

**After watching (learning outcomes)…**

Able to stop player sliding on ladder.


### 17 Perspective Vs Orthographic Cameras ###

**In this video (objectives)…**

1. Review the fundamental differences between the camera types.
2. Explain the reasons why we might use one camera over the other.

**After watching (learning outcomes)…**

Understand the differences in perspective and orthographic cameras.


### 18 Cinemachine Follow Camera ###

**In this video (objectives)…**

1. Import and set up Cinemachine.
2. Create a Cinemachine brain and Cinemachine virtual camera.
3. Tune the dead zone, dampening and look ahead of our camera.

**After watching (learning outcomes)…**

Be skilled at setting up a 2D follow camera using Unity's Cinemachine.


### 19 Cinemachine Confiner Extension ###

**In this video (objectives)…**

1. Create physics layers for Player and Background and alter the collision matrix so that the correct things can collide with one another.
2. Create a bounding box for the Cinemachine confiner.
3. Tune level and camera so that the player can only see what we want them to see.

**After watching (learning outcomes)…**

Implement the Cinemachine confiner extension.


### 20 State-Driven Cameras ###

**In this video (objectives)…**

1. Add a state-driven camera to the scene.
2. Link the player animator states to the camera states by creating additional cameras.
3. Adjust the blending between cameras.
4. Experiment with camera shake.

**After watching (learning outcomes)…**

Implement state-driven cameras using Unity Cinemachine.


### 21 Prevent Wall Jump ###

**In this video (objectives)…**

1. Add physics material to stop sticking to wall.
2. Add additional collider to represent player's feet.
3. Only allow feet to determine if player is touching the ground.

**After watching (learning outcomes)…**

Prevent funky wall behaviour.


### 22 Making Enemies ###

**In this video (objectives)…**

1. Import enemy sprite and set up required components.
2. Script a way for the enemy to flip when it reaches the end of a platform.

**After watching (learning outcomes)…**

Create an enemy that moves along platforms, turning when it reaches the end.


### 23 Player Death ###

**In this video (objectives)…**

1. Trigger player death when player collides with enemy.
2. Disable player control when player is in death state.
3. Implement some kind of dramatic death reaction.
4. Change player animation state when dying.

**After watching (learning outcomes)…**

Create vulnerability in the player by triggering a dramatic death.


### 24 Adding Hazards ###

**In this video (objectives)…**

1. Import some spikes.
2. Set up a "Hazards" tilemap.
3. Build the behaviour of the "Hazards" tilemap so that it harms the player.

**After watching (learning outcomes)…**

Create hazards in your levels which harm the player.


### 25 Level Flow Layout ###

**In this video (objectives)…**

1. Look at the method of laying out multiple scenes in the hierarchy.
2. Discuss level flow.
3. Create our first 3 levels for the player.

**After watching (learning outcomes)…**

Create the flow for the first 3 levels for the game.


### 26 Level Exit Portal ###

**In this video (objectives)…**

1. Create a level exit portal sprite.
2. Create coroutine for loading next level.
3. Set up build scene indexing.
4. Load next scene when player enters portal.

**After watching (learning outcomes)…**

Load the next scene when the player enters a portal.


### 27 Start & Success Screens ###

**In this video (objectives)…**

1. Add a start game button.
2. Add a success scene.
3. Add a replay game button.

**After watching (learning outcomes)…**

Be able to create start and success screens with corresponding buttons.


### 28 Game Session Controller ###

**In this video (objectives)…**

1. Create singleton for Game Session script.
2. Determine whether player has any lives remaining.
3. Reload current level or reset game to main menu if player has no lives.
4. Call the public method that processes the player death within Game Session class.

**After watching (learning outcomes)…**

Elegantly process the player death, loading and reseting of game.


### 29 Coin Pickups ###

**In this video (objectives)…**

1. Import and animate coins.
2. Create mechanism where the coins are picked up and destroyed.

**After watching (learning outcomes)…**

Start the process of creating a coin pickup which destroys when player touches it.


### 30 Persistent SFX ###

**In this video (objectives)…**

1. Examine the different ways to ensure SFX is not destroyed when game object is destroyed.
2. Implement PlayClipAtPoint() and reposition so that it is next to the camera.

**After watching (learning outcomes)…**

Trigger a SFX that persists even when the Game Object which triggered it is destroyed.


### 31 Persistent Score & Lives ###

**In this video (objectives)…**

1. Create UI text for lives and for score.
2. Show the lives and score text based upon the starting values.
3. Update lives and score when player dies or picks up coins.
4. Apply the singleton pattern to lives and score so that they persist when player dies.

**After watching (learning outcomes)…**

Display and update score and lives on the UI and persist their values when player dies and respawns.


### 32 Remembering Pickups ###

**In this video (objectives)…**

1. Create a scene persist script that uses a singleton pattern to not destroy any children objects (such as pickups).
2. Within our scene persist, check if the current build index differs to starting build index.
3. Destroy scene persist object if we move on to the next level.

**After watching (learning outcomes)…**

Create a system to allow objects to remember their state within a scene.


### 33 Adding Rising Water ###

**In this video (objectives)…**

1. Create a new water layer with some watery looking water on it.
2. Create a new script which allows us to scroll the water vertically to create a time hazard.

**After watching (learning outcomes)…**

Create a moving water hazard for the player to avoid.


### 34 Over To You Now ###

**In this video (objectives)…**

1. Well done for finishing this section.
2. There is so much that you can do with this platformer now to make it really exciting to you.

**After watching (learning outcomes)…**

Onwards and upwards!