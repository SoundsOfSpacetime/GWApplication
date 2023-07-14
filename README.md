<base target="_blank"> <!-- Opens all URLs in new tabs -->

# Sounds of Spacetime - [soundsofspacetime.org](https://soundsofspacetime.org)

Our purpose is to explore the physics of gravitational waves via an analogy to audible sounds. Gravitational waves (GW) are ripples in the fabric of spacetime produced by colliding black holes, neutron stars, supernovae, and other astrophysical phenomena. This application is intended to make the exploration of gravitational waves as accessible as possible.

# Interactive Gravitational Wave Tool

![GW Application Screenshot](https://i.imgur.com/5OjRYX7.png)

## Instructions

1. Go to the [Sounds of Spacetime - Interactive Gravitational Wave Tool](https://soundsofspacetime.github.io/GWApplication/) simulation. Google Chrome is highly recommended.
2. Enable sound on your device. Use of headphones is highly recommended. 
3. Use the "Select Device" dropdown menu to choose laptop speakers or headphones.

    Note: If using a cellphone speaker, you should click "Laptop". If using desktop speakers with a subwoofer, you should click "headphones".

4. Adjust the higher-order harmonic constant and the mass values.

5. Press "Play Waveform" or "Download Audio" to hear the sound corresponding to this waveform. Be sure to look at the values on the x-axis for each event. The duration of some sounds may be shorter than one second. Conceptually, it is important to know these events do not produce sounds. The audio generated in the simulation is another means of interpretting the signal received by the detectors.

## Generation of Plots

1. Plots are dynamically generated in JavaScript using approximate equations. These equations do not feature the ringdown period after the merger.
2. Strain values are extremely small and are normalized to have a minimum of -1, and maximum of 1. When the higher-order harmonic is non-zero, the normalized strain range will increase slightly.

## Dependencies

1. [Plotly.js](https://plotly.com/javascript/) [MIT License]
2. [WAV.js](https://github.com/taweisse/wavJS) created by Todd Weisse [MIT License]

## Credit

Programmed by Kevin Johansmeyer, advised by Dr. Marc Favata and Dr. Shaon Ghosh (Montclair State University)