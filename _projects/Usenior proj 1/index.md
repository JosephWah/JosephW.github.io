---
layout: post
title: Senior Capstone Project 1
description:  Designed a custom wind heater capable of taking kinetic energy from the wind and convertind it directly to heat without an electrical interface.
skills: 
- 3D Modeling
- QBlade
- Airfoil Design
- Design Optimization
- Project Management
- 
- FEA
main-image: /imageedit_15_8297985868.png
---

---
## Several initial concepts were developed first and Pugh Matrices were used to select the best one (higher is better):
<br>
<span style="font-size: 18px">Pugh Matrix for the wind turbine subsystems:</span>  
{% include image-gallery.html images="https://live.staticflickr.com/65535/54587430995_7646fa108f_w.jpg" height="400" %} 
<br>
<span style="font-size: 18px">Pugh Matrix for the heat generation subsystems:</span> 
{% include image-gallery.html images="https://live.staticflickr.com/65535/54587337738_d17798573c_w.jpg" height="400" %} 
<br><br><br>

## For the H-Type vertical-axis turbine, the NASA LRN 1015 airfoil was used not because it had the highest peak efficiency, but because it's operating range was the largest given the average wind speed in Bowling Green:
<br>
<span style="font-size: 18px">The average wind speed gusts for Bowling Green KY over the course of one year:</span> 
{% include image-gallery.html images="https://live.staticflickr.com/65535/54587340138_e3c38cdb34_w.jpg" height="400" %} 
<br>
<span style="font-size: 18px">The Cp vs TSR for each of the selected airfoils where the area under the graph can be considered the airfoils' general efficiency:</span> 
{% include image-gallery.html images="https://live.staticflickr.com/65535/54587448810_80bf2f75d1_w.jpg" height="450" %}
<br>
<span style="font-size: 18px">The NASA LRN 1015 airfoil:</span> 
{% include image-gallery.html images="https://live.staticflickr.com/65535/54586250162_3ac0ebf738_w.jpg" height="400" %}
<br><br><br>

## For the heat generation subsystem, Schieber's model for resistive torque was used as a baseline but some derivations were made to more appropriately model it for our use case:

<br>
<span style="font-size: 18px">The formula that was used to calculate the Power derived from the system is as follows:</span> 
{% include image-gallery.html images="https://live.staticflickr.com/65535/54587303576_8125cab620_w.jpg" height="400" %}
<br>
<span style="font-size: 18px">The formula for the torque produced by the magnets, and thus the minimum torque needed by the turbine to actually move, is given by:</span> 
{% include image-gallery.html images="https://live.staticflickr.com/65535/54586435782_d3bddeb504_m.jpg" height="400" %}
<br>
<span style="font-size: 18px">After landing on final turbine specs, everything could be plugged in to find the maximum number of magnets that could be used and thus the final design of the heating subsystem was created:</span> 
{% include image-gallery.html images="https://live.staticflickr.com/65535/54587118911_f414ab6bae_w.jpg" height="450" %}
