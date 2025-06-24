# Simple-Blockchain-Mining-Simulation-using-SHA-256
This project demonstrates a basic Proof-of-Work mining algorithm similar to how cryptocurrencies like Bitcoin perform mining. It uses the SHA-256 hash function to find a valid block hash that meets a specified difficulty level by brute-force searching over nonces.

# ⛏️ Simple Blockchain Mining Simulation

This is a beginner-friendly Python project that simulates **Proof-of-Work mining** using the **SHA-256** hashing algorithm. It mimics how Bitcoin and similar cryptocurrencies mine blocks by solving a computational puzzle.

---

## 🚀 Features

- 💡 Simple implementation of SHA-256 hashing.
- 🧱 Simulated block mining using nonce and transaction data.
- 🎯 Adjustable mining difficulty via leading zeros.
- ⏱️ Tracks mining time for performance testing.
- 📦 Minimal dependencies — pure Python standard libraries.

---

## 🧠 How It Works

1. **Inputs**: Block number, transactions, previous block's hash, and mining difficulty.
2. **Nonce Search**: Tries different nonce values to generate a SHA-256 hash.
3. **Target**: Finds a hash that starts with a given number of zeros (e.g., `00000` for difficulty 5).
4. **Output**: Prints the successful nonce, time taken, and resulting hash.

---

## 📄 Example Code Output

Start mining
Yay! Successfully mined bitcoins with nonce value: 15472
End mining. Mining took 3.94 seconds
00000a3b2c7f14e82e1a456bd3e60fe16ed63e6e8a1a5c9a4e69a3dbe912344c

🧩 Future Improvements (Optional Ideas)
Add multiple blocks (basic blockchain)

Include timestamps and block hashes

Add a transaction pool and validation

Implement Merkle Trees for transaction integrity

Simulate wallet addresses and balances

👨‍💻 Author
Made with ❤️ by Tharun


