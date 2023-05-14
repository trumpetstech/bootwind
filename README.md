<p align="center"><a href="https://bootwind.trumpetstech.com/start" target="_blank"><img src="https://bootwind.s3.eu-central-1.amazonaws.com/public/github/logo.png" width="200" height=""></a></p>

<h3 align="center">Bootwind CSS</h3>

<p align="center">
  Utility and component-centric Design System based on Bootstrap for fast, responsive UI development.
  <br>
  <a href="https://bootwind.trumpetstech.com/docs"><strong>Explore Documentation »</strong></a>
  <br>
  <br>
  <a href="https://github.com/trumpetstech/bootwind/issues/new?template=bug_report.md">Report bug</a>
  ·
  <a href="https://github.com/trumpetstech/bootwind/issues/new?template=feature_request.md">Request feature</a>
  ·
  <a href="https://bootwind.trumpetstech.com/components/">UI Components</a>
  ·
  <a href="https://bootwind.trumpetstech.com/blog/">Blog</a>
</p>

<p align="center"><a href="https://bootwind.trumpetstech.com/start" target="_blank"><img src="https://bootwind.s3.eu-central-1.amazonaws.com/public/github/products/css.png" ></a></p>

## Install via npm

For most projects (and to take advantage of the customization features), you'll want to install Bootwind CSS and its peer-dependencies via npm.

```txt
npm install @trumpetstech/bootwind@latest bootstrap@latest --save-dev
```

This will automatically install the latest Bootstrap version, so you don't need to do that manually.

## Create the Sass files

In your `scss` folder create two new files and name them:

- main.scss
- utility.scss

### Import the base styles and components

In your main.scss, you’ll import the source Sass files. Bootstrap is automatically loaded when you use the source files, so you don't need to worry about what Bootstrap files should you incorporate in your styles.

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

[**Click here**](https://github.com/trumpetstech/bootwind/blob/master/scss/components/_index.scss) to see the complete list of available components.

### Import the utility classes

In Bootwind CSS you'll notice that we don't create custom styles, but rather make use of the utility classes. We are using the new Bootstrap Utility API to generate a comprehensive list of classes.

In your utility.scss you'll import all the utilities:

```scss
@import "@trumpetstech/bootwind/utilities";
```

## Documentation

Check out our [documentation website](https://bootwind.trumpetstech.com/docs?ref=github).

## Integrations

If you want to see how it works, check out these functional examples of using Bootstrap and Bootwind CSS in common JS frameworks like Webpack, Parcel, Vite, and more!

[See all integrations](https://github.com/trumpetstech/bootwind/tree/master/integrations)

## Detailed UI components library

Explore, copy, use and mix hundreds of carefully crafted components made just for Bootstrap.

[Explore components](https://bootwind.trumpetstech.com/components?ref=github)

## Beautiful designer-made templates

Get your new web design project started with these amazing templates, or copy and paste elements into your existing projects to give them a creative boost.

[Explore templates](https://bootwind.trumpetstech.com/templates?ref=github)

## Community

Get updates on the development of our CSS tool and chat with the project maintainers and community members.

- Follow [@bootwind_](https://twitter.com/intent/user?screen_name=bootwind_) on Twitter
- Get inspired through our designs on [Dribbble](https://dribbble.com/bootwind)
- Read and subscribe to [The Official Bootwind Blog](https://bootwind.trumpetstech.com/blog)
- Join [Github Discussions](https://github.com/trumpetstech/bootwind/discussions)

## Thank you

- [Mark Otto and the Team](https://github.com/twbs/bootstrap)

## License

Made with ❤️ by [Bootwind](https://bootwind.trumpetstech.com?ref=github). Bootwind CSS is open-sourced software licensed under the [MIT license](https://github.com/trumpetstech/bootwind/blob/master/LICENSE).
