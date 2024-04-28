---
title: Robomaster EP
version: 1.0.0
theme: mrdaviescs
footer: Robomaster EP
paginate: true
marp: true
size: 16:9
---

# Robomaster EP
### **Omnidirectional ground robots**

---

## The Robomaster EP
The robomaster Educational Platform is an **omnidirectional** robot with a **claw arm** or a **turret firing infra-red or soft projectiles**


![bg left:53% 95%](https://www1.djicdn.com/cms/uploads/65cb924aab90492428e558773dd4bce7@374*374.png)


---

# Building the Robomaster EP
<br />

## Video 1: The wheels and body

## Video 2: The arm and accessories

---

<iframe style="display:block; margin-left:auto; margin-top:-1em; width:100%; height:105%;" src="https://www.youtube.com/embed/wq1dDl36Luc" title="How to Assemble RoboMaster S1" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>

---

<iframe style="display:block; margin-left:auto; margin-top:-1em; width:100%; height:105%;" src="https://www.youtube.com/embed/J2-EiRKzMuQ" title="How to Assemble RoboMaster S1" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>

---

## Piloting the Robomaster

Using the app choose `solo` mode, use the on screen controls

![bg left:65% ](https://image.winudf.com/v2/image1/Y29tLmRqaS5yb2JvbWFzdGVyX3NjcmVlbl8wXzE1NjA0MDg4ODRfMDg4/screen-0.jpg?fakeurl=1&type=.webp)

---

## Programming the Robomaster

The EP can be programmed with blocks (scratch like) or python, we will use python.

![bg left:60% 100%](https://www.robotwonderland.com/wp-content/uploads/2022/04/import_scratch_program.jpg)

---

## Robomaster Python Example

```python
from robomaster import robot # import robot
ep = robot.Robot()
ep.initialize(conn_type="sta") # initialise
epChassis = ep.chassis # chassis setup

# Move Forward by 0.5m then left by 0.6m
epChassis.move(x=0.5, xy_speed=0.7).wait_for_completed()
epChassis.move(y=-0.6, xy_speed=0.7).wait_for_completed()

# Turn Clockwise 90 degrees
epChassis.move(z=90, z_speed=45).wait_for_completed()
ep.close()
```

---

## The Challenges

<div class="columns">
<div>
<!-- Column 1 -->

- Race

- Obstacle Course
- Target practice
- Run and Gun
- Musical areas

</div>
<div>
<!-- Column 2 -->

- Pick up and drop

- Delivery course
- Seek and destroy
- King of the hill
- Capture the cube

</div>
</div>

---

### 1/ Race 🏁
Control your EP directly or use code to race around a race track in the atrium.

**Winning Condition:**
First to the finish

**Allowed modes:**
**👨‍🚀 vs 👨‍🚀 / 💻 vs 💻 / 💻 vs 👨‍🚀**

---

### 2/ Obstacle Course ⚠
Control your EP directly and be the first through the obstacle course.

**Winning Condition:**
First to the finish, hitting an obstacle = disqualification

**Allowed modes:**
**👨‍🚀 vs 👨‍🚀 / 💻 vs 💻 / 💻 vs 👨‍🚀**

---

### 3/ Target Practice 🎯
Shoot all the targets in the time limit, *targets further from the starting position are worth more.*

**Winning Condition:**
Most points in the time limit

**Allowed modes:**
**💻 vs 💻 / 💻 vs 👨‍🚀**

---

### 4/ Run and Gun 🏁 🎯 
Race around the course and shoot all the targets in time.

**Winning Condition:**
First to the finish, hit all targets

**Allowed modes:**
**💻 vs 💻 / 💻 vs 👨‍🚀**

---

### 5/ Musical Areas 🎶
Must move while music is playing, when music stops move to an active area.

**Winning Condition:**
Last one standing wins, last robot to get to an area when the music stops is eliminated

**Allowed modes:**
**👨‍🚀 vs 👨‍🚀 / 💻 vs 💻 / 💻 vs 👨‍🚀**

---

### 6/ Pick up and Drop 📦 
Identify and pick up the right box and put it down in the right place carefully as fast as you can.

**Winning Condition:**
fastest time, dropped package = disqualification

**Allowed modes:**
**💻 vs 💻 / 💻 vs 👨‍🚀**

---

### 7/ Delivery Course ⚠ 📦
Deliver the package from one side of the obstacle course to another.

**Winning Condition:**
First to the finish, dropped package or hitting obstacle = disqualification

**Allowed modes:**
**💻 vs 💻 / 💻 vs 👨‍🚀**

---

### 8/ Seek and destroy 🎯 💥 👥
Team challenge, Robot laser tag, destroy your opponents to win, hitting an opponent disables for 10 seconds, *10 points per disable*.

**Winning Condition:**
Team with highest store

**Allowed modes:**
**💻 vs 💻 / 💻 vs 👨‍🚀**

---

### 9/ King of the hill 🗻 👑 👥
Team challenge, Control the hill with your team for the longest, hitting an opponent disables for 10 seconds.

**Winning Condition:**
Team with longest time on the hill

**Allowed modes:**
**💻 vs 💻 / 💻 vs 👨‍🚀**

---

### 10/ Capture the cube 🎲 💻 👥
Team challenge, capture and keep hold of the cube for the longest time, hitting an opponent forces the opponent's gripper to open and disables for 10 seconds.

**Winning Condition:**
Team who holds the cube longest

**Allowed modes:**
**💻 vs 💻 / 💻 vs 👨‍🚀**

---

## Resources 

<!--
- [Quick Start Guide (build instructions)](https://dl.djicdn.com/downloads/ROBOMASTER_EP/20200707/RoboMaster_EP_Quick_Start_Guide_Multi_0707.pdf)
-->

<!--
- [Scratch Programming Guide](https://dl.djicdn.com/downloads/ROBOMASTER_EP/20200515/RoboMaster%20EP%20Programming%20Guide%20V1.0.pdf)
-->

- [User Manual](https://dl.djicdn.com/downloads/ROBOMASTER_EP/20220429UM/RoboMaster_EP_User_Manual_v1.2_EN_1.pdf)
- [Setup and Instruction Videos](https://www.dji.com/hk-en/robomaster-ep/video)
- [More Videos](https://www.youtube.com/watch?v=qkjCOEtv294&list=PL8-vxWY64sBPbR5MACO7rbLtDQRLum21o)
- [Vision Markers](https://dl.djicdn.com/downloads/ROBOMASTER_EP_CORE/20200923/RoboMaster_EP_Core_Vision_Maker.pdf)
- [Online programming Guide](https://www.dji.com/hk-en/robomaster-s1/programming-guide) (Scratch & Python)
- [Robomaster SDK](https://robomaster-dev.readthedocs.io/en/latest/) readthedocs.io
- [Robomaster EP Examples](https://github.com/dji-sdk/RoboMaster-SDK/tree/master/examples)
- Robomaster Software: [windows](https://service-adhoc.dji.com/download/app/pc/aa9163ed-66a5-4917-b747-f63933df4038) or [mac](https://service-adhoc.dji.com/download/app/pc/b87f06ab-e4ee-4590-bf01-e3314e11fdc1)
