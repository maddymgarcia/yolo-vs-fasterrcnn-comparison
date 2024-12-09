# MSBA 503 Take Home Assignment - Madison Garcia

This project compares the performance of YOLO and Faster R-CNN models on object detection tasks. It evaluates the models based on speed, the number of objects detected, and average confidence for a series of images.

## Files
- `msba_503_take_home_assingment_madison_garcia.py`: A single script that runs both YOLO and Faster R-CNN models and logs the results.
- `output_log.txt`: A log file containing the results for both models, including objects detected, probabilities, and processing times.

## How to Run
1. Ensure the required libraries are installed:
   - PyTorch
   - torchvision
   - ultralytics (for YOLOv8)
   - Pillow (PIL)
   - matplotlib

2. Place your test images in the same directory as the script or update the paths in the `image_paths` list in the script.

3. Run the script:
   ```bash
   python "msba_503_take_home_assingment_madison_garcia.py"

## Results

The table below summarizes the performance of YOLO and Faster R-CNN models in terms of objects detected, processing time, and average confidence for the test images:

| Image Name     | Model         | Objects Detected | Processing Time (s) | Average Confidence |
|----------------|---------------|------------------|----------------------|--------------------|
| imageOne.jpg   | YOLO          | 5                | 4.36                | 0.68               |
| imageOne.jpg   | Faster R-CNN  | 3                | 12.68               | 0.92               |
| imageTwo.jpg   | YOLO          | 3                | 5.40                | 0.74               |
| imageTwo.jpg   | Faster R-CNN  | 8                | 14.58               | 0.78               |
| imageThree.jpg | YOLO          | 5                | 4.50                | 0.47               |
| imageThree.jpg | Faster R-CNN  | 13               | 14.07               | 0.72               |
| imageFour.jpg  | YOLO          | 2                | 3.54                | 0.95               |
| imageFour.jpg  | Faster R-CNN  | 2                | 12.38               | 1.00               |
| imageFive.jpg  | YOLO          | 17               | 4.55                | 0.54               |
| imageFive.jpg  | Faster R-CNN  | 13               | 9.26                | 0.81               |

**Summary:** YOLO performed faster across all images, making it suitable for real-time applications. However, Faster R-CNN demonstrated higher confidence and detected more objects, though at the cost of longer processing times.
