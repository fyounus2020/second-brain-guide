# Building a Claude Second Brain

A passcode-protected setup guide for replicating a Claude Code + Obsidian
second-brain workflow.

The guide body is encrypted at rest with AES-256-GCM; the key is derived from
the passcode with PBKDF2-SHA256 (310,000 iterations). Only ciphertext is
published here. Decryption happens in the browser after the correct passcode
is entered, so the content is not recoverable from this repository's source.

If you were sent a link to this guide, you were also sent the passcode.
