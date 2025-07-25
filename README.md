# Bouncing DVD Logo

A faithful recreation of the classic DVD screensaver logo in HTML, CSS, and JavaScript.

- The "DVD" logo (styled in [Orbitron](https://fonts.google.com/specimen/Orbitron)) bounces smoothly around the screen.
- Every time the logo collides perfectly with a corner, its color changes to a new random color and a counter is incremented.
- The total number of perfect corner hits is logged in the browser console.

## Demo

Open `index.html` in your browser to see it in action or head on over to **https://dvd-logo-neon.vercel.app/**

## Features

- **Accurate Bouncing**: The logo bounces off all four edges of the browser window, just like the classic screensaver.
- **Random Colors**: Each time the logo touches a wall, it changes to a new random color.
- **Corner Counter**: When the logo hits a corner perfectly, the event is logged in the console with a running count.
- **Simple Logo**: The logo consists of the text `DVD` in Orbitron font and a circle beneath it, styled with CSS.
- **Responsive**: The animation adapts to window resizing.

## How it Works

- The position and velocity of the logo are updated on each animation frame.
- When the logo collides with the window border, its direction reverses and its color changes.
- Perfect corner collisions are detected and counted, with the count logged to the console.

## Usage

1. **Clone or Download** this repository.
2. **Open `index.html`** in your browser.
3. **Check your browser's console** to see the number of corner hits.

## Customization

- Adjust the speed or size of the logo by editing the JavaScript variables in `index.html`.
- Change the logo's appearance by editing the CSS.

## Dependencies

- [Orbitron Font (Google Fonts)](https://fonts.google.com/specimen/Orbitron)

## License

MIT

---

Created for fun and nostalgia!



//Powered by Copilot this time
