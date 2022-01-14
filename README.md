# Loan Qualifier Application 

Welcome to the Loan Qualifier Application! Have you ever needed a loan, but you weren't sure which loans you would qualify for? This command-line interface application works by reading a `daily_rate_sheet` csv file that has loan criteria from various lenders, asking the users some questions to evaluate their loan eligibility, returning to them a list of qualifying loans, and allowing the users to save their list of qualifying loans. 

---

## Technologies

This project leverages python 3.7 with the following packages:

* [fire](https://github.com/google/python-fire) - For the command line interface, help page, and entry-point.

* [questionary](https://github.com/tmbo/questionary) - For interactive user prompts and dialogs.

---

## Installation Guide
Before running the application, first install the following dependencies:
```python
    pip install fire
    pip install questionary
```


In the terminal (Mac) or Git Bash (Windows), navigate to the directory where you want to clone the repository and enter the following command:
```python
git clone https://github.com/ccroft6/Loan_Qualifier_App.git
```

---

## Usage

To use the loan qualifier application, clone the repository and run the `app.py` with:
```python
    python app.py
```

Upon launching the loan qualifier app, you will be greated with the prompts shown in the video. 
* First, enter the file path `./data/daily_rate_sheet.csv`.
* Then, answer the questions with your own bank information.
* Finally, if you would like to save the list, use the arrow keys to select "yes" or "no" and press enter. You can save it to a file path such as `qualifying_loans.csv`.


![Example usage of Loan Qualifier App](loan_qualifier_example.gif)

---
---

## Contributors

Catherine Croft

Email: catherinecroft1014@gmail.com

LinkedIn: https://www.linkedin.com/in/catherine-croft-4715481aa/

---

## License

MIT
