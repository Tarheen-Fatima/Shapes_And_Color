# Shape Generator with User-Defined Colors and Shapes

This repository demonstrates two different methods for generating user-defined shapes (like circles, squares, triangles, hexagons, pentagons, and stars) with specified colors using **NumPy**, **Matplotlib**, and **skimage** for shape manipulation. We will also compare the differences between the two methods:

1. **Pixel-Based Shape Drawing**
2. **Matplotlib Patches-Based Shape Drawing**

We are generating shapes based on user input in two ways:
- **Solution 1**: A **pixel-based approach** where the image is treated as a grid of pixels, and shapes are drawn by modifying specific pixel values.
- **Solution 2**: A **patch-based approach** using `matplotlib.patches`, which provides smoother and more precise shapes directly rendered using `matplotlib`.
  
## Solution 1: Pixel-Based Drawing

In this solution, we use a **grid of pixels** to define and draw shapes on a NumPy array. The color is applied to the shape based on user input. This method allows for full control over the pixel data, but results in jagged edges due to the small canvas size, especially when dealing with complex shapes like stars and hexagons.

## Solution 2: Patches-Based Drawing

In this solution, we use **`matplotlib.patches`** to generate smoother shapes with more precision. This method is more efficient and results in clean, crisp lines, making it ideal for geometric shapes.
