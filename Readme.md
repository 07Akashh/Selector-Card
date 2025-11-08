Here’s a clean and professional **`README.md`** for your *Selector Card UI* project 👇

---

```markdown
# 🟨 Selector Card UI

A modern and responsive selector card built using **HTML, CSS, and JavaScript**.  
This component allows users to select multiple options (pages) — including a global “All Pages” selector — with smooth hover, press, and selection animations.

---

## 🖼️ Preview

The card consists of:
- A list of selectable options (Page 1, Page 2, Page 3, Page 4)
- An “All Pages” option to select or deselect all
- A “Done” button with smooth hover and active animations

Each option has a **custom animated checkbox** with a ripple and checkmark effect.

---

## ✨ Features

- ✅ Custom checkboxes with animated selection effect  
- 🌈 Smooth hover and press transitions  
- 🟨 Interactive “Done” button with press feedback  
- 🔁 “All Pages” option toggles all page selections at once  
- 📱 Responsive and minimal UI  
- 💎 Built with only **HTML + CSS + Vanilla JavaScript**

---

## 📂 Project Structure

```

SelectorCard/
│
├── index.html       # Main file containing structure, styles, and logic
└── README.md        # Project documentation

```

---

## 💻 How It Works

### 🧩 HTML
Defines the layout:
- A `.selector-card` container
- `.option` elements for each selectable item
- A `.done-btn` button at the bottom

### 🎨 CSS
- Styled with **Montserrat** font for modern typography  
- `.checkbox` elements include hover, ripple, and checkmark animations  
- `.done-btn` supports `:hover` and `:active` states for smooth feedback  

### ⚙️ JavaScript
- Handles click events for each option  
- Toggles `selected` class on click  
- “All Pages” dynamically selects/deselects all other options  

---

## 🧠 Logic Summary

| Action | Behavior |
|--------|-----------|
| Click on “All Pages” | Selects/deselects all pages |
| Click on individual page | Toggles that page only |
| All individual pages selected | Automatically checks “All Pages” |
| Press “Done” | Visual feedback on click (CSS `:active` state) |

---

## 🪄 Customization

You can easily modify:
- Checkbox color → Update `background-color` in `.option.selected .checkbox`
- Checkmark thickness → Adjust `border-width` in `.checkbox::after`
- Ripple effect size → Edit `.checkbox:active::before`
- Button colors → Change `.done-btn`, `.done-btn:hover`, `.done-btn:active`

---

## 🚀 Usage

1. Clone or download the repository.
2. Open `index.html` in your browser.
3. Click on any option or the **Done** button to see animations in action.

---

## 📸 Example

**Selecting “All Pages”**

```

All pages  ☑️
Page 1     ☑️
Page 2     ☑️
Page 3     ☑️
Page 4     ☑️

```

**Toggling “Page 2”**

```

All pages  ☐
Page 1     ☑️
Page 2     ☐
Page 3     ☑️
Page 4     ☑️

```

---

## 🧾 License

This project is open source and available under the [MIT License](LICENSE).

---

### 👨‍💻 Author
**Rahul**  
Frontend Developer | UI/UX Enthusiast  
📧 [rahulk.softdev@gmail.com](mailto:rahulk.softdev@gmail.com)  
🌐 [GitHub: 07Akashh](https://github.com/07Akashh)
```

---

Would you like me to include **animated screenshots (GIF instructions)** section or **live preview (CodePen/Netlify style)** instructions next?
