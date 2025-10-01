# btc-multi-address-sending
This project is a frontend for sending transactions to multiple Bitcoin/Ordinal addresses, developed using Next.js.
It utilizes PSBT (Partially Signed Bitcoin Transactions) for transaction management, handles UTXOs (Unspent Transaction Outputs), and supports Ordinals/inscriptions. Below is a detailed README to guide you through understanding, setting up, and using the project.

## Introduction
This project offers a web application for sending Bitcoin and Ordinals to multiple addresses, built using the modern Next.js framework. It focuses on efficiently managing multiple addresses and UTXOs, ensuring secure transaction signing through PSBT, while providing a seamless user experience.

## Features
- **Next.js:** A fast and scalable React framework.
- **PSBT (Partially Signed Bitcoin Transactions):** Used for creating and managing secure transactions.
- **UTXO Management:** Efficient tracking and utilization of UTXOs for transactions.
- **Ordinals/Inscription:** Support for Bitcoin Ordinals and inscriptions.
- **Multiple Address Handling:** Enables sending transactions to multiple addresses from a single source.
- **Testnet Support:** Available for development and testing purposes.
- **Secure Environment Configuration:** Sensitive information is stored securely using `.env` files.

## How to run
Start the development server
```
npm run dev
# or
yarn dev
```

### Creating and Sending a Transaction:
- Generate addresses at the specified endpoint.
- Enter the recipient addresses and corresponding amounts.
- Use PSBT to create and sign the transaction.
- Broadcast the signed transaction to the Bitcoin network.

### Managing UTXOs:
- View all available UTXOs.
- Select UTXOs to create transactions, optimizing for fees and efficiency.

### Ordinals/Inscription:
- Track and manage Ordinals.
- Ensure proper integration of inscriptions into the transaction process.


## Contact Info
### Contact Info

LinkedIn: [@Dias Ishbulatov](https://www.linkedin.com/in/dias-ishbulatov/)

Telegram: [@Dias](https://t.me/@bitman09)

X: [@DiasIbt101](https://x.com/DiasIbt101)
