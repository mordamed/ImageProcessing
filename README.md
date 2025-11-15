# Image Processing - TP1 & TP2

This repository contains practical exercises for learning image processing techniques using Python, scikit-image, and numpy.

## Project Structure

```
.vscode/
    settings.json
TP1/
    TP1_Image_Information.ipynb  # Image analysis and histogram processing
    data/
        camera.jpg
        view.jpg
TP2/
    TP2_Image_Filtering.ipynb    # Image filtering techniques
    data/
```

## TP1: Image Information

The [TP1_Image_Information.ipynb](TP1/TP1_Image_Information.ipynb) notebook covers fundamental image analysis:

### 1. Read & Write Images
- Loading images with scikit-image
- Understanding image data types and shapes
- Grayscale vs RGB images
- Pixel value analysis

### 2. Image Histograms
- Computing and plotting histograms
- Normalized histograms
- Cumulative distribution functions (CDF)
- Image segmentation using histogram analysis

### 3. RGB vs HSV Color Analysis
- Color space conversions
- Euclidean distance in color space
- Brown cell detection in immunohistochemistry images
- Interactive pixel inspection tools

### 4. Image Entropy
- Information theory concepts
- Entropy calculation for images
- Comparison of random vs uniform images

### 5. Image Compression
- Pyramid decomposition
- Subsampling techniques
- Entropy evolution with compression

### 6. Co-occurrence Matrix
- Spatial pixel relationships
- Texture analysis
- Distance-based entropy measurements

### 7. Watermark Project
- Adding watermarks to photographs
- Transparency effects
- Adaptive watermark brightness

## TP2: Image Filtering

The [TP2_Image_Filtering.ipynb](TP2/TP2_Image_Filtering.ipynb) notebook covers advanced filtering techniques:

### 1. Look-up Tables (LUTs)
- Image inversion
- Thresholding
- Gray level reduction
- Histogram stretching
- Histogram equalization

### 2. Kernel Convolution
- Understanding convolution operations
- Mean filters for noise reduction
- Median filters for salt-and-pepper noise

### 3. 2D Fourier Transform
- Frequency domain filtering
- Low-pass and high-pass filters
- Dithering reduction

### 4. Morphological Operations
- Erosion and dilation
- Opening and closing operations
- Circle detection and removal

### 5. Edge Detection
- Sobel filter implementation
- Canny edge detection
- Hough transform for line detection

### 6. Picture Enhancement Project
- Automatic photo enhancement
- Combining multiple filtering techniques

## Getting Started

1. **Install required packages:**
   ```bash
   pip install numpy matplotlib scikit-image scipy
   ```

2. **Open the notebooks:**
   ```bash
   jupyter notebook TP1/TP1_Image_Information.ipynb
   # or
   jupyter notebook TP2/TP2_Image_Filtering.ipynb
   ```

3. **Complete the exercises:**
   - Look for cells marked with `## -- Your code here -- ##`
   - Follow the instructions in the markdown cells
   - Use the provided helper videos for additional guidance

## Key Libraries Used

- `numpy` - Array operations and mathematical functions
- `matplotlib` - Plotting and image display
- `scikit-image` - Image processing algorithms
- `scipy` - Scientific computing and signal processing

## Features Implemented

### TP1 Highlights:
- Interactive pixel inspection by clicking on images
- Automatic brown pixel detection in medical images
- Custom histogram computation and visualization
- Image entropy calculation and analysis
- Pyramid compression with reconstruction

### TP2 Highlights:
- Complete filtering pipeline implementations
- Real-time parameter adjustment capabilities
- Noise reduction and enhancement algorithms
- Edge detection and feature extraction
- Morphological image processing

## Exercise Completion

Each section contains multiple code cells to implement. The notebooks provide:
- Theoretical background and mathematical formulas
- Step-by-step implementation instructions
- Example code snippets and best practices
- Video tutorials for additional learning
- Interactive tools for parameter exploration

Work through each section sequentially, as later exercises build upon earlier concepts.

## Expected Outputs

You'll create various processed images demonstrating:
- Histogram analysis and manipulation
- Color space transformations
- Noise reduction techniques
- Edge detection results
- Morphological operation outcomes
- Enhanced photographs with watermarks

## Tips for Success

1. Read the markdown explanations and mathematical formulas carefully
2. Experiment with different parameter values to understand their effects
3. Compare results with original images to see improvements
4. Use the interactive pixel inspection tools to understand color values
5. Test your implementations on different images in the data folders
6. Watch the provided video tutorials for deeper understanding

## Video Resources

Each notebook includes links to helpful video tutorials covering:
- Image I/O operations
- Histogram computation and analysis
- Color space conversions
- Filtering techniques
- Edge detection methods
- Morphological operations

## Contributing

This is an educational project. Feel free to:
- Add new test images to the data folders
- Implement additional filtering techniques
- Create variations of existing algorithms
- Document your findings and observations

## License

Educational use - Part of image processing coursework.