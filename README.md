# Q-Sports-AI Backup OAuth

Private-use Google OAuth application for the Q-Sports-AI owner's encrypted backup workflow.

## Purpose
The owner uses rclone to access their Google Drive and Restic to encrypt, upload, list, and restore Q-Sports-AI backup snapshots from their own server. This is not a public backup service.

## Data and security
- Google Drive access is used only to operate the owner's backup repository.
- Restic encrypts backup contents before uploading them.
- OAuth tokens, client secrets, Restic passwords, and backup files are not stored in this repository.
- The repository contains public-facing documentation only.

Read the [Privacy Policy](PRIVACY.md).

## Contact
For questions, contact the repository owner through GitHub.
