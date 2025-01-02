# Student Performance Predictor

## Overview
The **Student Performance Predictor** is an AI-powered web application designed to provide insights into a student's predicted academic performance based on various inputs. This tool uses a self-created neural network model, deployed through Flask and ngrok, to deliver real-time predictions. It offers users actionable feedback to help them improve their study habits and overall performance.

---

## Features
- **AI-Powered Predictions**: Predicts performance based on study hours, previous scores, and other factors.
- **Actionable Insights**: Generates a detailed report with performance analysis and recommendations.
- **User-Friendly Interface**: Intuitive and professional design for an enhanced user experience.
- **Responsive Design**: Accessible on various devices with modern browser support.

---

## Technologies Used
- **Frontend**: HTML, CSS, JavaScript
- **Backend**: Flask, Python
- **Machine Learning**: TensorFlow, Joblib
- **Deployment**: ngrok

---

## Getting Started

### Prerequisites
Ensure you have the following installed on your system:
- Python 3.8 or higher
- pip (Python package installer)
- TensorFlow
- Flask
- Joblib
- ngrok

### Installation Steps
1. **Clone the Repository**:
   ```bash
   git clone https://github.com/yourusername/student-performance-predictor.git
   cd student-performance-predictor
   ```

2. **Install Dependencies**:
   ```bash
   pip install -r requirements.txt
   ```

3. **Run the Application**:
   ```bash
   python app.py
   ```

4. **Expose Local Server using ngrok**:
   ```bash
   ngrok http 5000
   ```
   Use the provided ngrok URL to access the application.

---

## Usage
1. Open the application in a web browser using the ngrok URL.
2. Input the required details such as:
   - Hours Studied
   - Previous Scores
   - Extracurricular Activities
   - Sleep Hours
   - Sample Question Papers Practiced
3. Click the **Submit** button to get predictions and a detailed analysis report.

---

## Screenshots
### Home Page
![Home Page Screenshot](./assets/home-page.png)

### Prediction Result
![Prediction Result Screenshot](./assets/prediction-result.png)

---

## Project Details
**Author**: Sahil Chaubey  
**Department**: AI & DS, 3rd Year  

This project showcases a custom neural network model developed to predict student performance using historical and behavioral data. It is a culmination of theoretical knowledge and practical implementation in AI and web development.

---

## Contribution
Contributions are welcome! Follow these steps to contribute:
1. Fork the repository.
2. Create a new branch:
   ```bash
   git checkout -b feature/your-feature
   ```
3. Commit your changes:
   ```bash
   git commit -m "Add your message"
   ```
4. Push to the branch:
   ```bash
   git push origin feature/your-feature
   ```
5. Submit a Pull Request.

---

## License
This project is licensed under the [MIT License](LICENSE). Feel free to use and modify the code for personal and professional projects.

---

## Acknowledgments
- TensorFlow and Flask documentation
- Community contributors for their insights
- ngrok for seamless deployment

---

For any queries or feedback, feel free to contact **Sahil Chaubey** at [your-email@example.com](mailto:your-email@example.com).
