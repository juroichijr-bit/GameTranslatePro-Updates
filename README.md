# Game Translate Pro — Updates

Public distribution of Windows application releases only. The source repository remains private.

The application checks the [latest release](https://github.com/juroichijr-bit/GameTranslatePro-Updates/releases/latest) for `GameTranslatePro-Windows11.zip` and its `.sha256` checksum.

Releases are published from the private source repository by a manually approved GitHub Actions run. The build workflow requires a fine-grained token with **Contents: Read and write** access to this distribution repository, stored as `GTP_RELEASE_TOKEN` in the private repository's Actions secrets. Never commit or share this token.

**Security:** A checksum detects corruption but does not independently authenticate the publisher. Only publish builds you have tested. Windows may require the application to be placed in a writable installation directory for in-place updates; a signed installer is preferable for production.
