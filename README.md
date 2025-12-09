# ComputerGraphicsFinalExam

**Pac-Man**

Hologram

<img width="370" height="308" alt="image" src="https://github.com/user-attachments/assets/90b4ce94-63d5-4c92-b4d6-fb43835788fa" />
<img width="411" height="349" alt="image" src="https://github.com/user-attachments/assets/93b8ecb7-64ee-435f-b8bf-ef2f92e4ce27" />

I used the hologram shader on the ghosts (visualized with a capsule) to show when they are able to be eaten by Pac-Man. In the original game they flash when weakened but for this project I wanted a hologram to show their defences lowering (decending lines on the hologram).


**Scrolling**

<img width="293" height="304" alt="image" src="https://github.com/user-attachments/assets/e063e494-3b81-4cc9-aaf2-12dbbb234f5e" />

Its hard to tell in the picture but I used the scrolling shader to create a spiraling effect on the powerup dots (the ones you eat to eat the ghosts) to give them a more impactful look. Sadly they only show the spiral well in the editor and not in game view because it makes them more choppy and not as smooth.


**Rim Lighting (Shader from the first half)**

<img width="331" height="468" alt="image" src="https://github.com/user-attachments/assets/eac60b6a-b381-43df-bc73-30ab82b98912" />

I used rim lighting on the walls to give them the blue glowing outline that they have. Opposite to the hologram and scrolling shaders, the rim lighting looks better in the game view compared to the editor view. The outline also appears relative to the camera's position due to the top-down view, so if I were to move it in any direction it would show up more prominetly on that side (you can see the blue outline get thinner the further it is from the middle).


**Glass (Shader from the second half)**

<img width="205" height="221" alt="image" src="https://github.com/user-attachments/assets/981b4162-7e56-4ace-875e-4a52c8302b9e" />
<img width="376" height="166" alt="image" src="https://github.com/user-attachments/assets/f8cf13a7-5da3-4cb4-9791-6f1a2db6cf02" />


I used the glass shader/effect on the normal dots to give them a glow effect. The glass allowed them to have a glow due to the tint intensity property being raised from a max of 5 to a max of 50. Since the dots are the main way the player will get points I wanted them to appear more distinct with a glow besides just some white dots.
