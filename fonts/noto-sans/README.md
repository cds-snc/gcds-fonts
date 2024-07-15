# GC Design System Fonts - Noto Sans

GC Design System paragraphs and other, non-heading text use the font `Noto Sans`.

## Installation

### Install `Noto Sans` font with CDN

To use the GC Design System font `Noto Sans` in your project, place the following code in your CSS or include the [gcds-noto-sans.css](https://github.com/cds-snc/gcds-fonts/blob/main/fonts/noto-sans/gcds-noto-sans.css) file in your project:

```css
<!-- GC Design System Fonts - Noto Sans -- >
@font-face {
  font-family: "Noto Sans";
  src: url("https://cdn.design-system.alpha.canada.ca/@cdssnc/gcds-fonts@1.0.0/fonts/noto-sans/gcds-noto-sans-light.woff2")
      format("woff2"), url("https://cdn.design-system.alpha.canada.ca/@cdssnc/gcds-fonts@1.0.0/fonts/noto-sans/gcds-noto-sans-light.woff")
      format("woff");
  font-weight: 300;
  font-style: normal;
}

@font-face {
  font-family: "Noto Sans";
  src: url("https://cdn.design-system.alpha.canada.ca/@cdssnc/gcds-fonts@1.0.0/fonts/noto-sans/gcds-noto-sans-light-italic.woff2")
      format("woff2"), url("https://cdn.design-system.alpha.canada.ca/@cdssnc/gcds-fonts@1.0.0/fonts/noto-sans/gcds-noto-sans-light-italic.woff")
      format("woff");
  font-weight: 300;
  font-style: italic;
}

@font-face {
  font-family: "Noto Sans";
  src: url("https://cdn.design-system.alpha.canada.ca/@cdssnc/gcds-fonts@1.0.0/fonts/noto-sans/gcds-noto-sans-regular.woff2")
      format("woff2"), url("https://cdn.design-system.alpha.canada.ca/@cdssnc/gcds-fonts@1.0.0/fonts/noto-sans/gcds-noto-sans-regular.woff")
      format("woff");
  font-weight: 400;
  font-style: normal;
}

@font-face {
  font-family: "Noto Sans";
  src: url("https://cdn.design-system.alpha.canada.ca/@cdssnc/gcds-fonts@1.0.0/fonts/noto-sans/gcds-noto-sans-regular-italic.woff2")
      format("woff2"), url("https://cdn.design-system.alpha.canada.ca/@cdssnc/gcds-fonts@1.0.0/fonts/noto-sans/gcds-noto-sans-regular-italic.woff")
      format("woff");
  font-weight: 400;
  font-style: italic;
}

@font-face {
  font-family: "Noto Sans";
  src: url("https://cdn.design-system.alpha.canada.ca/@cdssnc/gcds-fonts@1.0.0/fonts/noto-sans/gcds-noto-sans-medium.woff2")
      format("woff2"), url("https://cdn.design-system.alpha.canada.ca/@cdssnc/gcds-fonts@1.0.0/fonts/noto-sans/gcds-noto-sans-medium.woff")
      format("woff");
  font-weight: 500;
  font-style: normal;
}

@font-face {
  font-family: "Noto Sans";
  src: url("https://cdn.design-system.alpha.canada.ca/@cdssnc/gcds-fonts@1.0.0/fonts/noto-sans/gcds-noto-sans-medium-italic.woff2")
      format("woff2"), url("https://cdn.design-system.alpha.canada.ca/@cdssnc/gcds-fonts@1.0.0/fonts/noto-sans/gcds-noto-sans-medium-italic.woff")
      format("woff");
  font-weight: 500;
  font-style: italic;
}

@font-face {
  font-family: "Noto Sans";
  src: url("https://cdn.design-system.alpha.canada.ca/@cdssnc/gcds-fonts@1.0.0/fonts/noto-sans/gcds-noto-sans-semibold.woff2")
      format("woff2"), url("https://cdn.design-system.alpha.canada.ca/@cdssnc/gcds-fonts@1.0.0/fonts/noto-sans/gcds-noto-sans-semibold.woff")
      format("woff");
  font-weight: 600;
  font-style: normal;
}

@font-face {
  font-family: "Noto Sans";
  src: url("https://cdn.design-system.alpha.canada.ca/@cdssnc/gcds-fonts@1.0.0/fonts/noto-sans/gcds-noto-sans-semibold-italic.woff2")
      format("woff2"), url("https://cdn.design-system.alpha.canada.ca/@cdssnc/gcds-fonts@1.0.0/fonts/noto-sans/gcds-noto-sans-semibold-italic.woff")
      format("woff");
  font-weight: 600;
  font-style: italic;
}

@font-face {
  font-family: "Noto Sans";
  src: url("https://cdn.design-system.alpha.canada.ca/@cdssnc/gcds-fonts@1.0.0/fonts/noto-sans/gcds-noto-sans-bold.woff2")
      format("woff2"), url("https://cdn.design-system.alpha.canada.ca/@cdssnc/gcds-fonts@1.0.0/fonts/noto-sans/gcds-noto-sans-bold.woff")
      format("woff");
  font-weight: 700;
  font-style: normal;
}

@font-face {
  font-family: "Noto Sans";
  src: url("https://cdn.design-system.alpha.canada.ca/@cdssnc/gcds-fonts@1.0.0/fonts/noto-sans/gcds-noto-sans-bold-italic.woff2")
      format("woff2"), url("https://cdn.design-system.alpha.canada.ca/@cdssnc/gcds-fonts@1.0.0/fonts/noto-sans/gcds-noto-sans-bold-italic.woff")
      format("woff");
  font-weight: 700;
  font-style: italic;
}

/* Set "Noto Sans" + fallback as the default body font */
body {
  font-family: "Noto Sans", sans-serif;
  font-weight: 400;
}
```

### Install `Noto Sans` font with npm

Navigate to the root folder of your project and run:

```js
npm install @cdssnc/gcds-fonts
```

Place the following code in your CSS and replace `path/to/node_modules` with the location where you've added the node modules:

```css
<!-- GC Design System Fonts - Noto Sans -->
@font-face {
  font-family: "Noto Sans";
  src: url("path/to/file/gcds-noto-sans-light.woff2") format("woff2"), url("path/to/file/gcds-noto-sans-light.woff")
      format("woff");
  font-weight: 300;
  font-style: normal;
}

@font-face {
  font-family: "Noto Sans";
  src: url("path/to/file/gcds-noto-sans-light-italic.woff2") format("woff2"), url("path/to/file/gcds-noto-sans-light-italic.woff")
      format("woff");
  font-weight: 300;
  font-style: italic;
}

@font-face {
  font-family: "Noto Sans";
  src: url("path/to/file/gcds-noto-sans-regular.woff2") format("woff2"), url("path/to/file/gcds-noto-sans-regular.woff")
      format("woff");
  font-weight: 400;
  font-style: normal;
}

@font-face {
  font-family: "Noto Sans";
  src: url("path/to/file/gcds-noto-sans-regular-italic.woff2") format("woff2"), url("path/to/file/gcds-noto-sans-regular-italic.woff")
      format("woff");
  font-weight: 400;
  font-style: italic;
}

@font-face {
  font-family: "Noto Sans";
  src: url("path/to/file/gcds-noto-sans-medium.woff2") format("woff2"), url("path/to/file/gcds-noto-sans-medium.woff")
      format("woff");
  font-weight: 500;
  font-style: normal;
}

@font-face {
  font-family: "Noto Sans";
  src: url("path/to/file/gcds-noto-sans-medium-italic.woff2") format("woff2"), url("path/to/file/gcds-noto-sans-medium-italic.woff")
      format("woff");
  font-weight: 500;
  font-style: italic;
}

@font-face {
  font-family: "Noto Sans";
  src: url("path/to/file/gcds-noto-sans-semibold.woff2") format("woff2"), url("path/to/file/gcds-noto-sans-semibold.woff")
      format("woff");
  font-weight: 600;
  font-style: normal;
}

@font-face {
  font-family: "Noto Sans";
  src: url("path/to/file/gcds-noto-sans-semibold-italic.woff2") format("woff2"),
    url("path/to/file/gcds-noto-sans-semibold-italic.woff") format("woff");
  font-weight: 600;
  font-style: italic;
}

@font-face {
  font-family: "Noto Sans";
  src: url("path/to/file/gcds-noto-sans-bold.woff2") format("woff2"), url("path/to/file/gcds-noto-sans-bold.woff")
      format("woff");
  font-weight: 700;
  font-style: normal;
}

@font-face {
  font-family: "Noto Sans";
  src: url("path/to/file/gcds-noto-sans-bold-italic.woff2") format("woff2"), url("path/to/file/gcds-noto-sans-bold-italic.woff")
      format("woff");
  font-weight: 700;
  font-style: italic;
}

/* Set "Noto Sans" + fallback as the default body font */
body {
  font-family: "Noto Sans", sans-serif;
  font-weight: 400;
}
```

## Example

Open the [`Noto Sans` example]() to see a list of all supported font weights for the GC Design System `Noto Sans` font. You can find the code for the `Noto Sans` example page in the [examples folder](https://github.com/cds-snc/gcds-fonts/tree/main/examples/noto-sans).
