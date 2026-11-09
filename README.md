# Computer Vision: Object Detection & Segmentation

### Progree Artificial Intelligence Internship — Task 4

## 📌 Project Overview

This project implements a computer vision pipeline using Python and OpenCV to process video frames, perform image segmentation, and extract contour-based regions.

The system applies image processing techniques to detect contour regions, visualize them on video frames, and evaluate processing performance.

## 🎯 Objectives

- Process video frames using OpenCV.
- Apply Gaussian Blur for noise reduction.
- Convert frames into grayscale.
- Perform Adaptive Thresholding.
- Extract and filter contours.
- Visualize contour regions.
- Display frame numbers and contour counts.
- Evaluate processing time and FPS.
- Generate performance graphs and CSV logs.

## 🛠️ Technologies Used

- Python
- OpenCV
- NumPy
- Matplotlib
- Google Colab

## ⚙️ Project Workflow

1. Load the input video.
2. Extract video frames.
3. Apply Gaussian Blur.
4. Convert frames to grayscale.
5. Apply Adaptive Thresholding.
6. Extract contours using OpenCV.
7. Filter contours based on pixel area.
8. Draw contours on frames.
9. Display frame numbers and contour counts.
10. Save processed video and performance logs.

## 📊 Performance Results

| Metric | Result |
|---|---:|
| Total Frames Processed | 1,507 |
| Average Contours per Frame | 23.67 |
| Maximum Contours | 57 |
| Minimum Contours | 6 |
| Average Processing Time | 0.1649 seconds |
| Average Processing FPS | 6.07 |

## 📁 Project Outputs

The project generates:

- `processed_output.mp4` — Processed video
- `frame_detection_log.csv` — Frame-wise contour information
- `processing_time_log.csv` — Processing time records
- `performance_summary.csv` — Performance statistics
- Contour count graph
- Processing time graph

**Note:** Input and output video files are not included in this repository because of GitHub file size limitations.

## 🚀 How to Run

1. Open the notebook in Google Colab.
2. Upload the input video.
3. Install or import the required libraries.
4. Run the notebook cells in sequence.
5. View the processed frames and performance graphs.
6. Download the generated output files.

## ⚠️ Limitations

- The system detects contour regions rather than specific object classes.
- It does not perform semantic object classification.
- Contour count does not necessarily represent the number of physical objects.
- Results may vary depending on lighting and background conditions.
- The pipeline does not perform persistent object tracking.
- Processing speed is lower than the input video frame rate.

## 🔮 Future Improvements

- Integrate YOLO for deep learning-based object detection.
- Implement object tracking using SORT or DeepSORT.
- Optimize processing speed.
- Improve segmentation accuracy.
- Explore GPU acceleration.

## 📝 Conclusion

This project demonstrates the practical application of traditional computer vision techniques for video processing and contour-based segmentation.

It provides a foundation for future improvements involving deep learning-based object detection, semantic segmentation, and object tracking.

## 👩‍💻 Internship

**Program:** Progree Artificial Intelligence Internship  
**Task:** Task 4 — Object Detection & Segmentation

