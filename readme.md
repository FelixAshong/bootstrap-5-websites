# Bootstrap 5 Websites

> 5 website projects from the [Bootstrap 5 From Scratch]

<img src="screen.png" />

## Demos

- [Ebook Website](https://bootstrapfromscratch.com/ebook-website)
- [Corso Training Website](https://bootstrapfromscratch.com/corso-website)
- [Portfolio Website](https://bootstrapfromscratch.com/portfolio-website)
- [Yavin Office Design Website](https://bootstrapfromscratch.com/yavin-website)
- [Vera Software Solutions Website](https://bootstrapfromscratch.com/vera-website)

## Usage

These projects were built with [Bootstrap](https://getbootstrap.com/) and [Sass](https://sass-lang.com/). They also use [Font Awesome](https://fontawesome.com/) for icons.

To customize any of these websites, you need to install [Node.js](https://nodejs.org/en/) and run the following in the project folder:

```bash
npm install
```

This will install Bootstrap, Sass and Font Awesome. To build your CSS files from Sass, run:

```bash
npm run sass:build
```

To watch your Sass files for changes, run:

```bash
npm run sass:watch
```

For custom stying, use the `scss/styles.scss` file.

To customize Bootstrap, you can add Bootstrap variables to the `scss/bootstrap.scss` file. You can look at the file `node_modules/bootstrap/dist/scss/_variables.scss` for a list of all the variables. Do NOT edit the `variables.scss` file directly, as it will be overwritten when you update Bootstrap.

