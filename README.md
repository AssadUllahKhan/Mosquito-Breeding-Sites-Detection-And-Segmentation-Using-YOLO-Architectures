# Mosquito Breeding Sites Detection and Segmentation Using YOLO Architectures 🦟

This repository focuses on **mosquito breeding site detection and segmentation** using various YOLO architectures. It contains models for both **object detection** and **segmentation**, along with results and data visualization.

---

## Repository Structure

```
Mosquito Breeding Sites Detection and Segmentation Using YOLO Architectures
│
├── Models_Trained
│   ├── breeding-place-detection
│   │   ├── YOLOv5s
│   │   ├── YOLOv8n
│   │   └── YOLOv9s
│   │
│   └── water-surface-segmentation
│       ├── Segmentation Model YOLOv11s SIG
│       └── Segmentation Model YOLOv8x SIG
│
├── Docs
│   └── Poster-of-Mosquito-Breeding-Sites-Detection-and-Water-Surface-Segmentation-Project.pdf
│
└── 01DataVisualization.ipynb

```

- **Breeding Place Detection:** Contains YOLO detection models (YOLOv5s, YOLOv8n, YOLOv9s) and their results for detecting mosquito breeding sites.  
- **Segmentation:** Contains YOLO segmentation models (YOLOv11s SIG, YOLOv8x SIG) and their segmentation results.  
- **01DataVisualization.ipynb:** Jupyter Notebook for visualizing dataset samples, detection results, and segmentation masks.

---

## Key Features

- Detect mosquito breeding sites using multiple YOLO detection architectures.  
- Segment water surfaces in mosquito breeding areas using YOLO-based segmentation models.  
- Visualize dataset and model outputs using a Jupyter Notebook.  

---

## YOLO Architectures Used

### Detection
- **YOLOv5s:** Lightweight detection model, optimized for speed.  
- **YOLOv8n:** Improved YOLO version with better detection performance.  
- **YOLOv9s:** Advanced detection model with higher accuracy.

### Segmentation
- **YOLOv11s SIG:** Segmentation model for extracting water surfaces.  
- **YOLOv8x SIG:** Extended segmentation model for precise mask outputs.  

---

## Getting Started

1. **Clone the repository**  
```bash
git clone https://github.com/<your-username>/Mosquito-Breeding-Sites-Detection-and-Segmentation-Using-YOLO-Architectures.git
```

2. **Navigate to the repository folder**  
```bash
cd Mosquito-Breeding-Sites-Detection-and-Segmentation-Using-YOLO-Architectures
```

3. **Open the Jupyter Notebook**  
```bash
jupyter notebook 01DataVisualization.ipynb
```

4. Explore detection and segmentation results in their respective folders.

---

## Results

- Detection outputs are stored inside each YOLO detection model folder under `breeding-place-detection`.  
- Segmentation outputs are stored inside each YOLO segmentation model folder under `water-surface-segmentation`.  
- The notebook `01DataVisualization.ipynb` allows visualization of images, bounding boxes, and segmentation masks.

---

## License

This repository is for **educational and research purposes**. Please cite if used in publications or projects.

---

## Contact
**Assad Ullah Khan**  
📧 Email: assadullahkhan556@gmail.com <br/>🔗 LinkedIn: www.linkedin.com/in/assadullahkhan

