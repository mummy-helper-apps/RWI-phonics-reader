# RWI Phonics Fluency Reader — User & Parent Guide

The **Read Write Inc. (RWI) Phonics Fluency Reader** is an interactive web application designed to help Year 1 children develop quick word recognition, automaticity, and decoding fluency across all Read Write Inc. stages (Set 1.1 through Set 3).

Designed specifically for parents, teachers, and teaching assistants, this tool combines structured phonics progression with smart repetition technology to target reading hesitation and tricky words.

---

## 🌟 Key Features

- **Full RWI Stage Coverage**: Exercises covering Set 1.1 through Set 3 (speed sound vowels and complex graphemes).
- **Flexible Word Types**: Practice decodable **Green Words**, non-decodable **Red Words**, or **Alien (Nonsense) Words** to test decoding accuracy.
- **Smart Repetition Engine**: Automatically tracks child response times and errors to show struggle words more frequently in future sessions.
- **Parent Assessment Controls**: Simple one-tap buttons (or keyboard shortcuts) to mark words as **Fluent/Correct** or **Incorrect/Struggled**.
- **Child-Friendly Design**: High-contrast "day mode" text in dark navy blue (`#0f2042`), Sassoon-style typography (`Lexend`), and soft pastel card backgrounds aligned with phonics conventions.
- **Visual Phonics Helps**: Phonics sound dots and bars rendered beneath decodable words to support Fred-talking when needed.
- **Pronunciation Audio**: Built-in speech synthesis to demonstrate correct word pronunciation.
- **100% Private & Local**: All progress, timing, and mistake history are stored directly on your device (`localStorage`). No sign-up or internet required after loading.

---

## 🚀 How to Use the App

### Step 1: Configure Your Practice Session
When you open the app, you will land on the **Parent Setup** screen:

1. **Select RWI Stage / Set**: Tap the stage matching your child's current reading level (e.g., `Set 1.1` for initial single sounds up to `Set 3` for complex vowels like `ea`, `oi`, `ai`).
2. **Select Word Type**: Choose one of five practice modes:
   - **Option A (Green Words):** Real, decodable words (e.g., *mat*, *cat*, *play*).
   - **Option B (Red Words):** Tricky, non-decodable sight words (e.g., *the*, *said*, *you*).
   - **Option C (Alien Words 🛸):** Nonsense words testing pure phonic decoding (e.g., *smat*, *fub*, *zigh*).
   - **Option D (Mix - Green & Red):** A balanced mix of decodables and tricky words.
   - **Option E (Full Mix):** Comprehensive challenge across Green, Red, and Alien words.
3. **Select Word Count**: Choose how many words to practice in this session (5, 10, 15, 20, or 25 words).
4. **Smart Repetition Engine Toggle**: Leave this checked (recommended) so words your child finds difficult appear more often.
5. Click **Start Practice Session**.

---

### Step 2: Running the Flashcard Session
During the session, place the device in front of your child while you control the assessment buttons:

1. **The Flashcard Displays**:
   - The card background color indicates the word category:
     - 💚 **Pastel Green**: Decodable Green Word
     - 🔴 **Pastel Red**: Tricky Red Word
     - 💙 **Pastel Blue**: Alien Word 🛸
   - Below decodable words, sound dots (•) and sound bars (━) show how the word breaks down phonetically.
2. **Audio Pronunciation**: Tap the speaker icon (🔊) or press the `Spacebar` to hear the word pronounced.
3. **Timing & Assessment**:
   - A live timer records how long the child takes to read the word out loud.
   - Click **Correct & Fluent** (Green button) if read smoothly.
   - Click **Incorrect / Struggled** (Red button) if the child made a mistake, hesitated significantly, or required help.

#### ⌨️ Keyboard Shortcuts for Parents (Desktop/Laptop):
- **Right Arrow (`→`)**: Mark Correct & Fluent
- **Left Arrow (`←`)**: Mark Incorrect / Struggled
- **Spacebar (`Space`)**: Hear Word Pronunciation

---

### Step 3: Session Summary & Feedback
When the session ends:
- A celebratory confetti effect rewards the child for finishing!
- You will see a quick summary:
  - **Accuracy Percentage**
  - **Average Time per Word**
  - **Total Correct Count**
- An itemized list breaks down each word presented, whether it was correct, and how many seconds it took to decode.

---

### Step 4: Tracking Progress in Parent Stats
Click **Parent Stats** in the top navigation bar at any time to view performance history:

- **Word History Table**: Displays every word practiced, attempt count, accuracy %, average response speed, and priority score.
- **Priority Score**: Words with lower accuracy or slower decoding speeds get higher priority scores, meaning the Smart Repetition Engine will include them more frequently in upcoming sessions.
- **Search & Filter**: Search for specific words or filter by RWI Stage.
- **Reset History**: Tap "Reset Local History" if you want to clear stored data and start fresh.

---

## 💡 Phonics Practice Tips for Parents

1. **Keep Sessions Short & Frequent**: Two 5-minute sessions a day (10 words each) build automaticity faster than one long session.
2. **Encourage "Fred Talk in Your Head"**: For Green and Alien words, encourage your child to say the sounds silently before blending out loud.
3. **Remind Them About Red Words**: Remind children that Red Words are "tricky" and cannot be Fred-talked—they need to be recognized by sight!
4. **Praise Effort, Not Speed**: Focus praise on trying hard to blend sounds accurately; fluency naturally follows accuracy.

---

## 🛠️ Technical Overview

- **Format**: Single-file HTML5 web application (`index.html`).
- **Dependencies**: Tailwind CSS (via CDN), Canvas Confetti (via CDN), Google Fonts (`Lexend`, `Comic Neue`, `Fredoka`).
- **Offline Compatibility**: Once loaded in a browser, works offline without active internet.
- **Data Privacy**: No analytics trackers, no server communication, no accounts required. All data remains on the user's browser.