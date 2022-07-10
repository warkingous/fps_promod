# **FPS Challenge Promod 2.32**
based on PromodLive 2.20

**Changelog:**
========
 * [Automatic overtime](#automatic-overtime)
 * [Minor changes](#minor-changes)
 * [League mode](#league-mode)
 * [Map fixes](#map-fixes)
 * [Prone to Crouch fix](#prone-to-crouch-animation-fix)


## Automatic overtime:

Automatic overtime is automatically set in **Knockout mode**, default overtime value is `MR3`. There could be multiple (infinite) number of overtimes.
There is no overtime in Match mode by default, there is no need for that.
You can change MR of overtime by adding "_ot{number}" in promod_mode:

promod_mode `knockout_ot6`

## Minor changes:

+ **Match** and **Knockout** modes defaulted to `MR12`.
+ **Knockout** mode has default overtime of `MR3`.

## League mode:

League mode can be set by adding "`_league`" to promod_mode:

promod_mode `knockout_league`

+ **League** mode has default strat time to 10 seconds.


## Map fixes:

### **Citystreets**:
1. Fixed one-way vision from L to carpark

<p float="left">
<img src="https://cod4promod.eu/files/cod4/images/city-carpark-bug.jpg" width="360">
<img src="https://cod4promod.eu/files/cod4/images/city-carpark-fix.jpg" width="360">
</p>
2. Fixed one-way vision under Ticket on B

<p float="left">
<img src="https://cod4promod.eu/files/cod4/images/city-ticket-bug.jpg" width="360">
<img src="https://cod4promod.eu/files/cod4/images/city-ticket-fix.jpg" width="360">
</p>

### **Crash**:
1. Fixed one-way vision from wooden to lower A
<p float="left">
<img src="https://cod4promod.eu/files/cod4/images/crash-wooden-bug.jpg" width="360">
<img src="https://cod4promod.eu/files/cod4/images/crash-wooden-fix.jpg" width="360">
</p>
1. Fixed one-way vision on B long
<p float="left">
<img src="https://cod4promod.eu/files/cod4/images/crash-long-bug.jpg" width="360">
<img src="https://cod4promod.eu/files/cod4/images/crash-long-fix.jpg" width="360">
</p>

### **Strike**:
1. Fixed one-way vision
<p float="left">
<img src="https://cod4promod.eu/files/cod4/images/strike-bins-bug.jpg" width="360">
<img src="https://cod4promod.eu/files/cod4/images/strike-bins-fix.jpg" width="360">
</p>

## Prone to Crouch animation fix:
---


> When you go from prone position to crouch position, the animation makes you invisible to enemy (your head is invisible for some time) and that gives you an advantage - you can see your enemy faster. 

Playing the animation faster makes it visible for both players at the same time.

**Demonstration:**

Normal speed:
![Alt Text](https://cod4promod.eu/files/cod4/images/normal.gif)

4x Slower:
![Alt Text](https://cod4promod.eu/files/cod4/images/slower.gif)
