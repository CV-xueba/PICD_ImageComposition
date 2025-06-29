# PICD: Photographic Image Composition Dataset  
**Can Machines Understand Composition? A Dataset and Benchmark for Photographic Image Composition Embedding and Understanding**  
📌 *CVPR 2025 Highlight*

📄 [CVPR 2025 Paper](https://openaccess.thecvf.com/content/CVPR2025/html/Zhao_Can_Machines_Understand_Composition_Dataset_and_Benchmark_for_Photographic_Image_CVPR_2025_paper.html)  
📑 [Supplementary Appendix](https://openaccess.thecvf.com/content/CVPR2025/supplemental/Zhao_Can_Machines_Understand_CVPR_2025_supplemental.pdf)

---

## 📌 Overview

**PICD** is a large-scale dataset for **photographic image composition analysis**, currently containing **49,123 high-quality images** annotated with **24 composition categories**.

This dataset supports the evaluation and advancement of composition learning in AI models. It is suitable for tasks such as **aesthetic quality assessment**, **composition-aware image cropping**, and beyond. We invite the research community to explore novel and creative applications of PICD.

The composition label system is organized along two axes:

- **Element Types**: Points, Lines, and Shapes (inspired by Kandinsky’s principles)  
- **Arrangement Patterns**: Rule of Thirds, Centered, Diagonal, Vertical, Horizontal, Triangle, C-curve, O-curve, S-curve, Radial, Dense, Scatter, etc.

📖 For detailed category definitions and the design of the label system, please refer to the [Appendix](https://openaccess.thecvf.com/content/CVPR2025/supplemental/Zhao_Can_Machines_Understand_CVPR_2025_supplemental.pdf).

<p align="center">
  <img width="419" alt="Label System Figure" src="https://github.com/user-attachments/assets/5bf1aa5e-d0fa-4480-9334-bc1d130b4510" />
</p>
<p align="center">
  <em>Figure 1. The PICD label system, structured by element types and arrangement patterns. Column 1 (green) lists arrangement types. Columns 2–4 show compositional element types. Categories are numbered 1–24 with blue abbreviations. Red boxes indicate merged categories; blue strikethroughs denote excluded ones due to low frequency. Column 5 highlights dominant compositional factors.</em>
</p>

<p align="center">
  <img width="887" alt="Category Sample Figure" src="https://github.com/user-attachments/assets/fc5a477e-d9ce-4e6d-bfdb-c4590a672f64" />
</p>
<p align="center">
  <em>Figure 2. Sample images from the 24 composition categories in PICD. Category abbreviations are shown in blue parentheses.</em>
</p>

---

## 📊 Dataset Information

PICD is actively maintained and will continue to expand. The current release includes:

- ✅ **19,123 images**
- ✅ Verified composition category annotations  
- ⏳ Negative samples (images not conforming to any predefined category) — *coming soon*  
- ⏳ Composition quality scores — *coming soon*  
- ⏳ Textual composition descriptions — *coming soon*

---

## 🔗 Download

PICD includes both image data and annotations. Due to varying licensing conditions, images are provided in two categories:

### 1. Images

- 📥 **Images from open platforms and redistributable open-source datasets**  
  These include platforms like Unsplash and Pexels. We provide direct download links:  
  👉 **[TODO: Google Drive / Baidu Netdisk download link]**

- 🗂️ **Images from public datasets that do not allow redistribution**  
  For datasets such as AVA, we provide a mapping file that links each image's original ID or URL to its corresponding PICD image ID:  
  👉 **[Image ID Mapping File](https://github.com/CV-xueba/PICD_ImageComposition/blob/main/image_link_public.csv)**  
  (`PICD_image_id ↔ original_dataset_image_link_or_id`)  
  If you encounter any issues downloading or locating these images, feel free to [contact us](mailto:your.email@example.com) — we’re happy to help.

### 2. Annotations

- ✏️ **Image Annotations**  
  👉 **[Annotation File](https://github.com/CV-xueba/PICD_ImageComposition/blob/main/labels_PICD.csv)**  
  This CSV file includes:
  - `img_id`: the PICD image ID  
  - `category_id`: the composition category index 
  - `category_abbre`: the abbreviated category label
  - `category_full_name`: the full name of the composition category

The mapping among `category_id`, `category_abbre`, and `category_full_name` follows the structure defined in **Figure 1** above.

---

## 📄 License and Terms

PICD is released under the  
**Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International License (CC BY-NC-SA 4.0)**.

In addition, all users must agree to the official dataset usage terms:  
📄 [PICD Dataset Terms of Use (PDF)](https://github.com/CV-xueba/PICD_ImageComposition/blob/main/PICD_Dataset_Terms_of_Use.pdf)

---

## 🔧 Citation

If you use PICD in your research, please cite:

```bibtex
@inproceedings{zhao2025picd,
  title     = {Can Machines Understand Composition? Dataset and Benchmark for Photographic Image Composition Understanding},
  author    = {Zhaoran Zhao and [Other Authors]},
  booktitle = {Proceedings of the IEEE/CVF Conference on Computer Vision and Pattern Recognition (CVPR)},
  year      = {2025}
}
