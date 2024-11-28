# Typography Guidelines for Web Design

To make typography functional and pleasing, here are general guidelines for responsive web design.

## 1. Font Size
Base size for body text: **16px**.
Headings: to have the text scale with user settings, use relative units such as `em` or `rem`.<br/>
Example:
```css
h1 { font-size: 2.5rem; }
h2 { font-size: 2rem; }
```

## 2. Line Height
**Line-height** is optimal at **1.5** or **150%**, as this improves readability by allowing whitespace around text blocks.

## 3. Letter Spacing
Use **0.05em** to **0.1em** letter spacing to prioritize legibility, which can become more critical when text is in all capital letters.<br/>
Example:
```css
letter-spacing: 0.05em;
```
## 4. Responsive Typography
Use media queries and vw units to scale typography according to the screen size.<br/>
Example:
```css
html {
  font-size: 16px;
}

@media (max-width: 768px) {
  html {
    font-size: 14px;
  }
}

@media (min-width: 1024px) {
  html {
    font-size: 18px;
  }
}
```
## 5. Contrast and Color
Ensure a high contrast ratio between text and background. A minimum contrast ratio of **4.5:1** is recommended for normal text, and **3:1** for large text.
