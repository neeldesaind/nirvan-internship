# Event Handling (HTML, CSS and JAVA SCRIPT)

This repository contains examples demonstrating the use of JavaScript to handle both keyboard and mouse events effectively. These examples cover basic and advanced event handling techniques, including capturing multiple key presses, preventing default actions, and customizing mouse interactions.

## Project Files

### 1. **Keyboard Events (Basic)**  
**File:** `keyboard_events.html`  
- **Description:** Displays the details of a pressed key in real-time.  
- **Features:**  
  - Shows the `Key`, `KeyCode`, and `Code` of the pressed key.
  - Dynamically updates the values on every key press.  

### 2. **Mouse Events (Basic)**  
**File:** `mouse_events.html`  
- **Description:** Detects mouse button clicks and displays the corresponding button name (Left, Middle, or Right).  
- **Features:**  
  - Uses `mousedown` event to capture mouse button clicks.
  - Displays the button name in a user-friendly format.
  
### 3. **Multiple Key Capture**  
**File:** `multiple_keycapture.html`  
- **Description:** Tracks and displays multiple keys being pressed simultaneously.  
- **Features:**  
  - Shows all currently pressed keys, their `KeyCodes`, and `Codes`.
  - Prevents default browser behavior for keys using `event.preventDefault()`.
  - Handles both `keydown` and `keyup` events to maintain an updated list of active keys.

### 4. **Prevent Keyboard Events**  
**File:** `prevent-keyboard-events.html`  
- **Description:** Demonstrates how to prevent default actions for keyboard events.  
- **Features:**  
  - Blocks the default behavior of key presses using `event.preventDefault()`.
  - Captures and displays the `Key`, `KeyCode`, and `Code` for informational purposes.

### 5. **Prevent Mouse Events with Custom Context Menu**  
**File:** `prevent-mouse-events.html`  
- **Description:** Implements a custom context menu that appears on a right-click, preventing the default browser context menu.  
- **Features:**  
  - Displays a custom-designed menu when the user right-clicks.
  - Hides the custom menu when clicking elsewhere on the page.
  - Contains a clickable menu item linking to a portfolio.

## How to Use

1. Clone or download this repository.
2. Open any of the `.html` files in your favorite web browser.
3. Interact with the keyboard or mouse as described for each example to see the functionality in action.

## Highlights

- **Keyboard Events:**
  - Learn how to capture key presses and retrieve key details.
  - Explore how to track multiple key presses simultaneously.
  - Understand how to prevent default key behaviors in specific scenarios.

- **Mouse Events:**
  - Discover how to customize mouse interactions.
  - Implement a custom right-click menu using JavaScript and CSS.
  - Block default mouse events like the browser's context menu.

## Customization

Feel free to modify the scripts and styles to better suit your own projects. Each example provides a simple yet powerful starting point for handling events in JavaScript.

## Contributing

If you have suggestions or additional examples you'd like to share, feel free to submit a pull request or open an issue.

## Author

**Neel Desai**  
[Linkedin](https://www.linkedin.com/in/neeldesaind)  
