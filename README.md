# AstraLens
AstraLens: An interactive lunar explorer for the NASA Space Apps Challenge. Visualizes real mission data (Apollo, ShadowCam) on an interactive map.

AstraLens makes NASA's vast lunar image archives interactive, plotting thousands of real observations from the Apollo and ShadowCam missions directly onto an explorable map.

🚀 The Challenge

(Action Required: Briefly describe the NASA Space Apps Challenge your team chose to address. For example: "This project addresses the 'Seeing the Unseen' challenge by developing a new way to visualize and interact with data from permanently shadowed regions...")

Core Features

AstraLens transforms raw mission datasets into a seamless, explorable canvas with powerful tools:

🛰️ Real Mission Data: Visualizes thousands of data points from historic missions, including Apollo (DPSC, Metric, Pan) and the LRO ShadowCam.

🔥 Heatmap Analysis: Instantly reveals the density of observations to show where missions focused their attention, from equatorial orbits to polar targets.

🧠 AI-Powered Insights (Simulated): Each data point includes a simulated AI summary, providing instant scientific context about the observation's purpose and conditions (e.g., identifying PSR targets).

📏 Measurement Tool: Accurately calculate the distance between any two points on the lunar surface in kilometers.

🌐 Interactive Map: A smooth, fast, and responsive map interface powered by Leaflet.js, allowing users to pan, zoom, and explore.

Data Sources

All data is processed from publicly available NASA datasets:

Apollo Panoramic Camera (Pan)

Apollo Metric Camera (Metric)

Apollo DPSC Camera

Lunar Reconnaissance Orbiter (LRO) ShadowCam

Data is courtesy of NASA and the PDS Imaging Node.

🛠️ Tech Stack

Frontend: HTML5, Tailwind CSS

Mapping: Leaflet.js

Leaflet Plugins: leaflet.heat (for heatmaps), Leaflet.Polyline.Measure (for distance measurement)

Data: JSON (processed from original mission CSVs)

How to Run Locally

No complex setup is required!

Clone this repository.

Open the index.html (or index2.html) file directly in your web browser.

💡 Future Ideas

Integrate more datasets (e.g., LRO LOLA, Chandrayaan).

Add a time-slider to visualize missions chronologically.

Implement a search and filter function for specific image IDs or locations.
