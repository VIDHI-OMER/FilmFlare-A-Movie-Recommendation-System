<img width="1224" height="561" alt="image" src="https://github.com/user-attachments/assets/b208fcfb-5241-4a84-a913-6de834424260" />🎬 FilmFlare – Movie Recommendation System

FilmFlare is an interactive movie recommendation system built using Python, Streamlit, and Machine Learning. It recommends movies similar to the one selected by the user using content-based filtering and similarity scores.

🚀 Features

🎯 Content-based movie recommendation

🧠 Uses cosine similarity for predictions

⚡ Fast and lightweight (optimized model files)

🖼️ Movie posters with titles displayed

🔍 Simple and user-friendly search interface

🎨 Clean Streamlit UI

🧠 How It Works

Movie dataset is processed and converted into vectors

Similarity matrix is generated using cosine similarity

When a user selects a movie, top similar movies are fetched

Results are displayed with movie posters and titles

🛠️ Tech Stack
Category	Technology
Language	Python
Framework	Streamlit
Libraries	pandas, numpy, joblib, requests
ML Type	Content-Based Filtering
📁 Project Structure
FilmFlare/
│
├── app.py                  # Main Streamlit app
├── model/
│   ├── movie_list.pkl      # Compressed movie data
│   └── similarity.pkl      # Compressed similarity matrix
├── requirements.txt
└── README.md

▶️ How to Run Locally
1️⃣ Clone the Repository
git clone https://github.com/VIDHI-OMER/FilmFlare-A-Movie-Recommendation-System.git

2️⃣ Navigate into Project
cd FilmFlare-A-Movie-Recommendation-System

3️⃣ Install Required Dependencies
pip install -r requirements.txt

4️⃣ Run the Application
streamlit run app.py

📸 Demo 
<img width="1224" height="561" alt="image" src="https://github.com/user-attachments/assets/ce0b5d3c-ec4f-489a-8c47-a8b9770d33f9" />



🔮 Future Enhancements

Add hybrid filtering (content + collaborative)

Deploy on Streamlit Cloud / Render

Add user login + watch history

Use deep learning embeddings (BERT / Sentence Transformers)

🙌 Acknowledgements

TMDB dataset

Streamlit community

Python open-source ecosystem

⭐ Support

If you like this project, please star ⭐ the repository — it motivates future development!

👩‍💻 Developer

Vidhi Omer
GitHub: https://github.com/VIDHI-OMER
