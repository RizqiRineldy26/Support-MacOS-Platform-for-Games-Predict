# Judul Project
MacOS Device Support Plaform for Games Prediction

## Repository Outline
1. README.md - Penjelasan gambaran umum project
2. Modeling.ipynb - Notebook yang berisi analisa data, permodelan, serta pemilhan model yang terbaik untuk dilakukan Tuning
3. Inference.ipynb - Notebook untuk melakukan pengetesan / inference pada model yang sudah dipilih
4. games.csv - Dataset yang sudah direduce beberapa fitur yang tidak mempengaruhi target
5. model_gb.pkl - File Model dipilih yang sudah dilakukan Hyperparameter Tuning, Model = Gradient Boosting
6. Deployment Folder - Berisi script file py untuk deployment

## Problem Background
Mengetahui dan Memprediksi apakah suatu game compatible terhadap paltform MacOS atau tidak

## Project Output
Output Project adalah analisis dan machine learning

## Data
Sumber dataset berasal dari Kaggle dengan daftar games yang ada di Palform Stream pada bulan Maret 2025. Data tersebut mempunyai sekitar 90.000 baris dan 47 Kolom

## Method
project ini mengenai machine learning sehingga metode yang dipakai adalah model supervised learning. Dikarenakan target nya berupa nilai boolean machine learning yang digunakan bersifat Clasifier. Untuk model yang digunakan yaitu Decision Tree, Random Forest, KNN, LinearSVC, serta Gradient Boosting

## Stacks
Library Python yang digunakan :
1. Scikit Learn
2. Matplotlib
3. Seaborn
4. Pandas
5. Numpy
6. Feature Engine
7. Scipy

## URL
- Justifikasi : [Click Here](https://www.howtogeek.com/macos-is-finally-becoming-a-legit-gaming-platform/)
- Dataset URL : [Click Here](https://www.kaggle.com/datasets/artermiloff/steam-games-dataset/data)
- Dataset cloud : [Click Here](https://drive.google.com/drive/folders/19zRFjrooeTkH8zTyfcYQKbrpbiKREI5a?usp=sharing)
- Deployment  : [Click Here](https://rizqirineldy-predict.streamlit.app/)
