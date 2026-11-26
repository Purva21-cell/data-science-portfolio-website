# Data Science Portfolio Website

An interactive, multi-page portfolio website built with **Python** and **Streamlit**. The project demonstrates a personal profile, project gallery, machine-learning prediction interface, and interactive data exploration.

## Features

- **Home Page:** Introduction, featured projects, key focus areas, and skills visualization.
- **Projects Page:** Summaries of software, computer-vision, and data-science projects.
- **Interactive ML Demo:** KNN classifier trained on the Iris dataset with interactive predictions and probability charts.
- **Data Explorer:** Interactive filters, visitor and conversion metrics, Plotly charts, and CSV upload functionality.
- **About Me:** Education, interests, technical skills, and contact information.
- **Reusable Code Structure:** Shared utility modules and custom CSS styling.

## Technology Stack

- Python
- Streamlit
- Pandas
- NumPy
- Plotly
- Scikit-learn

## Project Structure

```text
data_science_portfolio/
├── app.py
├── pages/
│   ├── 1_Projects.py
│   ├── 2_Interactive_ML_Demo.py
│   ├── 3_Data_Explorer.py
│   └── 4_About_Me.py
├── utils/
│   ├── __init__.py
│   ├── data.py
│   └── ui.py
├── assets/
│   └── style.css
├── requirements.txt
├── .gitignore
└── README.md
```

## Installation and Setup

1. Install Python 3.10 or newer.
2. Clone or download this repository.
3. Open a terminal in the project directory.
4. Install the required dependencies:

```bash
pip install -r requirements.txt
```

5. Run the application:

```bash
streamlit run app.py
```

6. Open the local application at:

```text
http://localhost:8501
```

## Deployment

This application can be deployed using Streamlit Community Cloud.

1. Push the project to GitHub.
2. Visit https://share.streamlit.io/
3. Sign in using GitHub.
4. Select the project repository.
5. Choose the `main` branch.
6. Set the main file path to `app.py`.
7. Click Deploy.

## Important Notes

- The Data Explorer contains illustrative sample data.
- The Iris classifier is an educational machine-learning demonstration.
- Update personal contact information before publishing.
- Verify all project descriptions and links before submission.

## Author

**Purva Ghate**
