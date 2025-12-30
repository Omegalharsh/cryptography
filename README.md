# cryptography
python test1.py encrypt_file <file_path>
python test1.py decrypt_file <encrypted_file>
python test1.py encrypt_text
python test1.py decrypt_text

🔐 Encryption Workflow
📝 Text Encryption

AES: Password → PBKDF2 → Fernet

DES: 8-character key → CBC Mode

RSA: Public Key Encryption

📂 File Encryption

Generates random AES key

Encrypts file data using AES

Encrypts AES key using RSA public key

Saves output as .cryptonix

⚠️ Important Notes

Always save the RSA private key shown after encryption

Losing the private key means permanent data loss

DES is included for educational purposes only

AES and RSA are recommended for real-world use

🎓 Use Cases

Academic cryptography projects

Cybersecurity demonstrations

Secure file sharing

Data protection learning tools

Encryption/decryption practicals

🧠 Technologies Used

Python

Cryptography (Fernet, RSA, PBKDF2)

PyCryptodome (DES)

Base64 Encoding

CLI-based UI with ANSI colors

📈 Future Enhancements

GUI version (Tkinter / PyQt)

Support for more algorithms (Blowfish, ChaCha20)

Key file import/export

Logging and audit reports

Cross-platform installer

👨‍💻 Author

Harsh Valani
Cybersecurity & Software Development Project

📜 License

This project is intended for educational and academic use.
Use responsibly and do not apply for illegal activities.
