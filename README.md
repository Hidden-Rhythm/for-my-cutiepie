<div align="center">

# ♡ For My Cutiepie

### *a little piece of the heart, written in code.*

<br>

<a href="https://for-my-cutiepie-dishu.vercel.app">
  <img src="https://img.shields.io/badge/♡%20Live%20Website-Open%20the%20Surprise-f43f5e?style=for-the-badge" alt="Live Website">
</a>
&nbsp;
<a href="https://github.com/Hidden-Rhythm/for-my-cutiepie">
  <img src="https://img.shields.io/badge/💻%20Source-GitHub-111111?style=for-the-badge&logo=github" alt="Source Code">
</a>

<br><br>

<img src="https://img.shields.io/badge/HTML-100%25-e34f26?style=for-the-badge&logo=html5&logoColor=white" alt="HTML">
<img src="https://img.shields.io/badge/Tailwind%20CSS-Utility%20UI-38bdf8?style=for-the-badge&logo=tailwindcss&logoColor=white" alt="Tailwind CSS">
<img src="https://img.shields.io/badge/JavaScript-Interactive-f7df1e?style=for-the-badge&logo=javascript&logoColor=black" alt="JavaScript">

</div>

---

## ✦ About

**For My Cutiepie** is a small interactive love-letter website made for one special person.

Instead of being a normal webpage, it unfolds like a little digital experience — beginning with a sealed envelope and gradually revealing **music, photographs, memories, reasons, flowers, and a personal letter.**

> some things are easier to say when you write them in code. ♡

---

## ✦ The Experience

```text
                    ┌─────────────────────┐
                    │    SEALED ENVELOPE  │
                    │         ♡           │
                    └──────────┬──────────┘
                               │
                            Open it
                               │
                               ▼
                    ┌─────────────────────┐
                    │    INTRODUCTION     │
                    │  Music + Message    │
                    └──────────┬──────────┘
                               │
                               ▼
                    ┌─────────────────────┐
                    │   MEMORY ALBUM      │
                    │ Photos + Captions   │
                    └──────────┬──────────┘
                               │
                               ▼
                    ┌─────────────────────┐
                    │      REASONS        │
                    │ Little things ♡    │
                    └──────────┬──────────┘
                               │
                               ▼
                    ┌─────────────────────┐
                    │    LOVE LETTER      │
                    │ Words from the     │
                    │ heart               │
                    └──────────┬──────────┘
                               │
                               ▼
                    ┌─────────────────────┐
                    │   READ IT AGAIN ↻  │
                    └─────────────────────┘
```

---

## ✦ What's Inside

### 💌 Interactive Envelope

The experience begins with a floating illustrated envelope.

Clicking the envelope:

* opens the flap
* lifts the letter
* starts the music
* transitions into the main experience

The envelope uses CSS transforms and custom SVG artwork rather than a static image.

---

### 🎵 Music Player

The main section includes a built-in music player with:

* play / pause
* animated progress indicator
* album artwork
* song title
* artist name
* looping background audio
* visual playing state

The music can be controlled directly from the page.

---

### 📸 Memory Album

A dedicated photo section presents memories as an interactive gallery.

It includes:

* large featured photograph
* captions
* previous / next controls
* thumbnail navigation
* image counter
* animated image transitions
* hover effects on photographs

```text
        ←        ┌──────────────┐        →
                 │              │
                 │   MEMORY     │
                 │    PHOTO     │
                 │              │
                 └──────────────┘

                  01 / 03
              [01] [02] [03]
```

---

### 🌸 Little Reasons

The reasons section turns small thoughts into individual cards.

Each card contains:

* a custom illustrated flower
* a personal message
* glassmorphism styling
* entrance animation
* staggered timing

The flowers are generated as inline SVG artwork, so they remain lightweight and scale cleanly across screens.

---

### 📝 The Letter

The final section is the heart of the experience.

It contains:

* personal greeting
* introductory paragraphs
* photographs
* longer personal messages
* closing message
* handwritten-style signature
* final note
* replay button

The letter is intentionally presented as part of the experience rather than simply displayed as a block of text.

---

## ✦ Visual Design

The entire interface follows a soft romantic aesthetic.

### Palette

```text
Lavender     #c4b5fd
Purple       #a78bfa
Rose         #f43f5e
Pink         #fbcfe8
Background   #f3e8ff
White        rgba(255,255,255,0.65)
```

