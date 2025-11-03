🔐 Secure Messaging Application (RSA + Diffie-Hellman)

This project is a prototype secure messaging application developed for the CS285 Semester Project.
It demonstrates the use of Diffie-Hellman key exchange for secure shared key generation and RSA encryption/decryption for message confidentiality.

🧩 Features

🔑 Diffie-Hellman Key Exchange – Establishes a shared secret between client and server over an insecure channel.

🔐 RSA Encryption & Decryption – Ensures messages are encrypted using RSA public/private key pairs.

✉️ Secure Messaging – Client and server exchange encrypted messages through socket communication.

🧾 Optional Signing – Messages can be signed using RSA or the shared secret to verify integrity.

🧠 Client-Server Architecture – Clear separation between client and server processes.

⚙️ System Architecture

Server

Generates RSA public/private keys.

Performs Diffie-Hellman key exchange.

Decrypts and verifies incoming messages.

Client

Performs Diffie-Hellman key exchange.

Uses the server’s RSA public key to encrypt messages.

Sends encrypted messages to the server.

🧪 Prototype Testing

✅ Key Exchange: Verify that both client and server derive the same shared secret.
✅ RSA Functionality: Test encryption and decryption using the generated RSA keys.
✅ Message Integrity: (Optional) Sign messages using the shared secret or RSA private key.
