🧹 CleanMyData

CleanMyData is a simple, interactive data-cleaning and visualization web app built with Streamlit
. It helps you quickly upload CSV files, remove missing values, explore your dataset, and generate visual insights — all from your browser, no code required.


🚀 Features
- 📂 Upload CSV files directly from your computer

- 🔍 Get an instant data summary (rows, columns, data types, unique values)

- 🧽 Clean your dataset by removing missing values with one click

- 📊 Generate a bar chart to visualize categorical data distributions

- ⚙️ Easy-to-extend architecture — add your own cleaning or visualization logic

🧰 Tech Stack

- Python 3

- Streamlit — for building the web UI

- Pandas — for data manipulation

- Matplotlib and Seaborn — for data visualization

🏗️ How to Run Locally

1. Clone this repository:
        git clone https://github.com/pratyush2514/Clean-My-Data.git
        cd Clean-My-Data
2. Create and activate a virtual environment (optional but recommended):

python -m venv venv
source venv/bin/activate       # On macOS/Linux
venv\Scripts\activate          # On Windows
Install dependencies:

bash
Copy code
pip install -r requirements.txt
(If you don’t have a requirements.txt yet, create one with this line:)

bash
Copy code
streamlit pandas matplotlib seaborn
Run the app:

bash
Copy code
streamlit run app.py
Open in your browser:
Streamlit will automatically open the app at
👉 http://localhost:8501

🧠 Example Workflow
Upload a CSV file

View summary stats (rows, columns, data types, unique counts)

Click “Clean Data” to remove missing values

Select a column and generate a bar chart visualization

🧩 Future Improvements
Add more advanced data cleaning (outlier removal, normalization, duplicates handling)

Include multiple chart types (histogram, scatter, heatmap)

Export cleaned data as a downloadable CSV

Add caching for large datasets
