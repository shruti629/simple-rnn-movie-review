#  Movie Review Sentiment Analysis (IMDB Dataset)

This project demonstrates **Sentiment Analysis of Movie Reviews** using a **Simple Recurrent Neural Network (RNN)** trained on the IMDB dataset.  
The model classifies reviews as **Positive** or **Negative**.

##  Features
- Preprocessed IMDB dataset for training and testing.
- Implemented **Simple RNN** using TensorFlow/Keras.
- Interactive **Streamlit Web App** for real-time predictions.
- Dashboard with input text, prediction result, and confidence score.

## Installation

Clone this repository:

    git clone https://github.com/shruti629/simple-rnn-movie-review.git
    cd simple-rnn-movie-review    
Create Conda environment:

    conda create -p venv python=3.12 -y
    conda activate venv/
Install requirements:

    pip install -r requirements.txt
Run the Streamlit:

    streamlit run app.py
Then open http://localhost:8501/

## Dashboard

**The Streamlit dashboard allows you to:**
- Enter a movie review and get sentiment prediction
- View confidence score
- Visualize overall positive vs negative review distribution

## Dashboard
![Dashboard Screenshot](https://github.com/shruti629/simple-rnn-movie-review/blob/1b4f6cb55d0ef82882798628cf12bf67cd794a90/Streamlit%20-%20Google%20Chrome%208_19_2025%209_28_33%20AM.png)

