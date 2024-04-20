# Siganl-Viewer-


[Uploading Recording 2024-04-20 233124.mp4…](https://github.com/ZeyadKhaled-29/Siganl-Viewer-/assets/161847692/fbbc6e7d-a0e4-43e0-898c-e934a7c618f3)


The Multi-Port, Multi-Channel Signal Viewer, developed for the Digital Signal Processing course at Cairo University's Faculty of Engineering, enables simultaneous visualization of diverse medical signals, fostering understanding of signal processing concepts in healthcare.

# Multi-Port, Multi-Channel Signal Viewer

## Introduction
The Multi-Port, Multi-Channel Signal Viewer is a desktop application developed in Python using PyQt5. This application serves the critical function of monitoring vital signals in an ICU setting. It allows users to visualize multiple medical signals simultaneously, providing essential features for signal analysis and manipulation.

## Features
- **Signal File Selection:** Users can browse their PC to open various signal files, including examples of different medical signals such as ECG, EMG, EEG, etc., with both normal and abnormal samples provided.
- **Dual Graph Display:** The application contains two main identical graphs, each with its own controls. Users can open different signals in each graph, enabling independent analysis. Graphs can also be linked to display the same time frames, signal speed, and viewport when necessary.
- **Cine Mode:** Signals are displayed in a cine mode, resembling the dynamic display seen in ICU monitors. The signals run continuously through time, and users can rewind or stop the signal playback.
- **Manipulation Controls:** Users can manipulate running signals through intuitive UI elements, including:
  - Changing signal colors
  - Adding labels/titles for each signal
  - Showing/hiding signals
  - Controlling/customizing cine speed
  - Zooming in/out
  - Pausing/playing/rewinding signals
  - Scrolling/Panning signals in any direction
  - Moving signals between graphs
- **Boundary Conditions Handling:** The application ensures that manipulations like scroll/pan are restricted within signal boundaries to prevent empty graphs or invalid data display.
- **Exporting & Reporting:** Users can generate reports of one or more snapshots for the graphs, including data statistics on displayed signals. The report is constructed within the application, providing a nicely organized layout with data tables and snapshots.



## Acknowledgments
This application was developed as a task project, inspired by the need for efficient signal monitoring tools in medical environments. We thank the creators of PyQt5 and the Python community for their contributions to open-source software development.






