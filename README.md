# Celestial Script — The Agrippa / Metatron Alphabet Typewriter

A browser-based typewriter that transliterates Hebrew text into the **Alphabet of Metatron** (also known as the Celestial Alphabet, *Alfa Beta shel Metatron*, or the *Malachim* script recorded by Heinrich Cornelius Agrippa) — the dot-and-line "celestial scribe" cipher used for centuries in Kabbalistic and angelic magic traditions.

Type in Hebrew — using your own keyboard or the built-in on-screen one — and watch your text transform in real time into these ancient glyphs, complete with a full reference chart and a Hebrew gematria calculator.

> **Live demo:** open `index.html` in any modern browser, or visit the GitHub Pages link for this repo.

---

## ✨ Features

### 1. Typewriter
- Type Hebrew letters (including final/*sofit* forms — ך ם ן ף ץ) and each one is instantly rendered as its corresponding **celestial glyph**, traced directly from the original Agrippa chart.
- Glyphs lay out right-to-left, matching natural Hebrew writing direction, with proper word-wrapping and line breaks.
- A blinking cursor and parchment-style ruled background give it the feel of an old manuscript.
- **Clear** button to reset the page.
- **Show letter key** toggle reveals a quick-reference legend of all 22 letters and their glyphs without leaving the tab.

### 2. On-Screen Hebrew Keyboard
- No Hebrew keyboard layout required — a full virtual keyboard (including final letter forms) lets anyone type the script from any device.
- Includes space and backspace keys, with correct right-to-left cursor behavior.

### 3. Reference Chart
- A complete side-by-side chart of all **22 Hebrew letters**, each paired with:
  - its **celestial glyph** (cropped directly from the original manuscript image),
  - its **letter name** (Aleph, Bet, Gimel, …),
  - and its **gematria value**.
- A clean, at-a-glance "Rosetta Stone" for the whole system.

### 4. Gematria Calculator
- Type or use the on-screen keyboard to enter any Hebrew word or phrase.
- Instantly see its **total gematria value** (standard *mispar hechrachi*, 1–400, including final forms).
- A letter-by-letter breakdown shows each letter's celestial glyph alongside its individual numeric value.
- Fully synced with the Typewriter tab — anything you type in either tab appears as glyphs in both.

---

## 🔤 About the Alphabet

The **Alphabet of Metatron** is one of several "celestial" or "angelic" scripts recorded in Western esoteric tradition. Each Hebrew letter is assigned a glyph built from simple straight or curved strokes terminating in small circles ("nodes") — a visual style shared with related systems like the Theban and Enochian alphabets. It appears in manuscripts associated with Heinrich Cornelius Agrippa's *Three Books of Occult Philosophy*, and has long been used on amulets, talismans, and in Kabbalistic study as a way of "veiling" sacred text.

This project digitizes that chart, mapping all 22 Hebrew letters (including final forms) to their corresponding glyphs so the script can be typed and read interactively.

---

## 🛠️ How It Works

This is a **single self-contained HTML file** — no build step, no server, no dependencies.

- **Glyph images** are real crops from the original chart, embedded directly in the page as base64-encoded PNGs.
- **Hebrew → glyph mapping** is handled by a simple lookup table, with final letter forms mapped to their base-letter glyph.
- **Gematria values** follow the standard table (Aleph=1 … Yod=10, Kaf=20 … Tsadi=90, Qof=100 … Tav=400), with final forms carrying the same value as their base letter.
- The interface is built with plain HTML, CSS, and vanilla JavaScript — open it in any browser, online or offline.

---

## 🚀 Usage

1. Clone or download this repo.
2. Open `index.html` in your browser — that's it.
3. Use the **Typewriter**, **Reference Chart**, and **Gematria** tabs to explore the script.

To host it publicly, enable **GitHub Pages** for this repository (Settings → Pages → Deploy from branch `main`, folder `/root`) and your typewriter will be live at:

```
https://<your-username>.github.io/<repo-name>/
```

---

## 📜 Disclaimer

This tool is offered for educational, artistic, and historical-curiosity purposes — an interactive way to engage with a centuries-old cipher tradition. Letter shapes are best-effort digitizations of a historical chart and may vary slightly from other published versions of the Metatron alphabet.

---

## 🙏 Credits

- Glyphs digitized from a traditional Agrippa-style "Alphabet of Metatron" chart.
- Built collaboratively with [Claude](https://claude.ai) by Anthropic.
