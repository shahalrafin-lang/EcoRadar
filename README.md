🌍 EcoRadar 

NISAR Earth Surface Change Analyzer

Explore Earth's changing surface through satellite radar observations.

🌐 Live Demo: "Open EcoRadar" (https://shahalrafin-lang.github.io/EcoRadar/)

🚀 About

EcoRadar is an interactive Earth-observation platform that uses real NASA-ISRO NISAR satellite data to visualize and compare radar observations.

The project focuses on a sample region in Greenland, helping users explore changes between two satellite acquisitions through interactive visualization.

Developed for the NASA Space Apps Challenge 2026.

✨ Features

- Real NISAR Greenland satellite observations.
- Side-by-side and split-view comparison.
- Pixel-level difference visualization (A − B).
- Linear and decibel display modes.
- Interactive zoom and pan.
- Pixel inspector and histogram.
- Multiple colour ramps and image adjustments.
- CSV and PNG export.
- Synthetic demonstration views.

🛰️ Data Sources

- Mission: NASA-ISRO NISAR
- Product: Level-2 GCOV
- Source: ASF Earthdata Cloud
- Study Region: Greenland
- Acquisition A: November 3, 2026
- Acquisition B: October 22, 2026
- Resolution: 20 metres
- Format: GeoTIFF

🛠️ Technologies

HTML5 · CSS3 · JavaScript · Python · GDAL · Rasterio · GeoTIFF

▶️ Run Locally

1. Clone or download this repository.
2. Open the project folder.
3. Open "index.html" in a modern web browser.

git clone https://github.com/shahalrafin-lang/EcoRadar.git
cd EcoRadar

📁 Project Structure

EcoRadar/
├── index.html
├── README.md
├── data/
│   ├── Greenland_NISAR_B.tif
│   └── Greenland_NISAR_HHHH.tif
└── tools/
    ├── ref_decode.py
    └── verify_embedded_data.py

⚠️ Scientific Note

Radar differences are useful for exploring changes in measurements, but they do not independently prove glacier movement, ice loss, or specific environmental events. Scientific interpretation requires further validation. Synthetic views are demonstrations, not real satellite measurements.

---

EcoRadar — Observing Earth. Exploring Change.
