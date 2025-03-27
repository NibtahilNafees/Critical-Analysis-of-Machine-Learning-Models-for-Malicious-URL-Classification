# ** Malicious URL Detection Using Machine Learning**  

## ** Overview**  
This project focuses on detecting **malicious URLs** by classifying them into five categories:  
**Benign** | **Defacement** | **Phishing** | **Malware** | **Spam**  

We implemented **Random Forest, XGBoost, and CNN**, achieving a **maximum accuracy of 91.1%**.  

## **🗂️ Dataset**  
- **Source:** Merged dataset containing **653,046 URLs**  
- **Classes:** Benign, Defacement, Phishing, Malware, Spam  
- **Imbalance Handling:** SMOTE for fair representation  

## **🛠️ Tech Stack**  
- **Python** (Pandas, NumPy, Matplotlib, Seaborn)  
- **Scikit-learn** (Machine Learning Models)  
- **XGBoost** (Gradient Boosting)  
- **TensorFlow/Keras** (CNN Model)  

## ** Feature Engineering**  
- **Structural Features**: URL length, subdomains, special characters  
- **NLP Features**: Tokenized URL parts, TLD extraction  
- **Path Analysis**: Query length, number of parameters  

## **📊 Model Performance**  

| Model        | Accuracy | Notes |
|-------------|----------|----------------|
| **Random Forest** | 91.0% | Best performance |
| **XGBoost** | 87.0% | Strong feature handling |
| **CNN** | 80.80% | Worked well |

🚫 **SVM was not used** due to difficulties in handling URL-based feature vectors.  
🚀 **BERT was not included** to focus on traditional ML & deep learning methods.  

## **📈 Exploratory Data Analysis (EDA)**  
✅ URL length distributions  
✅ Boxplots for malicious categories  
✅ TLD analysis  
✅ Word Cloud of URL components  

## **🛠️ Installation & Usage**  
```bash
# Clone the repository
git clone https://github.com/your-username/malicious-url-detection.git
cd malicious-url-detection

# Install dependencies
pip install -r requirements.txt

# Run the model training script
python train.py
```

## ** Future Enhancements**  
- ✅ **BERT/GPT-based URL classification**  
- ✅ **Hybrid models (XGBoost + LSTM)**  
- ✅ **Real-time deployment & detection**  

## **📜 License**  
🔓 MIT License – Free to use and modify!  

