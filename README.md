<h1 align="center">🎂 Little Gift for My Dishu</h1>

<p align="center">
  <strong>A tiny birthday surprise, made with a lot of love.</strong>
  <br>
  An animated, interactive birthday webpage created specially for Dishu.
</p>

<p align="center">
  <a href="https://github.com/Hidden-Rhythm/little-gift-for-my-dishu">
    <img src="https://img.shields.io/badge/💻%20SOURCE-GitHub-18181B?style=for-the-badge&logo=github" alt="Source Code">
  </a>
  <img src="https://img.shields.io/badge/HTML5-E34F26?style=flat-square&logo=html5&logoColor=white" alt="HTML5">
  <img src="https://img.shields.io/badge/CSS3-1572B6?style=flat-square&logo=css3&logoColor=white" alt="CSS3">
  <img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black" alt="JavaScript">
  <img src="https://img.shields.io/badge/GSAP-88CE02?style=flat-square&logo=greensock&logoColor=white" alt="GSAP">
</p>

---

<h2 align="center">💌 The Idea</h2>

<p align="center">
  This isn't just a birthday webpage.<br>
  It's a small animated story made for one person.
</p>

<p align="center">
  <strong>From a simple "Huii Dishu" → to a whole little birthday surprise.</strong>
</p>

---

## ✨ What's Inside

|     | Feature                |                                                        |
| --- | ---------------------- | ------------------------------------------------------ |
| 🎂  | **Birthday Intro**     | Opens with a personalized greeting                     |
| 💬  | **Animated Messages**  | Messages appear one after another                      |
| ⌨️  | **Chat-style Section** | Birthday message with character-by-character animation |
| 💭  | **Story Sequence**     | A series of animated thoughts and messages             |
| 💖  | **Personal Message**   | A custom message written specifically for Dishu        |
| 🖼️ | **Personal Image**     | Uses a custom image from the `img` directory           |
| 🎈  | **Floating Balloons**  | Animated SVG balloons                                  |
| 🎩  | **Birthday Hat**       | Animated birthday hat element                          |
| 🎉  | **Birthday Animation** | GSAP-powered celebration sequence                      |
| 🔁  | **Replay**             | Restart the entire animation at the end                |
| ⚙️  | **Easy Customization** | Main text can be changed through `customize.json`      |

---

## 🎬 How It Works

```text
                 ┌─────────────────────┐
                 │      index.html     │
                 │    Birthday Page     │
                 └──────────┬──────────┘
                            │
                            ▼
                 ┌─────────────────────┐
                 │    customize.json   │
                 │  Personal Messages  │
                 └──────────┬──────────┘
                            │
                            ▼
                 ┌─────────────────────┐
                 │      main.js        │
                 │   GSAP Animation     │
                 └──────────┬──────────┘
                            │
              ┌─────────────┼─────────────┐
              ▼             ▼             ▼
         💬 Messages     🎈 Balloons    🎂 Birthday
              │             │             │
              └─────────────┼─────────────┘
                            ▼
                    💖 Final Surprise
```

---

## 🪄 Animation Sequence

The page runs through a scripted GSAP timeline:

```text
Greeting
   ↓
Birthday Message
   ↓
Chat-style Message
   ↓
"I wanted to do something special"
   ↓
Personal Message
   ↓
"S O"
   ↓
🎈 Balloons
   ↓
🖼️ Dishu's Picture
   ↓
🎂 Happy Birthday
   ↓
✨ Final Message
   ↓
🔁 Replay
```

The animation is controlled from `script/main.js` using GSAP's timeline and staggered animations.

---

## 🛠️ Built With

| Technology          | Purpose                                   |
| ------------------- | ----------------------------------------- |
| 🌐 **HTML5**        | Page structure                            |
| 🎨 **CSS3**         | Layout, typography and animations styling |
| ⚡ **JavaScript**    | Personalization and animation logic       |
| 🟢 **GSAP**         | Main animation timeline                   |
| ✍️ **Patrick Hand** | Handwritten-style typography              |
| 🖼️ **SVG / PNG**   | Balloons, hat, profile image and favicon  |

---

## 📂 Project Structure

```text
little-gift-for-my-dishu/
│
├── index.html
├── customize.json
├── LICENSE
│
├── img/
│   ├── ballon1.svg
│   ├── ballon2.svg
│   ├── ballon3.svg
│   ├── dishu.png
│   ├── favicon.png
│   └── hat.svg
│
├── script/
│   └── main.js
│
└── style/
    └── style.css
```

---

## ⚙️ Customization

Most of the personal text is separated into:

```text
customize.json
```

You can change things such as:

```json
{
  "greeting": "Huii",
  "name": "Dishu",
  "greetingText": "I don't like your sister btw 😝(jk)",
  "text1": "It's your birthday ˃ᴗ˂",
  "wishHeading": "Happy Birthday!"
}
```

The JavaScript automatically loads the values from `customize.json` and inserts them into the corresponding elements.

### 🖼️ Change the Image

Update:

```json
"imagePath": "img/dishu.png"
```

to point to another image inside the project.

---

## 🚀 Run Locally

No build system or package installation is required.

### 1. Clone the repository

```bash
git clone https://github.com/Hidden-Rhythm/little-gift-for-my-dishu.git
cd little-gift-for-my-dishu
```

### 2. Open the page

You can simply open:

```text
index.html
```

in a browser.

For a local server, any static HTTP server can be used.

For example:

```bash
python -m http.server 8000
```

Then open:

```text
http://localhost:8000
```

---

## 🔁 Replay

After the animation finishes, the final screen contains a replay option.

Clicking it restarts the GSAP timeline from the beginning:

```javascript
tl.restart();
```

So the whole birthday sequence can be watched again without refreshing the page.

---

## 💝 Why This Exists

Some gifts don't need a box.

Sometimes it's just:

```text
a webpage
+ a few silly messages
+ some animations
+ one picture
+ way too much effort
```

and somehow that's enough. :)

---

<p align="center">
  <br>
  <strong>🎂 Made for Dishu.</strong>
  <br>
  <sub>A little piece of code with a lot of meaning.</sub>
  <br><br>
  <a href="https://github.com/Hidden-Rhythm/little-gift-for-my-dishu">
    💻 <strong>View Source</strong>
  </a>
</p>
