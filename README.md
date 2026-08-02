Hi, I'm Harini Rajesh

I'm a third-year CSE student at VIT, mostly into data science and machine learning. I like building things that actually help people.

Here are a few projects I've worked on.

## Lexora - Legal Intelligence Platform
Built during my internship at 8Queens. This one uses NLP to make Indian Supreme Court judgements easier to search and understand. I trained a model to predict case outcomes using TF-IDF and Logistic Regression, and along the way I found a data leakage bug that was making my results look way better than they actually were (99.6% F1, which was fake). Fixed it and got an honest 0.6 F1 instead. Also added semantic search using SBERT and FAISS so you can search by meaning instead of just keywords, plus topic modeling with BERTopic to find patterns across thousands of cases.

Built with Python, Scikit-learn, XGBoost, FastAPI, and React.

[Check it out](https://github.com/harinirajeshvit2024-ctrl/Lexora)

## Tamil Nadu Crime Rate Prediction
A project where I predicted crime rates across TN districts. Made about 20 features from the raw data (things like historical averages and year over year change), then tested a few models to see which predicted best. Gradient Boosting won by a good margin, and after trimming down to just the most useful features, I got the model to explain about 93% of the variation in crime rates.

Built with Python, Pandas, and Scikit-learn.

[Check it out](https://github.com/harinirajeshvit2024-ctrl/TN-Crime-Rate-Prediction)

## HemoHub - Blood Bank Management System
A full stack app for managing blood donations, with separate views for admins, staff, and donors. The interesting part is the AI forecasting feature, it uses an LLM to look at current stock and recent requests and flag which blood groups are at risk of running low, then suggests what to do about it.

Built with React, Node.js, MongoDB, and Groq's API.

[Check it out](https://github.com/harinirajeshvit2024-ctrl/HemoHub-Smart-BloodBank-Management-System)

## Tools I use
Python, JavaScript, React, FastAPI, Node.js, Scikit-learn, Pandas, TensorFlow
