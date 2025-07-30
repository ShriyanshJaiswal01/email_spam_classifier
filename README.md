# Email/SMS Spam Classifier

This project is a simple web application that classifies email or SMS messages as "Spam" or "Not Spam" using a machine learning model. The app is built with [Streamlit](https://streamlit.io/) for the user interface.

## Features

- Input any email or SMS message and get an instant spam prediction.
- Uses a pre-trained machine learning model and TF-IDF vectorizer.
- Text preprocessing includes tokenization, stopword removal, and stemming.

## Files

- [`app.py`](app.py): Main Streamlit application.
- `model.pkl`: Pre-trained spam classification model.
- `vectorizer.pkl`: Pre-trained TF-IDF vectorizer.
- `.gitattributes`: Git configuration file.

## Requirements

- Python 3.7+
- Streamlit
- NLTK
- scikit-learn
- pickle

## Setup

1. **Clone the repository** and navigate to the project directory.

2. **Install dependencies**:
    ```sh
    pip install streamlit nltk scikit-learn
    ```

3. **Download NLTK data** (if not already downloaded):
    ```python
    import nltk
    nltk.download('punkt')
    nltk.download('stopwords')
    ```

4. **Run the app**:
    ```sh
    streamlit run app.py
    ```

5. **Open your browser** and go to the URL provided by Streamlit (usually http://localhost:8501).

## Usage

- Enter your email or SMS message in the input box.
- Click the "Predict" button to see if the message is spam or not.

## License

This project
