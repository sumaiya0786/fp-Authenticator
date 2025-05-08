# fp-Authenticator


This is a simple frontend demo that uses the **WebAuthn (Web Authentication API)** to allow users to register and log in using their fingerprint or device's biometric feature.

 Features

- Register user with email and username
- Create and store fingerprint credential (in browser memory)
- Login using fingerprint
- Displays list of registered users (on screen only)

 Technologies Used

- HTML5
- CSS (Bootstrap)
- JavaScript (WebAuthn API)

 How It Works

1. User enters email and username, clicks "Register Fingerprint".
2. Browser prompts for fingerprint/biometric access.
3. Credential is created and stored temporarily in memory.
4. For login, user enters email and system verifies fingerprint.
5. Successful login shows confirmation.

 Limitations

- This demo does not store credentials permanently.
- No real backend — all data is stored in browser memory during the session.
- For production use, implement a secure backend to handle credential storage and verification.

 License

This project is licensed under the MIT License.
