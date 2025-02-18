# SkinThickness_AUC_MATLAB
# MATLAB Skin Thickness & AUC Analysis

## 📌 Overview
This MATLAB script processes `.nd2` image files to:
- Extract **skin thickness** using Z-step size and slice count.
- Compute **Area Under Curve (AUC)** for fluorescence intensity.
- Generate a **cumulative skin thickness vs. AUC graph** for better data interpretation.

## 🛠️ Features
✅ Automatic extraction of Z-stack metadata  
✅ Accurate skin thickness calculation  
✅ AUC computation for fluorescence quantification  
✅ Sequential representation of skin thickness in the x-axis  

## 📂 File Structure
- `main_script.m` → The primary MATLAB script
- `LICENSE.txt` → Legal usage details
- `README.md` → Instructions and usage guide

## 🖥️ Installation & Requirements
1. Install **MATLAB** (R2024b or later recommended).
2. Add **Bio-Formats Toolbox** to your MATLAB path:
   ```matlab
   addpath('C:\Program Files\MATLAB\R2024b\bfmatlab\bfmatlab');
