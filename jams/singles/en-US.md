# How to Make a Simple Game in GameMaker Studio

### Description  
This tutorial will guide you step-by-step to create a simple 2D game in GameMaker Studio. By the end, you'll have a working game featuring a player character, enemies, and basic gameplay mechanics.

### Contributor  
- **GitHub Username:** yourGitHubUsername  
- **Slack ID:** yourSlackID  

### Thumbnail  
![Workshop Thumbnail](https://example.com/thumbnail.png)

---

## Workshop Details

| **Field**                | **Value**                                             |
|--------------------------|-------------------------------------------------------|
| **Time Estimate**        | 1-2 hours                                             |
| **Difficulty**           | Beginner                                              |
| **Keywords**             | GameMaker, beginner, game development, 2D games       |
| **Slug**                 | `simple-gamemaker-game`                               |

---

## Resources

- **Slides (Figma):** [View in Figma](https://figma.com/project)  
- **Slides (Presentation Mode):** [Play the Slides](https://figma.com/project/play)  
- **Slides (PDF):** [Download PDF](https://example.com/slides.pdf)  
- **Notes:** [Access Notes](https://example.com/notes)  
- **Poster:**  
  ![Poster](https://example.com/poster.png)  
- **Video Recording:** [Watch on YouTube](https://youtube.com/demo)  

---

## Instructions

### Step 1: Set Up GameMaker Studio
1. Download and install **GameMaker Studio 2** from [GameMaker's official website](https://gamemaker.io/).  
2. Open the software and create a new **2D Game Project**.  

---

### Step 2: Create the Player
1. Go to **Resources** > **Sprites** > **Create Sprite**.  
   - Name it `spr_player`.  
   - Draw a simple player character using the built-in sprite editor.  
2. Add an **Object**:  
   - Go to **Resources** > **Objects** > **Create Object**.  
   - Name it `obj_player`.  
   - Assign `spr_player` as the sprite.  
3. Add movement to the player:  
   - Open the `obj_player` and add an **Event** > **Keyboard** > **Key Press** > **Arrow Keys**.  
   - Add movement actions for each key (e.g., `x = x + 4` for right).  

---

### Step 3: Add Enemies
1. Create another sprite and object for the enemy:  
   - **Sprite:** `spr_enemy`.  
   - **Object:** `obj_enemy`.  
   - Assign `spr_enemy` to `obj_enemy`.  
2. Add basic movement to the enemy:  
   - Use the **Step Event** to make the enemy move in a straight line or bounce off walls.  

---

### Step 4: Add a Collision
1. Open `obj_player` and add a **Collision Event** > **obj_enemy**.  
   - In the event, add actions to display a **Game Over** message or restart the game.  

---

### Step 5: Create a Level
1. Open the **Room Editor** and add `obj_player` and `obj_enemy` to the room.  
2. Arrange the objects to design your game level.  

---

### Step 6: Test the Game
1. Click the **Run** button (green triangle) to test your game.  
2. Debug any errors and make adjustments.  

---

## Optional Add-Ons
- **Score System:** Add objects to collect points.  
- **Music/Sound Effects:** Use the sound editor to add background music or effects.  
- **Multiple Levels:** Create additional rooms for more levels.

---

## Notes  
- You can extend the game by following advanced GameMaker tutorials.  
- Save your progress frequently to avoid losing work.

---

## Example Game
- Check out this [example project](https://example.com/game-project) for inspiration.
