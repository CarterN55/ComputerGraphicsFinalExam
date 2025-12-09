# ComputerGraphicsFinalExam
**ALL MOVING SHADERS (HOLOGRAM AND SCROLLING) WORK IN THE BUILD**

**Pac-Man**

<img width="353" height="608" alt="image" src="https://github.com/user-attachments/assets/d5d58657-0aff-40dc-8bd7-76ab328d0245" />


Hologram

<img width="370" height="308" alt="image" src="https://github.com/user-attachments/assets/90b4ce94-63d5-4c92-b4d6-fb43835788fa" />
<img width="411" height="349" alt="image" src="https://github.com/user-attachments/assets/93b8ecb7-64ee-435f-b8bf-ef2f92e4ce27" />
<img width="364" height="276" alt="image" src="https://github.com/user-attachments/assets/3444cdb5-8202-4fcf-b25b-e0ab200db5a5" />

I used the hologram shader on the ghosts (visualized with a capsule) to show when they are able to be eaten by Pac-Man. In the original game they flash when weakened but for this project I wanted a hologram to show their defences lowering (decending lines on the hologram). Typically a constant effect decending around a character is precieved as a debuff or loss of something, that was the goal for the decending hologram around the ghosts. They are in a weakened state and will try to run from Pac-Man so a weakened "aura" around them helps to show that.


**Scrolling**

<img width="293" height="304" alt="image" src="https://github.com/user-attachments/assets/e063e494-3b81-4cc9-aaf2-12dbbb234f5e" />
<img width="376" height="245" alt="image" src="https://github.com/user-attachments/assets/f12e0235-4aa6-4248-86d3-899822766b0d" />

Its hard to tell in the picture but I used the scrolling shader to create a spiraling effect on the powerup dots (the ones you eat to eat the ghosts) to give them a more impactful look. Sadly they only show the spiral well in the editor and not in game view because it makes them more choppy and not as smooth. Since I didn't have any good images to use for the scrolling I just found a built in Unity image, this is when I found the spiral effect. Because the object is a sphere/rounded instead of a flat surface like a plane it starts the scrolling from the top of the sphere and spirals down the object repeating it as it goes down (pretty much like a screw).


**Rim Lighting (Shader from the first half)**

<img width="324" height="464" alt="image" src="https://github.com/user-attachments/assets/3057befe-c1b2-452e-864d-68bb40607854" />
<img width="363" height="88" alt="image" src="https://github.com/user-attachments/assets/b8d849de-bfec-4350-be72-4623fee543d7" />

I used rim lighting on the walls to give them the blue glowing outline that they have. Opposite to the hologram and scrolling shaders, the rim lighting looks better in the game view compared to the editor view. The outline also appears relative to the camera's position due to the top-down view, so if I were to move it in any direction it would show up more prominetly on that side (you can see the blue outline get thinner the further it is from the middle). The outline apperaing smaller or larger depending on the camera angle is probably due to the rim colour being projected on the faces of the walls rather than around the actual object. This could be even cooler if the camera could be wiggled around slightly while playing the game which would show the blue outline constantly shifting like it was almost 3D.


**Glass (Shader from the second half)**

<img width="213" height="223" alt="image" src="https://github.com/user-attachments/assets/e22bbe2f-05f9-4a17-a8d4-5159e843103b" />
<img width="368" height="409" alt="image" src="https://github.com/user-attachments/assets/6df95584-9bd9-4ac4-8d93-48f0c67088b8" />

I used the glass shader/effect on the normal dots to give them a glow effect. The glass allowed them to have a glow due to the tint intensity property being raised from a max of 5 to a max of 50. Since the dots are the main way the player will get points I wanted them to appear more distinct with a glow besides just some white dots. Not only did the shader allow me to add a glow effect but it also allowed me to add an image which I used to create a slight blueish glow to the dots using a default Unity image as the texture since I didn't have time to import any new ones. i would say that the blue glow also adds to the scene since its a bit less harsh on your eyes then a full white glow would be.
