# ColdPath: Secure USB Protocol for Cold Wallets

## Vision
ColdPath is a protocol for securely transferring Bitcoin transactions between air-gapped wallets and full nodes using USB drives. It prioritizes privacy and security.

## MVP Objectives
- Secure transfer of Bitcoin transactions (PSBT) via USB drives.
- Cryptographic hash validation for file integrity.
- Integration with Bitcoin Core.

## Development Steps
1. Design the file structure for transaction data.
2. Implement file transfer validation using SHA-256.
3. Test air-gapped compatibility.
4. Document setup and usage instructions.

## Future Features
- Multi-signature transaction support.
- USB encryption for sensitive data.
