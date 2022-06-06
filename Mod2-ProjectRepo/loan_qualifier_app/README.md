# FinTech Loan Qualification Application

*Welcome to my repository for a FinTech project on a 'Loan Qualifier App'*

---

## Background
The application program allows users to access a daily bank list of lenders and provide a list of loans that are available to applicants or customers qualifications.  It also allows the user to interact more efficiently with customers on the data provided for a more comprehensive experience in the decision process. The program is more efficient by taking the 'daily_rate_sheet' of bank loan data from lenders, asking qualifying lending questions from customers, and returning a matching list of available qualifying loans for the customer. 

---

## Technologies

The software operates on python 3.9 with the following packages:

* [fire](https://github.com/google/python-fire) - For the command line interface, help page, and entrypoint.

* [questionary](https://github.com/tmbo/questionary) - For interactive user prompts and dialogs 

---

## Installation Guide

In this section, you should include detailed installation notes containing code blocks and screenshots.

Before running the application first install the following supporting python apps.

```python
  pip install fire
  pip install questionary
```

---

## Usage

To enable the loan qualifier application you must clone the repository and run the **app.py** with: 

```python
python app.py
```

Upon launching the loan qualifier application the user will be greeted with the following prompts to retreive the file path to the latest banking 'daily_rate_sheet.csv'. Then the user will be prompted with dialogue to get applicants financial information to determine which loans they are qualified to select. According to applicant's answers the user will recieve a return of no list (0 qualifying loans) or a list of qualifying loans from lenders. When prompted the user can choose to save the qualifying loans list and the file location to save it.  

![Loan Qualifier Prompts](https://github.com/digi-Borg/Mod2-ProjectRepo/blob/main/Images/1M2Chllg_Loan_Qualifier_2022-04-03%20150028.png?raw=true) 

![Loan Qualifier Prompts](https://github.com/digi-Borg/Mod2-ProjectRepo/blob/main/Images/2M2Chllg_Loan_Qualifier_2022-04-03%20154502.png?raw=true)

After specifying the file location the user can retrieve it to review the returned qualifying_loans.csv list with the applicant and share the list of banking lenders willing to underwrite the loan. This will help the user assist the applicant in the decision making process to choose the best loan.  

![Loan Qualifier Prompts](https://github.com/digi-Borg/Mod2-ProjectRepo/blob/main/Images/M2Chllg_1qualifying_loans.csv%202022-04-05%20180056.png?raw=true) 

---

## Contributors

*Provided to you by digi-Borg FinTek*, 
Dana Hayes: nydane1@gmail.com

---

## License

When you share a project on a repository, especially a public one, it's important to choose the right license to specify what others can and can't with your source code and files. Use this section to include the license you want to use. 

Columbia U. Engineering
