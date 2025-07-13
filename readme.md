# Bitcoin Wallet Educational Demo in PHP

This repository provides a step-by-step, well-commented PHP script that demonstrates how Bitcoin seed phrases (mnemonics), seeds, root keys, and addresses are generated according to the BIP39 and BIP32 standards.

The code is written for educational purposes, with a focus on clarity and conceptual understanding. Each step is explained in detail, making it ideal for students, developers, and anyone interested in how Bitcoin wallets work under the hood.

---

## Features

- **BIP39 Mnemonic Generation:**  
  Shows how entropy is converted into a mnemonic phrase (seed phrase) using the official BIP39 wordlist.

- **BIP39 Seed Derivation:**  
  Demonstrates how the mnemonic is turned into a binary seed using PBKDF2.

- **BIP32 Root Key Derivation:**  
  Explains how the BIP32 root (master) key is derived from the seed.

- **Bitcoin Address Generation:**  
  Walks through the process of generating a Bitcoin address from the root key.

- **Step-by-Step Output:**  
  Each step prints intermediate values and explanations, making it easy to follow the process.

---

## Usage

1. **Clone the repository:**
    ```sh
    git clone https://github.com/yourusername/php-bitcoin-wallet-demo.git
    cd php-bitcoin-wallet-demo
    ```

2. **Run the script:**
    ```sh
    php php-bitcoin-wallet-demo.php
    ```

3. **Read the output:**  
   The script will print each step, showing how entropy is transformed into a mnemonic, seed, root key, and address.

---

## Requirements

- PHP 7.0 or higher
- PHP extensions: `gmp`, `openssl`

---

## Security Warning

**This code is for educational and demonstration purposes only.**  
Do not use it to generate real wallets or store real funds.  
Never share or use the generated mnemonics, seeds, or private keys on mainnet or with real assets.

---

## References

- [BIP39: Mnemonic code for generating deterministic keys](https://github.com/bitcoin/bips/blob/master/bip-0039.mediawiki)
- [BIP32: Hierarchical Deterministic Wallets](https://github.com/bitcoin/bips/blob/master/bip-0032.mediawiki)
- [Mastering Bitcoin](https://github.com/bitcoinbook/bitcoinbook)
- [iancoleman.io/bip39](https://iancoleman.io/bip39/)

---

## License

MIT License

---

## Author

Hussain Sarfaraz  
(With educational improvements and suggestions by the open source community)

---

## Contributing

Pull requests and suggestions are welcome! If you have ideas for making the script even more educational or clear, please open an issue or PR.
