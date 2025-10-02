# 📌 Assignment 4: Augmented Reality with PyTorch3D

## 🎯 Project Overview
This project demonstrates **Augmented Reality (AR)** by overlaying synthetic 3D objects onto real images using **camera pose estimation** and **PyTorch3D rendering**.  
The system estimates the camera’s extrinsic parameters from a planar object (e.g., a book surface) and correctly aligns 3D objects (cube, sphere, teapot, pyramid) within the scene.

---

## 🛠 Features
- ✅ Camera Pose Estimation from 4 planar points  
- ✅ PyTorch3D renderer setup with correct intrinsics/extrinsics  
- ✅ Rendering of multiple 3D meshes (cube, sphere, pyramid, teapot)  
- ✅ Overlay on real images with reprojection error visualization  
- ✅ Interactive **Gradio interface** for experimentation  
- ✅ Bonus utilities: saving/loading camera parameters, frustum visualization  

---

## 📂 Repository Structure
```
├── AR_PyTorch3D.ipynb   # Main Jupyter/Colab notebook
├── README.md                        # Project documentation
├── example_input.png                # Example input image
├── example_ar_output.png            # Example AR output
```

---

## ⚙️ Installation
Run this project in **Google Colab** (recommended) or locally.

### Google Colab
1. Upload the notebook (`.ipynb`) to Colab.
2. Ensure GPU runtime is enabled (`Runtime > Change runtime type > GPU`).
3. Run all cells.
---

## ▶️ Usage
-Just run all the cell of the notbook.

## 📊 Results
- The renderer aligns synthetic objects with real-world geometry.
- Reprojection error (RMSE) is computed to validate accuracy.
- Example outputs are included in this repo.

