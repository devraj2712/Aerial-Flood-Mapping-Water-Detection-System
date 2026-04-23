# 🌊 Aerial Flood Mapping & Water Detection System

An automated, end-to-end image processing pipeline designed to detect, map, and analyze waterlogged regions using aerial and satellite RGB imagery. This project leverages computer vision to provide rapid, actionable insights for disaster management and urban planning.

##  Problem Statement & Vision
Urban flooding poses a severe environmental and societal threat, especially under heavy rainfall and poor drainage conditions. Traditional manual inspection is time-consuming and dangerously inefficient during crises. 

This project solves that by replacing ground surveys with an **automated satellite/aerial imagery segmentation system**. By instantly distinguishing water from land, it empowers government authorities and emergency response teams to execute quick and reliable flood analysis.

##  Key Features
* **Advanced Color Space Conversion:** Transforms standard RGB images into HSV color spaces to perfectly isolate and distinguish water from land.
* **Dynamic Image Enhancement:** Utilizes median filtering and histogram equalization to guarantee high visibility and accuracy even under poor lighting or storm conditions.
* **Autonomous Segmentation:** Applies dynamic Otsu Thresholding to automatically segment water regions without manual intervention.
* **Severity Classification:** Conducts zone-wise analysis to calculate the exact percentage of flooded areas, categorizing risk levels into **Low, Medium, or High**.
* **Actionable Reporting:** Generates comprehensive insights, including emergency alerts and response time recommendations.

##  Methodology & Image Processing Pipeline
1. **Input:** Raw Aerial/Satellite RGB Image.
2. **Preprocessing:** Noise reduction and image enhancement for clarity.
3. **Color Space Analysis:** HSV conversion for water-body highlighting.
4. **Segmentation:** Automatic thresholding (Otsu's method) to separate flooded zones from safe zones.
5. **Output Generation:** Segmented map with a generated severity and risk report.

##  Results & Impact
The pipeline successfully demonstrates high-accuracy segmentation of flooded areas, even within highly complex urban environments. By mapping the flood distribution across different zones, the system provides a clear, quantitative understanding of the disaster scale. This highly efficient approach proves entirely suitable for real-world flood monitoring, disaster management, and immediate emergency response.

---
##  Author

**Devraj** 

