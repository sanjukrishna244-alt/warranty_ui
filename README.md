### 📌 **TASK**
Convert the provided UI image into **pixel-perfect HTML + CSS**.
There should be **no minute changes** from the design in the image.

---

### 🎨 **STRICT DESIGN RULES**

#### **1️⃣ Do NOT modify size, padding, margin, or spacing**
- Every spacing must exactly match the image.
- No automatic horizontal padding unless shown in the image.
- Border radius must match exactly.

#### **2️⃣ Colors & Borders**
- Use exact image colors only.
- If a highlight color (like blue or green) is shown, use it exactly—no shade change.
- If a border appears but color isn’t obvious, use a neutral `#E5E5E5`.

#### **3️⃣ Input & Button Controls**
- Size & height must match exactly.  
- Example rule: search input must NOT stretch beyond design given.
- Do not add unwanted padding/bottom spacing.
- Buttons must align vertically with inputs.

#### **4️⃣ Responsiveness**
- Make responsive without breaking the fixed layout spacing.
- On mobile: stack controls, preserve spacing, do not stretch search input unrealistically.

---

### 📦 **COMPONENTS TO ADD EXACTLY AS IN IMAGE**
- A top control bar (search input + dropdown/select + date input + button).
- A large bordered content box with centered placeholder text (ex: “No data”).
  - Use **no color outline if not visible** in the image.
- A small floating bottom-right card (inside the large box).
  - Match exact padding, border radius, and position (no movement).

---

### 🔧 **CODE STYLE REQUIREMENTS**
- Use **pure HTML + CSS only**.
- Avoid frameworks (Bootstrap, Tailwind, etc.) unless image shows them.
- Use clean, readable class names:
  ```
  .container, .control-bar, .ctrl-input, .ctrl-btn, .content-box, .floating-card
  ```

---

### 🧪 **DYNAMIC/PRODUCTION READY**
- Write code usable in a real dynamic site.
- Structure must support:
  - API data injection
  - Future iteration with JS + map() rendering (but do NOT implement JS unless asked)

---

### 💎 **OUTPUT FORMAT**
⚠️ Output must include:
- Final **HTML**
- Final **CSS**
- No placeholder explanation in the code — only clean code.

---

### 🔥 FINAL REMINDER
> **DO NOT change even 1px of spacing, width, height, margin, border, or layout from the image.**
> Ensure the design is **identical**, not similar.

