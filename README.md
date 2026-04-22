# 3D Skull Reconstruction from CT Imaging

## Overview
This project demonstrates the reconstruction of a 3D model of human cranial anatomy from CT scan data using 3D Slicer. The objective was to isolate bone structures through segmentation and generate a clean 3D visualization of the skull.

## Tools Used
- 3D Slicer
- CT imaging data (.nrrd)

## Methodology
1. Imported CT scan data into 3D Slicer  
2. Applied threshold-based segmentation to isolate bone tissue  
3. Refined segmentation using manual editing tools  
4. Generated a 3D surface model from the segmentation  
5. Exported the model as an STL file  

## Results
A 3D skull model was successfully reconstructed and visualized from multiple anatomical perspectives. Minor surface layering artifacts are present due to CT slice resolution, which is typical in medical imaging datasets.

---

## Preview

### Front View
![Front](Front.pdf)

### Right View
![Right](Right.pdf)

### Left View
![Left](Left.pdf)

### Top View
![Top](Top.pdf)

### Inferior (Bottom) View
![Bottom](Underneath.pdf)

---

## Files Included
- `Segmentation_bone.stl` → 3D model of the skull  
- `Segmentation-bone-label.nrrd` → segmentation data  
- CT-derived visualizations (PDFs) for multiple anatomical views  

---

## Skills Demonstrated
- Medical image processing  
- CT segmentation (thresholding + refinement)  
- 3D anatomical reconstruction  
- Data visualization and export  

---

## Limitations
- Surface layering artifacts due to CT slice spacing  
- No dental structures present in dataset  
- Resolution limited by source imaging data  

---

## Future Work
- Use higher-resolution CT datasets  
- Improve segmentation for finer anatomical detail  
- Incorporate dental reconstruction if data is available  

---

## License
This project is for educational and portfolio purposes.

If using this work, please provide appropriate attribution.

---

## Author
Emily Delgado
