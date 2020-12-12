# Digital Production Arts
#### DPA 8070 3D Modeling and Animation with Jim Sidletsky
#### By: Benjamin B. Warner

[Back to the main page](https://benwarnerdigitalarts.github.io/3Dworks/)

## Final Project: Pipeline Trials - Taking a "Weredog" From Zbrush to Animation
### Date: Decemeber 9th, 2020

<video src="https://benwarnerdigitalarts.github.io/3Dworks/dpa8070/finalPropject-wereDog/render/wereDogVid.mp4" width="800" height="600" controls preload></video>

[Download the wereDog maya file!](https://benwarnerdigitalarts.github.io/3Dworks/dpa8070/finalProject-wereDog/wereDog4.zip)

### Objective:
#### Choose a focus: advanced modeling, advanced texturing/shading/lighting/rendering, advanced animation, advanced rigging, or e?ects. Your project needs to either explore a topic we did not tackle in a class project or go beyond what we did in a previous project. You can use any of our previous models (or ?nd other assets but always cite your sources). Your ?nal movie should be saved in standard format (e.g., .mov), minimum size 800x600 but 1024x768 is preferred.

### Solution:
#### For my project, I focused on advanced modeling by way of importing one of my past Zbrush projects into Maya, and then I also wanted to make an advanced rig to control it. Finally, I made an interesting animation to demonstrate some of the capabilities of the rig. Shading and lighting are relatively basic in this example, but the shading for the ground, wood, and clothing are all procedurally generated with Mix shaders and creative use of noise textures.

#### To start, I revisited my old Zbrush project to clean up and optimize the model as much as possible before exporting it to Maya using the "GoZ" features.  Fortunately, I had already remeshed the model to be ideal for modeling and animation. The fur was modeled as large masses with finely manipulated geometries, so something different would have to be pursued for the Maya implementation for a better effect.

[View my final composited Zbrush shots from Insun Kwon's class!](https://benwarnerdigitalarts.github.io/3Dworks/zbrush/)
![Zbrush reduction](https://benwarnerdigitalarts.github.io/3Dworks/dpa8070/finalProject-wereDog/images/zbrush-process.PNG)

#### Additionally, I created an improved set of UVs manually through Maya's UV editor for the main body mesh to allow easier detailing of the skin in Substance Painter. This was primarily done to create some distinction between the finger nails, toe nails, inner mouth bag, eye bags, nose, and hand/foot pads. Here is what the resulting UVs and Substance Painter result look like:

![SP and UVs](https://benwarnerdigitalarts.github.io/3Dworks/dpa8070/finalProject-wereDog/images/sp-uvs.PNG)

The rest of the items on this model make use of simpler shaders to give the impression of metals, then use some noisy mix shaders for straps or the orange leather. A simple scene was also created using some noisy mix shaders for wood and ground textures.  These noisy mixes also make use of some slight displacment to create some more interesting surface irregularities. An HDRI was used for the skybox, which was sourced from the wonderful website: hdrihaven.com/hdris. An overview of the hypershader view can be seen here:

![Hypershader](https://benwarnerdigitalarts.github.io/3Dworks/dpa8070/finalProject-wereDog/images/hypershader-view.PNG)







