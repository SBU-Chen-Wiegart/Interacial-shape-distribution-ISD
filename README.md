# Interacial-shape-distribution-ISD

Interfacial shape distribution (ISD) calculation from meshed 3D datasets exported from Avizo/Amira.

The surface mesh and principal curvatures need to be first generated in Avizo/Amira, and saved as ASCII files. 

Under ‘Input section:’, add necessary information
1. Add file path, e.g., path = r'C:\Users\testfolder’ 
2. Add file name for meshed surface, e.g., filename_mesh = r'test_meshedfile.surf'
3. Add file name for the principal curvatures (min/max curvatures), e.g., filename_curvatures = r'BothCurvatures.am'
4. Add feature size; the unit needs to be consistent with the pixel size. If this is not needed, leave it as 1. The X and Y axis titles need to be changed to k1 and k2.
5. Adjust the xbins and ybins based on the data

**Acknowledgement**

We kindly appreciate that you cite this code and the following article:
1. Xiaoyin, Z., Xiaoyang, L., & Yu-chen Karen, C. (2022). Interfacial shape distribution calculation (Version 1.0.0) [Computer software]. https://github.com/SBU-Chen-Wiegart/Interacial-shape-distribution-ISD
2. Kammer, D. Three-Dimensional Analysis and Morphological Characterization of Coarsened Dendritic Microstructures. Northwestern University, 2006.



