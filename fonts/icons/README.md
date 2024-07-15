# GC Design System Fonts - Icons

GC Design System Fonts - Icons is a custom icon font created for the GC Design System. Icon fonts provide scalable vector icons that enhance performance, maintain consistency, and offer easy customization through CSS. Icons are used for visual communication that helps a person understand context.

To remove the reliance on a third-party icon library (Font Awesome) we built a custom icon font. This also provides the GC Design System with more control over icons available to users. FontAwesome provides an extensive collection of icons, most of which will not be used for our components. By limiting the scope of available icons, we aim to prevent misuse and provide clear guidelines on the appropriate usage of each icon.

## Installation

### Install icon font with CDN

To use GC Design System icons in your project, place the following code in your CSS or include the [gcds-icons.css](https://github.com/cds-snc/gcds-fonts/blob/main/fonts/icons/gcds-icons.css) file in your project:

```css
<!-- GC Design System Fonts - Icons -->
@font-face {
  font-family: "gcds-icons";
  src: url("https://cdn.design-system.alpha.canada.ca/@cdssnc/gcds-fonts@1.0.0/fonts/icons/gcds-icons.eot");
  src: url("https://cdn.design-system.alpha.canada.ca/@cdssnc/gcds-fonts@1.0.0/fonts/icons/gcds-icons.eot#iefix")
      format("embedded-opentype"), url("https://cdn.design-system.alpha.canada.ca/@cdssnc/gcds-fonts@1.0.0/fonts/icons/gcds-icons.ttf")
      format("truetype"),
    url("https://cdn.design-system.alpha.canada.ca/@cdssnc/gcds-fonts@1.0.0/fonts/icons/gcds-icons.woff")
      format("woff"), url("https://cdn.design-system.alpha.canada.ca/@cdssnc/gcds-fonts@1.0.0/fonts/icons/gcds-icons.svg")
      format("svg");
  font-weight: normal;
  font-style: normal;
  font-display: block;
}

[class^="icon-"],
[class*=" icon-"] {
  /* use !important to prevent issues with browser extensions that change fonts */
  font-family: "gcds-icons" !important;
  speak: never;
  font-style: normal;
  font-weight: normal;
  font-variant: normal;
  text-transform: none;
  line-height: 1;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
}

.icon-chevron-down:before {
  content: "\e900";
}

.icon-chevron-left:before {
  content: "\e901";
}

.icon-chevron-right:before {
  content: "\e902";
}

.icon-chevron-up:before {
  content: "\e903";
}

.icon-external:before {
  content: "\e904";
}

.icon-email:before {
  content: "\e905";
}

.icon-download:before {
  content: "\e906";
}

.icon-warning-triangle-outline:before {
  content: "\e907";
}

.icon-search:before {
  content: "\e908";
}

.icon-checkmark-circle-solid:before {
  content: "\e909";
}

.icon-exclamation-circle-solid:before {
  content: "\e90a";
}

.icon-information-circle-solid:before {
  content: "\e90b";
}

.icon-close:before {
  content: "\e90c";
}

.icon-phone:before {
  content: "\e90d";
}

.icon-warning-triangle-solid:before {
  content: "\e90e";
}

.icon-checkmark-circle-outline:before {
  content: "\e90f";
}

.icon-exclamation-circle-outline:before {
  content: "\e910";
}

.icon-information-circle-outline:before {
  content: "\e911";
}
```

### Install icon font with npm

Navigate to the root folder of your project and run:

```js
npm install @cdssnc/gcds-fonts
```

Place the following code in your CSS and replace `path/to/node_modules` with the location where you've added the node modules:

```css
<!-- GC Design System Fonts - Icons -->
@font-face {
  font-family: "gcds-icons";
  src: url("path/to/node_modules/@cdssnc/gcds-fonts/fonts/icons/gcds-icons.eot");
  src: url("path/to/node_modules/@cdssnc/gcds-fonts/fonts/icons/gcds-icons.eot#iefix")
      format("embedded-opentype"), url("path/to/node_modules/@cdssnc/gcds-fonts/fonts/icons/gcds-icons.ttf")
      format("truetype"),
    url("path/to/node_modules/@cdssnc/gcds-fonts/fonts/icons/gcds-icons.woff") format("woff"),
    url("path/to/node_modules/@cdssnc/gcds-fonts/fonts/icons/gcds-icons.svg") format("svg");
  font-weight: normal;
  font-style: normal;
  font-display: block;
}

[class^="icon-"],
[class*=" icon-"] {
  /* use !important to prevent issues with browser extensions that change fonts */
  font-family: "gcds-icons" !important;
  speak: never;
  font-style: normal;
  font-weight: normal;
  font-variant: normal;
  text-transform: none;
  line-height: 1;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
}

.icon-chevron-down:before {
  content: "\e900";
}

.icon-chevron-left:before {
  content: "\e901";
}

.icon-chevron-right:before {
  content: "\e902";
}

.icon-chevron-up:before {
  content: "\e903";
}

.icon-external:before {
  content: "\e904";
}

.icon-email:before {
  content: "\e905";
}

.icon-download:before {
  content: "\e906";
}

.icon-warning-triangle-outline:before {
  content: "\e907";
}

.icon-search:before {
  content: "\e908";
}

.icon-checkmark-circle-solid:before {
  content: "\e909";
}

.icon-exclamation-circle-solid:before {
  content: "\e90a";
}

.icon-information-circle-solid:before {
  content: "\e90b";
}

.icon-close:before {
  content: "\e90c";
}

.icon-phone:before {
  content: "\e90d";
}

.icon-warning-triangle-solid:before {
  content: "\e90e";
}

.icon-checkmark-circle-outline:before {
  content: "\e90f";
}

.icon-exclamation-circle-outline:before {
  content: "\e910";
}

.icon-information-circle-outline:before {
  content: "\e911";
}
```

## How to use icons

Open the [icons overview]() to see a list of all available GC Design System icons and find the icon class name of the icon you want to use. Apply the class to any HTML element where you want the icon to appear. Replace `icon-name` with the specific class name for the icon you want to use.

```html
<span class="icon-name"></span>
```

If you want to use the close icon, for example, you need to add the class `icon-close`:

```html
<span class="icon-close"></span>
```

## Example

Open the [icons overview]() to see a list of all available GC Design System icons. You can find the code for the icons overview page in the [examples folder](https://github.com/cds-snc/gcds-fonts/tree/main/examples/icons).
