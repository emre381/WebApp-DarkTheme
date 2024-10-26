
```markdown
# WebApp-DarkTheme

This project is a simple web application that allows users to toggle between light and dark themes. The theme switching feature updates the background, text, and button colors dynamically with each click.

## Features

- **Light and Dark Mode Toggle**: Users can switch between light and dark themes by clicking the button on the screen. The theme is applied using CSS custom properties for easy color management.
- **Responsive Design**: The app adjusts well on various screen sizes and maintains usability.
- **Minimalist UI**: A clean and simple interface that focuses on task management.

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/emre381/WebApp-DarkTheme.git
   ```
2. Navigate to the project folder:
   ```bash
   cd WebApp-DarkTheme
   ```
3. Open `index.html` in your preferred browser.

## Usage

- Open the application in your browser.
- Click the **Dark** button to toggle the theme. The button text will change based on the current theme (showing "Light" in dark mode and "Dark" in light mode).

## Code Structure

- `index.html`: Contains the HTML structure of the page, including a button for switching themes.
- `main.css`: Holds the CSS, including styles for both light and dark themes, as well as button styling.
- `app.js`: Contains the JavaScript for toggling themes by changing the class on the `<body>` element.

## Customization

To change theme colors, adjust the CSS variables in the `:root` selector in `main.css`:

```css
:root {
    --green: #00FF00;
    --white: #FFFFFF;
    --black: #000000;
}
```




