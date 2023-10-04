# Datasets
### Description:
This repository contains several datasets for TableExtraction project. The repository includes the following datasets:

1. **TablePlot Recognition Dataset**: A dataset created for recognizing tables and plots on scanned PDF pages. Images from the TableBank dataset were used.
Annotations in the COCO format with two classes.
2. **Table Cell Recognition Dataset**: A dataset created for recognizing table cells ctructure in images.
Annotations in COCO format for detection table cells on image of table.
3. **Table Cell Classification Dataset**: This dataset is created for recognizing table cells with additional classification into content and column headers.
Annotations in COCO format indicating the class of content and column header cells.
4. **Literaturnaya font OCR Dataset**: This dataset is specifically generated for training OCR, in my case EasyOCR, on the Literaturnaya font. I used it because it was used in Soviet books and documents. The images were generated using the function text2image.
Simple annotation in CSV format.
### Directory Structure:
```markdown
   - Datasets/
    - TablePlot/
        - annotations/
        - train/
        - val/
    - TableCell/
        - annotations/
        - train/
        - val/
    - TableCellClassification/
        - annotations/
        - train/
        - val/
    - Literaturnaya/
        - train/
        - val/
   ```
Each dataset has its own directory containing images and an annotation file.