📖 ChapterLens

A lightweight readability assistant for authors

ChapterLens is a free, browser-based writing tool that helps authors quickly identify sentences that may be difficult for readers to understand.

Instead of manually checking an entire chapter, an author can paste their text into ChapterLens and immediately get a readability overview and the five hardest sentences highlighted.

«Built as a rapid AI-assisted product prototype.»

---

🚀 Live Demo

Live Demo: [Add your GitHub Pages link here]

---

🎯 Problem

Authors often receive feedback such as:

- “This paragraph is difficult to follow.”
- “This sentence is too complicated.”
- “The pacing feels slow here.”

However, identifying the exact sentences causing reading difficulty can require manual editing or expensive writing tools.

ChapterLens aims to provide a quick first-pass signal by showing authors where their text may be difficult to read.

---

💡 Solution

ChapterLens analyzes a pasted chapter and provides:

- 📊 Readability Score
- 🎓 Approximate Grade Level
- 📝 Word Count
- 📄 Sentence Count
- 📏 Average Words per Sentence
- 🔤 Estimated Syllable Count
- 🔎 Five Hardest Sentences
- 🟨 Highlighted Difficult Sentences

The author can then decide which sentences deserve another look.

---

✨ Key Features

1. Instant Analysis

The chapter is analyzed immediately in the browser without requiring an account or complicated setup.

2. Readability Score

ChapterLens uses a standard readability calculation to provide a quick indication of how easy the text may be to read.

3. Hardest Sentence Detection

Instead of only giving an overall score, the tool identifies the five sentences with the highest estimated reading difficulty.

4. Visual Highlighting

The identified sentences are highlighted directly in the chapter so the author can find them without manually searching.

5. Privacy-Friendly Design

The analysis happens locally in the browser.

The pasted chapter does not need to be sent to a backend server.

---

🧠 How It Works

The current prototype follows this basic flow:

Author pastes chapter
        ↓
Text is split into sentences
        ↓
Words and syllables are estimated
        ↓
Readability metrics are calculated
        ↓
Sentence difficulty is estimated
        ↓
Five hardest sentences are selected
        ↓
Difficult sentences are highlighted

---

📐 Readability Method

The prototype uses the Flesch Reading Ease formula to calculate the overall readability score.

It also estimates the Flesch-Kincaid Grade Level to provide a rough indication of the educational level required to understand the text.

These metrics are useful signals, but they should not be treated as a definitive measurement of writing quality.

---

🛠️ Technology Stack

Frontend

- HTML5
- CSS3
- JavaScript

Analysis

- JavaScript-based text processing
- Flesch Reading Ease
- Flesch-Kincaid Grade Level

Development

- GitHub
- GitHub Pages
- ChatGPT-assisted development

---

🤖 AI-Assisted Development

ChatGPT was used during development for:

- Product ideation
- Feature planning
- UI structure
- Initial implementation
- JavaScript logic
- Debugging
- Improving the sentence-difficulty approach
- Reviewing the product concept

The final prototype was tested and refined rather than blindly accepting generated code.

---

⚠️ Limitations

ChapterLens is intentionally a lightweight prototype and has several limitations.

Vocabulary estimation

The current version estimates syllables using a rule-based approach. This can be inaccurate for unusual words, names, abbreviations, or technical terminology.

Context

A readability formula cannot fully understand literary context, tone, irony, narrative style, or authorial intent.

Sentence difficulty

A mathematically complex sentence is not necessarily a bad sentence. The “hardest” sentences should therefore be treated as editing signals, not automatic recommendations to rewrite.

Language

The current prototype is primarily designed for English-language text.

---

🔍 What I Would Improve Next

If developed further, ChapterLens could include:

1. AI-powered explanations
   Explain why a sentence may be difficult.

2. Rewrite suggestions
   Offer multiple simpler alternatives while preserving the author's voice.

3. Writing-style preservation
   Detect the author's tone and avoid unnecessarily simplifying intentional literary writing.

4. Chapter comparison
   Compare readability across different chapters or drafts.

5. Progress tracking
   Show how readability changes between draft versions.

6. More accurate linguistic analysis
   Use NLP models instead of basic syllable estimation.

7. Exportable reports
   Allow authors and editors to export analysis results.

---

🎯 Product Philosophy

ChapterLens is not designed to tell authors how to write.

It is designed to help authors quickly discover where to look.

The final editorial decision should always remain with the writer.

---

📌 Project Status

Status: Working prototype

The current version focuses on validating the core idea:

«Can a simple tool help an author quickly identify potentially difficult sentences in a chapter?»

Future versions could expand this into a more complete AI-powered writing and editing assistant.

---

📄 License

This project is created as a prototype and learning project.
