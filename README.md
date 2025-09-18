# Predicting-Lifespan-and-Usability-of-Metal-Parts
This project applies supervised machine learning techniques to predict the lifespan of manufactured metal parts (regression task) and classify their usability/quality (classification task).  
Got it — you don’t want it to look like “just a coursework submission” but more like a **standalone ML project repo**. Let’s frame it as a **research/ML project on metal part quality prediction and classification**.

### Models Used
- **Regression**: Gradient Boosting, Multi-layer Perceptron (MLP)  
- **Classification**: Support Vector Machine (SVM with RBF kernel), Multi-layer Perceptron (MLP)  

---

## Results

- **Gradient Boosting Regressor** achieved the highest accuracy for lifespan prediction (R² = 0.9508).  
- **SVM with RBF kernel** achieved the best performance in usability classification (Accuracy = 94.5%).  
- Gradient Boosting is recommended for robust regression, while SVM is preferred for classification.  

---

## Repository Structure

```text
comp1801-ml-project/
│
├── README.md                 → Project overview
├── LICENSE                   → MIT License
├── requirements.txt           → Dependencies
│
├── report/
│   └── MetalParts_ML_Report.pdf
│
└── notebooks/
    └── Sara_Hodaei_MetalParts_ML.ipynb
````

---

## Environment

Developed and tested in **Google Colab** with:

* Python 3.10
* scikit-learn
* pandas, numpy
* matplotlib, seaborn
* scipy


---

## Getting Started

Clone the repository and install dependencies:

```bash
git clone https://github.com/YOUR_USERNAME/comp1801-ml-project.git
cd comp1801-ml-project
pip install -r requirements.txt
```


---

## License

This project is released under the [MIT License](LICENSE).

```

