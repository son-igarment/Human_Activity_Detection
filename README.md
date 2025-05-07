# Human Activity Detection

**Project Owner: Phạm Lê Ngọc Sơn**

## Project Overview
This project focuses on using data analysis, machine learning, and sensor data to identify and classify various physical activities performed by humans. The system captures motion data from sensors and applies advanced algorithms to recognize activities such as walking, running, sitting, and more.

## Project Structure
```
Human_Activity_Detection/
├── data/                  # Raw and processed sensor data
│   ├── raw/               # Original sensor recordings
│   └── processed/         # Cleaned and pre-processed datasets
├── notebooks/             # Jupyter notebooks for analysis and visualization
├── src/                   # Source code
│   ├── preprocessing/     # Scripts for data cleaning and feature extraction
│   ├── models/            # Machine learning model implementations
│   └── utils/             # Helper functions and utilities
├── tests/                 # Unit and integration tests
├── docs/                  # Documentation files
└── README.md              # Project information (this file)
```

## Features
- Data collection from various motion sensors (accelerometers, gyroscopes)
- Advanced signal processing and feature extraction
- Machine learning models for activity classification
- Real-time activity recognition capabilities
- Visualization tools for data analysis and results

## Technologies Used
- Python for data processing and model development
- Scikit-learn, TensorFlow, and PyTorch for machine learning
- Pandas and NumPy for data manipulation
- Matplotlib and Seaborn for visualization
- Signal processing libraries for sensor data analysis

## Installation and Setup
1. Clone the repository:
   ```
   git clone https://github.com/ngocson/Human_Activity_Detection.git
   cd Human_Activity_Detection
   ```

2. Install required dependencies:
   ```
   pip install -r requirements.txt
   ```

3. Download the dataset (if not included):
   ```
   python src/utils/download_data.py
   ```

## Usage
1. Preprocessing the data:
   ```
   python src/preprocessing/process_data.py
   ```

2. Training a model:
   ```
   python src/models/train_model.py
   ```

3. Making predictions:
   ```
   python src/models/predict.py --input [path_to_sensor_data]
   ```

4. For interactive analysis, run the notebooks:
   ```
   jupyter notebook notebooks/
   ```

## Future Enhancements
- Support for more sensor types
- Deep learning models for improved accuracy
- Mobile application integration
- Cloud-based processing capabilities
- Expanded activity recognition categories

## License
This project is licensed under the MIT License - see the LICENSE file for details.

## Contact
For any questions or collaborations, please contact Phạm Lê Ngọc Sơn at [son.phamlengoc@gmail.com]
