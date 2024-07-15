# GC Design System Fonts - Noto Sans Mono

Use GC Design System's `Noto Sans Mono` font when citing code to give specific code examples.

## Installation

### Install `Noto Sans Mono` font with CDN

To use the GC Design System font `Noto Sans Mono` in your project, place the following code in your CSS or include the [gcds-noto-sans-mono.css](https://github.com/cds-snc/gcds-fonts/blob/main/fonts/noto-sans-mono/gcds-noto-sans-mono.css) file in your project:

```css
<!-- GC Design System Fonts - Noto Sans Mono -- >
@font-face {
  font-family: "Noto Sans Mono";
  src: url("https://cdn.design-system.alpha.canada.ca/@cdssnc/gcds-fonts@1.0.0/fonts/noto-sans-mono/gcds-noto-sans-mono.woff2") format("woff2"),
       url("https://cdn.design-system.alpha.canada.ca/@cdssnc/gcds-fonts@1.0.0/fonts/noto-sans-mono/gcds-noto-sans-mono.woff") format("woff");
  font-weight: 400;
  font-style: normal;
}

/* Set "Noto Sans Mono" + fallback as the code font */
code {
  font-family: "Noto Sans Mono", monospace;
  font-weight: 400;
}
```

### Install `Noto Sans Mono` font with npm

Navigate to the root folder of your project and run:

```js
npm install @cdssnc/gcds-fonts
```

Place the following code in your CSS and replace `path/to/node_modules` with the location where you’ve added the node modules:

```css
<!-- GC Design System Fonts - Noto Sans Mono -- >
@font-face {
  font-family: "Noto Sans Mono";
  src: url("path/to/node_modules/@cdssnc/gcds-fonts@1.0.0/fonts/noto-sans-mono/
gcds-noto-sans-mono.woff2") format("woff2"),
       url("path/to/node_modules/@cdssnc/gcds-fonts@1.0.0/fonts/noto-sans-mono/gcds-noto-sans-mono.woff") format("woff");
  font-weight: 400;
  font-style: normal;
}

/* Set "Noto Sans Mono" + fallback as the code font */
code {
  font-family: "Noto Sans Mono", monospace;
  font-weight: 400;
}
```

## Example

Open the [`Noto Sans Mono` example]() to see a code example using the GC Design System `Noto Sans Mono` font. You can find the code for the `Noto Sans Mono` example page in the [examples folder](https://github.com/cds-snc/gcds-fonts/tree/main/examples/noto-sans-mono).
