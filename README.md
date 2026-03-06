# Glassmorphism Login Page with Background Overlay

A beginner-friendly HTML/CSS project that creates a beautiful login page with a glassmorphism effect (blurred background card) and an overlay that replicates text from a background image. This project demonstrates fundamental front-end skills.

## 🌟 Features

- **Responsive Design** – works on desktop and mobile (the overlay hides on smaller screens).
- **Glassmorphism Effect** – achieved with `backdrop-filter: blur()`.
- **Custom Font** – Google Fonts "Poppins".
- **Icon Integration** – Font Awesome icons for user and lock fields.
- **Background Overlay** – text overlay matches the design of a provided background image.
- **CSS Flexbox** – for layout alignment and spacing.
- **Separated CSS** – styles are in an external file (`style.css`) for cleaner code and easier maintenance.

## 🛠️ Technologies Used

- **HTML5** – structure of the page.
- **CSS3** – styling, including Flexbox, gradients, box shadows, and media queries.
- **Google Fonts** – Poppins font family.
- **Font Awesome** – icons (via CDN).

## 📚 What I Learned

- How to link an external CSS file using `<link rel="stylesheet">`.
- Using `@import` to bring in external fonts.
- The difference between `position: relative` and `absolute` to create overlays.
- Using `backdrop-filter` to create a frosted glass effect.
- Making a layout responsive with `@media` queries.
- Aligning items with Flexbox (`justify-content`, `align-items`, `gap`).
- Styling form inputs and buttons for a consistent look.
- Adding icons inside input fields using absolute positioning.

## 🚀 How to View

1. Clone this repository or download the ZIP.
2. Place your own background image named `Registration Background.jpg` in the same folder as the HTML file (or update the CSS `url()` to match your image).
3. Open `index.html` in any modern web browser.

> **Note:** If you don't have the exact background image, the page includes a fallback gradient so it still looks nice.

## 📁 File Structure

project-folder/
│
├── index.html                   # Main HTML file
├── style.css                    # All CSS styles
├── Registration Background.jpg  # Background image (you need to add it)
└── README.md                    # Project documentation

## 💡 Future Improvements

- Add actual form validation with JavaScript.
- Make the navigation links functional.
- Connect to a backend for real authentication.
- Add more interactive hover effects.

## 🙏 Acknowledgements

- Font Awesome for the icons.
- The design was made by a background image from Freepik.

---

*This project is part of my portfolio as I learn HTML and CSS. Feel free to explore, use, or modify it!*