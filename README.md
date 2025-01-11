# Task-4-Sentiment-Analysis
# Prodigy_DS_04

🌀 **Sentiment Analysis and Prediction with Dynamic Visualizations** 🌟

Welcome to the world of sentiment analysis and prediction! This repository is packed with mysterious insights into how textual data is processed and transformed into sentiment-based predictions. 🚀

## 🧩 What's Inside?

### 📊 Datasets:
- `twitter_training.csv` - Used for training and analysis.

- https://1drv.ms/x/c/f6bc90f75ca4b431/EaohkNhnoaZCssRsdDsqZBgBhMAWkhEEJrIosZJ3OsJNwA?e=h2K5lP

- `twitter_validation.csv` - Used for validation and sentiment prediction.

- https://1drv.ms/x/c/f6bc90f75ca4b431/EUWvR668yWRMvgARjdKbLxwBI_ngzMtIvMVSukg9oYH8sA?e=X82gTj

### 🎨 Dynamic Visualizations:
- Advanced visualizations of sentiment distributions and company-specific sentiment trends.
- Compare actual vs predicted sentiments seamlessly!

### 🔮 Interactive Interface:
- Input your custom tweet and watch the magic unfold as the TextBlob model predicts the sentiment!

## 🤔 What Does This Program Do?
- Loads and processes two datasets (`twitter_training.csv` and `twitter_validation.csv`).
- Applies TextBlob, a powerful sentiment analysis model, to predict sentiment types (Positive, Negative, Neutral, or Irrelevant).
- Enhances the `twitter_validation.csv` file by appending a new column: `Predicted_Sentiment`.
- Visualizes the sentiment distributions dynamically using Dash.
- Provides an interactive interface to input tweets and get real-time sentiment predictions.

## 📈 Output Highlights
- ✨ **Predicted Sentiments**: A new column, `Predicted_Sentiment`, is created in the validation dataset.
- ✨ **Dynamic Graphs**: Visualize trends and patterns across actual and predicted sentiments.
- ✨ **Interactive Results**: Input a tweet, and see its sentiment predicted instantly!

## 🛠 Libraries Used
### 💻 Core Libraries:
- `pandas` - For data manipulation and analysis.
- `numpy` - For numerical operations.

### 📊 Visualization Tools:
- `plotly` - For dynamic and interactive graphs.
- `dash` - To create a web-based interactive visualization interface.

### 🤖 Sentiment Analysis:
- `TextBlob` - For natural language processing and sentiment prediction.

## 🔥 What Have I Done?
### Loaded the Data
- Used two datasets: `twitter_training.csv` for analysis and `twitter_validation.csv` for testing and predictions.

### Analyzed the Data
- Explored the sentiment distribution across companies and tweets.
- Visualized trends using advanced bar charts and other interactive plots.

### Predicted Sentiments
- Applied TextBlob to predict the sentiment type and appended this to the `twitter_validation.csv` file.

### Created an Interface
- Developed a Jupyter Notebook interface to let users input tweets and see predicted sentiments in real-time.

### Visualized the Data Dynamically
- Built company-wise sentiment visualizations for both actual and predicted values.
- Compared actual vs predicted sentiments dynamically.

## 🌟 Sample Outputs
### 📄 Enhanced Validation Dataset
| Sentiment_ID | Company | Sentiment | Tweet_TEXT | Predicted_Sentiment |
|--------------|---------|-----------|------------|---------------------|
| 8312         | Microsoft | Negative | @Microsoft Why do I pay for WORD when it functions so poorly on my @SamsungUS Chromebook? | Negative |
| 5130         | GrandTheftAuto(GTA) | Negative | Oh shit I got 1 day to finish this fuk | Negative |

### 📊 Sample Visualizations on Twitter Training Dataset (`twitter_training.csv`)
#### Sentiment Distribution
![image](https://github.com/user-attachments/assets/305e8bf4-7ca0-4fcf-b854-86a14de7200a)
![image](https://github.com/user-attachments/assets/bf8e7d88-05ca-44ca-bf36-9a634d049aef)

#### Company-Wise Sentiment Trends

![image](https://github.com/user-attachments/assets/236c547e-06ff-4395-bb5e-a1a3d3d4475d)


### Interactive Interface for Predictions
![image](https://github.com/user-attachments/assets/99111626-3b64-431f-babe-bf604fa5ba2b)


### Sample Visualizations on Twitter Validation Dataset (`twitter_validation.csv`)
#### Confusion Matrix: Actual vs Predicted
![image](https://github.com/user-attachments/assets/1dae7982-52d5-4f07-b54f-21381743e280)


#### Sentiment Distribution (Actual) vs  Sentiment Distribution (Predicted)
![image](https://github.com/user-attachments/assets/1e1e84b4-5de1-42a1-ad43-1772c9bf66ab)


#### Company Wise Sentiment Distribution
![image](https://github.com/user-attachments/assets/0ed735a8-c31a-4e42-8131-5eaa5a475d43)


## 🌐 Explore It Yourself
Clone this repository and explore the mystery behind sentiment analysis. 🕵️‍♂️ Who knows what you’ll uncover? 🌟

---
