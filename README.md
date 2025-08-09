# AES-128 Implementation in Python

This project contains a Python implementation of the AES-128 block cipher, including key expansion, encryption, and decryption. It also features a basic implementation of the Cipher Block Chaining (CBC) mode for handling longer messages and padding/unpadding functions to ensure message blocks are the correct size.

---

## 🔐 Features

- Full implementation of **AES-128 encryption and decryption**
- Support for **key expansion (key schedule)**
- Predefined constants: S-Box, Inverse S-Box, and RCON
- Matrix-based transformations like **ShiftRows, MixColumns**, and their inverses
- Easy-to-read and modular Python functions

---
## 🧠 How It Works

AES-128 operates on a 4x4 byte matrix called the **state**. The encryption process consists of:

1. **AddRoundKey**
2. **SubBytes**
3. **ShiftRows**
4. **MixColumns**
5. Repeat for 10 rounds (with a slight variation in the final round)

Decryption performs the inverse of each step in reverse order.

---

## 🚀 Getting Started

1. Clone the repository or download the `.ipynb` file.
2. Open the notebook in Jupyter Notebook or VS Code.
3. Run the cells sequentially to execute AES encryption/decryption.
4. Modify the `plaintext` and `key` variables to test with your own inputs.

---

## 🛠️ Requirements

This project uses only Python’s standard libraries—no external packages required.

---

## 📜 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---

## 📚 References

- Cryptography and Network Security: Principles and Practices, 6th Edition- W. Stallings
