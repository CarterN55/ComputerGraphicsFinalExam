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

<img width="328" height="232" alt="image" src="https://github.com/user-attachments/assets/4889810c-92b4-43ee-8adb-c33c23547c2b" />

I used rim lighting on the walls to give them the blue glowing outline that they have. Opposite to the hologram and scrolling shaders, the rim lighting looks better in the game view compared to the editor view. The outline also appears relative to the camera's position due to the top-down view, so if I were to move it in any direction it would show up more prominetly on that side (you can see the blue outline get thinner the further it is from the middle).
