# 🎨 Introduction to CSS

**CSS (Cascading Style Sheets)** is the language used to **style and design** HTML elements on a web page. While HTML provides the structure, CSS controls the **visual presentation**, including layout, colors, fonts, spacing, animations, and responsiveness.

### 🎯 Purpose of CSS:
- Separate **content** (HTML) from **design**
- Create visually engaging and responsive web pages
- Apply consistent styles across multiple pages

### 🔑 Key Features:
- 🎨 Control of color, fonts, spacing, and layout
- 📱 Responsive design using media queries
- 🧱 Box model for element sizing and spacing
- ⚙️ Support for animations, transitions, and effects
- 🧩 Can be written as inline, internal, or external styles

### 📘 Example:
```html
<style>
  body {
    background-color: #f0f0f0;
    font-family: Arial, sans-serif;
  }

  h1 {
    color: #2c3e50;
    text-align: center;
  }
</style>

---

## What is CSS?

CSS is a styling language used to control the layout, colors, fonts, and overall appearance of your website. It’s how you turn simple HTML into something beautiful and user-friendly.

---

## Why Do You Need CSS?

- **Customization** – With CSS, you can control every aspect of how your page looks, like text colors, background colors, fonts, and more.
- **Responsive Design** – CSS makes your website look good on any screen size, whether it's a phone, tablet, or desktop.
- **Organization** – By separating content (HTML) from design (CSS), your code becomes cleaner and easier to manage.

---

## Basic Syntax

```css
selector {
  property: value;
}
1. **Inline CSS** – Add CSS directly to an HTML element using the `style` attribute:
   <h1 style="color: blue;">Hello World</h1>

2. **Internal CSS** – Include CSS rules within the `<style>` tag inside the `<head>` section of your HTML:
   <head>
     <style>
       h1 {
         color: blue;
       }
     </style>
   </head>

3. **External CSS** – The most common method, where you link to a separate `.css` file from your HTML:
   <head>
     <link rel="stylesheet" href="styles.css">
   </head>

   And in the external `styles.css` file:
   h1 {
     color: blue;
   }
