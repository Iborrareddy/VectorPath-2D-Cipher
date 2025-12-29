# VectorPath 2D Cipher 🚀🔐

**VectorPath 2D Cipher** is a next-generation web-based encoding tool. It utilizes a **Fixed-Width 2-Digit Protocol** to transform text into a structured numeric pattern. Unlike standard ciphers, it preserves document layout (spaces, tabs, and newlines) while ensuring every character has a unique, reversible signature.

---

### 🌐 Live Demo
Experience the tool here:  
[https://Iborrareddy.github.io/VectorPath-2D-Cipher/](https://Iborrareddy.github.io/VectorPath-2D-Cipher/)

---

### ✨ Features
- **Binary-Visual Hybrid**: Uses numerical sequences that vary in length based on character position.
- **Fixed-Width Logic**: Numbers (30+) and Symbols (99-) use 2-digit pairs to prevent decoding ambiguity.
- **Layout Preservation**: Full support for `\n`, `\t`, and multiple spaces.
- **Cyberpunk UI**: Glassmorphism design with a high-contrast terminal aesthetic.
- **Secure Handling**: Client-side processing ensures your data never leaves the browser.

---

### 🛠 The Protocol (How It Works)



**Encoding Strategy:**
- **Ascending Path**: Letters **A-M** increment sequentially (e.g., `B` -> `12`).
- **Descending Path**: Letters **N-Z** decrement sequentially (e.g., `O` -> `98`).
- **Numeric Shift**: Digits **0-9** are mapped to pairs starting at `30` (e.g., `1` -> `3031`).
- **Extended Symbols**: Mapped to a stable descending range starting at `99`.
- **Case Sensitivity**: Lowercase characters are identified by a unique `0` prefix.

---

### 📖 How to Use
1. **Input**: Type or paste your text into the **Input Stream**.
2. **Transform**: Click **Encode Data** to see the VectorPath pattern.
3. **Revert**: Paste a piped pattern into the stream and click **Decode Stream**.
4. **Export**: Use the **Copy** or **Download** buttons to save your results.

---

### 💾 Local Development
1. Clone the repository:
   ```bash
   git clone [https://github.com/Iborrareddy/VectorPath-2D-Cipher.git](https://github.com/Iborrareddy/VectorPath-2D-Cipher.git)
