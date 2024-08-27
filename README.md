# ATM Simulation in Java

This Java project simulates an ATM system, offering functionalities like balance inquiry, cash withdrawal, cash deposit, PIN change, and transaction history.

## Features

- **Balance Inquiry:** View current account balance.
- **Cash Withdrawal:** Withdraw funds, ensuring a minimum withdrawal amount and sufficient balance.
- **Cash Deposit:** Deposit funds with a minimum deposit requirement.
- **PIN Change:** Securely update your account PIN.
- **Transaction History:** View all transaction details.

## Getting Started

### Prerequisites

- **Java Development Kit (JDK):** Download from [Oracle's website](https://www.oracle.com/java/technologies/javase-jdk11-downloads.html).

### Running the Application

1. **Clone the repository:**

   ```bash
   git clone https://github.com/your-username/atm-simulation-java.git
   cd atm-simulation-java

1. **Compile the Java files:**

   javac ATMSimulation.java
   
1. **Run the ATM Simulation:**

   java ATMSimulation
   
## Menu Options

**1. Balance Inquiry:** Displays account balance.
**2. Cash Withdrawal:** Withdraw funds if minimum amount is ₹100 and balance is sufficient.
**3. Cash Deposit:** Deposit funds, minimum ₹100.
**4. PIN Change:** Update PIN after validation.
**5. Transaction History:** View transaction history.
   
## Security

Default PIN: Set to 4353.
PIN Validation: Required for all operations.

## Future Enhancements

Support for multiple accounts
Persistent data storage
Enhanced security features
