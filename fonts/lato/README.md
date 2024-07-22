([Français](#polices-de-système-de-design-gc--lato))

# GC Design System Fonts - Lato

GC Design System headings use the font `Lato`.

## Installation

### Install `Lato` font with CDN

To use the GC Design System font `Lato` in your project, place the following code in your CSS or include the [gcds-lato.css](https://github.com/cds-snc/gcds-fonts/blob/main/fonts/lato/gcds-lato.css) file in your project:

```css
<!-- GC Design System Fonts - Lato -->
@font-face {
  font-family: "Lato";
  src: url("https://cdn.design-system.alpha.canada.ca/@cdssnc/gcds-fonts@1.0.0/fonts/lato/gcds-lato.woff2")
      format("woff2"), url("https://cdn.design-system.alpha.canada.ca/@cdssnc/gcds-fonts@1.0.0/fonts/lato/gcds-lato.woff")
      format("woff");
  font-weight: 700;
  font-style: normal;
}

@font-face {
  font-family: "Lato";
  src: url("https://cdn.design-system.alpha.canada.ca/@cdssnc/gcds-fonts@1.0.0/fonts/lato/gcds-lato-italic.woff2")
      format("woff2"), url("https://cdn.design-system.alpha.canada.ca/@cdssnc/gcds-fonts@1.0.0/fonts/lato/gcds-lato-italic.woff")
      format("woff");
  font-weight: 700;
  font-style: italic;
}

/* Set "Lato" + fallback as the heading font */
h1,
h2,
h3,
h4,
h5,
h6 {
  font-family: "Lato", sans-serif;
  font-weight: 700;
}
```

### Install `Lato` font with npm

Navigate to the root folder of your project and run:

```js
npm install @cdssnc/gcds-fonts
```

Place the following code in your CSS and replace `path/to/node_modules` with the location where you've added the node modules:

```css
<!-- GC Design System Fonts - Lato -->
@font-face {
  font-family: "Lato";
  src: url("path/to/node_modules/@cdssnc/gcds-fonts@1.0.0/fonts/lato/gcds-lato.woff2")
      format("woff2"), url("path/to/node_modules/@cdssnc/gcds-fonts@1.0.0/fonts/lato/gcds-lato.woff")
      format("woff");
  font-weight: 700;
  font-style: normal;
}

@font-face {
  font-family: "Lato";
  src: url("path/to/node_modules/@cdssnc/gcds-fonts@1.0.0/fonts/lato/gcds-lato-italic.woff2")
      format("woff2"), url("path/to/node_modules/@cdssnc/gcds-fonts@1.0.0/fonts/lato/gcds-lato-italic.woff")
      format("woff");
  font-weight: 700;
  font-style: italic;
}

/* Set "Lato" + fallback as the heading font */
h1,
h2,
h3,
h4,
h5,
h6 {
  font-family: "Lato", sans-serif;
  font-weight: 700;
}
```

## Example

Open the [`Lato` example]() to see a list of all heading levels using the GC Design System `Lato` font. You can find the code for the `Lato` example page in the [examples folder](https://github.com/cds-snc/gcds-fonts/tree/main/examples/lato).

---

# Polices de Système de design GC — Lato

Les titres de Système de design GC utilisent la police `Lato`.

## Installation

### Installer la police `Lato` avec le CDN

Pour utiliser la police `Lato` de Système de design GC dans votre projet, placez le code suivant dans votre CSS ou incluez le fichier [gcds-lato.css](https://github.com/cds-snc/gcds-fonts/blob/main/fonts/lato/gcds-lato.css) dans votre projet :

```css
<!-- Polices de Système de design GC — Lato -->
@font-face {
  font-family: "Lato";
  src: url("https://cdn.design-system.alpha.canada.ca/@cdssnc/gcds-fonts@1.0.0/fonts/lato/gcds-lato.woff2")
      format("woff2"), url("https://cdn.design-system.alpha.canada.ca/@cdssnc/gcds-fonts@1.0.0/fonts/lato/gcds-lato.woff")
      format("woff");
  font-weight: 700;
  font-style: normal;
}

@font-face {
  font-family: "Lato";
  src: url("https://cdn.design-system.alpha.canada.ca/@cdssnc/gcds-fonts@1.0.0/fonts/lato/gcds-lato-italic.woff2")
      format("woff2"), url("https://cdn.design-system.alpha.canada.ca/@cdssnc/gcds-fonts@1.0.0/fonts/lato/gcds-lato-italic.woff")
      format("woff");
  font-weight: 700;
  font-style: italic;
}

/* Set "Lato" + fallback as the heading font */
h1,
h2,
h3,
h4,
h5,
h6 {
  font-family: "Lato", sans-serif;
  font-weight: 700;
}
```

### Installer la police `Lato` avec npm

Naviguez jusqu'au dossier racine de votre projet et exécutez :

```js
npm install @cdssnc/gcds-fonts
```

Placez le code suivant dans votre CSS et remplacez `path/to/node_modules` par l'emplacement où vous avez ajouté les modules de Node :

```css
<!-- Polices de Système de design GC — Lato -->
@font-face {
  font-family: "Lato";
  src: url("path/to/node_modules/@cdssnc/gcds-fonts@1.0.0/fonts/lato/gcds-lato.woff2")
      format("woff2"), url("path/to/node_modules/@cdssnc/gcds-fonts@1.0.0/fonts/lato/gcds-lato.woff")
      format("woff");
  font-weight: 700;
  font-style: normal;
}

@font-face {
  font-family: "Lato";
  src: url("path/to/node_modules/@cdssnc/gcds-fonts@1.0.0/fonts/lato/gcds-lato-italic.woff2")
      format("woff2"), url("path/to/node_modules/@cdssnc/gcds-fonts@1.0.0/fonts/lato/gcds-lato-italic.woff")
      format("woff");
  font-weight: 700;
  font-style: italic;
}

/* Set "Lato" + fallback as the heading font */
h1,
h2,
h3,
h4,
h5,
h6 {
  font-family: "Lato", sans-serif;
  font-weight: 700;
}
```

## Exemple

Ouvrez l'[exemple `Lato`]() pour afficher la liste de tous les niveaux de titre utilisant la police `Lato` de Système de design GC. Vous trouverez le code accompagnant l'exemple `Lato` dans le dossier [exemples](https://github.com/cds-snc/gcds-fonts/tree/main/examples/lato).