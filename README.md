# ARjs - Single AR Model Example
#### [AR.js](https://ar-js-org.github.io/AR.js-Docs/) Hello Metaverse example: load a file from Rhino in AR
This is a sample repository for [Parametrics](https://parametrics.space/) students to fork.  Instructions below for forking this repo, setting up github pages to serve your site over the web, and swapping in your own content from Rhino and Grasshopper are below.  


## Mirar Blob Demo - [https://bhowes-pratt.github.io/ARjs-Single-Model-Example/](https://bhowes-pratt.github.io/ARjs-Single-Model-Example/)
This model that came from Grasshopper:  
![Blob Demo GIF](https://github.com/bhowes-tt/Markerceratops/blob/main/docs/Markerceratops_MirarBlobDemo.gif)

## Try it!
Point that phone of yours at the QR code below, and then keep the AEC marker in frame, and lo and behold --- the state of the Free AR art! 
![QR](https://github.com/bhowes-pratt/ARjs-Single-Model-Example/blob/main/docs/ARjs-Sample-QR-small.png )
![Marker](https://github.com/bhowes-pratt/ARjs-Single-Model-Example/blob/main/docs/AECmarker.png)


# Instructions:

### 1) Fork this repo
Sign up for a github account and fork this repo.  Rename your new repo.  Clone the repo to your machine using Github Desktop, and practice pushing your first commit: Change LICENSE file to attribute copyright to yourself using Visual Studio Code or the text editor of your chosing.

### 2) Turn on Github Pages
Repo settings > Pages tab > Enable pages.  After you turn this on, github will start publishing a live version of your site.  For the AR.js stuff to work on your phone, you have to open the site from a trusted source on the web, and github checks out.  This also lets you push updates out in real time 🤙

### 3) Create a .glb file from a Rhino Model
Using the Shapediver Rhino GLTF exporter or the other newer GLTF exporter, or by going OBJ > Three.js editor > export gltf ... create a .glb file by exporting meshes from Rhino.  We'll cover this in the workshop/video, but the gist is to use the template files in this repo and any means necessary to get a clean glb file that can be embedded in the fancy new AR website you made in steps 1 and 2.  A template rhino file and a sample grasshopper file are included in the /docs/rhino directory.

### 4) Swap in your model for the sample
Add your .glb file to the /assets folder and commit it.  Then, edit index.html to point to the new .glb model.  Commit and push your changes, and test the site using your phone.

### 5) Iterate!
Now you can test on your phone over the web!  Iterate on the GLB file until it looks 😻 on your phone's screen.  Material settings and export options/process will make a lot of difference!  
