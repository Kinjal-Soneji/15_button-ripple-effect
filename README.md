# Button Ripple Effect

A modern, interactive button component that creates an engaging ripple animation effect when clicked. The project demonstrates the implementation of Material Design-inspired ripple effects using pure HTML, CSS, and JavaScript.

## Features

- Material Design-inspired ripple animation
- Supports multiple button styles (Primary and Secondary)
- Responsive and centered layout
- Smooth gradient backgrounds
- Dynamic ripple effect based on click position

## Technologies Used

- HTML5
- CSS3 (with animations)
- Vanilla JavaScript

## Project Structure

```
button-ripple-effect/
├── index.html
├── style.css
├── main.js
└── README.md
```

## Implementation Details

The ripple effect is achieved through the following key components:

1. **HTML**: Buttons with `ripple-effect` class that serves as containers for the animation
2. **CSS**: 
   - Gradient backgrounds for visual appeal
   - Keyframe animation for the ripple expansion
   - Positioning and overflow handling
3. **JavaScript**:
   - Click event listeners on buttons
   - Dynamic creation of ripple elements
   - Calculation of click coordinates
   - Automatic cleanup of ripple elements

## Usage

1. Clone the repository
2. Open `index.html` in a web browser
3. Click on either button to see the ripple effect in action

To add the ripple effect to your own buttons:

1. Add the `ripple-effect` class to your button
2. Include the CSS and JavaScript files in your project
3. For secondary style, add the `secondary` class

```html
<button class="ripple-effect">Primary Button</button>
<button class="ripple-effect secondary">Secondary Button</button>
```

## Customization

You can customize the following aspects:

- Button colors by modifying the gradient values in CSS
- Animation duration by adjusting the keyframe animation timing
- Ripple size by changing the final height/width in the animation
- Button padding and border-radius in the CSS file

## Browser Support

Works in all modern browsers that support:
- CSS Animations
- ES6 JavaScript
- CSS Grid/Flexbox
