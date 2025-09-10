# 🩺 Cancer Simulation and Prediction

![License](https://img.shields.io/badge/License-GPLv3-blue.svg)
![Python](https://img.shields.io/badge/Python-3.8%2B-blue.svg)
![Streamlit](https://img.shields.io/badge/Built%20With-Streamlit-orange)
![Machine Learning](https://img.shields.io/badge/Machine%20Learning-Logistic%20Regression-green)

> **Empowering Healthcare with AI: Predict Breast Cancer with Confidence and Insight.**

---

## 🚀 Overview

**Cancer Simulation and Prediction** is an interactive and intuitive platform designed to assist medical professionals and researchers in predicting breast cancer outcomes. Leveraging machine learning, specifically logistic regression, this tool analyzes cytosis lab measurements to determine whether a breast mass is benign or malignant. The application also provides advanced simulations and visual analytics to accelerate cancer research and diagnostics.

- **Built with:** Python, Streamlit, Plotly, Scikit-Learn  
- **License:** GPL v3.0

---

## 🎯 Features

- **🧬 Breast Cancer Predictor:** Predicts malignancy using real cytosis lab data.
- **📊 Interactive Data Input:** Adjust cell nuclei measurements with easy-to-use sliders.
- **🔮 Real-Time Prediction:** Instantly see model predictions as you adjust inputs.
- **📈 Visual Analytics:** Dynamic radar charts and data visualization powered by Plotly.
- **💡 Research Support:** Simulate cancer growth and analyze critical features that influence diagnosis.
- **👩‍⚕️ Clinical Guidance:** Designed to assist, not replace, professional diagnosis.

---

## 🛠️ How It Works

1. **Data Processing:** The app ingests and cleanses data from your cytosis lab.
2. **Feature Engineering:** Key features like radius, texture, area, smoothness, and more are extracted.
3. **Model Training:** A logistic regression model is trained and evaluated on processed data.
4. **User Interaction:** Use the sidebar sliders to manually input or adjust measurements.
5. **Visualization:** Radar charts provide a holistic view of the input features.
6. **Prediction:** The model predicts malignancy probability based on the current inputs.

---

## 🚦 Usage

1. **Install Requirements:**
    ```bash
    pip install -r requirements.txt
    ```

2. **Run the App:**
    ```bash
    streamlit run app/main.py
    ```

3. **Interact:**
    - Adjust the sidebar sliders to simulate various cell measurements.
    - View real-time predictions and data visualizations.
    - Use insights for research or clinical support.

---

## 📂 Project Structure

```
Cancer-Simulation-And-Prediction/
├── app/
│   └── main.py         # Streamlit frontend and data visualization
├── model/
│   └── main.py         # Model training and evaluation
├── data/
│   └── data.csv        # Dataset (ensure this path is correct)
├── README.md
├── LICENSE
```

---

## 📊 Key Model Features

- **Input Variables:**  
    - Radius (mean, se, worst)
    - Texture (mean, se, worst)
    - Perimeter (mean, se, worst)
    - Area (mean, se, worst)
    - Smoothness, Compactness, Concavity, Concave points, Symmetry, Fractal dimension (mean/se/worst)
- **Target:**  
    - Diagnosis (`M`: Malignant, `B`: Benign)

---

## ⚠️ Disclaimer

> This app is intended to assist medical professionals but **should not be used as a substitute for professional diagnosis**.

---

## 📢 License

This project is licensed under the GNU General Public License v3.0.  
See [LICENSE](LICENSE) for more details.

---

## 🤝 Contact

- **Author:** [Debarjun Pal](https://github.com/DebarjunPal)
- **Email:** *debarjunpal134@gmail.com*

---

## 🌟 Contributions

Contributions, issues, and feature requests are welcome!  
Feel free to check the [issues page](https://github.com/DebarjunPal/Cancer-Simulation-And-Prediction/issues).

---

## 🧑‍💻 Acknowledgements

- Built with [Streamlit](https://streamlit.io/) and [scikit-learn](https://scikit-learn.org/)
- Data science for a better tomorrow!

---
