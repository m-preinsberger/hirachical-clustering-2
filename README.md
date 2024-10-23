# Hierarchical Clustering for Image Color Reduction

This notebook demonstrates the use of hierarchical clustering to reduce the number of colors in an image.
This README is a bit short but the code is well comented so no need for double explaining stuff.

## Steps:
1. **Loading the Image:**
   - The image is fetched from a URL and resized to a manageable size (16x16 pixels) for easier processing.
   
2. **Visualizing the Colors:**
   - The image colors are mapped into a 3D space (R, G, B) and displayed using `matplotlib`.

3. **Hierarchical Clustering:**
   - Hierarchical clustering is implemented to iteratively merge the most similar colors in the image, reducing the overall color palette.

4. **Reconstructing the Image:**
   - The clustered colors are used to recreate the image, showing the result with a reduced color palette.

## Dependencies:
- Python libraries: `PIL`, `requests`, `matplotlib`, `numpy`.

## Running the Code:
To run this notebook, ensure all dependencies are installed and execute the cells step-by-step to visualize the color reduction process.
