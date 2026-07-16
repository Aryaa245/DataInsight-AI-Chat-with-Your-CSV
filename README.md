# DataInsight AI – Chat with Your CSV

DataInsight AI is an AI-powered chatbot that enables users to analyze CSV datasets using natural language. Users can upload a CSV file, ask questions about the data, generate visualizations, and receive automated insights without writing code.

## Overview

Traditional data analysis often requires knowledge of SQL, Python, or spreadsheet tools. DataInsight AI simplifies this process by allowing users to interact with datasets through a conversational interface powered by Large Language Models (LLMs).

The application combines data processing, visualization, and AI-driven analysis to make data exploration more accessible.

## Features

* Upload and analyze CSV datasets
* Ask questions in natural language
* Generate automated insights
* Create data visualizations
* Detect missing values and outliers
* Perform basic statistical analysis
* Interactive chat interface
* Support for Indonesian and English queries

## Example Questions

* What is the total sales amount?
* Which product generated the highest revenue?
* Show the monthly sales trend.
* Are there any missing values in the dataset?
* Identify potential outliers.
* Provide key insights from this dataset.

## System Workflow

1. User uploads a CSV file.
2. The dataset is loaded into a Pandas DataFrame.
3. The AI model interprets the user's question.
4. Relevant analysis is executed using Python and Pandas.
5. Results, insights, and visualizations are returned to the user.

## Tech Stack

### Frontend

* Streamlit

### Backend

* Python

### Data Processing

* Pandas
* NumPy

### Visualization

* Plotly
* Matplotlib

### AI Model

* Gemini 2.5 Flash

## Project Structure

```text
datainsight-ai/
├── app.py                 # Streamlit main
├── core/
│   ├── data_loader.py      # baca & validasi CSV
│   ├── llm_agent.py        # prompt engineering + call LLM
│   ├── executor.py         # eksekusi kode aman (sandbox)
│   └── eda.py               # auto EDA logic
├── utils/
│   └── chart_generator.py
└── requirements.txt
```

## Installation

Clone the repository:

```bash
git clone https://github.com/yourusername/DataInsightAI.git
```

Navigate to the project directory:

```bash
cd DataInsightAI
```

Install dependencies:

```bash
pip install -r requirements.txt
```

Run the application:

```bash
streamlit run app.py
```

## Future Improvements

* Multi-file dataset support
* Automated EDA reports
* PDF report generation
* Dashboard generation
* Advanced statistical analysis
* Machine learning recommendations
* Database connectivity (MySQL/PostgreSQL)

## Author

Stefanus Arya Bayu Samudra Bataona

Informatics Student | Data Analyst Enthusiast | AI & Machine Learning Enthusiast
