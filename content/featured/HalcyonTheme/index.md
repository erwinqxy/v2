---
date: '1'
title: 'Agent Maverick '
cover: './Encryptionv2.png'
github: 'https://github.com/erwinqxy/lifehack22-PrBros'
external: 'https://devpost.com/software/steganography-encryption-bot?ref_content=user-portfolio&ref_feature=in_progress'
tech:
  - Python 
  - TelegramBot 
  - Encryption
  - Image Steganography
---

**Agent Maverick** is a Telegram bot that takes in a PNG (only) image alongside the secret message (ASCII characters) that the user intends to hide. We **encrypt** the secret message using **Caesar cipher**, then embed the ciphertext into the image provided via **image steganography**. The resultant image is then sent back to the user.