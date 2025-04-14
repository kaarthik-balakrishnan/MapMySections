# 🧠 MapMySections Challenge

This repository contains code and analysis for the [Allen Institute's MapMySections Data Challenge](https://alleninstitute.github.io/MapMySections/). The goal is to map fluorescent images of genetic tools to transcriptomic cell types in the mouse visual cortex.

---

## 📁 Contents

- `MapMySections_Starter.ipynb` — Starter notebook for setting up the environment, loading sample data, and running a basic image registration demo using SimpleITK.
- `section_sample.tif` — Sample brain section used for testing.
- (Upcoming) Image registration pipeline for real data with Allen CCFv3

---

## 🚀 Getting Started (in Google Colab)

1. **Clone the repo in Colab**:
```python
!git clone https://github.com/kaarthik-balakrishnan/MapMySections.git
%cd MapMySections
```

2. **Install dependencies**:
```python
!pip install numpy pandas matplotlib scikit-image tifffile SimpleITK
```

3. **Run the starter notebook**:
   - Upload or open `MapMySections_Starter.ipynb` from Colab
   - Visualize and register images
   - Modify as needed for your submission

4. **Push changes to GitHub**:
```bash
!git add .
!git commit -m "Update notebook with results"
!git push origin main
```

---

## 📌 Dependencies

- Python 3.8+
- numpy, pandas, matplotlib
- scikit-image, tifffile
- SimpleITK

---

## 📫 Contact

Questions? Reach out to the Allen Institute on [GitHub Discussions](https://github.com/AllenInstitute/MapMySections/discussions) or open an issue.

