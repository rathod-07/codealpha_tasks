# 🎮 Hangman Game (Python) — CodeAlpha Task 1

[![Python Version](https://img.shields.io/badge/Python-3.x-blue.svg)](https://www.python.org/)
[![Internship](https://img.shields.io/badge/CodeAlpha-October%20Batch-orange.svg)](https://www.codealpha.tech/)

A robust, interactive command-line implementation of the classic *Hangman Game* built using Python. Developed as part of the *CodeAlpha Python Programming Internship*.

---

## 📌 Overview

The game challenges players to guess a hidden word letter-by-letter within 6 attempts. It features dynamic ASCII art graphics representing the hangman stages, secure random word selection, and comprehensive input validation to ensure a smooth user experience.

---

## ✨ Key Features

- *🔒 Secure Randomness:* Leverages Python's random.SystemRandom() to select secret words using operating system security.
- *🎨 Visual ASCII Progress:* Renders classic hangman stages corresponding to incorrect guess counts (0 through 6).
- *🛡️ Input Validation & Error Handling:* 
  - Prevents non-alphabetic inputs or multi-character entries.
  - Detects and alerts on duplicate letter guesses without penalizing attempts.
- *📊 Real-time Game State:* Displays current word progress (e.g., p y _ h o n), remaining attempts, and previously guessed letters.

---

## 🛠️ Project Architecture

```text
codealpha_tasks/
│
├── hangman.py          # Main executable Python script
└── README.md           # Documentation
