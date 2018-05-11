# ATBonesSem2

# What you need to run the project

The first thing is Unreal Engine 4. I have built the start of the game on Version 4.17.2, So I would recommend 4.17.2 or above to avoid any errors. From what I know UE4 should run on both mac and pc, and since I haven’t done any C++, there is no need to install external software to write code. All of my work has been done in the blueprint editor, which is contained in ue4 itself. 

## File types and what is inside

#### .UASSET

This file is the most common in the file paths. The most important ones are in the folder called body_deafult. These are currently the baseline for the new DISMANTLE system and have the most blueprint code.


#### CONFIG FOLDER

I wouldn't touch anything in this folder, it will just edit the environment for you and make it look more like my screenshots. 



#### BONES UNREAL PROJECT FILE

I do not suggest booting this file as it does not boot the assets with it. This file will boot UE4 and a shell of the BONES project.



# How to boot, run, and navigate the project

Image 1: 
![alt text][img1]

[img1]: https://i.imgur.com/e1mUBwL.png "Project Selection"


Fig 1: When You boot up UE4 you should be brought to a screen like this. Click browse and find the folder downloaded from github.



Image 2: 
![alt text][img2]

[img2]: https://i.imgur.com/baBomtj.png "Main screen"

Figure 2: This is the main screen. It may look a tad different due to screen resolution and what I have disabled and etc. From here you can simulate the game by hitting the play button(highlighted in orange in this shot). You can also navigate all of the assets I have played around with in the content browser. In the screenshot you can see the head, chest, and Larm. Try double clicking on the head.

Image 3: 
![alt text][img3]

[img3]: https://i.imgur.com/CVJKJK8.png "Character viewport"


Figure 3: Here is what is contained in the skull “character. It contains a viewport to view the model, as well as the components active such as the camera, collision box, and a vector. Along the middle top, you can see three tabs. Construction script, Event Graph, and Viewport.  The Event Graph is the blueprint work I have been doing so click there to proceed. 
Image 4: 
![alt text][img4]

[img4]: https://i.imgur.com/o25X35Y.png "Character viewport"


Figure 4: This image is quite hefty and I shrunk it down. On your end you should see what I have done. There are two primary sections, my camera and movement, and then the DISMANTLE system implementation v1 You can look at the little details on each node and read the logic that is contained in something that looks pretty simple.


OK OK, so I couldn't upload to github because the entire project is too large, and I spent a good amount of time doing this md so here is a link to the project where I have uploaded the entire project. 
[click here to download](https://drive.google.com/drive/folders/1FkIV1fQ0kFCOLONLiGVFAPY-K1zShP1L?usp=sharing)
