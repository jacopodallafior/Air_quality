# AIR QUALITY PREDICTOR 🌍💨  

**Air Quality Predictor** is an advanced machine learning system designed to forecast air quality levels at **Serso via dei Caduti**, leveraging a feature store for integrated batch and real-time data pipelines. Inspired by O'Reilly's *Building Machine Learning Systems with a Feature Store: Batch, Real-Time, and LLMs*, this project demonstrates the power of scalable and interactive ML systems.

---

## 📌 Pipeline Overview  

The pipeline integrates:
- **Data Collection**: Automated retrieval of historical and real-time weather and air quality data.
- **Data Processing**: Cleaning, aggregation, and transformation for ML readiness.
- **Feature Management**: Efficient storage and retrieval of engineered features via a feature store.
- **Model Predictions**: Batch and real-time forecasts using an XGBoost regressor.  

![Pipeline Diagram](images/pipeline.png)  
*Figure: Data flow and system architecture.*

---

## ✨ Key Features  

1. **Dual Mode Processing**  
   - Supports both **real-time** and **batch** predictions for flexible operations.  

2. **Advanced Feature Store**  
   - Optimized feature management ensures fast access and version control for training and inference.  

3. **LLM Integration**  
   - Pioneering techniques such as **Fine-Tuning** and **Retrieval-Augmented Generation (RAG)** for extending capabilities.  

4. **Interactive Dashboard**  
   - Real-time insights via a live dashboard to monitor predictions and trends.  

5. **Scalable and Modular**  
   - Easy to extend for new locations, features, or predictive models.  

---

## 🚀 Getting Started  

### 1. Access the Predictions  
View the live predictions on the [Interactive Dashboard](https://grandediw.github.io/Air-Quality-Prediction/air-quality/).

### 2. Set Up Locally  
Clone the repository and follow these steps:  

```bash
# Clone the repo
git clone https://github.com/Grandediwername/air-quality-prediction.git

# Navigate to the project directory
cd air-quality-prediction

# Install required dependencies
pip install -r requirements.txt

# Launch the pipeline
python main.py
```

### 3. Deploy the Dashboard  
Follow the [dashboard setup guide](docs/DASHBOARD_SETUP.md) for hosting locally or on a cloud platform.

---

## 🛠️ How to Contribute  

We welcome contributions from the community! Here's how you can help:  
1. Fork the repository.  
2. Create a feature branch for your changes.  
3. Submit a pull request.  

Ideas for contribution:  
- Add support for more weather variables.  
- Enhance the dashboard UI.  
- Optimize prediction models.  

---

## 🤝 Acknowledgments  

This project was inspired by the book *Building Machine Learning Systems with a Feature Store: Batch, Real-Time, and LLMs* by O'Reilly. Special thanks to the [Hopsworks](https://www.hopsworks.ai/) team for their exceptional feature store platform.  

---

For questions or feedback, feel free to [open an issue](https://github.com/Grandediw/air-quality-prediction/issues).  
