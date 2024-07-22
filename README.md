
# Strokes Master: Cricshot Analyzer and Visualization

# Overview

Strokes Master is a state-of-the-art cricket shot analysis and visualization system. Utilizing advanced pose estimation technology, this project aims to revolutionize how cricket shots are analyzed and understood. By capturing key body landmarks in real-time, Strokes Master provides comprehensive insights into player performance, making it an invaluable tool for players, coaches, and analysts.

# Objectives

- To accurately capture and analyze cricket shots using pose estimation technology.
- To provide real-time feedback on player performance through intuitive visualizations.
- To aid players and coaches in improving cricket techniques by offering detailed analysis.

# Key Features

- Advanced Pose Estimation: Utilizes cutting-edge pose estimation algorithms to capture key body landmarks during cricket shots.
- Real-Time Analysis: Offers immediate feedback on shot accuracy and player posture.
- Intuitive Visualizations: Provides clear and comprehensive visual representations of player movements and shot analysis.
- Data Comparison: Enables side-by-side comparison of correct and incorrect shots for detailed performance evaluation.

# Tech Stack

 Programming Languages: Python
 Libraries: OpenCV, MediaPipe, NumPy, Pandas, EasyGUI, Openpyxl
 Tools: Git, Jupyter Notebook, Visual Studio

# System Architecture

 Data Collection and Preprocessing

The project begins with the collection of a diverse dataset of cricket shots, both correct and incorrect. These images and videos are sourced from matches, practice sessions, and simulations. The data is preprocessed to remove anomalies and ensure consistency.

# Pose Estimation

Strokes Master leverages the "Realtime Multi-Person 2D Pose Estimation using Part Affinity Fields" algorithm by Cao et al. This advanced technique allows for the precise extraction of key body landmarks, which are crucial for accurate shot analysis.

# Visualization Techniques

The extracted data is visualized using innovative methods, including bar charts for X Landmarks, Y Landmarks, and Visibility Comparison. These visualizations help in understanding the differences in posture, balance, and technique between correct and incorrect shots.

# Real-Time Feedback

The system provides real-time feedback on player performance. By analyzing the captured body landmarks, Strokes Master offers immediate insights into shot execution, enabling players and coaches to make informed decisions on technique improvement.

## Installation and Setup

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/strokes-master.git
   ```
2. Navigate to the project directory:
   ```bash
   cd strokes-master
   ```
3. Install the required dependencies:
   ```bash
   pip install -r requirements.txt
   ```
4. Run the project:
   ```bash
   python main.py
   ```

## Usage

1. Upload cricket shot images or videos through the provided interface.
2. The system will process the data and display key body landmarks.
3. View real-time visualizations and receive detailed shot analysis.
4. Compare different shots to identify areas for improvement.

## Contributing

We welcome contributions from the community! If you'd like to contribute to Strokes Master, please follow these steps:

1. Fork the repository.
2. Create a new branch (`git checkout -b feature-branch`).
3. Make your changes and commit them (`git commit -m 'Add new feature'`).
4. Push to the branch (`git push origin feature-branch`).
5. Open a Pull Request.


## Acknowledgments

- Special thanks to Cao et al. for their groundbreaking work on pose estimation.
- Thanks to all contributors and supporters of this project.
