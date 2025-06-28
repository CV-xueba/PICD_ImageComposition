# PICD: Photographic Image Composition Dataset  
**Can Machines Understand Composition? A Dataset and Benchmark for Photographic Image Composition Embedding and Understanding**  
📌 *CVPR 2025 Highlight*

📄 [CVPR 2025 Paper](https://openaccess.thecvf.com/content/CVPR2025/html/Zhao_Can_Machines_Understand_Composition_Dataset_and_Benchmark_for_Photographic_Image_CVPR_2025_paper.html)  
📑 [Supplementary Appendix](https://openaccess.thecvf.com/content/CVPR2025/supplemental/Zhao_Can_Machines_Understand_CVPR_2025_supplemental.pdf)

---

## 📌 Overview

**PICD** is a large-scale dataset for **photographic image composition analysis**, currently containing **48,523 high-quality images** annotated across **24 composition categories**.

This dataset is designed to support the evaluation and exploration of composition learning in AI models. It can be applied to tasks such as **aesthetic quality assessment**, **composition-aware image cropping**, and more. We encourage the research community to explore creative uses of PICD — your imagination is the only limit.

The composition label system is structured along two dimensions:

- **Element Types**: Points, Lines, and Shapes (inspired by Kandinsky’s principles)  
- **Arrangement Patterns**: Rule of Thirds, Centered, Diagonal, Vertical, Horizontal, Triangle, C-curve, O-curve, S-curve, Radial, Dense, Scatter, etc.

📖 For detailed category definitions and dataset design, please refer to the [Appendix](https://openaccess.thecvf.com/content/CVPR2025/supplemental/Zhao_Can_Machines_Understand_CVPR_2025_supplemental.pdf) of our paper.

<p align="center">
  <img width="419" alt="Label System Figure" src="https://github.com/user-attachments/assets/5bf1aa5e-d0fa-4480-9334-bc1d130b4510" />
</p>
<p align="center">
  <em>Figure 1. The PICD label system is organized by two axes: element types and arrangement patterns. Column 1 (green) shows the arrangement types; Columns 2–4 show three compositional element types. Categories are numbered 1–24 with abbreviations in blue. Red boxes indicate merged categories, and strikethroughs indicate excluded ones due to low frequency. Column 5 highlights dominant compositional factors.</em>
</p>

<p align="center">
  <img width="887" alt="Category Sample Figure" src="https://github.com/user-attachments/assets/fc5a477e-d9ce-4e6d-bfdb-c4590a672f64" />
</p>
<p align="center">
  <em>Figure 2. Sample images for the 24 composition categories in PICD. Category abbreviations are shown in blue parentheses.</em>
</p>

---

## 📊 Dataset Information

PICD is actively maintained and will be continuously expanded. The current release includes:

- ✅ **48,523 images**
- ✅ Verified composition category annotations  
- ⏳ Negative samples (images not conforming to any predefined composition) — *coming soon*  
- ⏳ Composition quality scores — *coming soon*  
- ⏳ Textual descriptions of image composition — *coming soon*

---

## 🔗 Download

The dataset includes both downloadable images and supplementary metadata files.

- 📥 **Images from open platforms and open-source datasets that allow redistribution**  
  This includes platforms such as Unsplash and Pexels. We provide direct download links:  
  👉 **[TODO: Google Drive / Baidu Netdisk download link]**

- 🗂️ **Images from public datasets that do not allow direct redistribution**  
  For these images (e.g., AVA, COCO, VOC), we provide a mapping file between the original dataset image link or ID and the corresponding PICD image ID:  
  👉 **[TODO: Download link for image ID mapping file]**  
  (`original_dataset_image_link_or_id ↔ PICD_image_id`)

- ✏️ **Image annotations**  
  This file contains:
  - `img_id`: the PICD image ID  
  - `category_id`: the composition category index (1–24)  
  - `category_abbre`: the category abbreviation (as shown in Figure 2)  
  - `category_full_name`: the full category name  
  👉 **[Annotation File](https://github.com/CV-xueba/PICD_ImageComposition/blob/main/labels_PICD.csv)**

The mapping between `category_id`, `category_abbre`, and `category_full_name` follows the definitions shown in **Figure 2** above.

If you encounter any issues accessing the files—especially if downloading from open platforms is cumbersome—please feel free to [contact us](mailto:your.email@example.com), and we will assist you promptly.

---

## 📄 License and Terms

PICD is released under the  
**Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International License (CC BY-NC-SA 4.0)**.

In addition, all users must agree to the following dataset terms of use:  
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
