# 🌿 Herbarium Specimen Trait Analysis: Automating Ecological Discovery

## 🚀 The Mission

For over a century, botanical history has been "locked" in physical herbarium cabinets. This project breaks those chains. By combining **Computer Vision** and **Optical Character Recognition (OCR)**, I have built an automated pipeline that digitizes raw specimen images to extract chronological metadata and quantitative leaf traits—unlocking data for ecological research in seconds, not months.

## 🛠 How It Works

This project transforms messy, historical physical records into structured digital data through a four-stage pipeline:

1. **Image Preprocessing**: Using `OpenCV` adaptive thresholding to remove centuries of paper stains and uneven lighting.
2. **Smart Localization**: Automatically targeting the specimen's metadata label using relative coordinate mapping.
3. **Data Extraction**: Leveraging `Tesseract OCR` and `Regex` to parse handwritten and typed collection dates from unstructured documents.
4. **Trait Analysis**: Applying `HSV color-space masking` to isolate leaf material and calculate vital biological metrics:
* **Surface Area**: Total pixel count of the specimen.
* **Perimeter**: Boundary detection for morphological complexity.
* **Circularity**: A key ecological indicator of how leaf shapes evolve over time.



## 📊 Scientific Insights

By mapping `Collection Year` against `Leaf Circularity`, this pipeline enables the identification of temporal trends in plant morphology, helping researchers visualize how flora has adapted to changing environmental conditions over decades.

## ⚙️ Technical Stack

* **Core**: Python 3
* **Computer Vision**: OpenCV (`cv2`)
* **OCR Engine**: Tesseract
* **Data Analysis**: Pandas, NumPy
* **Visualization**: Matplotlib

## 📦 Getting Started

1. **Clone the repo**: `https://github.com/mahamtaqi3-cloud/Herbarium-Specimen-Trait-Analysis/blob/main/README.md
2. **Install dependencies**: `pip install -r requirements.txt`
3. **Run the analysis**: Open `herbarium_analysis.ipynb` in Google Colab or Jupyter and point it to your image directory.

---

*Built with passion for botanical conservation and data science. 
