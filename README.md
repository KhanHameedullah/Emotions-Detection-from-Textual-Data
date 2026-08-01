# Emotion Detection from Textual Data using DistilBERT

This project is a simple NLP application that detects emotions from text using a pre-trained DistilBERT model from Hugging Face. Instead of training a model from scratch, it uses transfer learning to classify the emotion expressed in each line of text and provides an overall summary of the detected emotions.

The project was developed as a learning exercise to explore transformer-based models and emotion classification in Natural Language Processing (NLP).

---

## Features

- Detects emotions from text using a pre-trained DistilBERT model
- Analyzes text line by line
- Calculates the average emotion distribution
- Displays the results as a horizontal bar chart
- No model training required

---

## Supported Emotions

The model can recognize the following emotions:

- Joy
- Love
- Anger
- Fear
- Sadness
- Surprise

---

## Project Structure

```text
Emotions-Detection-from-Textual-Data/
│
├── README.md
├── requirements.txt
├── emotions_detector.ipynb
├── sample_text.txt
└── sample_output.png

```

---

## Installation

Clone the repository:

```bash
git clone https://github.com/KhanHameedullah/Emtions-Detection-from-Textual-Data.git
```

Move into the project folder:

```bash
cd Emtions-Detection-from-Textual-Data
```

Install the required libraries:

```bash
pip install -r requirements.txt
```

---

## How to Run

Open the notebook:

```text
emotions_detector.ipynb
```

Run all the cells.

The notebook will:

- Load the DistilBERT emotion classification model
- Read the input text
- Predict the emotion for each sentence
- Calculate the average emotion distribution
- Display the results as a bar chart

---

## Example Input

```text
Today is a wonderful day.
I feel excited.
I'm a little nervous about tomorrow.
```

---

## Example Output

| Emotion | Score |
|---------|------:|
| Joy | 62% |
| Love | 14% |
| Fear | 9% |
| Sadness | 7% |
| Surprise | 5% |
| Anger | 3% |

---

## Model

This project uses the following pre-trained model from Hugging Face:

**bhadresh-savani/distilbert-base-uncased-emotion**

---

## Technologies Used

- Python
- PyTorch
- Hugging Face Transformers
- DistilBERT
- Matplotlib
- NumPy
- Jupyter Notebook

---

## Future Improvements

Some ideas for extending this project include:

- Support for PDF files
- Support for CSV files
- A Streamlit web application
- Real-time emotion detection
- Exporting results to Excel

---

## Author

**Khan Hameedullah**

M.Sc. Information and Communication Engineering  
University of Electronic Science and Technology of China (UESTC)

GitHub: https://github.com/KhanHameedullah

---

If you found this project useful, consider giving it a ⭐ on GitHub.
