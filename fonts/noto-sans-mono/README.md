([Français](#polices-de-système-de-design-gc--noto-sans-mono))

# GC Design System Fonts - Noto Sans Mono

GC Design System code examples use the open-source font `Noto Sans Mono`.

## Installation

### Install `Noto Sans Mono` font with CDN

To use the `Noto Sans Mono` font in your project, place the following code in your CSS or include the [gcds-noto-sans-mono.css](https://github.com/cds-snc/gcds-fonts/blob/main/fonts/noto-sans-mono/gcds-noto-sans-mono.css) file in your project:

```css
<!-- GC Design System Fonts - Noto Sans Mono -->
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

Place the following code in your CSS and replace `path/to/node_modules` with the location where you've added the node modules:

```css
<!-- GC Design System Fonts - Noto Sans Mono -->
@font-face {
  font-family: "Noto Sans Mono";
  src: url("path/to/node_modules/@cdssnc/gcds-fonts@1.0.0/fonts/noto-sans-mono/gcds-noto-sans-mono.woff2") format("woff2"),
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

Open the [`Noto Sans Mono` example]() to see a code example using the `Noto Sans Mono` font. You can find the code for the `Noto Sans Mono` example page in the [examples folder](https://github.com/cds-snc/gcds-fonts/tree/main/examples/noto-sans-mono).

---

# Polices de Système de design GC — Noto Sans Mono

Les exemples de code de Système de design GC utilisent la police à source ouverte `Noto Sans Mono`.

## Installation

### Installer la police `Noto Sans Mono` avec le CDN

Pour utiliser la police `Noto Sans Mono` dans votre projet, placez le code suivant dans votre CSS ou incluez le fichier [gcds-noto-sans-mono.css](https://github.com/cds-snc/gcds-fonts/blob/main/fonts/noto-sans-mono/gcds-noto-sans-mono.css) dans votre projet :

```css
<!-- Polices de Système de design GC — Noto Sans Mono -->
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

### Installer la police `Noto Sans Mono` avec npm

Naviguez jusqu'au dossier racine de votre projet et exécutez :

```js
npm install @cdssnc/gcds-fonts
```

Placez le code suivant dans votre CSS et remplacez `path/to/node_modules` par l'emplacement où vous avez ajouté les modules de Node :

```css
<!-- Polices de Système de design GC — Noto Sans Mono -->
@font-face {
  font-family: "Noto Sans Mono";
  src: url("path/to/node_modules/@cdssnc/gcds-fonts@1.0.0/fonts/noto-sans-mono/gcds-noto-sans-mono.woff2") format("woff2"),
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

## Exemple

Ouvrez l'[exemple `Noto Sans Mono`]() pour voir un exemple de code utilisant la police `Noto Sans Mono`. Vous trouverez le code accompagnant l'exemple `Noto Sans Mono` dans le dossier [exemples](https://github.com/cds-snc/gcds-fonts/tree/main/examples/noto-sans-mono).
