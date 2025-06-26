# PICD: Photographic Image Composition Dataset

📄 [CVPR 2025 Paper](https://openaccess.thecvf.com/content/CVPR2025/html/Zhao_Can_Machines_Understand_Composition_Dataset_and_Benchmark_for_Photographic_Image_CVPR_2025_paper.html)  
📑 [Appendix (Supplemental)](https://openaccess.thecvf.com/content/CVPR2025/supplemental/Zhao_Can_Machines_Understand_CVPR_2025_supplemental.pdf)

---

## 📌 Overview

**PICD** is a large-scale dataset for **photographic image composition analysis**, currently containing **48,523 high-quality images** annotated across **24 composition categories**.

This dataset is designed to support the evaluation and exploration of composition learning in AI models. It can be used for tasks such as **aesthetic quality assessment**, **composition-aware image cropping**, and more. We encourage the community to use PICD creatively — your imagination is the only limit.

The composition label system is organized along two dimensions:

- **Element Types**: Points, Lines, and Shapes (inspired by Kandinsky’s principles)
- **Arrangement Patterns**: Rule of Thirds, Centered, Diagonal, Vertical, Horizontal, Triangle, C-curve, O-curve, S-curve, Radial, Dense, Scatter, etc.

📖 For detailed category definitions and dataset design, please refer to the [Appendix](https://openaccess.thecvf.com/content/CVPR2025/supplemental/Zhao_Can_Machines_Understand_CVPR_2025_supplemental.pdf) of our paper.

<p align="center">
  <img width="306" alt="label system figure 1" src="https://github.com/user-attachments/assets/a92bc2af-091f-467a-9f96-d824d9b159fa" />
</p>

<p align="center">
  <img width="887" alt="label system figure 2" src="https://github.com/user-attachments/assets/fc5a477e-d9ce-4e6d-bfdb-c4590a672f64" />
</p>

---

## 📊 Dataset Information

PICD is actively maintained and will be continuously expanded. The current release includes:

- ✅ **48,523 images** with verified composition category annotations  
- ⏳ **Negative samples** (images not conforming to any predefined composition) — *coming soon*  
- ⏳ **Composition quality scores** — *coming soon*  
- ⏳ **Textual descriptions** of composition for each image — *coming soon*

---

## 🔗 Download

The dataset includes both image content and supplementary metadata.

- 📥 **Images from open platforms** (e.g., Unsplash, Pexels) and their download links:  
  👉 **[TODO: Google Drive / Baidu Netdisk download link]**

- 🗂️ **Images from public datasets** are referenced via image IDs. A mapping file is provided:  
  👉 **`original_dataset_image_id ↔ PICD_image_id`**  
  👉 **[TODO: Download link for mapping file]**

If you experience difficulties accessing any download links, please [contact us](mailto:your.email@example.com) and we will help you resolve the issue promptly.

---

## 📄 License and Terms

PICD is released under the **Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International License (CC BY-NC-SA 4.0)**.

See [`LICENSE.md`](./LICENSE.md) for complete license details.

> ⚠️ All third-party images retain their original copyrights.  
> Refer to `source_links.txt` for detailed provenance and attribution of each image.

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
