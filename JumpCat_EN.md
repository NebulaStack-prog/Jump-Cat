## **Part 1. Main Document.**

### **1. Title and Basic Information.**

• **Name:** Jump Cat

• **Purpose:** Project No.10. Product

• **Project Phase:** Phase I

• **Technology Stack:** Construct 3

• **Project Status:** Fully completed.

### 2. Project Overview.

• Jump Cat is a memory-based endless runner game. The cat runs forward, collecting yarn balls or treats while avoiding ground obstacles.

• On collision with an obstacle, one life is lost (5 total). The goal is to collect as many items as possible.

• Characters and backgrounds are animated using frame-by-frame animation. The game does not include complex mechanics, but it contains something more important: sincerity and light, similar to the Diving Cats project.

### 3. Clear Project Goals.

• Create a project that becomes a memory.

• Implement simple controls and soft visual graphics.

• Expand the NebulaStack project showcase.

### 4. Project Components.

• **Main character:** Cat (Zhorik).

• **Enemies:** obstacles such as stones and logs.

• **Objectives:** yarn balls, fish.

• **Lives:** five hearts displayed in the top corner of the screen.

• **Score:** displayed in the center of the top part of the screen.

### 5. Usage Instructions.

• Download the project file from GitHub.

• Open Construct 3 (browser or app) → “Open” → select the downloaded file.

• Launch the game using the “Start” button on the top panel.

• Controls: holding Spacebar — jump.

• Construct 3 is required to run the project (free version is sufficient). There is currently no standalone executable (.exe).

### 6. Memory and Creation Context.

• **This project, like Diving Cats, differs from others due to its main purpose — to preserve the memory of a beloved cat who has passed away.**

• **His name — Zhorik — will remain within NebulaStack as long as the ecosystem exists.**

• **A tribute to a small companion who spent his long life beside humans, showing affection, love, and loyalty.**

## **Part 2. Technical Document.**

### 1. Development Goals.

• Create a stable 2D game with animation and simple controls.

• Provide a template foundation for future NS projects.

### 2. Technologies Used.

• **Game Engine:** Construct 3

### 3. Project Architecture.

• The project is divided into several modules, each responsible for a specific part of the game:

• **PLAYER:** movement of the main character (Space key held down).

• **BARRIERS:** spawning obstacles, collision handling with the player (life loss), game over condition.

• **BACKGROUND:** background movement (soundtrack planned in future updates).

• **GOALS:** spawning collectible items and increasing score upon collection.

• **HEARTS:** managing lives and heart removal animations.

• **GAME OVER:** restart via Space key, final screen showing current and best score.

### 4. Project Structure.

• The project consists of one main file: JumpCat.c3p (Construct 3 format).

• This file contains the entire game: assets, audio, UI settings, sprites, and all logic.

• Construct 3 is required to run the project.

### 5. Key System Components.

• Game asset set.

• Sprites.

• Global variables (score, lives).

• Event system (Event Sheet).

• Collision logic.

### 6. UI Implementation.

• The interface uses pixel-art assets selected from compatible asset packs.

• UI elements are positioned at the top of the screen (corners and center) for better readability.

• The visual style remains consistent across all elements.

### 7. Development Process.

• Creation of sprites for the main character, collectibles, obstacles, and background.

• Definition of basic mechanics for each sprite and their interactions.

• Implementation of lives system, score system, and game over screen.

• Asset integration and music addition.

### 8. Main Challenges and Solutions.

• **(1)** Issue: the main character could move outside the map boundaries.

Solution: boundary barrier sprites were added to restrict movement.

• **(2)** Issue: game speed remained constant over time, making the endless mode too easy.

Solution: game speed gradually increases over time, and spawn intervals for obstacles and collectibles decrease.

### 9. Current Project Limitations.

• No main menu.

• No audio settings or mute option.
