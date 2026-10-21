# Niblack and Otsu Stepper

Interactive, step-by-step walkthroughs of two thresholding methods on the same 4×4 image:

- **Niblack (adaptive):** T = m + k·s per pixel, with window selection and border clipping, local mean, population standard deviation, threshold and label.
- **Otsu (global):** between-class variance σ²_B(k) = P₁·P₂·(m₁ − m₂)² for every candidate k, the histogram split, the chosen k*, and a side-by-side comparison with Niblack.

Open the Otsu tab directly: https://mohammedsohail-virufy.github.io/niblack-stepper/#otsu

**Live page:** https://mohammedsohail-virufy.github.io/niblack-stepper/

Made by **Mohammed Sohail** as a study aid for MAI621 Computer Vision and Image Processing, Abu Dhabi University. Instructors: Dr. Azza Basiouni and Dr. Syed Gilani. The worked example is based on the Topic 5 class notes.

Single HTML file, no build step.
