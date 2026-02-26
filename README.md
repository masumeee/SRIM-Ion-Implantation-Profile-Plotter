# SRIM-Ion-Implantation-Profile-Plotter - Free, Pro Visualization Online Tool

https://srim-ion-implantation-profile-plotter.netlify.app/               

SRIM Ion Implantation Profile Plotter - A free tool to visualize ion implantation profiles from SRIM .txt files. Compare multiple profiles, select units, export plots as PNG. James Ziegler - SRIM &amp; TRIM. ion implantation, profile, plotter, depth, concentration, doping, Depth vs. concentration profiles, Semiconductor, simulation &amp; analysis tool.

Why This Tool Exists
Working with ion implantation data from SRIM can be tedious. Manually creating plots from .txt output files is time-consuming and often requires programming or expensive software.
The SRIM Ion Implantation Profile Plotter solves this by providing a browser-based, professional-grade tool that lets researchers quickly visualize, compare, and export their ion implantation profiles without coding skills.

Features
Upload multiple SRIM .txt files for simultaneous comparison.
Choose units: Depth in Å, nm, or µm; Concentration in atoms/cm³ or fraction.
Compare profiles visually with distinct colors and markers.
Interactive plots: zoom, pan, and hover for precise data points.
Export high-resolution PNG images for presentations, papers, or posters.
Professional scientific formatting with bold axes and log-scale Y-axis.

Who Can Benefit
Semiconductor researchers analyzing dopant distributions.
Students learning about ion implantation.
Engineers preparing conference posters or journal figures.
Anyone needing clean, scientific plots from SRIM data.

Getting Started
Open the tool in your browser: Launch Plotter.
Upload your SRIM Range.txt files.
Customize units and plot settings.
Interact with the plot and export high-quality figures. Full Process Steps Below!

License
This project is completely free to use.You can use and share it for personal or professional purposes.

Snapshot of the tool Above!
TRY NOW --- https://srim-ion-implantation-profile-plotter.netlify.app/

- Only the **first two numeric columns** are used (depth and implanted ion concentration).  
- Other SRIM output details are ignored.

---

## Sample Input

1. `P_50keV_Range.txt`  
2. `B_100keV_Range.txt`  

**Dose:** `1e12` ions/cm²  
**Depth Unit:** `nm`  

> Multiple files can be uploaded simultaneously. The plot will scale concentrations based on the entered dose.

---

## Plot Customization

- **Depth Units:** Å, nm, or µm.  
- **Marker size and line width:** Built-in **thicker lines and markers** for journal-quality plots.  
- **Logarithmic y-axis:** Concentration shown in log scale.  
- **Dynamic y-axis:** Automatically adjusts from **min to max concentration**, even for very low or high doses.  

---

## Exporting Figures

- Click **Export High-Res PNG**.  
- The exported image is **high-resolution (3x scale)**, suitable for publication.  
- File name: `srim_implantation_profile.png`  

---

## Resetting/Start Over

- Click **Start Over** to:  
  - Clear dose input  
  - Clear file selection  
  - Remove the plot  
- Placeholder text will reappear: `"Plot will appear here after uploading SRIM files"`

---
TRY NOW --- https://srim-ion-implantation-profile-plotter.netlify.app/
