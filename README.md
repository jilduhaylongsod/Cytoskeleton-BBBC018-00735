## Cytoskeleton-BBBC018-00735

**Student ID:** 202303447

**Chosen Phenotype:** Peas in a pod

**Image-field ID:** 00735

**Actin filename:** 00735-actin.DIB

**DNA filename:** 00735-DNA.DIB

## Dataset

The images were obtained from the BBBC018 dataset, which contains fluorescence images of HT29 human colon-cancer cells. The actin images show cell shape and actin distribution, while the DNA images help identify the nuclei.

BBBC018 download link: https://bbbc.broadinstitute.org/BBBC018

## Fiji steps

<img width="959" height="445" alt="image" src="https://github.com/user-attachments/assets/b3a9ae1c-35d1-46c6-b567-b0356e606436" />

**Figure1.** Fiji Downloads webpage showing the available versions of Fiji for different operating systems, including Windows, macOS, and Linux.

<img width="454" height="428" alt="Screenshot 2026-10-20 175445" src="https://github.com/user-attachments/assets/d71ef7ce-c226-4a57-8845-a374910e6451" />

**Figure 2.** Example images of the different phenotypes of human HT29 colon-cancer cells from the Broad Bioimage Benchmark Collection (BBBC018). The images show variations in cell shape and actin staining patterns. The selected phenotype for this activity is Peas in a Pod.

<img width="259" height="47" alt="Screenshot 2026-10-20 175237" src="https://github.com/user-attachments/assets/f03855bc-5086-4f5a-8ee6-0b3f968108dd" />

**Figure 3.** Downloading the BBBC018 image dataset ZIP file, which contains fluorescence microscopy images used for the cytoskeleton and cell morphology analysis.

<img width="436" height="364" alt="image" src="https://github.com/user-attachments/assets/9374e73d-09be-431d-9169-29b5eec43e87" />

**Figure 4.** Extraction of the downloaded Fiji compressed folder to the selected destination on the computer. This step prepares the Fiji software files for use in the cytoskeleton and cell morphology lab activity.

<img width="959" height="504" alt="image" src="https://github.com/user-attachments/assets/106d631b-1f0f-4cdf-97f4-de54106ca0f8" />

**Figure 5.** Selecting the Bio-Formats import tool in Fiji/ImageJ to prepare for loading the actin fluorescence image for analysis.

<img width="418" height="314" alt="Screenshot 2026-10-20 181524" src="https://github.com/user-attachments/assets/54f8e972-22d5-4c13-b394-5c7b307405b9" />

**Figure 6.** The BBBC018 image directory in Fiji/ImageJ, showing the available fluorescence image files organized by field ID and staining channel for the selected cell morphology analysis.


<img width="959" height="506" alt="Screenshot 2026-10-20 182101" src="https://github.com/user-attachments/assets/4f40717f-1080-45ad-abb6-176112ea98ac" />

<img width="221" height="334" alt="Screenshot 2026-10-20 182117" src="https://github.com/user-attachments/assets/7d03702f-e143-4ac3-ada7-a7166723f01b" />

**Figure 7.** Setting the measurements in Fiji/ImageJ by selecting Area, Mean gray value, Shape descriptors, and Display label. These settings will be used to measure the size, actin fluorescence intensity, and shape of the five selected cells.

<img width="959" height="501" alt="Screenshot 2026-10-20 183603" src="https://github.com/user-attachments/assets/39e23a76-7e87-481b-8d32-8a1e7dfcd8c9" />

**Figure 8.** Using the freehand selection tool in Fiji/ImageJ to trace the outline of one cell in the actin image. This helps measure the cell's area, shape, and actin fluorescence intensity.

<img width="959" height="508" alt="Screenshot 2026-10-20 183541" src="https://github.com/user-attachments/assets/a4a1cd49-a048-4577-9207-6cc2a5697b52" />

**Figure 9.** Measuring five selected cells in Fiji/ImageJ using the freehand selection tool and ROI Manager. The Results window displays the area, mean gray value, and circularity of each cell. These measurements were used to analyze cell size, shape, and actin fluorescence intensity.

## Plot

<img width="900" height="650" alt="actin_intensity" src="https://github.com/user-attachments/assets/f072c242-e8e7-48e6-b8d7-f381986e17e1" />

**Figure 10.** Bar graph showing the mean actin fluorescence intensity of five selected cells from image 00735. Cell 2 has the highest actin signal, while Cell 5 has the lowest. The graph shows differences in actin fluorescence intensity among the measured cells.


<img width="900" height="650" alt="area_vs_circularity" src="https://github.com/user-attachments/assets/5f6ccce4-6cf7-41a6-9b4b-168f27f7e5ee" />

**Figure 11.** Scatter plot showing the relationship between cell area and circularity for five selected cells from the Peas in a Pod phenotype, image 00735. Cell 1 has the largest area, while Cell 3 has the highest circularity. The plot shows differences in cell size and shape among the five measured cells.

## Questions and Answers

**1. Which specific phenotype did you choose, and what visible features support that choice?**

I chose the Peas in a Pod phenotype. The cells appear close together in clusters, with some cells touching or arranged side by side. Most cells have rounded or irregular shapes, while a few appear slightly elongated. The actin staining helps show the outlines and shapes of the cells.

**2. Were your five cells mostly round or elongated? Refer to your circularity and aspect-ratio results.**

My five selected cells were mostly round rather than elongated. Their circularity values ranged from about 0.80 to 0.90, indicating that the cells were fairly close to a circular shape. The aspect-ratio results can also help confirm this: values closer to 1 indicate rounder cells, while higher values indicate more elongated cells. Overall, the results suggest that most of my selected cells were relatively round, although their shapes and sizes varied.

**3.  What role does actin play in maintaining cell shape and in cell movement (Karp Chapter 9)?**

Actin helps maintain the shape of the cell by forming filaments that support the cell’s outer part. It also helps the cell move by working with myosin to produce movement and changes in cell shape. Actin is important for keeping cells stable while allowing them to change shape and move when needed.

**4. Why can a single fixed fluorescence image NOT show how fast a cell moves?**

A single fixed fluorescence image cannot show how fast a cell moves because it only shows the cell at one moment. It does not show how the cell changes its position over time. To measure its speed, we need to observe the cell at different times and track its movement.
