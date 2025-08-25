# Customer Opinion Mining with BERT

This project demonstrates fine-tuning **BERT** for **sentiment analysis in English**, applied to customer reviews/opinions. The model classifies text into sentiment categories and highlights how transformer-based architectures can be applied for opinion mining tasks.  

---

## 📂 Repository Contents
- **`fine-tuning-bert.ipynb`** → Jupyter Notebook with preprocessing, model training, evaluation, and inference steps.  
- **`projectdataset.csv`** → Dataset used for fine-tuning BERT (customer reviews).    

---

### 1️⃣ Clone the repository
```bash
git clone https://github.com/alyanumair/customer-opinion-mining-bert.git
cd customer-opinion-mining-bert
```

### 2️⃣ Install dependencies
Make sure you have Python 3.8+ installed, then install required packages:  
```bash
pip install torch torchvision torchaudio
pip install transformers
pip install scikit-learn pandas matplotlib
```

### 3️⃣ Run the notebook
Open the Jupyter notebook:  
```bash
jupyter notebook fine-tuning-bert.ipynb
```

Follow the steps inside to:  
- Load and preprocess data  
- Fine-tune BERT  
- Evaluate performance (accuracy, F1-score)  
- Test predictions on new sentences  



## 🔗 References
- [BERT Paper](https://arxiv.org/abs/1810.04805)  
- [Hugging Face Transformers](https://huggingface.co/transformers/)  

---

## 👤 Author
**Alyan Umair**  
- [LinkedIn](https://www.linkedin.com/in/alyan-umair/)

