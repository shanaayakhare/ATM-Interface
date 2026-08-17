# ATM Interface — Banking Application & Cell-Switching Simulation

A C++-based banking ATM simulation that models common ATM operations such as **withdrawal, deposit, and balance inquiry**. The project also implements a simplified **connection-oriented cell-switching model** to simulate how transaction requests can be routed and processed through different system components.

---

## 📌 Project Overview

This project was developed to simulate the workflow of an ATM banking application while applying concepts from:

- Object-Oriented Programming
- Data Structures
- Transaction Processing
- Basic Computer Networking
- Cell Switching
- Randomized Testing

Each banking request is represented as a **transaction cell** containing information such as the account ID, transaction type, amount, source, and destination.

The transaction follows the workflow:

```text
ATM Request
     ↓
Transaction Cell Creation
     ↓
Transaction Queue
     ↓
Cell Switch / Routing
     ↓
Transaction Processor
     ↓
Account Operation
     ↓
Transaction Result
     ↓
Transaction Log
