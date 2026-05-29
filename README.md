# 🚀 Microsoft Landing Page Clone

> A modern and responsive clone of the Microsoft Homepage built using **HTML5**, **CSS3**, and **Remix Icons**.

---

# 📖 Project Overview

This project recreates the user interface of the Microsoft Homepage, including:

✅ Navigation Bar

✅ Hero Banner Section

✅ Product Categories

✅ Product Showcase Cards

✅ Windows 11 Promotional Banner

✅ Social Media Footer

✅ Multi-Column Footer

---

# 🛠️ Technologies Used

## 🛠️ Tech Stack

- 🌐 **HTML5** → Builds the structure and content of the webpage.
- 🎨 **CSS3** → Handles styling, colors, spacing, and layout.
- ⭐ **Remix Icons** → Provides scalable and modern vector icons.
- 📱 **Flexbox** → Creates responsive and flexible page layouts.
---

# 🧩 Code Explanation

---

# 1️⃣ Importing External Resources

### Code

```html
<link rel="stylesheet" href="style.css">

<link
href="https://cdn.jsdelivr.net/npm/remixicon@4.9.0/fonts/remixicon.css"
rel="stylesheet"
/>
```

### Explanation

- **style.css** contains all custom styling.
- **Remix Icons CDN** imports thousands of ready-made icons.

### Icons Used

```html
<i class="ri-facebook-fill"></i>
<i class="ri-twitter-x-line"></i>
<i class="ri-youtube-fill"></i>
```

| Icon Class | Purpose |
|------------|----------|
| **ri-facebook-fill** | Facebook icon |
| **ri-twitter-x-line** | X (Twitter) icon |
| **ri-youtube-fill** | YouTube icon |

---

# 2️⃣ Navigation Bar

### Code

```html
<nav>
    <div class="left">
        <img src="logo.png">

        <p>Microsoft365</p>
        <p>Azure</p>
        <p>Copilot</p>
        <p>Windows</p>
        <p>Surface</p>
        <p>Xbox</p>
        <p>Support</p>
    </div>
</nav>
```

### Explanation

The navigation bar is divided into two sections:

## 🔹 Left Section

Contains:

- Microsoft Logo
- Microsoft 365
- Azure
- Copilot
- Windows
- Surface
- Xbox
- Support

### Purpose

Provides quick access to Microsoft's major services and products.

---

## 🔹 Right Section

### Code

```html
<div class="right">
    <p>All Microsoft</p>
    <p>Search</p>
    <p>Cart</p>
</div>
```

### Purpose

Contains utility actions:

- Dropdown Menu
- Search Option
- Shopping Cart

---

# 3️⃣ Hero Banner Section

### Code

```html
<section>

    <img src="banner.jpg">

    <div class="content">
        <h1>Meet Surface Laptop</h1>

        <p>
            This laptop's unrivalled flexibility
            and AI features...
        </p>

        <button>Learn more</button>

    </div>

</section>
```

### Purpose

This section acts as the main promotional area of the website.

### Components

#### 🖼️ Banner Image

Displays Microsoft's promotional image.

#### 📝 Heading

```html
<h1>Meet Surface Laptop</h1>
```

Highlights the featured product.

#### 🔘 Call To Action Button

```html
<button>Learn more</button>
```

Encourages users to learn more about the product.

---

# 4️⃣ Product Categories Section

### Code

```html
<div class="container3">

    <div class="box">
        <img src="icon.png">
        <p>Shop Microsoft 365</p>
    </div>

</div>
```

### Purpose

Provides shortcuts to important Microsoft products.

### Categories Included

- Microsoft 365
- Xbox
- Windows 11
- Surface Devices

---

# 5️⃣ Featured Product Cards

### Code

```html
<div class="container4">

    <div class="box">

        <div class="topImg">
            <img src="product.jpg">
        </div>

        <div class="text">

            <h1>Surface Laptop, Copilot+ PC</h1>

            <p>
                Unlock AI features like
                Live Captions and Cocreator.
            </p>

            <button>Learn more</button>

        </div>

    </div>

</div>
```

### Purpose

Displays Microsoft's featured products in a card-based layout.

### Featured Products

| Product | Description |
|----------|-------------|
| 💻 Surface Laptop | AI-powered laptop |
| 🎮 Xbox Game Pass | Subscription service |
| ⚡ Xbox Series X | Powerful gaming console |
| 🎯 Xbox Series S | Compact next-gen console |

