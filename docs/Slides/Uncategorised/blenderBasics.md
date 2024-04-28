---
title: Blender Basics
version: 1.0.0
theme: mrdaviescs
footer: blender basics
paginate: true
marp: true
size: 16:9
---

# Blender Basics

### **getting started with 3D animation in Blender**

---

# What is blender?

![bg left:70% 96%](https://www.blender.org/wp-content/uploads/2019/07/blender_render-1280x720.jpg?x12104)

[Blender](https://www.blender.org/) is an industry standard but **free** 3D animation software

---

# Moving the Camera

Let's start with how to move the camera, there are three main camera controls.

| Pan | Orbit | Zoom
|-----|-----|-----|
| Shift + RMB | RMB | Scroll wheel
| moves the camera left and right | rotates the camera around a central point | zooms from the camera's central point

---

# Snow and Rain

![bg right:50% 102%](https://ddz4ak4pa3d19.cloudfront.net/cache/d4/d6/d4d6f4bcaf31e423e393d29ce4cefb2f.jpg)

We are going to use either [Snow v2](https://studio.blender.org/download-source/8b/8b8cfa3e2d0781c893d952513152347f/8b8cfa3e2d0781c893d952513152347f.zip) or [Rain v2](https://studio.blender.org/download-source/10/1033fad76f67bba3e362065d68c85791/1033fad76f67bba3e362065d68c85791.zip) 

These are both characters made by blender's animation studio, [Studio Blender](https://studio.blender.org/)

---

# Importing a character

Choose either Snow or Rain from the previous slide and download the file.

extract the file by right clicking and choosing 'unzip'

double click the **snow.blend** or **rain.blend** file to open it in blender

---

# Pose Mode

We want to animate so we will need to **pose** our character. 

You will need to select **pose mode** from the drop down menu at the top left.

Pose mode is only available when you select the character rig.

![bg left:30% 90%](https://docs.blender.org/manual/en/latest/_images/editors_3dview_modes_menu.png)

---

# Move, Rotate, Scale

Once you have a part of the rig selected you can use the following commands:

| Move | Rotate | Scale
|-----|-----|-----|
| g key | r key | s key

Pressing x y or z while moving will move only in that axis, pressing `shift` and x, y or z will move in the other two axes

---

# The Timeline

The timeline is used to keep track of **keyframes** that have been inserted, and to see the current frame (*blue line*)

- keyframes are displayed as a **diamond**
- keyframes that are the same are **joined with a solid line**
![bg vertical](1)
![bg vertical](1)
![bg 95%](https://docs.blender.org/manual/en/latest/_images/editors_timeline_interface.png)

---

# Inserting Keyframes

Pressing the `i key` will *insert* a **keyframe** on the current frame.

You will be asked what kind of keyframe you want to set.

Usually this will be **location, rotation** for a character, it's rare to change the scale of a character's rig.

---

# Animating your character

Now you've got all the tools you need, to animate your character follow these steps:

1) Select a frame
2) Pose your character by moving the parts of the rig around and rotating
3) select all parts of the rig, and insert _location rotation_ keyframes
4) choose a new frame and start again

<style scoped>
h1, h2 {
    padding-top: 0.0em;
}
</style>
