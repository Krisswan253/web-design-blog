---
title: Project 2
layout: layouts/base.njk
---
# Project 2

## Concept

Project #2 Concept - “The Earth is Breathing”

Concept:

visualizing the Earth as a living system by translating real environmental data into layered wave signals that behave like a pulse. Instead of presenting ocean and seismic data as numerical measurements, the site will reframe them as rhythms that reflect the planet’s constant movement between stability and disturbance.
The ocean serves as the steady baseline rhythm (like a heartbeat), representing slow, continuous planetary processes, while earthquakes appear as sudden disruptions layered on top of this motion (anxiety? Pressure? Can represent emotions like that). By combining these systems into a single visualization, my idea was to treat the earth and the human experience as one, using the earth’s natural movement to fit it into the human EKG reading. 
APIs Used: 
National Oceanic and Atmospheric Administration (NOAA buoy data) https://www.ndbc.noaa.gov/data/realtime2/
United States Geological Survey (USGS Earthquake API) https://earthquake.usgs.gov/fdsnws/event/1/

Step 1 -  Establishing the baseline (could be ocean waves or something else?)
Build the steady ocean wave using NOAA data.

Smooth motion driven by:

Scott’s idea?:
amplitude = waveHeight mapping
speed = wavePeriod mapping

Create a foundational rhythm?

 Step 2  - Introduce disturbance (I feel like earthquakes is a strong contender for this aspect but if yall have diff ideas thats fine too)

Add seismic layer using USGS data.

Sharp spikes appear when earthquakes occur =  disrupting the baseline wave.

Contrast between steady motion + sudden rupture becomes visible.


Step 3 - fun add-ons 
Add layer toggles?
Introduce subtle color shifts based on activity level?
Refine motion to emphasize rhythm?
Examples:
 Smooth transitions between values
Make the baseline wave move with a clear repeating rhythm (ekg style)
For earthquake: Slight variation instead of jitter 
Use gentle noise instead of harsh movement so it feels organic.
Like breathing instead of shaking.

Examples:
https://codepen.io/denisharda/pen/GNaaKO
https://editor.p5js.org/KaterinaMagarini/sketches/prnTtOJ29
https://www.youtube.com/watch?v=okfZRl4Xw-c