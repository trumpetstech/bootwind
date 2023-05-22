[//]: # (<p align="center"><a href="https://bootwind.trumpetstech.com/start" target="_blank"><img src="https://bootwind.s3.eu-central-1.amazonaws.com/public/github/logo.png" width="200" height=""></a></p>)

<h3 align="center">Bootwind CSS</h3>

<p align="center">
  A UI library based on BootstrapCSS with utilities like TailwindCSS combining the strengths of both frameworks, providing a powerful toolkit for building 
	attractive and responsive user interfaces with a wide range of styling options and customization possibilities.
</p>

## Install via npm

For most projects (and to take advantage of the customization features), you'll want to install Bootwind CSS and its
peer-dependencies via npm.

```txt
npm install @trumpetstech/bootwind@latest bootstrap@latest --save-dev
```

This will automatically install the latest Bootstrap version, so you don't need to do that manually.

## Create the Sass files

In your `scss` folder create two new files and name them:

- main.scss
- utility.scss

### Import the base styles and components

In your main.scss, you’ll import the source Sass files. Bootstrap is automatically loaded when you use the source files,
so you don't need to worry about what Bootstrap files should you incorporate in your styles.

```scss
@import "@trumpetstech/bootwind/base";
@import "@trumpetstech/bootwind/forms";

// Load all the components
@import "@trumpetstech/bootwind/components";
```

or pick the parts you need:

```scss
@import "@trumpetstech/bootwind/base";
@import "@trumpetstech/bootwind/forms";

// Load only the components you use
@import "@trumpetstech/bootwind/components/alerts";
@import "@trumpetstech/bootwind/components/avatars";
@import "@trumpetstech/bootwind/components/buttons";
@import "@trumpetstech/bootwind/components/navbars";
@import "@trumpetstech/bootwind/components/cards";
```

[**Click here**](https://github.com/trumpetstech/bootwind/blob/master/scss/components/_index.scss) to see the complete
list of available components.

### Import the utility classes

In Bootwind CSS you'll notice that we don't create custom styles, but rather make use of the utility classes. We are
using the new Bootstrap Utility API to generate a comprehensive list of classes.

In your utility.scss you'll import all the utilities:

```scss
@import "@trumpetstech/bootwind/utilities";
```

[//]: # (## Documentation)

[//]: # ()

[//]: # (Check out our [documentation website]&#40;https://bootwind.trumpetstech.com/docs?ref=github&#41;.)

## Integrations

If you want to see how it works, check out these functional examples of using Bootstrap and Bootwind CSS in common JS
frameworks like Webpack, Parcel, Vite, and more!

[See all integrations](https://github.com/trumpetstech/bootwind/tree/master/integrations)

[//]: # (## Detailed UI components library)

[//]: # ()
[//]: # (Explore, copy, use and mix hundreds of carefully crafted components made just for Bootstrap.)

[//]: # ()
[//]: # ([Explore components]&#40;https://bootwind.trumpetstech.com/components?ref=github&#41;)

## Thank you

- [Mark Otto and the Team](https://github.com/twbs/bootstrap)

## License

Made with ❤️ by [Trumpets](https://trumpetstech.com?ref=github). Bootwind CSS is open-sourced software licensed under
the [MIT license](https://github.com/trumpetstech/bootwind/blob/master/LICENSE).
