# app-english - Children's English Learning Game

## Overview
An interactive web-based educational game designed for 6-year-old children to learn English vocabulary. The app teaches words through flashcards and quizzes with a motivational reward system.

## Tech Stack
- **Type**: Static Single-Page Application
- **Technologies**: HTML5, CSS3, Vanilla JavaScript
- **Styling**: Bootstrap 5, Google Fonts (Baloo 2)
- **Hosting**: Any static web host (no backend required)

## Project Structure
```
app-english/
├── index.html      # Complete application (single file)
└── gemini.md       # Project documentation
```

## Key Features
- **Learning Mode**: Flashcards with images, Lithuanian/English words, and audio pronunciation
- **Game Mode**: Quiz to match Lithuanian words with English translations
- **Reward System**: Stars (points) earned for correct answers, 60 virtual prizes to purchase
- **Streak Bonuses**: Confetti effects for consecutive correct answers
- **Progress Persistence**: LocalStorage saves user progress

## Content
18 lesson categories with 150+ words:
- Animals, Colors, Numbers, Food, Family, Body parts
- Pronouns, Sentences, Transport, Clothes, School, Toys
- Home, Nature, Vegetables, Verbs, Emotions, Professions

## Development Notes
- Touch-friendly UI optimized for tablets
- Cartoon-style design with large buttons and bold fonts
- All code contained in single `index.html` file
- No build process required - edit and deploy directly

## Deployment
Simply upload `index.html` to any web hosting service.
