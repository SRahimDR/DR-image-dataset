# DR-image-dataset
Eye fundus images for diabetic retinopathy detection

# Retinal Fundus Image Dataset for Diabetic Retinopathy Detection
This is an open-source dataset of retinal fundus images collected for the purpose of developing and benchmarking machine learning models for **diabetic retinopathy and maculopathy detection**.

## 📂 Dataset Structure

- `DR and maculopathy 10 classes/`: Contains JPEG retinal fundus images.
- `README.md`: Documentation about the dataset.

## 📊 Label Format

- The diabetic retinopathy grade:
  - `1`: No DR
  - `2`: Mild DR without maculopathy
  - `3`: Mild DR with maculopathy
  - `4`: Moderate DR without maculopathy
  - `5`: Moderate DR with maculopathy
  - `6`: Severe DR without maculopathy
  - `7`: Severe DR with maculopathy
  - `8`: PDR without maculopathy
  - `9`: PDR with maculopathy
  - `10`: ADED
    
## 🔍 Purpose

This dataset is intended for:
- Training/testing deep learning models for DR classification
- Research on medical image analysis
- Benchmarking retinal image segmentation or grading tools

## 📝 Annotation Guidelines

Images were labeled by certified ophthalmologists based on the **International Clinical Diabetic Retinopathy scale**.

## 🔒 License

You are free to use it for academic purpose, with attribution.

## 📥 Download

You can download the dataset directly using:
```bash
git clone https://github.com/SRahimDR/DR-image-dataset.git

@misc{SRahim2025retinal,
  title={Retinal Fundus Image Dataset for Diabetic Retinopathy Detection},
  author={Rahim S. S},
  year={2025},
  howpublished={\url{https://github.com/SRahim/DR-image-dataset}}
}