---

# 6️⃣ Windows 11 Promotional Section

### Code

```html
<div class="container5">

    <div class="content2">

        <h1>
            Designed for life today – and tomorrow
        </h1>

        <button>
            See if your PC is ready
        </button>

    </div>

</div>
```

### Purpose

Promotes Windows 11 and encourages users to upgrade.

---

# 7️⃣ Social Media Section

### Code

```html
<div class="social">

    <i class="ri-facebook-fill"></i>

    <i class="ri-twitter-x-line"></i>

    <i class="ri-youtube-fill"></i>

</div>
```

### Purpose

Allows users to connect with Microsoft through social media.

### Platforms

- Facebook
- X (Twitter)
- YouTube

---

# 8️⃣ Back To Top Button

### Code

```html
<div class="back">

    <i class="ri-arrow-up-line"></i>

    <p>Back to top</p>

</div>
```

### Purpose

Improves user experience by allowing quick navigation to the top of the page.

---

# 9️⃣ Footer Links

### Code

```html
<div class="footer-links">
```

### Footer Categories

### 📰 What's New

Latest Microsoft products and updates.

### 🏪 Microsoft Store

Store support and account services.

### 🎓 Education

Educational resources and tools.

### 💼 Business

Business products and enterprise solutions.

### 👨‍💻 Developer & IT

Developer resources and technical platforms.

### 🏢 Company

Company information and career opportunities.

---

# 🔟 Bottom Footer

### Code

```html
<div class="bottom-footer">
```

### Left Side

```html
English (India)
Your Privacy Choices
Consumer Health Privacy
```

### Right Side

```html
Contact Microsoft
Privacy
Terms of use
Trademarks
About our ads
© Microsoft 2026
```

### Purpose

Provides legal information, support resources, and company policies.

---

# 🎯 Learning Outcomes

By building this project, I learned:

✔ Semantic HTML Structure

✔ Responsive Layout Design

✔ Flexbox Positioning

✔ Landing Page Development

✔ Card-Based UI Design

✔ Footer Architecture

✔ Icon Integration

✔ Modern Web Design Principles

---

# 📂 Folder Structure

```bash
Microsoft-Landing-Page/
│
├── index.html
├── style.css
└── README.md
```

---

# ⭐ Conclusion

This project successfully recreates the Microsoft Homepage using **HTML5**, **CSS3**, and **Remix Icons** while demonstrating modern front-end development practices, responsive layouts, structured components, and clean UI design.






# 🎨 CSS Code Explanation

The styling of this project is handled entirely using **CSS3**. It controls the layout, spacing, typography, colors, responsiveness, and overall appearance of the Microsoft Landing Page.

---

# 1️⃣ Global Reset

### Code

```css
* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}
```

### Explanation

This reset removes default browser spacing and ensures consistent sizing across all elements.

### Benefits

✔ Removes unwanted margins

✔ Removes unwanted padding

✔ Makes layouts easier to control

---

# 2️⃣ Body Styling

### Code

```css
html,
body {
  width: 100%;
  min-height: 100%;
  font-family: sans-serif;
}
```

### Explanation

Defines the overall page dimensions and sets the default font family for the website.

### Purpose

- Uses the full browser width.
- Ensures content fills the page height.
- Provides clean and readable typography.

---

# 3️⃣ Main Container

### Code

```css
main {
  width: 100%;
  display: flex;
  flex-direction: column;
}
```

### Explanation

The main container organizes all sections vertically using Flexbox.

### Purpose

- Stacks elements from top to bottom.
- Makes layout management easier.

---

# 4️⃣ Navigation Bar

### Code

```css
nav {
  padding: 15px 40px;
  display: flex;
  justify-content: space-between;
  align-items: center;
}
```

### Explanation

Creates a horizontal navigation bar.

### Features

- Flexbox alignment
- Equal spacing between left and right sections
- Vertical centering

---

## Left Navigation Section

### Code

```css
nav .left {
  display: flex;
  align-items: center;
  gap: 10px;
}
```

### Purpose

Aligns logo and navigation links in a row.

---

## Right Navigation Section

### Code

```css
nav .right {
  display: flex;
  align-items: center;
  gap: 20px;
}
```

### Purpose

Aligns Search, Cart, and All Microsoft options.

---

# 5️⃣ Profile Avatar

### Code

