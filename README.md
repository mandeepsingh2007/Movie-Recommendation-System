# 🎬 Movie Recommendation System

## 📌 Project Overview
The **Movie Recommendation System** suggests movies based on content similarity using **TF-IDF vectorization** and **cosine similarity**. It helps users find movies similar to their preferences.

## 🚀 Features
- 📂 Uses **TF-IDF Vectorization** to process movie features.
- 🔍 Finds the closest matching movie title from user input.
- 🧠 Computes **cosine similarity** to recommend similar movies.
- 🎭 Considers genres, keywords, taglines, cast, and director.
- 🎯 Returns top **20 recommended movies**.

## 📁 Dataset
The system uses a dataset named **movies.csv**, which contains essential information about movies:
- Title
- Genres
- Keywords
- Tagline
- Cast
- Director

## 🛠️ Technologies Used
- **Python** 🐍
- **NumPy** 📊
- **Pandas** 📑
- **Scikit-learn** 🤖
- **difflib** (for fuzzy matching)



## 📌 Code Workflow
1. **Data Preprocessing:**
   - Load movie dataset.
   - Fill missing values.
   - Combine relevant features into a single text column.
2. **Feature Extraction & Similarity Calculation:**
   - Apply **TF-IDF Vectorization**.
   - Compute **cosine similarity** between movies.
3. **Movie Recommendation:**
   - Get user input.
   - Find closest matching movie title.
   - Fetch similar movies based on similarity scores.



## 🤝 Contributing
Pull requests are welcome! If you want to enhance the system, feel free to fork the repository and submit a PR.

## 📄 License
This project is **MIT Licensed**.

📌 **Star the repository if you find it useful! ⭐**

