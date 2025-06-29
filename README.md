# PICD: Photographic Image Composition Dataset  
**Can Machines Understand Composition? A Dataset and Benchmark for Photographic Image Composition Embedding and Understanding**  
📌 *CVPR 2025 Highlight*

📄 [CVPR 2025 Paper](https://openaccess.thecvf.com/content/CVPR2025/html/Zhao_Can_Machines_Understand_Composition_Dataset_and_Benchmark_for_Photographic_Image_CVPR_2025_paper.html)  
📑 [Supplementary Appendix](https://openaccess.thecvf.com/content/CVPR2025/supplemental/Zhao_Can_Machines_Understand_CVPR_2025_supplemental.pdf)

---

## 📌 Overview

**PICD** is a large-scale dataset for **photographic image composition analysis**, currently containing **49,123 high-quality images** annotated with **24 composition categories**.

This dataset is intended to support the evaluation and advancement of composition learning in AI models. It is applicable to a wide range of tasks, including **aesthetic quality assessment**, **composition-aware image cropping**, and more. We encourage researchers and practitioners to explore creative uses of PICD.

The composition label system is structured along two axes:

- **Element Types**: Points, Lines, and Shapes (inspired by Kandinsky’s principles)  
- **Arrangement Patterns**: Rule of Thirds, Centered, Diagonal, Vertical, Horizontal, Triangle, C-curve, O-curve, S-curve, Radial, Dense, Scatter, etc.

📖 For detailed category definitions and label design, please refer to the [Appendix](https://openaccess.thecvf.com/content/CVPR2025/supplemental/Zhao_Can_Machines_Understand_CVPR_2025_supplemental.pdf).

<p align="center">
  <img width="419" alt="Label System Figure" src="https://github.com/user-attachments/assets/5bf1aa5e-d0fa-4480-9334-bc1d130b4510" />
</p>
<p align="center">
  <em>Figure 1. The PICD label system is structured along two axes: element types and arrangement patterns. Column 1 (green) shows arrangement types; Columns 2–4 show compositional element types. Categories are numbered 1–24 with abbreviations in blue. Red boxes indicate merged categories; blue strikethroughs mark excluded ones due to low frequency. Column 5 highlights dominant compositional factors.</em>
</p>

<p align="center">
  <img width="887" alt="Category Sample Figure" src="https://github.com/user-attachments/assets/fc5a477e-d9ce-4e6d-bfdb-c4590a672f64" />
</p>
<p align="center">
  <em>Figure 2. Sample images from the 24 composition categories in PICD. Category abbreviations appear in blue parentheses.</em>
</p>

---

## 📊 Dataset Information

PICD is actively maintained and will continue to be expanded. The current release includes:

- ✅ **49,123 images**
- ✅ Verified composition category annotations  
- ⏳ Negative samples (images not conforming to any predefined category) — *coming soon*  
- ⏳ Composition quality scores — *coming soon*  
- ⏳ Textual composition descriptions — *coming soon*

---

## 🔗 Download

PICD consists of both image files and annotations.

### 1. Images

Image download is divided into two parts based on licensing:

**Part 1: Images with redistribution permission**  
- This includes 44,577 images from open platforms and redistributable open-source datasets (e.g., Unsplash, Pexels).  
- These images can be downloaded directly via the following link:  
  👉 **[TODO: Google Drive / Baidu Netdisk download link]**

**Part 2: Images requiring user-side access**  
- This includes 546 images from public datasets that do not permit redistribution (e.g., AVA).  
- For these, we provide a mapping file that links each PICD-assigned image ID to the original dataset image ID or URL. You may download the original images from their respective sources using this mapping:  
  👉 **[Image ID Mapping File](https://github.com/CV-xueba/PICD_ImageComposition/blob/main/image_link_public.csv)**

**Alternative Access:**  
If you prefer to request both parts directly via email (especially for convenience or if you encounter access issues), please send a message to [your.email@example.com](mailto:your.email@example.com) with your affiliation and intended use. We will respond with the download links after reviewing your request.

> Accessing or using the dataset in any way implies agreement to the  
> 📄 [PICD Dataset Terms of Use (PDF)](https://github.com/CV-xueba/PICD_ImageComposition/blob/main/PICD_Dataset_Terms_of_Use.pdf)

---

### 2. Annotations

- ✏️ **Image Annotation File**  
  👉 **[Download Annotations](https://github.com/CV-xueba/PICD_ImageComposition/blob/main/labels_PICD.csv)**  
  This CSV file contains the following fields:
  - `img_id`: The PICD image ID  
  - `category_id`: Index of the composition category (1–24)  
  - `category_abbre`: Abbreviated category label (as shown in Figure 2)  
  - `category_full_name`: Full name of the composition category  

The mapping among `category_id`, `category_abbre`, and `category_full_name` follows the structure shown in **Figure 1**.

---

## 📄 License and Terms

PICD is released under the  
**Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International License (CC BY-NC-SA 4.0)**.

All users must also agree to the dataset-specific terms of use:  
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
