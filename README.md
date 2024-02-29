# Animated 3D Loader

This repository contains code for an animated 3D loader created using HTML and CSS. The loader consists of a series of dots arranged in a circular pattern, with accompanying text indicating loading activity. The animation creates a visually appealing effect suitable for various web applications.

## Preview
![preview](https://github.com/withaarzoo/Animated-3D-Loader/assets/59678435/32aea20d-5861-4792-9ee5-fa1eb98e1630)

## Features

- Smooth and eye-catching animation.
- Modern design with 3D effects.
- Adjustable colors and timing for customization.

## Usage

To use this animated loader in your project, follow these steps:

1. Copy the HTML code from `index.html` and paste it into your HTML file where you want the loader to appear.
2. Copy the CSS code from `style.css` and paste it into your CSS file.
3. Customize the loader by adjusting CSS variables to match your project's color scheme if desired.

```html
<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="stylesheet" href="style.css">
    <title>Animated 3D Loader</title>
</head>

<body>
    <div class="pl">
        <div class="pl__dot"></div>
        <div class="pl__dot"></div>
        <!-- Add more dots here if needed -->
        <div class="pl__text">Loading…</div>
    </div>
</body>

</html>
```

## Customization

You can customize the loader by modifying the CSS variables in `style.css`. Here are the variables you can adjust:

- `--bg`: Background color of the loader.
- `--fg`: Foreground color of the loader (dots and text).
- `--fg-t`: Transparent foreground color for text shadow.
- `--primary1`: Primary color used for animation.
- `--primary2`: Secondary color used for animation.
- `--trans-dur`: Transition duration for smoother animations.

## Compatibility

This loader is designed to work across modern web browsers and devices. However, for older browsers, particularly versions of Internet Explorer, some features may not be fully supported.

## Credits

This loader design is inspired by various CSS animation techniques found across the web. Special thanks to the CSS community for sharing their knowledge and creativity.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details. Feel free to use, modify, and distribute this code for your projects. Contributions are welcome!
