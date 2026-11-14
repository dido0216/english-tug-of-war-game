# Magic Academy Tug of War

An interactive English tug-of-war game for Taiwanese junior high school (Grade 7) students.

Two wizard teams — **Azure Star** and **Crimson Phoenix** — answer English questions to pull the Crystal of Light toward their side. A correct answer pulls the crystal one step; a wrong answer passes the turn. The first team to pull the crystal into its rune circle wins.

## Play online

Once GitHub Pages is enabled for this repository (Settings → Pages → Deploy from branch `main`, folder `/ (root)`), the game is playable at:

https://dido0216.github.io/english-tug-of-war-game/

## Play offline

Download `index.html` and open it in Chrome or Edge. The game is a single self-contained file — no server, backend, or account is needed. It loads a web font when online and falls back to system fonts offline.

## Features

- Teacher setup: team names, character choice, game mode (Classic / Sudden Death / Time Attack), question category, and difficulty
- 58 original questions with student-friendly explanations: Be Verbs, Present Simple, Present Continuous, Pronouns & Possessives, Articles & Plurals, Prepositions, Question Words, Vocabulary, Sentence Ordering, Fun Translation (Chinese → English), and Spelling
- No repeated questions in a game, shuffled answer options, sound effects with a mute button
- Winner announcement with Play Again and Restart — no page refresh needed
- Responsive layout for desktop, tablet, and mobile / classroom projectors

## Adding your own questions

Open `index.html` in a text editor, find the `QUESTION_BANK` array in the script, and copy an existing question block. Keep the question, four options, correct answer, category, difficulty, and explanation fields filled in.

## Embedding in Google Sites

1. Copy the GitHub Pages URL above.
2. In Google Sites, choose **Insert → Embed → By URL**.
3. Paste the URL, insert it, and drag it to full width and a tall height.
4. Preview on desktop, tablet, and phone, then publish.
