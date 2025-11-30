# OpenHRStrap
OpenHRStrap is an open-source DIY chest-strap heart-rate tracker built around the ESP32. It measures real biosignals through electrodes, filters the signal, and applies the Pan–Tompkins algorithm to detect R-peaks and compute heart rate in real time. The Pan-Tompkins algorithm has been implemented in Python to follow the filter chain as originally described in the paper. 

![First Version of OpenHRStrap]([https://your-image-url-here.jpg](https://github.com/MilosRasic98/OpenHRStrap/blob/main/Pictures/CroppedFinishedProject.png))

Latest Blog on the project: [element14 Running Tracker Blog](https://community.element14.com/challenges-projects/element14-presents/project-videos/w/documents/71995/build-your-own-esp32-fitness-heart-rate-monitor-tracker----episode-692?ICID=HP-E14P-EP692-FITNESS-HEART-RATE-MONITOR-NOV25)

Link to the latest video on the project: [Running Tracker Video Part 1](https://www.youtube.com/watch?v=Z1Dts_NHXyQ)

Original Pan-Tompkins Paper: [A Real-Time QRS Detection Algorithm](https://www.robots.ox.ac.uk/~gari/teaching/cdt/A3/readings/ECG/Pan+Tompkins.pdf)


## Project Updates

November 2025 — DIY-friendly version made using an XIAO ESP32 board with the AD8232 ECG module. Pan–Tompkins integration tested on static data works great; real-time detection while running is still a WIP. Scroll below for more details!  
V2 is in progress!

## Introduction


