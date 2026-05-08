# Deutsch Daily

Deutsch Daily is a single-page website for daily German practice. It focuses on one German sentence at a time, helping learners improve writing, listening, vocabulary, and pronunciation.

## Features

- Daily German sentence with English translation
- Pronunciation guide and browser voice playback
- Writing practice with spelling and sentence correction
- Voice practice with microphone-based pronunciation comparison
- Listen-and-write dictation exercise
- Vocabulary cards with saved words
- German dictionary tab with all lesson words and online lookup
- Progress tracking for streaks, completed sentences, writing score, and speaking score
- Light and dark mode
- Responsive layout for desktop and phone screens

## Run Locally

This project is a static HTML app. You can open `index.html` directly in a browser, but voice and microphone features work best from `localhost`.

Start a local server:

```bash
python3 -m http.server 8000
```

Open:

```text
http://127.0.0.1:8000/index.html
```

## Browser Notes

The app uses built-in browser APIs:

- `speechSynthesis` for reading German sentences aloud
- `SpeechRecognition` or `webkitSpeechRecognition` for microphone pronunciation checks
- `fetch` for German dictionary lookups through FreeDictionaryAPI.com, with local lesson fallback data
- `localStorage` for progress, saved words, and theme preference

For best results, use Chrome or Edge and allow microphone permission when prompted.

## Files

- `index.html` contains the full app: HTML, CSS, and JavaScript.
