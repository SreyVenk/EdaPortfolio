# 🐦 Bird Image Feature Extraction and Visualization

This project processes a small dataset of bird images (American Robin, Cardinal, and Sparrow), converts them to grayscale, resizes them, extracts block-based features, and visualizes the resulting feature space in 2D and 3D. It also demonstrates feature extraction using both non-overlapping and sliding windows.


Images used:

- `American-robin.PNG`
- `Cardinal.PNG`
- `Sparrow.PNG`

## 🧰 Libraries Used

- `cv2` (OpenCV)
- `pandas`
- `matplotlib`
- `mpl_toolkits.mplot3d`

## 🧪 Project Workflow

1. **Image Loading and Visualization**
   - Loads and displays RGB and grayscale versions of each bird image.

2. **Image Resizing**
   - All images are resized to a fixed height (256 px) while maintaining aspect ratio.
   - Dimensions are adjusted to be divisible by the block size (16).

3. **Feature Extraction**
   - Two methods are used:
     - **Block Method**: Non-overlapping 16x16 grayscale blocks.
     - **Sliding Window**: Overlapping 16x16 blocks with stride of 8.
   - Each block is flattened into a feature vector.
   - Features are saved into CSV files:
     - `block_feature_vectors.csv`
     - `sliding_block_feature_vectors.csv`

4. **Feature Analysis**
   - Computes statistics like mean and standard deviation.
   - Plots histograms of mean feature values per label.

5. **Dataset Merging and Shuffling**
   - Merges both feature sets into `merged_featurespace.csv`.

6. **2D and 3D Visualization**
   - First three features plotted using `matplotlib` to observe class separation.

## 📊 Output Files

- `block_feature_vectors.csv`
- `sliding_block_feature_vectors.csv`
- `merged_featurespace.csv`

## 📝 How to Run

1. Ensure image paths are correctly set to your local machine.
2. Run the script in a Python environment with the required packages.
3. All outputs will be saved to the same `birdsDataset-main` directory.

## 📌 Notes

- Make sure OpenCV (`cv2`) and `matplotlib` are installed:



- Image paths are hardcoded—modify them if using a different directory.
