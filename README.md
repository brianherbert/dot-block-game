# Spinning Square Game

A browser-based game built entirely with HTML, CSS, and vanilla JavaScript. In this game, you control a red ball inside a moving, spinning, growing, and shrinking square. Avoid letting the ball exit the square, or you'll trigger a loud, rumbling explosion!

## Features

- **Dynamic Square:**  
  The square rotates, moves across the screen, and continuously shrinks to 200px and then grows back to its original 300px. When it fully grows, its movement speed doubles.

- **Responsive Red Ball Control:**  
  - **Keyboard:** Use WASD keys.
  - **On-Screen Controls:** Tap the arrow emoji buttons for mobile devices.
  - **Gamepad Support:** The game seamlessly uses the Gamepad API if a controller (like an Xbox controller) is connected.

- **Audio Effects:**  
  A deep, rumbly explosion sound plays when the red ball exits the square.

- **Witty Reset Button:**  
  When you lose, a random witty phrase is displayed on the reset button to invite you to try again.

- **Self-Contained:**  
  No external libraries or dependencies are used.

## How to Play

1. **Open the Game:**  
   Open `index.html` in any modern web browser (Chrome, Firefox, Edge, etc.).

2. **Control the Red Ball:**  
   - **Desktop:** Use the WASD keys.
   - **Mobile:** Tap the on-screen arrow emoji buttons.
   - **Gamepad:** Use the left stick of your gamepad if connected.

3. **Avoid the Explosion:**  
   Keep the red ball inside the square. If it leaves the boundary, an explosion sound will play and "YOU DIED" will appear. Click the reset button to try again.

## Installation

1. Clone or download this repository.
2. Open the `index.html` file in your preferred web browser.
3. (Due to browser autoplay policies, you may need to tap or click on the canvas to enable audio.)

## Browser Compatibility

The game is designed to work on modern desktop and mobile browsers. It uses the Gamepad API for controller support, so ensure you’re using a browser that supports it.

## License

This project is released under the [MIT License](LICENSE).

## Acknowledgments

This project demonstrates how to use:
- HTML5 Canvas for graphics.
- The Web Audio API for sound effects.
- The Gamepad API for gamepad controls.
- Responsive design techniques for mobile on-screen controls.

Enjoy the game and have fun trying to keep the red ball inside the square!
