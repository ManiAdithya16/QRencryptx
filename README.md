QRCryptX: Secure File Sharing
QRCryptX is a Flask-based web application for secure file sharing using AES-256 encryption and QR codes. It allows users to encrypt files, generate a QR code with file details, and provide a decryption key for recipients to download the original file.

Features
AES-256 Encryption: Encrypts files up to 100MB.

QR Code Sharing: Generates QR codes containing file ID and filename for easy sharing.

File Decryption: Decrypts files using a File ID, Decryption Key, and original Filename.

QR Scanner: Browser-based QR code scanner to auto-fill decryption details.

Automatic Cleanup: Removes old encrypted files and QR codes after 24 hours.

Technologies
Backend: Flask, PyCryptodome, qrcode, Pillow.

Frontend: HTML, CSS, JavaScript, Bootstrap, Html5-qrcode.

Installation & Run
Install dependencies: pip install -r requirements.txt.

Run: python main.py.

The app runs on http://0.0.0.0:5000.

Usage
Encrypt: Visit the homepage (/), upload a file, and receive a QR code, File ID, and Decryption Key.

Decrypt: Go to /decrypt, scan the QR code or manually enter details, and download the decrypted file.
