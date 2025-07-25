# Sound Travel Rhythm Calculator

A modern web app for calculating rhythmic delays based on the speed of sound, distance, temperature, tempo, and beat unit.

## Features
- Calculates sound travel delay in musical note values (1/4, 1/8, 1/16, 1/32 notes)
- Visualizes results with interactive charts (powered by Chart.js)
- Sleek, responsive Bootstrap UI

## Usage
1. Open `index.html` in your browser. You also can go to [website](https://sjacksonhodum.github.io/Sound-Travel-Rhythm-Calculator/)
2. Enter:
   - Distance (yards)
   - Temperature (°F)
   - Tempo (BPM)
   - Beat unit (choose from dropdown or enter custom)
3. Click **Calculate**.
4. View results, rounded delays, and charts.

## Math
The calculator uses the following formula (matching the original iOS Shortcut):

```
t = (Distance [yd] / (362.114 * sqrt(((Temp [ºF] - 32)/1.8 + 273.15)/273.15))) * (Beat Unit * Tempo [beats/min]/60)
```

## Attribution
Idea initially developed by Jeremy Bahadirli, website built by @sjacksonhodum (calculations should be accurate)