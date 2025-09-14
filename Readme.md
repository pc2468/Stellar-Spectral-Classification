# Classification of Stars Based on Stellar Spectra  

This project focuses on **classifying stars based on their stellar spectra** and visualizing their placement on the **Hertzsprung–Russell (HR) diagram**.  

---

## Project Overview  

- Data is obtained from the **[Sloan Digital Sky Survey (SDSS)](https://www.sdss4.org/)**.  
- Unknown stars are sorted into **spectral classes (O, B, A, F, G, K, M)** using spectral features.  
- A set of known stars is then taken for reference using a simple **Python script**.  
- Finally, the stars are plotted on the **HR diagram** to show their relationship between **luminosity and temperature**.  

---

## Repository Structure  
.
├── data/ # SDSS data files (if included)
├── scripts/ # Python scripts for classification & plotting
├── figures/ # Figures & HR diagrams
└── output.pdf # Compiled LaTeX report


---

## Workflow  

1. **Fetch data**  
   - Download stellar spectra data from SDSS.  

2. **Classify stars**  
   - Sort unknown stars into spectral classes.  
   - Cross-check with known star data.  

3. **Analyze with Python**  
   - Use a Python script to select known stars.  
   - Generate and visualize the HR diagram.  

4. **Document findings**  
   - Full explanation and analysis written in LaTeX.  
   - Final compiled PDF report available in the repo.  

---

## Example: HR Diagram 

```bash
python hr_diagram.py

## Features
- Stellar classification using spectral analysis
- Clean HR diagram visualization
- Full LaTeX report for academic use
- Reproducible workflow with Python + SDSS data

## Acknowledgements
- SDSS Collaboration – for stellar spectra data
- Python & Matplotlib – for data analysis and visualization
- LaTeX – for professional scientific documentation