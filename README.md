🕯️ Lucid Fear

Lucid Fear is a first-person survival horror game developed using the Unity game engine. The player must navigate a pitch-black labyrinth, manage limited resources, and escape from a relentless entity known as "Zemheri."

🎮 About the Game

Waking up in the middle of a dark maze, Hayri must find his way out using a flashlight with limited battery life. However, he is not alone. Zemheri is an AI entity that tracks the player and pursues them relentlessly.

Your Goal: Scavenge for batteries, manage your stamina and light, and escape the maze before Zemheri catches you.

✨ Key Features
🔦 Resource Management:

Flashlight System: Real-time battery decay mechanics and lootable batteries scattered throughout the map.

Stamina System: Sprinting mechanics with fatigue and recovery cycles.

🧠 Advanced Enemy AI:

Dynamic pathfinding using Unity NavMesh.

A relentless pursuer that screams at specific intervals to heighten tension.

Smart Jumpscare System: When the player is caught, the enemy teleports directly in front of the camera using mathematical vector calculations (transform.forward), ensuring a guaranteed face-to-face jumpscare regardless of where the player is looking.

🎬 Cinematic Narrative:

Intro and Outro Cutscenes.

Seamless scene transitions.

⚙️ UI & Menu Systems:

Dynamic Stamina & Battery bars (Filled Image UI).

Start Menu, Pause Menu with "Time Scale" control, and Game Over loops.

🕹️ Controls

"W, A, S, D" - Move
Mouse - Look Around
Shift - Run (Consumes Stamina)
F - Toggle Flashlight
ESC - Pause Game
N - Developer Mode: Super Jump

💻 Technical Highlights
This project was developed using C# and Unity. Key technical implementations include:

Coroutines & Timing: Used IEnumerator for managing game flow, timed events, and enemy scream intervals.

Vector Mathematics: Utilized Camera.main.transform.forward to mathematically calculate the exact position for the enemy jumpscare, ensuring it always occurs within the player's field of view.

State Management: Enemy states (Idle, Scream, Chase, Attack) are controlled via custom scripts.

Physics Management: Handled interactions between CharacterController and Rigidbody to prevent physics glitches and falling through the map during death animations.

👨‍💻 Developer
Developed by Ali Görkem Sali. 
Cutscenes created by Ebru Çelik.
