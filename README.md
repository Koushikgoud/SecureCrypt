
SecureCrypt: Secure Document Sharing Platform
SecureCrypt is a cutting-edge solution designed to address the critical need for secure document sharing in today's digital landscape. It combines robust encryption techniques with a user-friendly interface, leveraging the File Transfer Protocol (FTP) for efficient and secure data transmission.

Features:
Hybrid Encryption System: Utilizes AES, DES, Blowfish (symmetric encryption), and RSA (asymmetric encryption) to ensure the highest level of security for document transmission.

Model-View-Presenter Architecture: Enhances scalability, maintainability, and organization of the application.

Intuitive Graphical User Interface: Simplifies complex encryption and file transfer processes, making it accessible to users of varying technical backgrounds.


Installation and Setup
Clone the Repository:
git clone https://github.com/Koushikgoud/SecureCrypt.git

Navigate to the Project Directory:
cd SecureCrypt

Usage: Starting the FTP Server
Run the server command from the main directory:
python -m python_ftp_server -u "username" -p "password" --ip 0.0.0.0 --port 6060 -d "path/to/storage"

Launching the Client Application:
Open a new terminal and execute:
python run.py
Uploading and Downloading Files
Connect to the FTP server using the provided IP, port, username, and password. Follow the prompts in the client application to upload and download files securely.

Contributions:
SecureCrypt is a collaborative project developed as part of the Advanced Cryptography course at Kennesaw State University. Contributions, suggestions, and feedback are welcome.
