# Safe Assessment Chain – Securing Examinations with Blockchain & AI

# Overview

The Safe Assessment Chain is an innovative system that enhances examination security using blockchain technology and computer vision. It tackles issues like cheating, identity fraud, and result manipulation by integrating Ethereum smart contracts and AI-powered facial recognition for authentication and monitoring.  

# Key Features

- Blockchain-Powered Security – Uses Ethereum smart contracts to maintain tamper-proof examination records.  
- AI-Based Facial Recognition – Ensures secure identity verification and real-time exam monitoring.  
- Decentralized Exam Management – Streamlines registration, attendance, and result processing securely.  
- Scalability – Adaptable for small and large-scale examination systems.  



# Project Structure  

# Directories & Files  

- `static/` – Contains static files like CSS, JavaScript, and images.  
- `templates/` – Stores HTML templates for the web interface.  
- `StudReg.sol` – Smart contract for student registration.  
- `ExamAdd.sol` – Smart contract for exam creation and management.  
- `UserAuth.sol` – Handles user authentication and roles.  
- `TransactionHandler_abi.json` – ABI file for blockchain communication.  
- `TransactionHandler_bytecode.txt` – Bytecode used for blockchain transactions.  
- `app.py` – Flask-based backend for handling application logic.  
- `config.py` – Configuration settings for Flask and blockchain integration.  
- `database.db` – SQLite database for storing supplementary data.  
- `requirements.txt` – List of required Python libraries.  

# Prerequisites  

Ensure you have the following installed before running the project:  

1. Python (Version 3.9 or later) 
2. Node.js & npm – Required for smart contract interaction.  
3. Ethereum Development Tools – Install Ganache and Truffle to set up a local blockchain.  
4. Python Dependencies – Install via `requirements.txt`:  

   ```bash
   pip install -r requirements.txt
   ```  

# Setup & Deployment  

# 1. Clone the Repository  

```bash
git clone https://github.com/ishan22399/Safe-Assessment-Chain.git  
cd Safe-Assessment-Chain  
```  

# 2. Set Up Blockchain Environment

1. Start Ganache – Launch a local Ethereum blockchain.  
2. Deploy Smart Contracts** – Use **Remix IDE** to deploy:  
   - `StudReg.sol` (Student Registration)  
   - `ExamAdd.sol` (Exam Management)  
   - `UserAuth.sol` (Authentication & Roles)  

# 3. Configure & Run the Application  

```bash
python app.py  
```  

Access the web interface at: http://127.0.0.1:5000 

