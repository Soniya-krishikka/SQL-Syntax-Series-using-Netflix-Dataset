# SQL-Syntax-Series-using-Netflix-Dataset

This project showcases the use of SQL for analyzing a dataset from Netflix. The analysis is conducted in a Python environment using Pandas and SQLite, allowing for efficient data manipulation and querying.

## Project Overview

The notebook is designed to perform various SQL operations on a dataset containing information about Netflix shows and movies. The dataset includes the following columns:

- **show_id**: Unique identifier for each show/movie.
- **type**: Indicates whether the entry is a movie or TV show.
- **title**: The title of the show/movie.
- **director**: Director(s) of the show/movie.
- **cast**: Main cast members.
- **country**: Country where the show/movie was produced.
- **date_added**: The date the show/movie was added to Netflix.
- **release_year**: The year the show/movie was released.
- **rating**: Age rating of the show/movie.
- **duration**: Duration of the movie or number of seasons for TV shows.
- **listed_in**: Categories or genres the show/movie belongs to.
- **description**: A brief description of the show/movie.

## Key Features

- **Data Loading**: The Netflix dataset is loaded into a Pandas DataFrame and then exported to a SQLite database.
- **SQL Queries**: The notebook contains several SQL queries that demonstrate different SQL operations, such as selecting specific columns, filtering data, and limiting the number of results.
- **Data Analysis**: The SQL queries are used to extract meaningful insights from the Netflix dataset.

## Getting Started

### Prerequisites

To run the notebook, you'll need the following:

- **Python 3.x** installed.
- **SQLite3**: Used as the database engine for running SQL queries.
- **Pandas**: For data manipulation and analysis.
- **Jupyter Notebook**: To run the `.ipynb` file interactively.

You can install the required Python packages using pip:

```bash
pip install pandas sqlite3
```

### Running the Notebook

1. Navigate to the project directory:
   ```bash
   cd sql-netflix-analysis
   ```
2. Launch Jupyter Notebook:
   ```bash
   jupyter notebook
   ```
3. Open the `SQL Syntax Series using Netflix Dataset.ipynb` file and run the cells to execute the analysis.

## Project Structure

- `SQL Syntax Series using Netflix Dataset.ipynb`: The main Jupyter Notebook containing the SQL queries and analysis.
- `data/`: A directory where you should place your Netflix dataset file (e.g., `netflix dataset.csv`).

## Contributions

Contributions are welcome! If you have any suggestions, improvements, or additional queries to include, feel free to fork this repository and submit a pull request.

## Acknowledgements

- Netflix for providing the dataset.
- The Python community for providing essential libraries like Pandas and SQLite.
