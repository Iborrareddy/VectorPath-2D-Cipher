# VectorPath 2D Cipher

**VectorPath 2D Cipher** is a **web-based 2D encoding and decoding tool** that uses a **bulletproof fixed-width 2-digit protocol** to securely transform text. The tool allows users to encode plain text into a custom numeric pattern and decode it back to readable text.

---

## 🔹 Live Demo

The project is hosted on **GitHub Pages**:  
[https://Iborrareddy.github.io/VectorPath-2D-Cipher/](https://Iborrareddy.github.io/VectorPath-2D-Cipher/)

---

## 🔹 Features

- **Encode text** into a 2D fixed-width numeric pattern.
- **Decode numeric patterns** back into the original text.
- Supports:
  - Uppercase and lowercase letters
  - Numbers
  - Common symbols
  - Spaces, tabs, and newlines
- **Interactive web interface** with real-time encoding/decoding.
- Copy output with a single click.
- Clear input/output easily with a button.
- Responsive design for mobile and desktop.

---

## 🔹 How It Works

1. **Encoding Logic:**
   - Letters A-M are converted using a sequential increment pattern.
   - Letters N-Z are converted using a decrement pattern.
   - Numbers are mapped to a fixed numeric sequence.
   - Symbols are mapped to a custom numeric range.
   - Spaces, tabs, and newlines have specific 2-digit codes.

2. **Decoding Logic:**
   - The numeric patterns are parsed and converted back to their original characters.
   - Handles lowercase/uppercase, numbers, symbols, and whitespace correctly.
   - Invalid patterns are detected and returned as `?`.

---

## 🔹 How to Use

1. **Input your text** in the "Input Stream" text area.
2. Click **Encode Data** to generate the numeric pattern.
3. Click **Decode Stream** to convert a numeric pattern back to text.
4. Click **Clear All** to reset the input and output.
5. Click **Copy** to copy the output to your clipboard.

---

## 🔹 Installation (Optional)

If you want to run locally:  

1. Clone the repository:

```bash
git clone https://github.com/Iborrareddy/VectorPath-2D-Cipher.git
