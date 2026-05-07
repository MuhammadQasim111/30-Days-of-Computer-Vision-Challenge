## 🚀 30 Days of Computer Vision Challenge
## Mastering Computer Vision in Python with OpenCV
This repository is a comprehensive, day-by-day documentation of my journey through the Educative curriculum. It tracks my progress from the basic pixel level to building full-scale automated vision systems.
------------------------------
## 📅 Daily Learning Log## Phase 1: The Basics

* Day 01: Introduction to Python OpenCV
Setting up the development environment, installing core dependencies (OpenCV, NumPy), and understanding the library's architecture and coordinate system.
* Day 02: Getting Started with Python OpenCV
Learning the internal representation of images as NumPy arrays and understanding how OpenCV handles BGR color order.
* Day 03: Reading and Writing Images
Implementing cv2.imread() and cv2.imwrite() to load local files and save processed outputs in various formats.
* Day 04: Reading Videos and Webcam Feeds
Using cv2.VideoCapture() to process video files and capture real-time frames from a local webcam.

## Phase 2: Advanced Editing

* Day 05: Splitting and Merging Color Channels
Deconstructing images into Blue, Green, and Red channels and merging them back to understand color distribution.
* Day 06: Joining Images
Using np.hstack and np.vstack to create image collages for side-by-side comparison of filters.
* Day 07: Bitwise Operations
Implementing AND, OR, XOR, and NOT operations to create complex shapes and regional masks.
* Day 08: Masking Images
Applying binary masks to isolate specific regions of interest (ROI) while ignoring background noise.
* Day 09: Histogram Computation
Visualizing pixel intensity distribution to analyze image contrast and brightness levels.

## Phase 3: Detection & Verification

* Day 10: Edge Detection
Using Canny and Sobel operators to identify structural boundaries within an image.
* Day 11: Shape Detection
Applying contour detection to identify and draw geometric shapes like circles and rectangles.
* Day 12: Face Detection
Using Haar Cascade classifiers to detect human faces in real-time video streams.
* Day 13: Advanced Assessment
A formal validation of skills covering all "Advanced Editing and Detection" modules to ensure technical proficiency.

## Phase 4: Real-Life Applied Projects

* Day 14: Build a Document Scanner (Part 1)
Implementing edge detection and contour sorting to find the largest rectangular object in a frame.
* Day 15: Build a Document Scanner (Part 2)
Applying Perspective Transform ("Birds-Eye View") to flatten and crop the scanned document perfectly.
* Day 16: Review of the Document Scanner
Optimizing the scanner's thresholding for better text readability and performance.
* Day 17: Build an Object Tracker (Part 1)
Setting up background subtraction and frame differencing to identify moving objects.
* Day 18: Build an Object Tracker (Part 2)
Implementing Centroid Tracking to maintain unique IDs for objects moving across the screen.
* Day 19: Review of the Object Tracker
Refining tracking logic to handle occlusions and fast-moving targets.

## Phase 5: The Capstone & Conclusion

* Day 20 - 28: Tracking Moving Objects Using Python
Building the final application: A traffic monitoring system that counts cars at an intersection using OpenCV, Tkinter for the GUI, and Pandas for data logging.
⬜ Phase 2: The Capstone - "Tracking Moving Objects" (Day 20 - 28)This phase documents the creation of a full-scale Traffic Analysis Application.
*Day 20: Project Architecture & RequirementsMapping out the application flow. Defining the roles of OpenCV for vision, Pandas for data storage, and Tkinter for the user interface.
*Day 21: Video Pre-processing & ROIImplementing Region of Interest (ROI) selection to focus detection only on traffic lanes, reducing computational load and false positives.
*Day 22: Background SubtractionImplementing the MOG2 (Mixture of Gaussians) algorithm to isolate moving vehicles from the static road background.
*Day 23: Noise Reduction & MorphologyApplying Erosion and Dilation to clean up the binary mask, removing shadows and "salt-and-pepper" noise from the detected vehicle shapes.
*Day 24: Centroid Tracking AlgorithmWriting the core logic to calculate the center point of each detected vehicle and assigning a unique ID to every object in the frame.
*Day 25: Directional Counting LogicEstablishing "Virtual Tripwires" (virtual lines in the frame) to detect when a centroid crosses a specific boundary to count "Entries" and "Exits.
*Day 26: Data Integration with PandasLinking the vision system to a Pandas DataFrame to log the timestamp, vehicle ID, and direction for exportable traffic reports.
*Day 27: GUI Development with TkinterBuilding the Glass-style dashboard. Adding buttons for "Start Stream," "Generate Report," and real-time counter displays.
*Day 28: Final System IntegrationMerging the vision engine with the GUI thread. Optimizing the script to ensure the video stream doesn't lag while the data is being logged.
* Day 29: Final Review & Project Refinement
Polishing the codebase, adding detailed comments, and optimizing performance for deployment.
* Day 30: Conclusion and Certification
Completing the course, reviewing the "What's Next?" module, and claiming the Certificate of Completion.

------------------------------
## 🛠 Tech Stack

* Computer Vision: OpenCV (cv2)
* Data Processing: NumPy, Pandas
* GUI Development: Tkinter
* Visualization: Matplotlib

------------------------------
## ⚙️ Setup

   1. Clone: git clone https://github.com
   2. Install: pip install opencv-python numpy pandas matplotlib

------------------------------
Next step: Since you are at the Assessment stage (as seen in your screen), would you like help preparing for the types of coding questions you might face regarding masking or edge detection?

