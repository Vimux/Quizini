# Quizini

**Quizini** (Quiz mini) — simple quiz app built on Vue.js 2.

**Nothing interesting, just my learning project.**

## Build Setup

```bash
# Install dependencies
npm install

# Run dev server with hot reload at localhost:8080
npm run dev

# Build for production with minification
npm run build
```

## data.json example

```json
{
  "questions": [
    {
      "question": "What is the name of the galaxy of which our sun is a member?",
      "type": "radio",
      "correct": 2,
      "answers": [
        "Sunflower Galaxy",
        "Cigar Galaxy",
        "Milky Way Galaxy",
        "Comet Galaxy"
      ]
    },
    {
      "question": "What does the 'e' of e-mail stand for?",
      "type": "input",
      "correct": "electronic"
    },
    {
      "question": "Michael Jordan's nicknames?",
      "caption": "Mark all that apply",
      "type": "checkbox",
      "correct": [0,2,3],
      "answers": [
        "Air Jordan",
        "Black Dog",
        "Black Cat",
        "His airness"
      ]
    },
    {
      "question": "What do you want if you send an S.O.S. signal?",
      "type": "radio",
      "correct": 1,
      "answers": [
        "Back-up",
        "Help",
        "Digital Television"
      ]
    },
    {
      "question": "What does CD stand for?",
      "type": "radio",
      "correct": 2,
      "answers": [
        "Capacity Disk",
        "Copyable Disk",
        "Compact Disc",
        "Circular Disk"
      ]
    },
    {
      "question": "Joseph Barbera and William Hannah created which cat and mouse duo?",
      "type": "radio",
      "correct": 3,
      "answers": [
        "Mickey and Minnie",
        "James and Jerry",
        "Tom and Mickey",
        "Tom and Jerry"
      ]
    },
    {
      "question": "Which Italian great mind, who made improvements to the telescope, is known as the 'father of modern science'?",
      "type": "radio",
      "correct": 1,
      "answers": [
        "Venturi",
        "Galileo",
        "Rubia",
        "Galvani",
        "Leonardo da Vinci"
      ]
    }
  ]
}
```