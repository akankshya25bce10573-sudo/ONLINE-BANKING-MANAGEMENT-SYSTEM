PROBLEM STATEMENT:

Traditional, manual banking processes are time-consuming, prone to human error, and require customers to physically visit a branch for basic transactions.
Managing a ledger of accounts (creation, deposits, withdrawals, and closure) manually is inefficient and lacks real-time accuracy, making it difficult to scale and provide timely customer service. 
A lack of an organized, digital system leads to poor data integrity and limits the bank's operational efficiency.
The core problem is the need for a simplified, digital, and accurate system to manage fundamental banking operations.

SCOPE OF THE PROJECT:

The project is focused on building the core transactional logic of a banking system, primarily managing the state and flow of money for individual accounts.
In Scope:
Account Management: Creating new accounts, generating unique account numbers, and closing existing accounts.
Core Transactions: Implementing logic for accurate deposits and withdrawals.
Querying: Functionality to check the current balance of any specific account.
Reporting: Ability to display a list of all active accounts and their current balances.
Validation: Basic checks for insufficient funds during withdrawal attempts and preventing transactions on closed accounts.
Data Persistence: Saving account data (e.g., to a local file or simple database like SQLite) so it persists between application sessions.

Out of Scope:
User Authentication/Security (Logins, Passwords).
Advanced Features (Loan processing, Interest calculation, Bill pay, Fund transfers between different banks).
Complex Reporting and Analytics.
Web or Mobile user interfaces (The primary interface will be a Command Line Interface (CLI)).

TARGET USERS:

Target User Group 
BANK OPERSTORS/CLERKS: Day-to-day management of customer accounts.
                       Fast, reliable tools for creating, depositing, withdrawing, and closing accounts.

 System Administrators: Maintaining data integrity and verifying system status.
                        A quick way to display and audit all active accounts and balances   

HIGH-LEVEL FEATURES:

The system MUST provide a function to create a new customer account, requiring a name and an initial deposit.
The system MUST be able to display the current balance when provided with a valid account number.
The system MUST allow the user to deposit funds into a specified account.
The system MUST allow the user to withdraw funds, provided the account has a sufficient balance.
The system MUST reject a withdrawal if it would result in a negative balance (Insufficient Funds).
The system MUST be able to list all active accounts, displaying their account number, name, and current balance.
The system MUST provide a function to permanently close a specified account.
