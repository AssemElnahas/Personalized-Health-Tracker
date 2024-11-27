# Personalized Health Tracker  

A simple Streamlit web application that allows users to input their daily health metrics and predicts their energy levels using machine learning. The app also visualizes user data compared to historical data.  



## Features  
- **Input Metrics**:  
  - Hours of Sleep  
  - Water Intake (in liters)  
  - Steps Taken (in thousands)  
  - Calories Consumed  
- **Energy Level Prediction**:  
  - Uses a Linear Regression model to predict energy levels based on inputs.  
- **Visualization**:  
  - Scatter plot comparing user input with historical data.  



## Installation  

### Prerequisites  
- Python 3.7 or above  
- Pip package manager  

### Steps  
1. Clone the repository:  
   ```bash  
   git clone https://github.com/yourusername/health-tracker.git  
   ```  
2. Navigate to the project directory:  
   ```bash  
   cd health-tracker  
   ```  
3. Install the required libraries:  
   ```bash  
   pip install -r requirements.txt  
  



## Running the App  
1. Run the Streamlit app:  
   ```bash  
   streamlit run health_tracker.py  
   ```  
2. Open your browser and go to:  
   ```
   http://localhost:8501  
   



## Usage  
1. Input your daily metrics in the sidebar (e.g., sleep, water intake, steps, and calories).  
2. View your predicted energy level on the main page.  
3. Analyze the scatter plot to compare your input with historical data.  



## File Structure  
```plaintext  
📁 health-tracker/  
├── health_tracker.py         # Main application file  
├── README.md                 # Project documentation  
├── requirements.txt          # Python dependencies  
```  



## Requirements  
The project requires the following Python libraries:  
- `streamlit`  
- `pandas`  
- `matplotlib`  
- `scikit-learn`  

Install all dependencies using:  
```bash  
pip install -r requirements.txt  
```  



## Future Enhancements  
- Add more metrics, such as heart rate or stress levels.  
- Include advanced visualizations like trend analysis.  
- Use a more robust ML model for predictions.  



## License  
This project is licensed under the MIT License.  



