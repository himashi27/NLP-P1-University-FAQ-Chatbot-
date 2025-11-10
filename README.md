University FAQ Chatbot
A lightweight NLP-based chatbot that answers common university questions such as admissions, fees, hostel, exams, timetable, scholarships, and more.

✅ Features
NLP preprocessing (tokenization, stopwords, lemmatization)
TF-IDF + Cosine Similarity for accurate answer matching
CSV-based FAQ dataset (easy to edit and expand)
Interactive chat mode
Optional Streamlit web app

✅ How It Works
Clean & preprocess all FAQ questions
Convert questions into TF-IDF vectors
Convert user query into a vector
Measure cosine similarity
Return the best-matched answer
If similarity is low → return fallback response

✅ Dataset Format (faq.csv)
Question	Answer
How much is the admission fee?	            The admission fee is ₹5000.
How can I apply for a hostel?	              Apply online at hostel.university.edu.
When will exams start?	                    Exams begin in December.

✅ Future Improvements
BERT / Sentence Transformers for deeper understanding
Multilingual support
Voice chatbot
PDF/Document-based Q&A
