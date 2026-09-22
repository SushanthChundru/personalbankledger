# Personal Bank Ledger Statement Generator

A Java project for recording personal banking transactions and generating a clear ledger statement.

## Team Details

**Team No:** KLH/PSPJAVA/[Section]/[Team Number]

| S.No. | Student ID | Name |
|---|---|---|
| 1 | 2620030635 | Lohith |
| 2 | [Enter ID] | Mahesh |
| 3 | [Enter ID] | Sushanth |

**Supervisor:** Dr Sukanya Ledalla

## Abstract

The Personal Bank Ledger Statement Generator is a Java-based project designed to help users record and organize their personal banking transactions. Maintaining records manually can take time and cause calculation mistakes. This project aims to provide a simple way to track money received, money spent, and the remaining account balance.

The application is designed to accept account details, an opening balance, and transaction information. Each transaction includes a date, description, amount, and type, such as a deposit or withdrawal. A deposit increases the balance, while a withdrawal decreases it. The balance is calculated after every transaction so users can clearly follow changes in their account.

The main purpose of the project is to generate an organized ledger statement. This statement will show the opening balance, individual transactions, total deposits, total withdrawals, and closing balance. Displaying the balance after each transaction helps users understand their financial activity and identify possible entry mistakes.

The proposed application will validate entries to prevent invalid amounts and withdrawals that exceed the recorded balance. File handling will allow transaction records to be saved and viewed later. Simple menu options will guide users through recording transactions, viewing their balance, and generating statements.

This project applies Java concepts such as classes, objects, methods, conditional statements, loops, and file handling. It aims to reduce manual work and help users maintain clear personal financial records. The generated statement is intended for personal tracking and is not an official bank-issued statement.

## Objectives

- Maintain transaction records in one place.
- Calculate the balance after each transaction.
- Reduce manual calculation errors.
- Generate an easy-to-read ledger statement.
- Save transaction records for future reference.

## Planned Features

- Enter account holder details and opening balance.
- Record deposits and withdrawals.
- View transaction history and current balance.
- Generate a statement with transaction totals.
- Validate transaction amounts.
- Save and load records using files.

## Technologies

- **Programming Language:** Java
- **Interface:** Console-based menu
- **Storage:** Local files
- **Version Control:** Git and GitHub

## Project Structure

| File or Folder | Purpose |
|---|---|
| `README.md` | Project overview and instructions |
| `src/PersonalBankLedger.java` | Main Java source file |
| `docs/` | Project documentation |
| `data/` | Saved transaction records |
| `results/` | Sample outputs and screenshots |
| `reports/` | Project reports |

## How It Works

1. Enter the account details and opening balance.
2. Choose an option from the menu.
3. Enter a deposit or withdrawal with its details.
4. The application checks the entry and updates the balance.
5. View transaction history or generate a ledger statement.
6. Save the records for later use.

**Balance calculation:**

Closing Balance = Opening Balance + Total Deposits − Total Withdrawals

## Execution Instructions

Install the Java Development Kit (JDK).

Open a terminal in the project folder and run:

```bash
cd src
javac PersonalBankLedger.java
java PersonalBankLedger
```

The public class in `PersonalBankLedger.java` must be named `PersonalBankLedger`.

## Sample Ledger

The following example starts with an opening balance of ₹1,000.

| Date | Description | Deposit (₹) | Withdrawal (₹) | Balance (₹) |
|---|---|---:|---:|---:|
| 01-09-2026 | Opening balance | — | — | 1,000 |
| 02-09-2026 | Money received | 2,000 | — | 3,000 |
| 03-09-2026 | Books purchased | — | 500 | 2,500 |
| 04-09-2026 | Travel expenses | — | 200 | 2,300 |

**Total Deposits:** ₹2,000  
**Total Withdrawals:** ₹700  
**Closing Balance:** ₹2,300

## Git Commands

Run these commands from the main project folder:

```bash
git init
git add .
git commit -m "Initial project commit"
git branch -M main
```

After creating an empty repository on GitHub, replace the placeholders below and run:

```bash
git remote add origin https://github.com/YOUR-USERNAME/YOUR-REPOSITORY.git
git push -u origin main
```

## Future Improvements

- Search transactions by date.
- Group expenses into categories.
- Export statements as PDF or CSV.
- Add a graphical user interface.
