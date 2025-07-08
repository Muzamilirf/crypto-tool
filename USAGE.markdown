# Crypto Tool Usage Guide

This guide explains how to use the Crypto Tool, a web-based application for encrypting and decrypting text using AES encryption.

## Interface Overview
The tool features a clean, intuitive interface with the following components:
- **Secret Key Input**: A password field for entering the encryption/decryption key.
- **Text Input Area**: A textarea for the text to encrypt or decrypt.
- **Encrypt/Decrypt Buttons**: Buttons to perform encryption or decryption.
- **Output Area**: Displays the result of the operation.
- **Error Messages**: Shows feedback for invalid inputs or errors.

## Features and Controls
### Secret Key Input
- **Entering the Key**: Type your secret key in the password field.
- **Visibility Toggle**: Click the eye icon to show/hide the key.
- **Copy**: Click the copy icon to copy the key to your clipboard.
- **Paste**: Click the paste icon to paste a key from your clipboard.

### Text Input Area
- **Entering Text**: Type or paste the text you want to encrypt or decrypt.
- **Copy**: Click the copy icon to copy the input text.
- **Paste**: Click the paste icon to paste text from your clipboard.

### Encrypt/Decrypt
- **Encrypt**: Click the "Encrypt 🛡️" button to encrypt the input text using the secret key. The encrypted text appears in the output area.
- **Decrypt**: Click the "Decrypt 🔓" button to decrypt the input text using the same secret key. The decrypted text appears in the output area.

### Output Area
- **Result Display**: Shows the encrypted or decrypted text.
- **Copy**: Click the copy icon to copy the output text to your clipboard.

### Error Handling
- If the secret key or input text is empty, an error message appears: "Please enter both a secret key and text! 😔".
- If encryption fails, the message "Encryption failed. Try again! 😕" is shown.
- If decryption fails (e.g., wrong key or invalid text), the message "Decryption failed. Check key or text! 😕" is shown.

## Step-by-Step Instructions
### Encrypting Text
1. Enter a secret key in the "Secret Key" field.
2. Type or paste the text to encrypt in the "Text to Encrypt/Decrypt" area.
3. Click the "Encrypt 🛡️" button.
4. The encrypted text will appear in the output area.
5. Click the copy icon in the output area to copy the encrypted text.

### Decrypting Text
1. Enter the same secret key used for encryption in the "Secret Key" field.
2. Paste or type the encrypted text in the "Text to Encrypt/Decrypt" area.
3. Click the "Decrypt 🔓" button.
4. The decrypted text will appear in the output area.
5. Click the copy icon in the output area to copy the decrypted text.

### Copy/Paste Features
- **Secret Key**: Use the copy/paste icons to manage the key.
- **Input Text**: Use the copy/paste icons in the textarea for quick text management.
- **Output**: Copy the result for use elsewhere.

## Tips
- Use a strong, memorable secret key to ensure security.
- Store encrypted text securely, as it can only be decrypted with the correct key.
- The tool runs client-side, so no data is sent to a server.
- Ensure your browser supports the Clipboard API for copy/paste functionality (modern browsers like Chrome, Firefox, and Edge do).

## Troubleshooting
- **Copy/Paste Not Working**: Ensure you're using a secure context (HTTPS or localhost). Some browsers restrict clipboard access otherwise.
- **Decryption Fails**: Verify the secret key matches the one used for encryption and the input text is valid encrypted text.
- **No Output**: Check for error messages and ensure both inputs are filled.

## Author
Muzamil Ahmad  
[LinkedIn](https://www.linkedin.com/in/muzamilirf/)