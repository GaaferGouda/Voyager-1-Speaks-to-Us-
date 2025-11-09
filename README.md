# Voyager 1 Radio Signal Analysis Tutorial 🚀

**Analyze real Voyager 1 radio signals from the Breakthrough Listen project using Python.**  

This Jupyter Notebook is a hands-on tutorial for learning **space-data analysis**. You’ll explore how scientists detect faint spacecraft signals amid massive amounts of radio noise using Python tools like `blimpy` and `turboSETI`.

---

## 🛰️ Purpose  

The notebook teaches the **SETI (Search for Extraterrestrial Intelligence)** data analysis pipeline. You’ll learn how to:  

- Download telescope recordings of Voyager 1  
- Visualize the data as spectrograms  
- Run signal detection algorithms to identify Doppler-shifting signals  
- Interpret results scientifically  

---

## 🔍 Main Sections  

1. **Introduction & Background**  
   - Overview of Voyager 1 and SETI  
   - Challenges in separating real signals from Radio Frequency Interference (RFI)  

2. **Setup**  
   - Python environment setup using `conda`  
   - Installation of key tools: `blimpy` and `turboSETI`  

3. **Telescope Data**  
   - Download `.h5` data from the Green Bank Telescope  
   - Work with real spectrogram data files  

4. **Analysis using turboSETI**  
   - Load data with `blimpy`  
   - Run Doppler drift searches to detect narrowband signals  

5. **Visualization**  
   - Plot spectrograms  
   - Highlight Voyager 1’s signal as a drifting line  

---

## 🧰 Requirements  

- Python ≥ 3.9  
- `conda` or `miniconda`  
- Python libraries:  
```bash
conda install -c conda-forge blimpy turbo-seti matplotlib numpy
```

## 📖 Usage

1. Open this notebook (`VoyagerTutorial.ipynb`) in Jupyter Notebook or JupyterLab.
2. Follow the notebook step by step to:
   - Download Voyager 1 telescope data (.h5 files)
   - Load the data using `blimpy`
   - Run Doppler drift searches with `turboSETI`
   - Visualize and interpret detected signals
3. You can modify parameters in the `turboSETI` search to explore different signal detection thresholds.


## 🧠 Learnings

By completing this notebook, you will understand:

- How to handle **real space radio data** from Voyager 1
- How to detect faint, Doppler-shifting signals in noisy data
- Techniques to visualize and interpret spectrograms
- Python workflows for SETI data analysis


## 🙏 Acknowledgments

Special thanks to **Dr. Mohamed Faran** for his guidance and mentorship in this project.  

This notebook is part of the **Space-Code** initiative — a larger project to make space-data analysis more accessible and hands-on. Launch coming soon, InshaaAllah!
