<h1 align="center">🎂 Little Gift for My Dishu</h1>

<p align="center">
  A tiny birthday surprise, made with a lot of love. ❤️
</p>

<p align="center">
  <a href="https://little-gift-for-my-dishu.vercel.app/">
    <strong>✨ Open the Live Website</strong>
  </a>
  &nbsp;&nbsp;·&nbsp;&nbsp;
  <a href="https://github.com/Hidden-Rhythm/little-gift-for-my-dishu">
    View Source
  </a>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/HTML5-E34F26?style=flat-square&logo=html5&logoColor=white" alt="HTML5">
  <img src="https://img.shields.io/badge/CSS3-1572B6?style=flat-square&logo=css3&logoColor=white" alt="CSS3">
  <img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black" alt="JavaScript">
  <img src="https://img.shields.io/badge/GSAP-88CE02?style=flat-square&logo=greensock&logoColor=white" alt="GSAP">
</p>

<br>

## 💌 The Idea

**Little Gift for My Dishu** is a small interactive birthday website built as a personal digital surprise.

Instead of being a simple birthday card, it turns the message into a short animated experience — starting with a greeting, moving through a story, and ending with a personalized birthday wish.

Everything is designed around one idea:

> **make something small that feels personal.**

---

## ✨ Features

| Feature               | Description                                       |
| --------------------- | ------------------------------------------------- |
| 🎂 Birthday Intro     | Personalized birthday opening sequence            |
| 💬 Animated Messages  | Messages appear through a scripted animation      |
| 💭 Chat-style Section | A playful conversation-style birthday message     |
| 📖 Story Sequence     | Multiple messages presented as an animated story  |
| ❤️ Personal Message   | A dedicated heartfelt section                     |
| 🖼️ Personal Image    | Custom image displayed during the final sequence  |
| 🎈 Floating Balloons  | Animated birthday balloons                        |
| 🎩 Birthday Hat       | Animated SVG birthday hat                         |
| 🎉 Birthday Animation | Large animated birthday greeting                  |
| 🔄 Replay             | Watch the entire experience again                 |
| ⚙️ Easy Customization | Main text can be changed through `customize.json` |

---

## 🎬 How It Works

```text
             ┌─────────────────┐
             │   Open Website  │
             └────────┬────────┘
                      │
                      ▼
             ┌─────────────────┐
             │ Birthday Intro  │
             └────────┬────────┘
                      │
                      ▼
             ┌─────────────────┐
             │ Animated Chat   │
             └────────┬────────┘
                      │
                      ▼
             ┌─────────────────┐
             │   Story Flow    │
             └────────┬────────┘
                      │
                      ▼
             ┌─────────────────┐
             │ Personal Message│
             └────────┬────────┘
                      │
                      ▼
             ┌─────────────────┐
             │ 🎈 Birthday End │
             └────────┬────────┘
                      │
                      ▼
             ┌─────────────────┐
             │      Replay     │
             └─────────────────┘
```

---

## 🎞️ Animation Sequence

The experience is driven by a GSAP timeline.

The animation roughly follows:

```text
Greeting
   ↓
Name
   ↓
Birthday Message
   ↓
Chat Box
   ↓
Animated Conversation
   ↓
Story Messages
   ↓
"Special"
   ↓
Personal Message
   ↓
S / O Animation
   ↓
Balloons
   ↓
Personal Image
   ↓
Birthday Hat
   ↓
Happy Birthday
   ↓
Final Wish
   ↓
Outro
   ↓
Replay
```

Each stage is controlled through the JavaScript animation timeline rather than requiring multiple pages.

---

## 🛠️ Built With

| Technology       | Purpose                               |
| ---------------- | ------------------------------------- |
| **HTML5**        | Page structure                        |
| **CSS3**         | Layout, typography and visual styling |
| **JavaScript**   | Content loading and interaction       |
| **GSAP**         | Animation timeline                    |
| **Patrick Hand** | Handwritten typography                |
| **SVG**          | Decorative birthday elements          |

---

## 📁 Project Structure

```text
little-gift-for-my-dishu/
│
├── 📄 index.html
├── 📄 customize.json
├── 📄 LICENSE
│
├── 📁 script/
│   └── main.js
│
├── 📁 style/
│   └── style.css
│
└── 📁 img/
    ├── ballon1.svg
    ├── ballon2.svg
    ├── ballon3.svg
    ├── dishu.png
    ├── favicon.png
    └── hat.svg
```

---

## ⚙️ Customization

Most of the displayed text is separated from the animation logic inside:

```text
customize.json
```

You can change values such as:

```json
{
  "greeting": "Huii",
  "name": "Dishu",
  "text1": "It's your birthday ˃ᴗ˂",
  "wishHeading": "Happy Birthday!"
}
```

The JavaScript automatically loads the configuration and inserts the values into the corresponding elements.

This makes it possible to personalize the experience without rewriting the animation logic.

---

## 🖼️ Changing the Image

The displayed image can also be changed through `customize.json`.

```json
{
  "imagePath": "img/dishu.png"
}
```

Place your image inside the `img/` directory and update the path accordingly.

---

## 🚀 Run Locally

Clone the repository:

```bash
git clone https://github.com/Hidden-Rhythm/little-gift-for-my-dishu.git
cd little-gift-for-my-dishu
```

You can open `index.html` directly in a browser.

For a local development server, you can also use Python:

```bash
python -m http.server 8000
```

Then open:

```text
http://localhost:8000
```

---

## 🔄 Replay

At the end of the experience, the replay option restarts the GSAP timeline.

No page reload is required — the animation simply starts again from the beginning.

---

## ❤️ Why This Exists

This isn't meant to be a huge project.

It's just a small corner of the internet made for someone special.

A few animations, a few messages, a little bit of code — and hopefully a smile at the end.

<br>

<p align="center">
  <strong>Made with ❤️ for Dishu.</strong>
</p>

<p align="center">
  <a href="https://little-gift-for-my-dishu.vercel.app/">
    ✨ <strong>Open the Gift</strong>
  </a>
</p>