### Design elements

* 🌸 Floating petals
* ✨ Decorative stars
* 💗 Soft gradients
* 🪟 Glassmorphism cards
* 📸 Polaroid-style photographs
* 💌 Illustrated envelope
* 🌷 Custom SVG flowers
* 🎞️ Smooth section transitions
* 💫 Floating animations
* 📱 Responsive layout

---

## ✦ Typography

The project combines several Google Fonts for different parts of the experience:

| Font                 | Used For                     |
| -------------------- | ---------------------------- |
| **Inter**            | General body text            |
| **Playfair Display** | Elegant headings             |
| **Quicksand**        | Buttons and interface labels |
| **Caveat**           | Handwritten messages         |

This combination gives the page a mix of **clean UI + handwritten personal letter** aesthetics.

---

## ✦ Animations

The experience uses lightweight CSS animations rather than a heavy animation framework.

### Section transitions

Sections fade and slide into view:

```text
opacity: 0
      ↓
translateY(20px)
      ↓
scale(0.98)
      ↓
opacity: 1
      ↓
translateY(0)
      ↓
scale(1)
```

### Floating elements

The interface includes:

* floating envelope
* floating mascot card
* swaying flowers
* falling petals
* pulsing controls
* staggered card entrances
* image scale transitions
* hover interactions

The animations are primarily handled with CSS `@keyframes` and transitions.

---

## ✦ Personalization

The content is organized inside a JavaScript configuration object.

This makes it possible to change things like:

```text
Envelope
├── Intro tag
├── Title
├── Subtitle
├── Signature
├── Seal
└── Mascot

Hero
├── Title
├── Subtitle
├── Message
├── Avatar
├── Song
└── Mini photos

Album
├── Title
├── Subtitle
├── Photos
└── Captions

Reasons
├── Title
├── Subtitle
└── Individual reasons

Letter
├── Greeting
├── Paragraphs
├── Photos
├── Closing
└── Signature
```

So the same underlying experience can be personalized without rebuilding the entire interface.

---

## ✦ Project Structure

```text
for-my-cutiepie/
│
├── index.html
└── README.md
```

The project is intentionally lightweight.

The main experience — including:

* styling
* Tailwind configuration
* animations
* JavaScript logic
* SVG illustrations
* gallery
* music controls
* personalized content

— lives inside `index.html`.

---

## ✦ Technology

| Technology         | Purpose                            |
| ------------------ | ---------------------------------- |
| **HTML5**          | Page structure                     |
| **Tailwind CSS**   | Utility-based styling              |
| **JavaScript**     | Interactions and application logic |
| **SVG**            | Custom illustrations and flowers   |
| **CSS Animations** | Transitions and motion             |
| **Google Fonts**   | Typography                         |
| **HTML Audio API** | Background music                   |

There is **no backend, database, framework build system, or server-side logic** required.

---

## ✦ Run Locally

Clone the repository:

```bash
git clone https://github.com/Hidden-Rhythm/for-my-cutiepie.git
cd for-my-cutiepie
```

Then simply open:

```text
index.html
```

in a modern browser.

Or use a local server:

```bash
python -m http.server 8000
```

Then open:

```text
http://localhost:8000
```

---

## ✦ Responsive

The experience is designed for both:

* 📱 Mobile phones
* 💻 Desktop screens

The layout uses responsive Tailwind utilities alongside custom CSS, with different spacing, typography, image sizes, and controls for smaller screens.

---

## ✦ A Small Detail

The envelope isn't just a visual intro.

It acts as the **entry point to the entire experience**.

```text
Closed
  │
  ▼
Click
  │
  ├── Envelope opens
  ├── Music starts
  └── Experience begins
```

That makes the first interaction feel more like opening something personal than simply loading another webpage.

---

## ✦ Live Website

### ♡ For My Cutiepie

<a href="https://for-my-cutiepie-dishu.vercel.app">
  https://for-my-cutiepie-dishu.vercel.app
</a>

---

## ✦ Source

The complete source is available here:

<a href="https://github.com/Hidden-Rhythm/for-my-cutiepie">
  github.com/Hidden-Rhythm/for-my-cutiepie
</a>

---

<div align="center">

### made for one person.

### coded with a lot of love. ♡

<br>

<sub>not a template. not a product. just a little something.</sub>

<br><br>

**Hidden-Rhythm**

</div>
