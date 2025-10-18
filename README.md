## 🧠 Master’s Thesis Repository  

### **Brain Tumor Segmentation in Pediatric MRI Using Transfer Learning and Redundancy Reduction through Model Pruning of nnU-Net**  

**Author:** Mohammad Nabizade-Ardakani  
**Supervisor:** Dr. Ahmad Mahmoudi-Aznaveh  
**Program:** M.Sc. in Information Technology Engineering (Multimedia Systems)  
**Institution:** Shahid Beheshti University — Cyberspace Research Institute  
**Defense Period:** October 2025 (Mehr 1404)  

---

### 🩺 Overview  
This repository has been created **exclusively for the Master’s thesis defense and academic evaluation** at **Shahid Beheshti University, Tehran**.  
It contains experimental code, model configurations, figures, and analytical results developed as part of the research titled:  
> *“Brain Tumor Segmentation in Pediatric MRI Using Transfer Learning and Redundancy Reduction through Model Pruning of nnU-Net.”*

The purpose of this repository is to provide transparent technical documentation and implementation details for the thesis supervisors and examiners, demonstrating the depth and originality of the conducted research.  

---

### 🧠 Network Architecture  

Below is the general structure of the proposed network used for **pediatric brain MRI tumor segmentation**.  
This diagram illustrates the base architecture derived from the **3D nnU-Net** framework, with adaptations for transfer learning and model pruning.

<p align="center">
  <img src="https://github.com/mohammadnabia/thesis-archive-oct2025-nabizade/blob/main/networkstructure.png" alt="Network Structure" width="700"/>
</p>

---

### ⚙️ Technologies and Frameworks  
- Python 3.10+  
- PyTorch 2.x  
- nnU-Net v2 / DA-nnU-Net  
- NumPy, Matplotlib, NiBabel  
- Google Colab Pro+ environment  

---

### 🧪 Research Context  
This work focuses on developing a **lightweight and adaptive version of 3D nnU-Net** for **pediatric brain tumor segmentation in MRI**.  
It explores **transfer learning**, **fine-tuning**, and **model pruning** strategies to improve computational efficiency while preserving segmentation accuracy.  

Key contributions include:  
- ⚙️ Non-structured weight pruning for sparsity analysis  
- 🧠 Fine-tuning across domain shift (BraTS → BraTS-PEDs)  
- 📊 Evaluation using Dice Score and Hausdorff Distance  
- 💾 Lightweight inference suitable for limited GPU resources  

---

### 🔒 License and Usage  
This project is **not open-source**.  
All materials — including source code, trained weights, and documents — are protected under **All Rights Reserved © 2025 Mohammad Nabizade-Ardakani**.  
Use, reproduction, or distribution is **strictly prohibited** without written permission from the author.  

📧 Contact: **mnabiard [at] gmail [dot] com**

---

### 🏛️ Acknowledgment  
This research has been conducted as part of the Master’s program at the **Cyberspace Research Institute, Shahid Beheshti University**, under the supervision of **Dr. Ahmad Mahmoudi-Aznaveh**.  
The author gratefully acknowledges the support and guidance of faculty members and colleagues who contributed to this academic journey.
