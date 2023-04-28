# Button Ripple Effect

[![Button Ripple Effect](https://sonnymay.github.io/Button-Ripple-Effect/assets/images/button-ripple-preview.gif)](https://sonnymay.github.io/Button-Ripple-Effect/)

**Button Ripple Effect** is a lightweight, easy-to-use JavaScript library that adds an elegant ripple effect to your buttons. Check out the [live demo](https://sonnymay.github.io/Button-Ripple-Effect/) to see it in action!

## Table of Contents

- [Features](#features)
- [Installation](#installation)
- [Usage](#usage)
- [Customization](#customization)
- [Browser Support](#browser-support)
- [Contributing](#contributing)
- [License](#license)

## Features

- Lightweight and easy to integrate
- Pure JavaScript, no dependencies
- Customizable ripple color and duration
- Works with mouse clicks and touch events

## Installation

There are two ways to install the Button Ripple Effect library:

1. **Direct download**: Download the `button-ripple-effect.min.js` file from the [GitHub repository](https://github.com/sonnymay/Button-Ripple-Effect) and include it in your project.

2. **CDN**: Add the following script tag to your HTML file:

```html
<script src="https://cdn.jsdelivr.net/gh/sonnymay/Button-Ripple-Effect/button-ripple-effect.min.js"></script>
```

## Usage

1. Add the `button-ripple` class to the buttons you want to have the ripple effect:

```html
<button class="button-ripple">Click me</button>
```

2. Initialize the ripple effect by including the following script in your HTML file:

```html
<script>
  document.addEventListener("DOMContentLoaded", function () {
    ButtonRippleEffect.init();
  });
</script>
```

## Customization

You can customize the ripple effect by modifying the following `data-` attributes:

- `data-ripple-color`: Set the ripple color (default: `rgba(0, 0, 0, 0.3)`).
- `data-ripple-duration`: Set the ripple duration in milliseconds (default: `600`).

Example:

```html
<button class="button-ripple" data-ripple-color="#FF5733" data-ripple-duration="800">
  Custom Ripple
</button>
```

## Browser Support

Button Ripple Effect supports modern browsers, including:

- Chrome 49+
- Firefox 42+
- Safari 10+
- Edge 14+
- Opera 36+

Please note that Internet Explorer is not supported.

## Contributing

We welcome contributions! If you'd like to contribute, please feel free to submit a pull request or open an issue on the [GitHub repository](https://github.com/sonnymay/Button-Ripple-Effect).

## License

Button Ripple Effect is released under the [MIT License](https://github.com/sonnymay/Button-Ripple-Effect/blob/main/LICENSE).
