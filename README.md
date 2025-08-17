# Statistical Shape Analysis - Code Setup
## Dependencies
- Python 3.8+
- Libraries: NumPy, SciPy, scikit-learn, geomstats (for Riemannian methods)
Install via: `pip install numpy scipy scikit-learn geomstats`
Running the Code
1. Preprocessing: Run `python preprocess.py` to align landmarks.
2. Analysis: Execute `python shape_analysis.py` for Procrustes/PCA/Riemannian methods.
3. Output: Results saved in `/output/` (mean shapes, curvature plots).
4. Example Data
- Files: `caesar_sample.csv`, `kidsize_sample.obj`
- Columns: Landmark IDs, X/Y/Z coordinates.
