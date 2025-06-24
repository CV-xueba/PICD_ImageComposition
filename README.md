# PICD: Photographic Image Composition Dataset

**CVPR 2025 Paper (Coming Soon)** | *Project Website (Optional)*  
**Author**: [Your Name] | **Institution**: [Your Institution]  
**Contact**: your.email@example.com

---

## 📌 Overview

**PICD** is a large-scale dataset for **photographic image composition analysis**, currently containing **X high-quality images** annotated across **24 composition categories**.

This dataset is designed to facilitate the evaluation and exploration of composition learning in AI models. It can be used in a wide range of tasks, such as **aesthetic evaluation**, **composition-aware image cropping**, and more. We encourage the community to use PICD creatively — your imagination is the only limit.

The composition categories are defined along two dimensions:

- **Element Types**: Points, Lines, and Shapes (inspired by Kandinsky’s principles)
- **Arrangement Patterns**: Rule of Thirds, Centered, Diagonal, Vertical, Horizontal, Triangle, C-curve, O-curve, S-curve, Radial, Dense, Scatter, etc.

📖 For detailed category definitions and dataset design, please refer to the Appendix in our paper.

---

## 📊 Dataset Information

The dataset is under active development and will be continuously expanded for broader research use.

The current version includes:

- **X images** with verified composition category annotations  
- **Negative samples**: images not conforming to any predefined composition (coming soon)  
- **Composition quality scores** for each image (coming soon)  
- **Textual descriptions** of image composition (coming soon)

---

## 🔗 Download

The dataset includes both image files and supplementary metadata.

- **Images from open platforms** (e.g., Unsplash, Pexels) and their download links:  
  📥 [Google Drive / Baidu Netdisk Download Link]

- **Images from public datasets** are referenced via image IDs. We also provide a mapping file:  
  📄 `original_dataset_image_id ↔ PICD_image_id`

---

## 📄 License and Terms

PICD is released under the **Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International License (CC BY-NC-SA 4.0)**.

See [`LICENSE.md`](./LICENSE.md) for full license terms.

> ⚠️ All third-party images retain their original copyrights.  
> Refer to `source_links.txt` for detailed provenance and source attribution.

---

## 🔧 Citation

If you use PICD in your research, please cite the following:

```bibtex
@inproceedings{your2025picd,
  title     = {PICD: A Large-Scale Dataset for Photographic Image Composition Understanding},
  author    = {Your Name and Coauthors},
  booktitle = {Proceedings of the IEEE/CVF Conference on Computer Vision and Pattern Recognition (CVPR)},
  year      = {2025}
}
