# Stellargaze - Exoplanet Night Sky Simulator

Created in the NASA Space Apps PS - "Exosky", where we had to simluate how the night sky would look like from different exoplanets!

This is an interactive 3D planetarium built using Three.js. Backend is written in Python Django. The star dataset is from the Hipparcos catalog and exoplanets from NASA Exoplanet Archive.



## Features

- **Exoplanet Night Sky Simulation**: Visualize the night sky as seen from various exoplanets, with star positions and brightness recalculated based on your chosen vantage point.
- **Real Astronomical Data**: Built using the Hipparcos star catalog and NASA Exoplanet Archive for accurate exoplanet coordinates.
- **Interactive 3D Planetarium**: Built using Three.js, you explore the sky in a smooth, immersive 3D environment.
- **Custom Constellations**: Draw and save your own constellations unique to each exoplanet’s sky.
- **Screenshot Capture**: You can even save snapshots of your custom constellations.
- **Exoplanet Selection**: Choose from some common well-known exoplanets or input custom exoplanet data (in NASA Exoplanet Archive format).


## How It Works

1. **Star Data Processing**: 
   - Starts with the Hipparcos catalog by fetching Right Ascension, Declination, distance, and apparent magnitude as seen from Earth.
   - Convert these into 3D coordinates and calculates absolute magnitude.
2. **Exoplanet Positioning**: 
   - Get 3D coordinates of exoplanets from the NASA Exoplanet Archive.
   - Compute the relative distance and orientation of stars from each exoplanet’s perspective.
3. **Sky Calculation**: 
   - Recalculate RA, Dec, and apparent magnitude of stars as they’d appear from the chosen exoplanet.
4. **Visualization**: 
   - Render the starfield in a 3D planetarium using Three.js, allowing users to explore, draw constellations, and save their view.



## Tech Stack

- **Backend**: Python, Django
- **Frontend**: Three.js (JavaScript), HTML, CSS
- **Data Sources**: 
  - Hipparcos Catalog (stellar data)
  - NASA Exoplanet Archive (exoplanet data)



## Usage
- Either clone and run locally, or visit https://astrophy-geek.github.io/stellargaze to try it out!
- Launch the app and select an exoplanet from the list, or input your own exoplanet data.
- Explore the 3D starfield, zoom, and pan to view the sky.
- Use the key 'c' and then click two points to draw a constellation line!
- Hit the camera iconto capture your view.
- Change ambient lighting and limiting magnitude of stars using the sliders.
- Use the trash icon to remove custom constellations.
- Toggle the Earth icon to show/hide the ground!

IMP: The server runs slow (free hosting, lol!) so it might take maybe even minutes to load. If it still doesn't refresh the tab, it loads faster at times.

---

## Contributing

I am looking to work further on this and create this into a full fledged simulator for educational purposes! 

Contributions are welcome! 
