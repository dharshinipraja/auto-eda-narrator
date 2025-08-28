

#  Data Storyteller Bot

 A mini AI + Data Science project that turns raw datasets into human-readable stories with automated EDA, insights, and simple visualizations.

---

## 🚀 Features

* Upload any CSV dataset in Google Colab.
* Automatically generates insights like:

  * `"The dataset contains 9994 rows and 21 columns."`
  * `"The average Sales is 229.86."`
  * `"The most common value in 'Category' is 'Office Supplies'."`
  * `"The highest Sales occurred in November."`
* Supports numerical, categorical, and time-series data.
* Creates bar charts for sales & category trends.
* Outputs a final narrated story .

---

## 🛠️ Tech Stack

* Python
* Pandas – data manipulation
* NumPy – numerical operations
* Matplotlib – plotting graphs
* Google Colab – run in the cloud

---

## 📂 Dataset

Demo dataset: [Superstore Sales Data](https://gist.githubusercontent.com/nnbphuong/38db511db14542f3ba9ef16e69d3814c/raw/Superstore.csv)

📌 But you can upload any CSV file to test the bot!

---

## 📖 How to Run

1. Open [Google Colab](https://colab.research.google.com/).
2. Upload the notebook `Data_Storyteller_Bot.ipynb`.
3. Run the cells step by step:

   * Load dataset
   * Generate insights
   * Plot graphs
   * View final auto-generated story
4. (Optional) Replace with your own dataset.

---

##  Example Output

```
 FINAL AUTO-GENERATED DATA STORY 

The dataset contains 9994 rows and 21 columns.
 The average Sales is 229.86.
 The maximum Profit is 8399.98.
 The most common value in 'Category' is 'Office Supplies'.
 The highest Sales occurred in November.
 The best performing year was 2017.
```

---

##  Installation (Local Option)

Clone this repo:

```bash
git clone https://github.com/your-username/data-storyteller-bot.git
cd data-storyteller-bot
pip install -r requirements.txt
```

---

##  Learning Goals

* Practice **EDA (Exploratory Data Analysis)**.
* Learn to combine **Pandas + simple NLP templating**.
* Build a **creative mini AI project** for portfolio/GitHub.

---

##  Contribution

Pull requests are welcome! Try testing with new datasets and adding more storytelling templates.

---

##  License

MIT License – free to use and modify.

