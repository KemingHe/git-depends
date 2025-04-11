# 🎮 Arnab's CSE 3241 Game Show! 🎮

This is a self-hosted version of Dr. Arnab Nandi's "vibe coding" work for database education.

## 🧠 About the Original

Dr. Nandi created this with Claude 3.7 Sonnet as a practical example of his research on LLMs in database education. His work explores how AI tools can enhance learning rather than replace it. This game show demonstrates LLMs' potential to create engaging educational tools while preserving pedagogical value. Learn more via [Vibe Coding](https://www.linkedin.com/pulse/vibe-coding-learning-tools-rapidly-curating-classroom-arnab-nandi-vuslc/) or read his [full paper](https://arnab.org/files/Nandi_DataEd24_Integrating_LLMs_into_Database_Systems_Education.pdf) on integrating LLMs into database systems education.

## ✨ Features

- Interactive quiz with real-time feedback and scoring
- CSV-based question bank for easy customization
- Game show-inspired UI with colorful animations
- **NEW!** "Try Demo" feature to instantly load CSE 3241 database questions
- Footer with attribution and direct GitHub repository link

## 📁 Files

- [`index.html`](index.html) - The main application with all HTML, CSS, and JavaScript
- [`questionbank.csv`](./questionbank.csv) - Database systems multiple-choice questions with explanations

## 🚀 Usage

There are two ways to use this application:

### Quick Start

1. Open `index.html` in any browser
2. Click the "Try Demo 🚀" button to instantly load the CSE 3241 question bank

### Custom Questions

1. Open `index.html` in any browser
2. Upload your own question bank CSV with the format:

   ```csv
   Question,Option A,Option B,Option C,Option D,Correct Answer,Comment A,Comment B,Comment C,Comment D
   ```

3. Click "Start Game Show!" to begin
4. Answer questions to earn points

## 💻 Recent Updates

- Added "Try Demo" feature for instant access to sample questions
- Implemented two-column layout for better user experience
- Added footer with proper attribution and links
- Fixed CSV loading functionality

## ⚖️ License

This project is licensed under the Apache License 2.0 - see the [LICENSE](./LICENSE) file for details.

Copyright 2025 Arnab Nandi and Keming He
