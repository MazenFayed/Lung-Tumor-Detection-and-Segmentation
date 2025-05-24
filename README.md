# Lung Tumor Detection and Segmentation

This project demonstrates lung tumor detection using object detection and semantic segmentation models. It involves visualizing predicted bounding boxes and masks from pre-trained PyTorch models on medical images.

## 📁 Project Files

- `Test of models.ipynb`: Runs evaluation on both detection and segmentation models.
- `final_detection_notebook.ipynb`: Inference and visualization for the detection model (bounding boxes).
- `final_segmentation_notebook.ipynb`: Inference and visualization for the segmentation model (bounding boxes + masks).
- `requirements.txt`: List of required Python packages.

## 🔗 Data

You can download the input dataset from this Google Drive folder:

**[Download Dataset](https://drive.google.com/drive/folders/15NbZ2GGKqKl32ezgaJhy7HMsxrx5-4pw?usp=drive_link)**

## 🧠 Pre-trained Models

Download the pre-trained models from the links below:

- [Detection Model](https://drive.google.com/file/d/1Q4Uum0DKb0whZodSSW1lpuc6scc_KtGH/view?usp=sharing)
- [Segmentation Model](https://drive.google.com/file/d/1LESADHFun1L1MJqJvwezqZJHhXJo2mWy/view?usp=sharing)

> ⚠️ These models are PyTorch `.pt` files. Ensure to load them with `torch.load(..., weights_only=False)` if you face any loading issues.

## ⚙️ Setup Instructions

1. **Clone the repository** (or download the notebook files).
2. **Create a virtual environment (optional but recommended)**:

    ```bash
    python -m venv venv
    source venv/bin/activate  # On Windows: venv\Scripts\activate
    ```

3. **Install dependencies**:

    ```bash
    pip install -r requirements.txt
    ```

4. **Download the dataset and model files** to your working directory.
5. **Open the notebooks** in Jupyter or Google Colab and run the cells step-by-step.

## 📊 Outputs

- Bounding box predictions are displayed with **green** (ground truth) and **red dashed** (predictions).
- Segmentation masks are shown alongside the input image for comparison.

---

### 📌 Note

- Ensure your runtime has access to GPU for faster inference.
- This project is intended for academic or research use on medical imaging data.

---

Feel free to raise issues or contribute improvements!
