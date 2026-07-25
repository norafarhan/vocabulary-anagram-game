# Vocabulary Anagram Game

An interactive vocabulary game built with Flask and AJAX that helps English language learners practice vocabulary by forming words from a randomized letter jumble. The application validates guesses in real time without requiring page reloads, creating a more responsive user experience.

---

## Table of Contents

- Features
- How It Works
- Why I Built It
- Tech Stack
- Installation
- Usage
- Future Improvements

---

## Features

- Interactive vocabulary anagram game
- Real-time word validation using AJAX
- Randomized letter jumble generation
- Tracks correctly identified vocabulary words
- Flask backend with JSON responses
- Automated unit tests for core functionality

---

## How It Works

1. A vocabulary list is loaded when the application starts.
2. A randomized jumble of letters is generated from selected vocabulary words.
3. Users type words that can be created from the jumble.
4. AJAX requests validate each guess in real time.
5. Correct words are added to the solved list until the puzzle is completed.

---

## Why I Built It

This project was developed to gain experience building interactive web applications using Flask and AJAX. It strengthened my understanding of asynchronous client-server communication, JSON APIs, session management, and backend application development while creating an engaging educational application.

---

## Tech Stack

### Backend
- Python
- Flask

### Frontend
- HTML
- CSS
- JavaScript
- AJAX (jQuery)

### Testing
- Nose

### Tools
- Docker
- Git

---

## Installation

```bash
git clone https://github.com/YOUR_USERNAME/vocabulary-anagram-game.git
```

Install dependencies:

```bash
pip install -r requirements.txt
```

Run the application:

```bash
python flask_vocab.py
```

---

## Usage

1. Open the application in your browser.
2. Review the randomized letter jumble.
3. Enter words created from the available letters.
4. Continue discovering vocabulary words until the puzzle is complete.

---

## Future Improvements

- Multiple difficulty levels
- User authentication and score tracking
- Timer and leaderboard
- Expanded vocabulary categories
- Mobile-friendly interface
- Accessibility improvements
