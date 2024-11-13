# Swing City
> Dylan Wijesinghe <br> Gian-Luca Battaglia <br> Zion Xiaoxi Su <br> William Dixon

>
> ## Movement
> 
> https://github.com/user-attachments/assets/d72d37a8-e420-4e20-a1b6-7219c6af63b5
>
> https://github.com/user-attachments/assets/cad42375-6943-4b62-916c-7770e19bff7f
> 
> https://github.com/user-attachments/assets/aa28ec26-be47-465a-b961-e279ca0a7e32
> 
> Movement in Swing City has been fully implemented with basic controls such as walking (WASD), sprinting (Shift + WASD), and jumping (Space). Since we also wanted the movement to be smooth rather than sudden, we gave the player a slightly slippery effect when walking and stopping. Jumping also has air drag, meaning the longer the player stays in the air, the more the horizontal velocity decreases over time.
> ## Sliding / Crouching
>
> Sliding and Crouching in Swing City has been implemented with the Control key. By holding Control, the player shrinks in half, allowing them to crawl under small spaces. A nice addition to crouching is when moving before they crouch, they can slide. Sliding is similar to crouching, but it maintains player speed for a short time before reverting to crawling speed.
> ## Wallrunning
> 
> https://github.com/user-attachments/assets/808c3b0b-b83a-4388-9f60-1d3134653e88
> 
> Wallrunning in Swing City has been implemented with a working camera tilt. When the player runs along the wall, the camera tilts smoothly to give the effect of running almost sideways. Wallrunning lasts for a short time, but players can jump away from the wall during that time, which leads to wall-jumping.
> 
> ## Swinging / Grappling
> 
> https://github.com/user-attachments/assets/ce823c3c-8c31-403e-8a04-7a60caaa6b9d
>
> https://github.com/user-attachments/assets/42f2cbab-218c-4c9d-95c5-c52d34fce715
> 
> Swinging and grappling in Swing City now work fluently with their purpose in levels. They are also highly adjustable and currently show differing colours for distinction. They are controlled by mouse clicks (left click for swinging, and right click for grappling). Swinging currently uses joints while Grappling uses trajectories.
> ## UI
> 
> https://github.com/user-attachments/assets/eef690c5-4821-41ce-b1bd-ba46e0151689
> 
> Swing City has a working UI for many kinds of menu systems such as the main menu, pause menu, and settings menu. While the options menu is empty since it does not have any adjustable settings yet, the controls menu now shows the visual implementation of which controls refer to which mechanic.
> ## Respawning
> 
> https://github.com/user-attachments/assets/ace63c4e-d531-47f1-a060-791a44e6760d
> 
> The respawn system has been implemented with working checkpoints. While there are hardly any checkpoints placed in the scene, the respawn is coded to teleport the player back to the previous checkpoint (or back to the start). There is a fade in and out segment in respawning but due to its buggy nature, we did not show it in the Alpha Build, but rather made the player respawn instantly. Despite the fade segment still being worked on, the respawn and checkpoint system is working fine.
> ## Speed / Jump Boosts
> 
> https://github.com/user-attachments/assets/525dbe94-97cb-4eef-82ea-53061b9b8795
> 
> https://github.com/user-attachments/assets/254a4c2e-337b-42d6-8267-abbf65dd0316
> 
> Speed and Jump Boost Pads in Swing City have been implemented with working functionality. Speed Boost Pads are coded to give the player a pushing force in the given direction, and a temporary speed boost. As for Jump Boost Pads, they have a simpler functionality by multiplying the player’s jump force. Both pads are coloured and drawn for distinction.
>
> ## Summary
> With these given mechanics, we were able to fully develop levels such as Tutorial, Hub World, and Level 1. However, we are still in the prototype phase as a lot of the assets lack design and instead use greyboxing elements in ProBuilder. Within the level design process, we are hoping to find art assets to use for Swing City and develop themes/biomes. 
>
> https://github.com/user-attachments/assets/e12e9eaa-6a10-4b2c-bf44-d4d8edd0b1dd
>
> https://github.com/user-attachments/assets/39a8ea4e-8c60-4eeb-9b20-08a0e5895046

---------------------------------------------------------------------------
