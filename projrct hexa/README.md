# Leaf Disease Detection Flask App

A web application for detecting plant leaf diseases using machine learning. This application allows users to upload images of plant leaves and receive instant analysis of potential diseases.

## Features

- User-friendly web interface
- Drag-and-drop image upload
- Real-time disease detection
- Confidence score display
- Responsive design

## Prerequisites

- Python 3.7+
- pip (Python package installer)
- Virtual environment (recommended)

## Installation

1. Clone the repository:
```bash
git clone <repository-url>
cd leaf-disease-detection
```

2. Create and activate a virtual environment:
```bash
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate
```

3. Install the required packages:
```bash
pip install -r requirements.txt
```

## Usage

1. Start the Flask application:
```bash
python app.py
```

2. Open your web browser and navigate to:
```
http://localhost:5000
```

3. Upload an image of a plant leaf using the web interface
4. View the analysis results

## Project Structure

```
leaf-disease-detection/
├── app.py                 # Main Flask application
├── requirements.txt       # Python dependencies
├── static/
│   ├── css/
│   │   └── style.css     # Custom styles
│   ├── js/
│   │   └── main.js       # Frontend JavaScript
│   └── uploads/          # Uploaded images
├── templates/
│   └── index.html        # Main HTML template
└── models/               # Trained model directory
```

## Model Training

The application uses a pre-trained model for leaf disease detection. To train your own model:

1. Prepare your dataset of leaf images
2. Use the provided training script (to be implemented)
3. Save the trained model in the `models` directory

## Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

## License

This project is licensed under the MIT License - see the LICENSE file for details.

## Acknowledgments

- PlantVillage dataset for training data
- TensorFlow and Keras for deep learning capabilities
- Flask for web framework 