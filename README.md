# Not Bad CSS Framework

A lite weight CSS framework developed for building modern websites.

**It's not bad CSS!**

## Installation

There are two ways to include Not Bad CSS in your project.

### 1. Link the CSS file

Link the compiled `style.css` file in the `<head>` of your HTML document.

```html
<link rel="stylesheet" href="./css/style.css">
```

### 2. Using Sass

For customization, you can use the source Sass files.

1.  Make sure you have Sass installed.
2.  Import the main `not_bad_css.scss` file into your project's main Sass file.

    ```scss
    @use './src/not_bad_css.scss';
    ```

3.  Compile your Sass files into CSS. You can use these npm script to watch for changes:

    ```bash
    npm install
    npm run sass:watch
    ```

## Usage

Not Bad CSS is a utility first framework similar to your other favs CSS frameworks. All you need to do is apply the classes directly in your HTML.

Check out the `index.html` file to see available utilities and components, including:

- Typography (font sizes & weights)
- Colors (background, text, border)
- Spacing (margin, padding)
- Buttons (solid, outline, ghost)
- Forms (inputs, textareas, selects, checkboxes)
- Tables

## Customization

You can easily customize the framework by modifying the Sass variables located in `src/variables/index.scss`. This file contains definitions for colors, fonts, spacing, and more.

After changing the variables, you will need to recompile the Sass files to see your changes reflected in the final `style.css` file.

**Its not bad CSS!**