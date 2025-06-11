# ADVANCED-ENCRYPTION-TOOL

COMPANY:CODTECH IT SOLUTIONS

NAME:LAVANYA MUDDAPATI

INTERN ID:CT08DN1958

DOMAIN:CYBER SECURITY

DURATION:8 WEEKS

MENTOR:NEELA SANTOSH

Task 4: ADVANCED-ENCRYPTION-TOOL Using AES-256 – Project Description

The primary objective of this project is to develop a fully functional Advanced Encryption Tool using the AES-256 algorithm in Python, complete with a Graphical User Interface (GUI). The application allows users to securely encrypt and decrypt files using a password of their choice. This project is especially relevant in today’s digital age, where data security and privacy have become critical concerns.
This tool is designed to help users protect their confidential files by using strong encryption mechanisms. It combines various core concepts from Python programming, such as file handling, GUI creation using Tkinter, and cryptographic operations using the PyCryptodome library. By completing this task, students gain hands-on experience with both front-end GUI development and back-end cryptographic logic.
 *About AES-256*
AES (Advanced Encryption Standard) is a symmetric block cipher that has become the standard for securing sensitive data. The “256” in AES-256 refers to the key length — 256 bits, making it highly secure and practically impossible to brute-force with current technology. It is widely used in sectors such as banking, government, and cloud storage.
AES operates by taking blocks of plaintext data and encrypting them into ciphertext using a secret key. In this project, the key is not directly typed in but is derived securely from a user-entered password using a key derivation function.
When the application is run, the user is greeted with a GUI window titled "Advanced Encryption Tool (AES-256)", which includes two main buttons:
Encrypt File
Decrypt File
Upon clicking Encrypt File, the user is prompted to choose a file from their system using a file dialog. After that, the user is asked to enter a password. The program then securely derives a 256-bit AES key from the password using PBKDF2 (Password-Based Key Derivation Function 2) with a random salt. This derived key is then used to encrypt the contents of the selected file. An Initialization Vector (IV) is also generated randomly to ensure that encrypting the same file with the same password produces different encrypted outputs.
The encrypted data is saved to a new file with a .enc extension, along with the salt and IV stored in the header of the file. A success message is displayed after encryption completes.
When the user clicks Decrypt File, the process is reversed. The encrypted file is selected, and the correct password must be entered. The tool reads the salt and IV from the file, regenerates the key using the same derivation method, and decrypts the file. The result is saved with a .dec extension and restored to its original form if the correct password was entered.
This task helps students learn several important technical skills and concepts:
Cryptographic Implementation: Use of AES encryption/decryption and PBKDF2 for password-based key generation.
Secure File Handling: Working with binary data and ensuring proper file write/read operations.
Randomization Techniques: Use of cryptographically secure random bytes for salt and IV generation.
User Input and GUI Design: Creating a user-friendly interface with Tkinter, including popup dialogs for file selection and password entry.
Error Handling: Gracefully managing incorrect passwords or corrupted files with error messages.
 Files Generated
example.txt → The original file
example.txt.enc → The encrypted output
example.txt.dec → The decrypted output after successful password entry
These files help validate the tool's correctness and are useful for submission as part of the output.
✅ Conclusion
This project is a strong demonstration of combining theory with practical implementation. It showcases how cryptography can be applied to real-world problems using programming skills. The use of AES-256 ensures strong data protection, while the GUI enhances accessibility for non-technical users.
The Advanced Encryption Tool is an excellent introduction to cybersecurity concepts like encryption, password hashing, and key management. It helps students build a foundation in secure software development and understand the critical importance of protecting digital data.

*OUTPUT*

![Image](https://github.com/user-attachments/assets/6d28af5d-c935-42c6-8f10-0e47a5ee0478)

![Image](https://github.com/user-attachments/assets/bcbc7c0b-cd79-408e-b4c5-72b485e29717)

![Image](https://github.com/user-attachments/assets/b7b47e0c-6fd3-475c-98a6-d6bf1b8a09df)

![Image](https://github.com/user-attachments/assets/8464a229-0b94-4ea4-b515-7b96f858a50b)


