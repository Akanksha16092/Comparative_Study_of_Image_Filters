# Comparative Study of Image Filters

## Overview
This project presents a comprehensive comparative study of various image filtering techniques and their effects on image processing. The study analyzes and compares different filters used in computer vision and image manipulation, evaluating their performance, quality, and practical applications.

## 🎯 Objectives
- Compare the effectiveness of different image filtering algorithms
- Analyze performance metrics and computational efficiency
- Evaluate image quality after applying various filters
- Provide visual comparisons and detailed analysis
- Document findings and recommendations

## 📋 Filters Included
This study covers the following categories of image filters:

### Spatial Filters
- Averaging/Mean Filter
- Median Filter
- Gaussian Blur
- Bilateral Filter
- Morphological Filters (Erosion, Dilation, Opening, Closing)

### Frequency Domain Filters
- Low-Pass Filters
- High-Pass Filters
- Band-Pass Filters
- Notch Filters

### Edge Detection Filters
- Sobel Operator
- Canny Edge Detection
- Laplacian Filter
- Prewitt Operator

### Enhancement Filters
- Histogram Equalization
- Contrast Stretching
- Sharpening Filters
- Unsharp Masking

## 🚀 Features
- Implementation of multiple image filtering algorithms
- Side-by-side comparison of filter effects
- Performance benchmarking and analysis
- Visual output generation for comparison
- Detailed metrics and statistics
- Support for various image formats

## 🛠️ Technologies Used
- **Python**: Primary programming language
- **OpenCV**: Computer vision and image processing
- **NumPy**: Numerical computations
- **Matplotlib/Pillow**: Image visualization
- **SciPy**: Scientific computing

## 📦 Installation

### Prerequisites
- Python 3.x
- pip package manager

### Steps
1. Clone the repository:
```bash
git clone https://github.com/Akanksha16092/Comparative_Study_of_Image_Filters.git
cd Comparative_Study_of_Image_Filters
```

2. Install required dependencies:
```bash
pip install -r requirements.txt
```

## 💻 Usage

### Basic Example
```python
# Load and apply filters
from filters import *
import cv2

# Read image
image = cv2.imread('path/to/image.jpg')

# Apply different filters
filtered_mean = apply_mean_filter(image)
filtered_gaussian = apply_gaussian_filter(image)
filtered_median = apply_median_filter(image)

# Compare results
compare_filters(image, [filtered_mean, filtered_gaussian, filtered_median])
```

### Running the Analysis
```bash
python main.py --image <path_to_image> --output <output_directory>
```

## 📊 Project Structure
```
Comparative_Study_of_Image_Filters/
├── README.md
├── requirements.txt
├── main.py
├── filters/
│   ├── spatial_filters.py
│   ├── frequency_filters.py
│   ├── edge_detection.py
│   └── enhancement.py
├── images/
│   └── sample_images/
├── output/
│   └── results/
└── analysis/
    └── comparison_analysis.py
```

## 📈 Results & Analysis
The comparative study provides:
- Quantitative metrics (MSE, PSNR, SSIM)
- Qualitative visual comparisons
- Performance benchmarks (execution time, memory usage)
- Recommendations for different use cases
- Detailed analysis reports

## 🎓 Key Findings
*Results and findings from the comparative analysis will be documented here as the project progresses.*

## 🤝 Contributing
Contributions are welcome! Please feel free to:
1. Fork the repository
2. Create a feature branch (`git checkout -b feature/YourFeature`)
3. Commit your changes (`git commit -m 'Add YourFeature'`)
4. Push to the branch (`git push origin feature/YourFeature`)
5. Open a Pull Request

## 📝 License
This project is licensed under the MIT License - see the LICENSE file for details.

## 👤 Author
**Akanksha16092**
- GitHub: [@Akanksha16092](https://github.com/Akanksha16092)

## 📚 References
- OpenCV Documentation: https://docs.opencv.org/
- Digital Image Processing Concepts
- Computer Vision Research Papers

## 🔗 Related Resources
- [OpenCV Tutorials](https://docs.opencv.org/master/d9/df8/tutorial_root.html)
- [Image Processing Fundamentals](https://en.wikipedia.org/wiki/Digital_image_processing)
- [Filter Types and Applications](https://en.wikipedia.org/wiki/Filter_(signal_processing))

## ❓ FAQ
**Q: What image formats are supported?**
A: The project supports common formats including JPG, PNG, BMP, and TIFF.

**Q: Can I use this for commercial purposes?**
A: This project is open-source under the MIT License, so it can be used for educational and commercial purposes.

**Q: How are filters compared?**
A: Filters are compared using quantitative metrics (PSNR, SSIM) and qualitative visual analysis.

---

**Last Updated**: 2026-02-23