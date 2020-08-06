# 2-AXIS-SOLAR-TRACKER


![](https://github.com/GUSAC-GIT/2-AXIS-SOLAR-TRACKER/blob/master/axis-images/axis1.jpg)


> 2-AXIS-SOLAR-TRACKER

---

### Contents


- [Components](#components)
- [Description](#description)
- [Team Info](#team-info)



---

## Components

- Arduino Uno + USB Cable
- Arduino Sensor Shield
- 2 x 9g Metal Gear Servos
- 1 x 5 Port Terminal Block
- 1 x 4 Port Terminal Block (or 3 port will do)
- 4 x 10K Ohm Resistors
- 4 x Light Detecting Resistors
- 4 x JST Socket Connector Cables
- Jumper Wires




[Back To The Top](#2-axis-solar-tracker)




## Description

Our tracker is a dual axis tracker, meaning it tracks in both X and Y. To put it into even more simple terms, it goes left, right, up, and down. This means once you have your tracker set up you will never need to change or adjust anything, since anywhere the sun moves your tracker will follow. This also impresses people at parties because you can have it track a flashlight around. This method gives the best results for power generation.
If you want to make things a bit more simple you can make a single axis tracker, one that does just X or Y. To put it in simple terms again, it'll do just left to right or just up and down. Typically people will make an X axis (left to right) tracker and then just set their panel at 45 degrees for Y. This still gives really high amounts of power generation while at the same time eliminating half the moving parts. You'll frequently find this approach being used in "dumb" trackers that are not computer controlled.

Our tracker is an active tracker which is controlled by computer program (via an Arduino). This means that we use sensors to find the brightest source of light at all times. If you were to take a flashlight and shine it at the sensors the tracker would follow it around. While this is the most interactive and exciting kind of tracking you can build, it's also overkill for larger setups.
The sun is highly predictable. If you can easily look up the time of every sunrise and sunset for the next 100 years as well as use some simple math to figure out the angle of the sun relative to your location at any time of the year. With this in mind many people end up using a scheduled tracker. This system uses a computer program that changes the angle of the panel based on the date, time, and physical location. While not as fancy or exciting as an active tracker, it is in fact far more efficient provided everything is set up properly. You can be sure that your panel is at the mathematically most efficient spot possible even under heavy cloud coverage.


[Back To The Top](#2-axis-solar-tracker)

---


## Team Info

Gusac Projects Team

[Back To The Top](#2-axis-solar-tracker)