```css
.Profile {
  height: 40px;
  width: 40px;
  border-radius: 50%;
}
```

### Explanation

Creates a circular user profile image.

### Features

✔ Circular shape

✔ Background image support

✔ Professional appearance

---

# 6️⃣ Hero Section

### Code

```css
section {
  position: relative;
  width: 95%;
  margin: auto;
}
```

### Explanation

Creates the main promotional banner section.

### Purpose

- Centers the banner
- Allows absolute positioning of content

---

# 7️⃣ Hero Content

### Code

```css
.content {
  position: absolute;
  top: 20%;
  left: 8%;
}
```

### Explanation

Places text on top of the hero image.

### Features

- Overlay effect
- Precise positioning
- Responsive alignment

---

## Heading Style

### Code

```css
.content h1 {
  font-size: 50px;
}
```

### Purpose

Creates a large attention-grabbing title.

---

## Paragraph Style

### Code

```css
.content p {
  line-height: 28px;
  font-size: 18px;
}
```

### Purpose

Improves readability of descriptive text.

---

## Button Styling

### Code

```css
.content button {
  background-color: #0067b8;
  color: white;
}
```

### Purpose

Creates Microsoft's signature blue call-to-action button.

---

# 8️⃣ Product Categories Section

### Code

```css
.container3 {
  display: flex;
  justify-content: center;
  gap: 40px;
}
```

### Explanation

Displays category items horizontally.

### Categories

- Microsoft 365
- Xbox
- Windows 11
- Surface

---

# 9️⃣ Product Cards Section

### Code

```css
.container4 {
  display: flex;
  gap: 40px;
}
```

### Explanation

Creates a four-column card layout.

### Features

✔ Equal spacing

✔ Modern card design

✔ Responsive arrangement

---

## Card Styling

### Code

```css
.container4 .box {
  box-shadow: 0 5px 7px rgba(0,0,0,0.16);
}
```

### Purpose

Adds depth and elevation to cards.

### Result

Creates a modern card-based UI appearance.

---

# 🔟 Product Images

### Code

```css
.container4 .box img {
  object-fit: cover;
}
```

### Explanation

Ensures images fit properly without distortion.

---

# 1️⃣1️⃣ Windows 11 Banner Section

### Code

```css
.container5 {
  background-image: url(...);
  background-size: cover;
}
```

### Explanation

Creates a full-width promotional banner using a background image.

### Features

✔ Cover image

✔ Center positioning

✔ Professional hero effect

---

# 1️⃣2️⃣ Banner Content

### Code

```css
.content2 {
  position: absolute;
  top: 50%;
}
```

### Explanation

Centers promotional text vertically over the image.

---

# 1️⃣3️⃣ Footer Section

### Code

```css
.footer {
  background-color: #f2f2f2;
}
```

### Explanation

Creates Microsoft's light gray footer background.

---

# 1️⃣4️⃣ Social Media Section

### Code

```css
.social {
  display: flex;
  gap: 25px;
}
```

### Purpose

Displays social media icons in a horizontal row.

### Platforms

- Facebook
- X (Twitter)
- YouTube

---

# 1️⃣5️⃣ Footer Links

### Code

```css
.footer-links {
  display: flex;
  justify-content: space-between;
}
```

### Explanation

Creates a multi-column footer layout.

### Columns Included

- What's New
- Microsoft Store
- Education
- Business
- Developer & IT
- Company

---

# 1️⃣6️⃣ Bottom Footer

### Code

```css
.bottom-footer {
  display: flex;
  justify-content: space-between;
}
```

### Explanation

Separates legal information and navigation links into left and right sections.

### Contents

#### Left Side

- Language Selection
- Privacy Choices
- Consumer Health Privacy

#### Right Side

- Contact Microsoft
- Privacy
- Terms of Use
- Trademarks
- About Our Ads

---

# 🎯 CSS Concepts Used

✔ Flexbox Layout

✔ Positioning (Relative & Absolute)

✔ Background Images

✔ Typography Styling

✔ Card Components

✔ Box Shadows

✔ Responsive Alignment

✔ Hover Effects

✔ Modern UI Design

---

# 📚 Learning Outcomes

Through this CSS implementation, I learned:

- Flexbox Layout System
- Modern Landing Page Design
- Hero Section Development
- Card-Based UI Components
- Footer Architecture
- Responsive Web Design
- Professional Styling Techniques
