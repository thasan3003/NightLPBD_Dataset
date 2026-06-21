# NightLPBD_Dataset
### NightLPBD is a dataset of Nighttime License Plates of Bangladeshi vehicles

This repository serves as the **official** landing page, documentation hub, and version registry for the **NightLPBD** (Nighttime License Plates of Bangladeshi vehicles). 

The dataset versions are hosted externally on dedicated AI repositories to ensure stable, high-speed downloads and seamless integration with machine learning pipelines. No training code is hosted in this repository.

---

## 📂 Dataset Versions & Access Links

### 🟢 Version 1.0 (Current Release)
* **Description:** The baseline dataset featured in our official IEEE COMPAS 2025 publication. Contains high-quality, real-world nighttime traffic images from Bangladesh with YOLO-formatted annotations.
* **Release Date:** 21 June 2026
* **Download Links:**
  * 🤗 [Download v1.0 via Hugging Face Datasets](https://huggingface.co/datasets/thasan3003/NightLPBD_Nighttime_License_Plates_of_Bangladesh)
  * 📋 [Download v1.0 via Kaggle Datasets](https://www.kaggle.com/datasets/thasan3003/nightlpbd-nighttime-license-plates-of-bangladesh)

### 🟡 Future Releases (Coming Soon)
* **Version 2.0 (In Development):** Enhanced dataset incorporating additional vehicle classes to test model robustness. 
* *Links will be populated upon official publication.*

---

## 📄 About the Dataset (v1.0)
NightLPBD is a specialized, benchmark image dataset designed to advance Automatic License Plate Recognition (ALPR) under challenging low-light conditions, specifically featuring **Bangla font license plates**. 

It addresses severe real-world traffic surveillance artifacts including:
* Diverse environment
* Multiple resolution
* Different angles and viewpoints

---

## ⚖️ Licensing
All versions of the NightLPBD dataset are released under the **Creative Commons Attribution 4.0 International License (CC BY 4.0)**. You are free to download, modify, and build upon this data, provided you cite the corresponding paper below.

---

## 🎓 Citation Requirements

Please cite the specific paper associated with the dataset version you are utilizing in your research:

### For Dataset v1.0 (Baseline Nighttime Data)
**Paper Link:** [https://doi.org/10.1109/COMPAS67506.2025.11381609](https://doi.org/10.1109/COMPAS67506.2025.11381609)

```bibtex
@inproceedings{hasan_nightlpbd_2025,
	title = {{NightLPBD}: {A} {YOLO}-{Based} {Single}-{Stage} {Framework} for {Nighttime} {License} {Plate} {Recognition}},
	shorttitle = {{NightLPBD}},
	author = {Hasan, Md. Tahmid and Ahsan, Sk. Md. Masudul},
	booktitle = {2025 {IEEE} 2nd {International} {Conference} on {Computing}, {Applications} and {Systems} ({COMPAS})},
	address = {Kushtia, Bangladesh},
	publisher = {IEEE},
	month = oct,
	year = {2025},
	volume={},
	number={},
	pages = {1--6},
	doi = {10.1109/COMPAS67506.2025.11381609},
}
```
