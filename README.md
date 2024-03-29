# Taken

A demo 3D game group project created in Unity. Player need to control the cars to rescue all of the hostages in the map and find the exit.

Demo video: https://drive.google.com/file/d/1WLRkArpBCY75NYfBNGmEDR_fZaNY5kRO/view?usp=sharing

The assets we found online:
- The main character(which is a car) prefab including model, audio, animation, control
- The low poly pack(include all environment models in each map)
- The traps particles effect pack
- The hostage model

The parts we implemented:
- The main camera script which determines following the car and switch directions when go forward and backward
- The saving hostages script that controls the progress bar when saving the hostages
- The door control scripts and animation
- The hostage animator
- The MenuUI script that controls the appearance of the Pass, Fail and Halt canvases base on different conditions. Also includes scene reloading.
- The trap script that slowes down the car
- Builds all the maps based on the models in low poly pack
- The light cycle particle effect surrounding the hostages
- The scene switch script that control the switching between different scenes
