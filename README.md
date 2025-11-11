# ISWC / ISRC Utils

A lightweight web utility for converting and validating **ISWC** and **ISRC** codes between their formatted and compact representations.

Built for quick everyday use — just paste a code like `T9121280997` or `SE-69Z-25-02263` and get both canonical and unformatted versions instantly.

## 🔧 Features

- Detects and formats both ISWC and ISRC automatically  
- Supports flexible input (with or without dashes, dots, or spaces)  
- Outputs:
  - **ISWC**: `T9121280997` ↔ `T-912.128.099-7`
  - **ISRC**: `SE69Z2502263` ↔ `SE-69Z-25-02263`
- Copy-to-clipboard for each result  
- Runs fully client-side — no data is sent anywhere  

## 🧩 Usage

1. Visit the hosted tool (GitHub Pages link below once deployed)  
2. Paste or type an ISWC or ISRC into the input field  
3. Click **Convert** or press **Enter**  
4. Copy any output format for use in your system

## 🚀 Deploy on GitHub Pages

1. Create this repository on GitHub (e.g. `iswc-isrc-utils`)  
2. Add the provided `index.html` file to the root of the repo  
3. Commit and push  
4. In **Settings → Pages**, choose:
   - **Source**: `Deploy from a branch`
   - **Branch**: `main` (or `master`)
   - **Folder**: `/ (root)`
5. GitHub will generate a live URL — your tool will be instantly available online.

## 📜 License

MIT License.  
Free for personal and professional use.

---

**Example:**  
Paste `T-923.502.140-6` → get  
