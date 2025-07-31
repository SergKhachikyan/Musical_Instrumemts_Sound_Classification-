# 🎵 Musical Instruments Sound Classification

This project focuses on classifying musical instrument sounds using machine learning techniques.  
It includes audio preprocessing, feature extraction (MFCC), model training, evaluation, and visualization of results.

## 📁 Project Structure

```
Musical_Instrumemts_Sound_Classification-/
├── data/                # Raw audio files
├── features/            # Extracted MFCC features
├── models/              # Saved models
├── notebooks/           # Jupyter notebooks for analysis
├── utils/               # Utility scripts
├── results/             # Reports and visualizations
├── main.py              # Entry point for training/evaluation
└── requirements.txt     # Project dependencies
```

## 🚀 Quick Start

1. Clone the repository:  
```  
git clone https://github.com/SergKhachikyan/London_House_Price_Prediction_Advanced_Techniques.git
```
2. Change directory:
```
cd Musical_Instrumemts_Sound_Classification
```
3. Create virtual environment:
```
py -m venv venv
```
4. Activate virtual environment:
```
venv\Scripts\activate
```
5. Update the package manager:
```
py -m pip install -U pip
```
6.Install dependencies:
```
pip install -r requirements.txt  
```
7.Launch the notebook:
```
jupyter notebook untitled.ipynb
```  
## 📊 Technologies Used

- Python 3.x  
- [Librosa](https://librosa.org/) — Audio feature extraction  
- [Scikit-learn](https://scikit-learn.org/) — Machine learning models  
- NumPy / Pandas / Matplotlib — Data processing and visualization  
- Seaborn — Advanced plots and statistical graphs  
- Jupyter — Interactive analysis  

## 📈 Results

> Sample metrics (replace with actual results if needed):

- **Accuracy:** 92.3%  
- **Confusion Matrix:** `results/confusion_matrix.png`  
- **Classification Report:** `results/report.txt`  

## 📊 Visualization

Visualization is an important part of this project and includes:

- 📈 **MFCC plots**: Temporal and frequency-based feature graphs  
- 🌀 **Spectrograms**: Visual representation of sound signals  
- 📉 **Confusion matrix**: Evaluate classification performance  
- 📊 **Distribution graphs**: Audio duration, class frequency, etc.

![Bisli (56)](https://github.com/user-attachments/assets/21efc1df-b3ed-48ac-9d50-5ab814bb702a)
![Bom (2)](https://github.com/user-attachments/assets/4d64b681-f547-4dd2-9ce1-42b6027ce184)
![Ksing Kynthei (1)](https://github.com/user-attachments/assets/4e633e96-161c-4f53-9c79-8581198ed53f)
![Ksing Shynrang (10)](https://github.com/user-attachments/assets/a8bc8f54-0cf8-4c72-bfad-00ebb5ffa497)
![Kynshaw (1)](https://github.com/user-attachments/assets/7af59a1e-b73f-42dd-bef5-39d88b47f357)
![Pdiah (3)](https://github.com/user-attachments/assets/1356b77b-fb94-4d0a-a11c-162068db7fe0)


All visual outputs are saved in the `results/` directory and also displayed within the `notebooks/`.

## 📦 Features

- Audio preprocessing (trimming, normalization)  
- MFCC feature extraction  
- Model training and evaluation  
- Data and results visualization  

## 📝 Roadmap

- [ ] Add CNN-based model using spectrograms  
- [ ] Streamlit web interface for real-time demo  
- [ ] Dataset expansion with additional instruments  

## 📚 Dataset

Specify your dataset source here.  
Example: [UrbanSound8K](https://urbansounddataset.weebly.com/urbansound8k.html) or a custom audio dataset.

## 🤝 Contributing

Pull requests and issues are welcome!  
Feel free to open discussions for ideas, bugs, or improvements.
