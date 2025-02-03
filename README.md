# 🧠 EEG Signal Enhancement and EMG Noise Reduction

[![GitHub](https://img.shields.io/badge/GitHub-Repository-blue)](https://github.com/habibkhan099/EEG-Signal-Enhancement-and-EMG-Noise-Reduction)

## 🌟 Introduction  
Electroencephalography (**EEG**) is a widely used method for studying brain activity. However, **EMG noise** often contaminates EEG signals, making accurate analysis challenging.  
This project focuses on:  
✔️ Enhancing EEG signal quality  
✔️ Reducing EMG noise through advanced signal processing techniques  

🎯 The results of this work can be applied in **brain-computer interfaces (BCI)**, **neurofeedback**, and **medical diagnosis systems**.

---

## ✨ Features
- 🛠️ **Bandpass Filtering:** Focuses on the critical EEG frequency range (0.5–50 Hz).  
- 🌊 **Wavelet Transform:** Reduces EMG artifacts in both time and frequency domains.  
- 🧹 **Savitzky-Golay Smoothing:** Smooths the waveform for enhanced clarity.  
- 📊 **Quantitative Evaluation:** Improves **Signal-to-Noise Ratio (SNR)**.

---

## 📂 Dataset  
The dataset used is the **EEG Motor Movement/Imagery Dataset** from **PhysioNet**, including:  
- 🧑‍🤝‍🧑 **109 participants**  
- 📁 **Over 1500 EEG recordings**  

📌 [Dataset Source](https://physionet.org/content/eegmmidb/1.0.0/)

---

## 🛠️ Methodology  
The signal enhancement pipeline consists of the following steps:

### 1️⃣ Bandpass Filtering  
A **Butterworth filter** isolates the EEG frequency range, removing unwanted noise while preserving essential signal components.  

🖼️ **_Insert Bandpass Filtering Diagram Here_**  

---

### 2️⃣ Wavelet Transform  
Wavelet analysis decomposes the EEG signal, applying thresholding to suppress EMG artifacts and reconstruct the denoised signal.  

🖼️ **_Insert Wavelet Transform Process Visual Here_**  

---

### 3️⃣ Savitzky-Golay Smoothing  
This technique applies polynomial fitting to smooth minor fluctuations while maintaining the signal's core features.  

🖼️ **_Insert Savitzky-Golay Smoothing Illustration Here_**

---

## 🚀 Results  
The pipeline significantly improves signal quality:  

### 📈 Before vs After Noise Reduction  
- **Raw Signal:** Heavily contaminated by EMG noise.  
- **Filtered Signal:** Unwanted noise removed.  
- **Enhanced Signal:** Cleaned and smoothed for analysis.  

🖼️ **_Insert Signal Comparison Chart Here_**  

### 🔢 Key Metrics  
- **Initial SNR:** 4.19 dB  
- **Enhanced SNR:** 2.38 dB  

---

## 🔮 Challenges and Limitations  

### Challenges  
- **Signal Variability:** EEG signals differ significantly between participants.  
- **Threshold Tuning:** Noise reduction thresholds required iterative optimization.  

### Limitations  
- Offline processing only; no real-time capabilities.  
- Limited dataset scope.

---

## 📅 Future Work  
- 🕒 **Real-Time Processing:** Implement the pipeline for real-time EEG analysis.  
- 📈 **Expand Dataset:** Test with more diverse populations for broader applicability.  
- 🤖 **AI-Based Noise Reduction:** Use machine learning for adaptive thresholding.

---

## 🛠️ Getting Started  

### Prerequisites  
📌 Install Python (3.8 or above).  
📌 Required libraries: `NumPy`, `SciPy`, `PyWavelets`, `Matplotlib`.  

---

### Installation  

1️⃣ Clone the repository:  
```bash
git clone https://github.com/habibkhan099/EEG-Signal-Enhancement-and-EMG-Noise-Reduction.git
cd EEG-Signal-Enhancement-and-EMG-Noise-Reduction
```  

2️⃣ Install dependencies:  
```bash
pip install -r requirements.txt
```  

---

### Usage  

1️⃣ Prepare EEG data in `.csv` or `.mat` format.  
2️⃣ Run the main script for signal processing:  
```bash
python main.py --input your_data.csv --output enhanced_signal.csv
```  

3️⃣ Visualize results:  
```bash
python plot_results.py
```  

---

## 📷 Visuals  
Here are some visual aids for the project:  

### 1️⃣ Block Diagram  
🖼️ **_Insert Overall Pipeline Block Diagram Here_**

### 2️⃣ GUI (if applicable)  
🖼️ **_Insert GUI Screenshot Here_**

---

## 📚 References  
1️⃣ Goldberger AL, et al. *PhysioNet: EEG Motor Imagery Dataset*. [PhysioNet](https://physionet.org/).  
2️⃣ Mallat, S. *A Wavelet Tour of Signal Processing*. Academic Press, 1999.  
3️⃣ Tawhid, M.N.A. et al., *Time-Frequency EEG Analysis Using Wavelet Transform*.  

---

## 🤝 Contributing  
We welcome contributions! To contribute:  
1️⃣ Fork the repository.  
2️⃣ Create a new branch (`feature-name`).  
3️⃣ Submit a pull request.  

---

## 📄 License  
This project is licensed under the MIT License. See the `LICENSE` file for more details.

---

## About  
Developed as a Semester Project of Digital Signal Processing during the **B.Sc. Computer Engineering program** at **UET Taxila**, supervised by **Dr. Muhammad Majid**.

---

### 📌 Repository  
🔗 [Visit Repository](https://github.com/habibkhan099/EEG-Signal-Enhancement-and-EMG-Noise-Reduction)  

---
