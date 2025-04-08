💰 VaultX – A Custom Cryptocurrency on Python
VaultX is a self-built cryptocurrency developed using Python, designed to simulate real-world digital transactions with blockchain-backed transparency. It allows users connected to the network to send and receive VaultX coins, while maintaining a secure and tamper-proof ledger of all transactions.

🔍 Project Overview
This project is a minimal blockchain implementation where VaultX coins can be:

🔁 Transferred between peers connected to the network.

📜 Verified through a decentralized ledger maintained using blockchain principles.

🔐 Secured with cryptographic hashes to ensure no transaction can be altered once recorded.

🧰 Tech Stack
Component	Technology
Backend Logic	Python
API Interface	Flask
Testing	Postman
Blockchain Core	Custom implementation using SHA-256
⚙️ Features
🌐 Simulated peer-to-peer VaultX transactions

🔗 Blockchain structure with chaining of blocks via hashes

✅ Transaction validation and block mining logic

📦 Simple REST APIs for testing with Postman

🔄 Real-time chain synchronization on new blocks

🗃️ Project Structure
bash
Copy
Edit
├── blockchain.py       # Core blockchain and VaultX logic
├── app.py              # Flask application to expose API routes
├── postman_collection/ # Postman requests collection (optional)
├── requirements.txt
└── README.md
🚀 Getting Started
Prerequisites
Python 3.x installed

Postman (for sending requests)

Flask library
📌 Usage
Add a transaction: Use /add_transaction with sender, receiver, and amount.

Mine a block: Call /mine_block to add pending transactions to the blockchain.

View the chain: Use /get_chain to see the entire VaultX ledger.

Connect new nodes: /connect_node for simulating a decentralized network.

Ensure consistency: /replace_chain to maintain longest valid chain across nodes.

🙌 Author
Saksham Gupta

📜 License
This project is intended for learning and educational use only.

