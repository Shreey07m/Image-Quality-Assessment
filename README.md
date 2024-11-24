# Image-Quality-Assessment
I developed a machine learning solution to optimize digital storage by identifying and recommending the best quality images among similar ones. Using ResNet-50 with transfer learning, it evaluates resolution, sharpness, and noise, achieving 82% accuracy. A Streamlit-powered frontend ensures efficient storage and energy conservation.

## Features
- Image Quality Analysis: Evaluates images based on resolution, sharpness, and noise levels using a ResNet-50 model with transfer learning.
- Recommendations: Identifies the best-quality image and suggests redundant ones for deletion.
- Interactive Frontend: A Streamlit-powered interface for easy image upload and visualization.
- Robust Backend: Machine learning model hosted with support for scalability and efficient processing.

## Tech Stack
- Machine Learning Frameworks: TensorFlow, PyTorch
- Frontend: Streamlit
- Backend: Dockerized container with support for data management
- Programming Language: Python
- Deployment Tools: Streamlit Cloud

## How It Works
- Image Upload: Users upload images via the Streamlit interface.
- Prediction: The ResNet-50 model evaluates image quality parameters.
- Recommendation: The system identifies the best-quality image and lists others for deletion.
- Visualization: Results are displayed with scores and images marked for deletion.

## Installation
1. Clone the repository:  ``` git clone https://github.com/your-username/image-quality-assessment.git
cd image-quality-assessment```
2. Install dependencies: ``` pip install -r requirements.txt ```
3. Run the application: ```streamlit run app.py```
4. Access the app at ```http://localhost:8501 ```





