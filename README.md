# link-lock

Link Lock is a tool to password-protect URLs by securely encrypting them with AES in the browser. Specifically, it encrypts with AES in Galois Counter Mode (GCM) and uses PBKDF2 and 100,000 iterations of SHA256 for key derivation. Encrypted data is then stored in the URL fragment, rather than on an external server.

## Contributing

Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

Please make sure to update tests as appropriate.
