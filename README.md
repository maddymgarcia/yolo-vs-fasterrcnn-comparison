# MSBA 503 Take Home Assignment - Madison Garcia

This project compares the performance of YOLO and Faster R-CNN models on object detection tasks. It evaluates the models based on speed, the number of objects detected, and average confidence for a series of images.

## Files
- `MSBA 503 Take Home Assignment - Madison Garcia.py`: A single script that runs both YOLO and Faster R-CNN models and logs the results.
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
   python "MSBA 503 Take Home Assignment - Madison Garcia.py"
