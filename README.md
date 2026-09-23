# Personal Bank Ledger Statement Generator



## Team Details

**Team No:** KLH/PSPJAVA/[Section]/[Team Number]

| S.No. | Student ID | Name |
|---|---|---|
| 1 | 2620030635 | Lohith |
| 2 | 2620030552 | Mahesh |
| 3 | 2620090074 | Sushanth |

**Supervisor:** Dr Sukanya Ledalla

## Abstract

The Personal Bank Ledger Statement Generator is a Java-based project designed to help users record and organize their personal banking transactions. Maintaining records manually can take time and cause calculation mistakes. This project aims to provide a simple way to track money received, money spent, and the remaining account balance.

The application is designed to accept account details, an opening balance, and transaction information. Each transaction includes a date, description, amount, and type, such as a deposit or withdrawal. A deposit increases the balance, while a withdrawal decreases it. The balance is calculated after every transaction so users can clearly follow changes in their account.

The main purpose of the project is to generate an organized ledger statement. This statement will show the opening balance, individual transactions, total deposits, total withdrawals, and closing balance. Displaying the balance after each transaction helps users understand their financial activity and identify possible entry mistakes.

The proposed application will validate entries to prevent invalid amounts and withdrawals that exceed the recorded balance. File handling will allow transaction records to be saved and viewed later. Simple menu options will guide users through recording transactions, viewing their balance, and generating statements.

This project applies Java concepts such as classes, objects, methods, conditional statements, loops, and file handling. It aims to reduce manual work and help users maintain clear personal financial records. The generated statement is intended for personal tracking and is not an official bank-issued statement.


## Project Structure

| File or Folder | Purpose |
|---|---|
| `README.md` | Project overview and instructions |
| `src/PersonalBankLedger.java` | Main Java source file |
| `docs/` | Project documentation |
| `data/` | Saved transaction records |
| `results/` | Sample outputs and screenshots |
| `reports/` | Project reports |




## Execution Instructions



Open a terminal in the project folder and run:

```bash

javac PersonalBankLedger.java
java PersonalBankLedger
```




