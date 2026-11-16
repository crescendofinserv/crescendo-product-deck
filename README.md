# Crescendo Finserv — Confidential Product Deck

This repository hosts the official, client-facing, password-protected interactive presentation for **Crescendo Finserv**.

## 🌐 Live Presentation Link
**[https://crescendofinserv.github.io/crescendo-product-deck/](https://crescendofinserv.github.io/crescendo-product-deck/)**

---

## 🔑 Access Details
- **Default Password**: `Crescendo2026` *(or `crescendo2026` — input is case and trailing-space insensitive)*
- **Security Standard**: AES-256-GCM encryption with PBKDF2 key derivation (100,000 iterations of SHA-256) via the native Web Crypto API.
- **Client Privacy**: The presentation content is stored exclusively as encrypted ciphertext. View Source or network inspection reveals zero slide data without entering the access code.
- **Session Auto-Unlock**: Keeps the deck unlocked across browser refreshes during client meetings via temporary `sessionStorage`.
- **Lock Deck Button**: Presenters can click the discreet **LOCK DECK** pill at the bottom-right corner at any time to re-lock the screen.

---

## 🛠 How to Update the Deck or Change Password
To update the slides or change the password, run:
```bash
python update_deck_and_password.py "YourNewPassword"
```
Or simply ask your Antigravity assistant.
