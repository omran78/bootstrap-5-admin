# [Volt - Bootstrap 5 Dashboard](https://demo.themesberg.com/volt/) [![Tweet](https://img.shields.io/twitter/url/http/shields.io.svg?style=social&logo=twitter)](https://twitter.com/intent/tweet?url=https%3A%2F%2Fgithub.com%2Fthemesberg%2Fvolt-bootstrap-5-dashboard&via=themesberg&text=Volt%20-%20Open%20Source%20Bootstrap%205%20Admin%20Dashboard)

 ![version](https://img.shields.io/badge/version-1.0.0-blue.svg) ![license](https://img.shields.io/badge/license-MIT-blue.svg) [![GitHub issues open](https://img.shields.io/github/issues/themesberg/volt-bootstrap-5-dashboard.svg?maxAge=2592000)](https://github.com/themesberg/volt-bootstrap-5-dashboard/issues?q=is%3Aopen+is%3Aissue) [![GitHub issues closed](https://img.shields.io/github/issues-closed-raw/themesberg/themesberg/volt-bootstrap-5-dashboard.svg?maxAge=2592000)](https://github.com/themesberg/volt-bootstrap-5-dashboard/issues?q=is%3Aissue+is%3Aclosed)

<a href="https://demo.themesberg.com/volt/">
 <img src="https://themesberg.s3.us-east-2.amazonaws.com/public/products/volt-bootstrap-5-dashboard/volt-bootstrap-5-dashboard-preview.jpg" alt="Volt Bootstrap 5 Dashboard Preview"/>
 </a>

Volt is a free and open source Bootstrap 5 Admin Dashboard featuring over 100 components, 11 example pages and 3 customized plugins. Volt **does not require jQuery** as a dependency meaning that every library and script's are jQuery free.

## Bootstrap 5 Components

Because it is created using the latest version of Bootstrap 5, every components and element is based on the latest Bootstrap 5 Sass variables and HTML markup. Check out the documentation of the components [here](https://themesberg.com/docs/volt-bootstrap-5-dashboard/components/accordions/).

## 11 Example pages

We created no less than 11 advanced example pages such as the overview page, transactions, user settings, sign in and sign up and many more.

## Full documentation

Every component, plugin and getting started is thoroughly documented on our [online documentation](https://themesberg.com/docs/volt-bootstrap-5-dashboard/getting-started/quick-start/).

## Workflow

This product is built using the following widely used technologies:

- Most popular CSS Framework Bootstrap
- Productive workflow tool Gulp
- Awesome CSS preprocessor Sass

## Table of Contents

* [Demo](#demo)
* [Quick Start](#quick-start)
* [Documentation](#documentation)
* [File Structure](#file-structure)
* [Browser Support](#browser-support)
* [Resources](#resources)
* [Reporting Issues](#reporting-issues)
* [Technical Support or Questions](#technical-support-or-questions)
* [Licensing](#licensing)
* [Useful Links](#useful-links)

## Demo

| Dashboard | Transactions | Settings | Forms |
| --- | --- | --- | --- |
| [![Dashboard](https://themesberg.s3.us-east-2.amazonaws.com/public/products/volt-bootstrap-5-dashboard/github/dashboard.jpg)](https://demo.themesberg.com/volt/pages/dashboard/dashboard.html) | [![Transactions](https://themesberg.s3.us-east-2.amazonaws.com/public/products/volt-bootstrap-5-dashboard/github/transactions.jpg)](https://demo.themesberg.com/volt/pages/transactions.html) | [![Settings](https://themesberg.s3.us-east-2.amazonaws.com/public/products/volt-bootstrap-5-dashboard/github/settings.jpg)](https://demo.themesberg.com/volt/pages/settings.html) | [![Forms](https://themesberg.s3.us-east-2.amazonaws.com/public/products/volt-bootstrap-5-dashboard/github/forms.jpg)](https://demo.themesberg.com/volt/pages/components/forms.html)

| Sign in | Sign up | Forgot password | Reset password |
| --- | --- | --- | --- |
| [![Sign in](https://themesberg.s3.us-east-2.amazonaws.com/public/products/volt-bootstrap-5-dashboard/github/signin.jpg)](https://demo.themesberg.com/volt/pages/examples/sign-in.html) | [![Sign up](https://themesberg.s3.us-east-2.amazonaws.com/public/products/volt-bootstrap-5-dashboard/github/signup.jpg)](https://demo.themesberg.com/volt/pages/examples/sign-up.html) | [![Forgot Password](https://themesberg.s3.us-east-2.amazonaws.com/public/products/volt-bootstrap-5-dashboard/github/forgot-password.jpg)](https://demo.themesberg.com/volt/pages/examples/forgot-password.html) | [![Reset password](https://themesberg.s3.us-east-2.amazonaws.com/public/products/volt-bootstrap-5-dashboard/github/forgot-password.jpg)](https://demo.themesberg.com/volt/pages/examples/reset-password.html)

| Lock Profile | 404 Not Found | 500 Server Error | Documentation |
| --- | --- | --- | --- |
| [![Lock Profile](https://themesberg.s3.us-east-2.amazonaws.com/public/products/volt-bootstrap-5-dashboard/github/lock.jpg)](https://demo.themesberg.com/volt/pages/examples/lock.html) | [![404 Not Found](https://themesberg.s3.us-east-2.amazonaws.com/public/products/volt-bootstrap-5-dashboard/github/404.jpg)](https://demo.themesberg.com/volt/pages/examples/404.html) | [![500 Server Error](https://themesberg.s3.us-east-2.amazonaws.com/public/products/volt-bootstrap-5-dashboard/github/500.jpg)](https://demo.themesberg.com/volt/pages/examples/500.html) | [![Documentation](https://themesberg.s3.us-east-2.amazonaws.com/public/products/volt-bootstrap-5-dashboard/github/docs.jpg)](https://themesberg.com/docs/volt-bootstrap-5-dashboard/getting-started/quick-start/)

-   [Live Preview](https://demo.themesberg.com/volt/)
-   [Details](https://themesberg.com/product/admin-dashboard/volt-bootstrap-5-dashboard)

## Quick start

1. Download from [Themesberg](https://themesberg.com/product/admin-dashboard/volt-bootstrap-5-dashboard) or clone this repository
2. Download the project's zip
3. Make sure you have Node locally installed.
4. Download Gulp Command Line Interface to be able to use gulp in your Terminal.

```
npm install gulp-cli -g
```

5. After installing Gulp, run npm install in the main `volt/` folder to download all the project dependencies. You'll find them in the `node_modules/` folder.

```
npm install
```

6. Run gulp in the `volt/` folder to serve the project files using BrowserSync. Running gulp will compile the theme and open `/index.html` in your main browser.

```
gulp
```

While the gulp command is running, files in the `assets/scss/`, `assets/js/` and `components/` folders will be monitored for changes. Files from the `assets/scss/` folder will generate injected CSS.

Hit `CTRL+C` to terminate the gulp command. This will stop the local server from running.

## Theme without Sass, Gulp or Npm

If you'd like to get a version of our theme without Sass, Gulp or Npm, we've got you covered. Run the following command:

```
gulp build:dev
```

This will generate a folder `html&css` which will have unminified CSS, Html and Javascript.

## Minified version

If you'd like to compile the code and get a minified version of the HTML and CSS just run the following Gulp command:

```
gulp build:dist
```

This will generate a folder `dist` which will have minified CSS, Html and Javascript.

## Documentation
The documentation for Volt is hosted on our [website](https://themesberg.com/docs/volt-bootstrap-5-dashboard/getting-started/quick-start/).

## File Structure
Within the download you'll find the following directories and files:

```
Volt Bootstrap 5 Admin Dashboard
.
├── README.md
├── gulpfile.js
├── package-lock.json
├── package.json
└── src
    ├── assets
    │   ├── img
    │   └── js
    ├── index.html
    ├── pages
    │   ├── components
    │   ├── dashboard
    │   ├── examples
    │   ├── settings.html
    │   ├── tables
    │   └── transactions.html
    ├── partials
    │   ├── _analytics.html
    │   ├── _footer.html
    │   ├── _head.html
    │   ├── _navigation.html
    │   ├── _pages-preview.html
    │   ├── _preloader.html
    │   ├── _scripts.html
    │   └── dashboard
    └── scss
        ├── volt
        └── volt.scss
```

## Browser Support

At present, we officially aim to support the last two versions of the following browsers:

<img src="https://s3.amazonaws.com/creativetim_bucket/github/browser/chrome.png" width="64" height="64"> <img src="https://s3.amazonaws.com/creativetim_bucket/github/browser/firefox.png" width="64" height="64"> <img src="https://s3.amazonaws.com/creativetim_bucket/github/browser/edge.png" width="64" height="64"> <img src="https://s3.amazonaws.com/creativetim_bucket/github/browser/safari.png" width="64" height="64"> <img src="https://s3.amazonaws.com/creativetim_bucket/github/browser/opera.png" width="64" height="64">

## Resources
- Demo: <https://demo.themesberg.com/volt/>
- Download Page: <https://themesberg.com/product/admin-dashboard/volt-bootstrap-5-dashboard>
- Documentation: <https://themesberg.com/docs/volt-bootstrap-5-dashboard/getting-started/quick-start/>
- License Agreement: <https://themesberg.com/licensing>
- Support: <https://themesberg.com/contact>
- Issues: [Github Issues Page](https://github.com/themesberg/volt-bootstrap-5-dashboard/issues)

## Reporting Issues

We use GitHub Issues as the official bug tracker for Volt Bootstrap 5 Admin Dashboard. Here are some advices for our users that want to report an issue:

1. Make sure that you are using the latest version of Volt Bootstrap 5 Admin Dashboard. Check the CHANGELOG from your dashboard on our [website](https://themesberg.com/docs/volt-bootstrap-5-dashboard/getting-started/changelog/).
2. Providing us reproducible steps for the issue will shorten the time it takes for it to be fixed.
3. Some issues may be browser specific, so specifying in what browser you encountered the issue might help.

## Technical Support or Questions

If you have questions or need help integrating the product please [contact us](https://themesberg.com/contact) instead of opening an issue.

## Licensing

- Copyright 2020 Themesberg (Crafty Dwarf LLC) (https://themesberg.com)
- Themesberg [license](https://themesberg.com/licensing#mit) (MIT License)

## Useful Links

- [More themes](https://themesberg.com/themes) from Themesberg
- [Free themes](https://themesberg.com/templates/free) from Themesberg
- [Bootstrap Themes, Templates & UI Kits](https://themesberg.com/templates/bootstrap) from Themesberg
- [Affiliate Program](https://themesberg.com/affiliate)

##### Social Media

Twitter: <https://twitter.com/themesberg>

Facebook: <https://www.facebook.com/themesberg/>

Dribbble: <https://dribbble.com/themesberg>

Instagram: <https://www.instagram.com/themesberg/>