# 🎬 Movie Genre Classifier (Machine Learning Project)

This is a machine learning project built during my **CodSoft Internship** to classify the genre of movies based on their plot descriptions.

It uses **text classification techniques** like TF-IDF and Logistic Regression to train a predictive model, and applies it to unseen movie summaries.

---

## 🚀 What This Project Does

- Loads a dataset of movie plot summaries
- Converts text into numbers using **TF-IDF**
- Trains a **Logistic Regression model**
- Predicts genres for new, unseen movie descriptions
- Saves the results in a CSV file (`test_predictions.csv`)

---

## 🧠 Technologies Used

- Python
- Pandas, NumPy
- Scikit-learn (for ML model + TF-IDF)
- Jupyter Notebook
- joblib (for saving models)

---

## 📂 Files in This Repo

| File | Description |
|------|-------------|
| `moviegenre.ipynb` | Main notebook with all 10 steps (from loading to prediction) |
| `train_data.txt` | Dataset with descriptions + genres |
| `test_data.txt` | Dataset with new descriptions (no genres) |
| `test_predictions.csv` | Final output with predicted genres |
| `genre_model.pkl` | Trained Logistic Regression model |
| `genre_vectorizer.pkl` | Saved TF-IDF vectorizer |

---

## 📈 Model Accuracy

Accuracy on validation set: `~xx%` (Replace with your real value)

---

## 💾 How to Run This Project

1. Upload `train_data.txt` and `test_data.txt` to your Jupyter environment
2. Open and run `moviegenre.ipynb` cell by cell
3. Final predictions will be saved in `test_predictions.csv`
4. You can view the output in Excel or any CSV viewer

---

## 💡 Future Ideas

- Use a deep learning model (e.g., LSTM)
- Handle multi-label genres
- Add more features like director, cast, etc.
- Deploy the model as a web app using Streamlit or Flask

---

## 👩‍💻 Made by Cherry 🍒

> Engineering student. Aspiring entrepreneur. Machine learning enthusiast.  
> Built with ✨love, code, and chaos✨ during the CodSoft internship.

Let’s connect!  
📫 [LinkedIn](#) (Add your link)  
📧 [Email](mailto:yourname@example.com)

