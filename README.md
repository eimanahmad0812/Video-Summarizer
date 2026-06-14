🎬 AI-Powered Video Summarizer & Keyframe Extractor
An intelligent Computer Vision tool designed to analyze long-form video content and automatically extract "key moments" based on scene-change detection and image sharpness metrics.

🔍 Overview
Processing hours of video footage to find relevant information is time-consuming. This tool automates the process by calculating the frame-by-frame difference (to detect scene cuts) and performing Laplacian variance analysis (to ensure image quality), ultimately generating a visual report for quick consumption.

🛠 Tech Stack
Core: Python

Computer Vision: OpenCV (for frame extraction, scene detection, and sharpness scoring)

Data Processing: NumPy (for mathematical analysis of frame variations)

Visualization: Matplotlib (for generating data-driven timelines and summaries)

Reporting: HTML/CSS (for creating shareable, browser-ready summary dashboards)

📈 How It Works
Scene Detection: The algorithm iterates through the video, calculating the pixel-wise difference between consecutive frames. When the difference exceeds a set threshold, the frame is flagged as a "Scene Change."

Quality Scoring: Each detected keyframe is analyzed using the Laplacian Variance method to measure edge density (sharpness), categorizing frames as Sharp, Acceptable, or Blurry.

Data Visualization: The system generates a visual timeline of scene changes and a grid-based summary of extracted frames.

Reporting: Finally, the tool exports a standalone video_summary_report.html file, providing a mobile-responsive dashboard of the video’s key insights.

📊 Project Impact
This project demonstrates the ability to implement end-to-end CV pipelines, moving from raw video data to actionable summaries. It highlights experience with real-time video processing, mathematical data optimization, and front-end report generation.

Built by Eiman Ahmad | https://www.linkedin.com/in/eiman-ahmad-64a211416/ | 
