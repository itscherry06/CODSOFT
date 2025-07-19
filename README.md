#Movie Genre Classifier (Machine Learning Project)

It's a machine learning project developed during my **CodSoft Internship** to predict the genre of movies from their plot descriptions.

It employs **text classification methods** such as TF-IDF and Logistic Regression to train a model, and uses it on unseen movie summaries.

---

##What This Project Does

- Loads a dataset of movie plot summaries
- Transforms text to numbers using **TF-IDF**
- Trains a **Logistic Regression model**
- Makes predictions for new, unseen movie descriptions
- Saves the predictions to a CSV file (`test_predictions.csv`)

---

## Technologies Used

- Python
- Pandas, NumPy
- Scikit-learn (for ML model + TF-IDF)
- Jupyter Notebook
- joblib (for saving models)

---

## Files in This Repo

| File | Description |
|------|-------------|
| `moviegenre.ipynb` | Principal notebook with all 10 steps (from loading to prediction) |
| `train_data.txt` | Dataset with descriptions + genres |
| `test_data.txt` | New data set with descriptions (without genres) |
| `test_predictions.csv` | End output with predicted genres |
| `genre_model.pkl` | Learned Logistic Regression model |
| `genre_vectorizer.pkl` | Stored TF-IDF vectorizer |

---

## Model Accuracy

Accuracy over validation set: 57.93 %
    

---

## How to Run This Project

1. Upload `train_data.txt` and `test_data.txt` into your Jupyter environment
2. Open and execute `moviegenre.ipynb` cell by cell
3. Final prediction will be saved in `test_predictions.csv`
4. You can see the output either in Excel or any CSV reader

---

## Future Plans

- Employ a deep learning model (e.g., LSTM)
- Process multi-label genres
- Include additional features such as director, cast, etc.
- Host the model as a web application using Streamlit or Flask

---

##  Made by Cherry 🍒

> Engineering student. Dreaming entrepreneur. Machine learning fanatic.
> Made with ✨love, code, and chaos✨ during the CodSoft internship.

Let’s connect!  
📫 [LinkedIn]( www.linkedin.com/in/sai-charan-neerudu)  
📧 [Email]( mailto:neerudusaicharan042@gmail.com)

