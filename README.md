# 🎮 Game Jam Final Submission: WariUBCO: Okanagan Outrage

## 📖 Description
**WariUBCO: Okanagan Outrage** is a retro game created for **COSC 416 Game dev Game Jam** within a set period of 2 weeks

---

## 🕹️ How to Play

- **Goal:** The goal of the game is to survive as long as possible through complete three similar minigames without losing all your three lives as the difficulty increases each round 
- **Progression:** Each three levels the difficulty will increase 

### Controls
- Each minigame will tell the controls that you need to  use
---

## 🛠️ Technologies Used

- Unity [6000.0.31f1]
- C#

---

## 📦 Installation / Play

### ▶️ Play Online
[https://btian58.itch.io/wariubco-okanagan-outrage](https://btian58.itch.io/wariubco-okanagan-outrage)]

### 💻 Local Build (Desktop)
1. Download the `.zip` file from [Google Drive / Itch.io / link].
2. Extract the folder.
3. Run `YourGameName.exe`.

---

## 👥 Team Members

| Role       | Name                |
|------------|---------------------|
| Programmer | Immanuel Wiessler(20803375) |
| Programmer    |  Adam Delfs (43151877)  |
| Programmer      | Timothy Thio 88723952    |
| Programmer     | Eddy Tian 42790253    |

---

**Feature Contribution  for this game jam for each team member is as follows:**

**(Immanuel wiessler_20803375)**
- Making the UI system (looks and feel of the game for main menu, GameOver screen, health and level)
- Making the Game Manager, which is responsible for:
  - Scene transitions
  - Health management
  - Level management
  - Resting the game(setting health to 0 and level to 1)
  - MiniGame Diffculty is exposed, allowing for manual adjustment of difficulty for the minigame in **Unity** that were made during this game Jam  
- Creation of the GameOver screen, which includes:
  - Keeping track of the last level reached by the player
  - Updating the high score if the last level reached is higher than the currently stored high score
  - A set of buttons:
    - **Main Menu**: which goes back to main menu scene 
    - **Play Again**: replaying the games, making sure that everything is reset 
    - **Quit**: Quit the application
   
- The creation of settings pages
  - Allows you to set the game to be fullscreen
  - adjust the in-game volume
   
   **commits and pulls**
    
    - https://github.com/A-Delfs/G14_GameJam/pull/1
    - https://github.com/A-Delfs/G14_GameJam/pull/6/commits/52b246c758a26a14a5db90c37717e53877a7241a
    - https://github.com/A-Delfs/G14_GameJam/pull/6/commits/fef2b72e3baa6513d17c0caa22deed3be66530a7

---

**Adam Delfs (43151877)**

- Designed the major sorter minigame whch includes:
  - Students counter
  - highlights paths based on player input 
  - success and fail sound effects 
  - camera shake on fail
  - random spanwing both in regards to location and major
  - collision prevention 
  - spawn rate and speed fields for scaling difficulty 
  - buildings based on UBCO campus


   **pr with relevant commits**
   - https://github.com/A-Delfs/G14_GameJam/pull/2/commits
 
  **polishing commit**
   - https://github.com/A-Delfs/G14_GameJam/pull/6/commits/0fbaaf165ccc50ab21b95ec9cdfd69066c388407

---

**Timothy Thio (88723952)**

- Created and designed the Avoid the TA minigame:
  - Pixel art assets with Aseprite
  - The TA detection mechanic using Raycasts
  - The Hiding mechanic so that students don't get caught by the TA
  - The walking, hiding, and caught animations
  - Spawning TAs based on the level
  - Adding smooth camera movement based on the location of the player
 
**PRs and Branches With Relevant Commits:**
https://github.com/A-Delfs/G14_GameJam/pull/5
https://github.com/A-Delfs/G14_GameJam/tree/tim-minigame

**Video Demo** 
https://github.com/user-attachments/assets/cb26639d-c5e3-40c0-bd8d-64782c004353

---

**Eddy Tian (42790253)**

- Created the Campus Crossing Minigame:
  - Large map that includes the majority of the UBCO campus with all of the paths that exist IRL 
  - Vehicle controls and physics for a player riding a scooter
  - UI instructions for which building to drive to, including a timer that decreases with each new round
  - Random spawning and goal selection between any of the buildings with classrooms on campus
  - Auto-generated colliders for every single building on campus
  - Input blocking between goals
 
**PRs and Branches With Relevant Commits:**
[https://github.com/A-Delfs/G14_GameJam/pull/5](https://github.com/A-Delfs/G14_GameJam/pull/4)
[https://github.com/A-Delfs/G14_GameJam/tree/tim-minigame](https://github.com/A-Delfs/G14_GameJam/pull/7)
[https://github.com/A-Delfs/G14_GameJam/tree/campus-crossing](https://github.com/A-Delfs/G14_GameJam/tree/campus-crossing)

---

## 📸 Screenshots
![image](https://github.com/user-attachments/assets/9fa1c7ba-9597-44b7-9813-06e87df9069c)
![image](https://github.com/user-attachments/assets/430d96d4-8470-43e1-a8df-31d5f1efaa2c)

![image](https://github.com/user-attachments/assets/08ad05cc-6a76-47d3-ae3a-f0ed59ec3558)
![image](https://github.com/user-attachments/assets/7cff4238-c1d1-47c2-9c72-d3765c6aee96)


---
## 📹 Video demo
[![Watch the video](https://img.youtube.com/vi/sLKzlnJ_070/maxresdefault.jpg)](https://youtu.be/sLKzlnJ_070)

### [click here to watch demo](https://youtu.be/sLKzlnJ_070)
