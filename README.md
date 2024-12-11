<<<<<<< HEAD:README.md
# Practical lesson pz-1-12 WEB
> repository contains base tamplate

### Students should create html markups use Bootstrap UI framework.

### Acceptance criteria

* Use css media queries
* Use mobile-first methodology
* Use scss
* Use css variables
* Add sourcemap for scss
* Base template should have slider
* Markups must be adapted according to design and Bootstrap breakpoint

# Directory Structure

Follow this pattern for organization of developed components.

```
├── app
│   ├── css
│   ├── fonts
│   ├── img
│   ├── js
│   ├── libs
│   ├── scss
│   └──  index.html 
├──.editorconfig
├──.gitignore
├──.CHANGELOG.md
├──.gulpfile.js
├──README.md
├──package.json
└── 
```

```
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0, user-scalable=yes"/>
  <title>PZ_1_12</title>
  <link rel="stylesheet" type="text/css" href="css/app.css">
</head>
<body>

<script src="js/bundle.js"></script>

</body>
</html>
```
### Design for 768
<img src="https://user-images.githubusercontent.com/10829855/134765111-3b35611a-88a4-40ed-81d5-c7cb256252dd.png" alt="Design for 768" width="400"/>

### Design for 1024
<img src="https://user-images.githubusercontent.com/10829855/134765182-f2fcbd28-faa6-4fd1-a5e0-54978d4e42c8.png" alt="Design for 1024" width="800"/>

### Design for 1280
<img src="https://user-images.githubusercontent.com/10829855/134765202-aaa8cd10-00e4-4996-a0b9-c8f4956a5d85.png" alt="Design for 1280" width="800"/>

### Design for 1440
<img src="https://user-images.githubusercontent.com/10829855/134765217-933215ac-d606-4d45-888d-45e7fa3cc2aa.png" alt="Design for 1440" width="800"/>

# Useful links
* [Bootsrap](https://getbootstrap.com/).
* [Browsersync + Gulp.js](https://browsersync.io/docs/gulp#gulp-sass-css).
* [Gulp 4: The new task execution system](https://fettblog.eu/gulp-4-parallel-and-series/).
* [Getting started with CSS sourcemaps](https://medium.com/@toolmantim/getting-started-with-css-sourcemaps-and-in-browser-sass-editing-b4daab987fb0).
* [Sourcemaps](https://symfonycasts.com/screencast/gulp/sourcemaps).
* [Створення і використання Source Maps для css і js в GULP 4](https://denis-creative.com/source-maps-gulp-4/#).
=======
# Practical lesson pz-1-6 WEB
> repository contains base tamplate

### Students should create responsive html markups for mobile, table, desktop use different methodology float, flex, grid.
### Acceptance criteria
* Use different files for different methodology 
* Use css media queries
* Use css variables 
* Markups must be adaptive and responsive according to design

### Directory Structure

Follow this pattern for organization of developed components.

```
├── pz-1-6
│   ├── float.html
│   ├── flex.html
│   ├── grid.html
│   ├── css
│   │   ├── float.css
│   │   ├── grid.css
│   │   ├── flex.css
│   │   ├── float-media-query.css
│   │   ├── flex-media-query.css
│   │   ├── grid-media-query.css
│   │   ├── reset.css
│   │   ├── variables.css
│   │   └── media-query.css
│   ├── img
│   │   ├── main-mobile.jpg
│   │   ├── main-table.jpg
│   │   └── main-desktop.jpg
└── 
```

### Markup for mobile
![Screenshot 2021-09-11 at 13 49 43](https://user-images.githubusercontent.com/10829855/132945343-3b7c7532-688b-4a54-9d71-c22268dde74f.png)
### Markup for table
![Screenshot 2021-09-11 at 13 50 02](https://user-images.githubusercontent.com/10829855/132945348-6b3b32ae-221d-434d-93fb-837c5312337b.png)
### Markup for desktop
![Screenshot 2021-09-11 at 13 50 27](https://user-images.githubusercontent.com/10829855/132945359-2b302a46-c4a6-48ff-8160-05623b209a77.png)

# Markup
Scripts should be placed before closing body tag.
 
```
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0, user-scalable=yes"/>
  <title>PZ_1_6</title>
  <link rel="stylesheet" type="text/css" href="css/reset.css">
  <link rel="stylesheet" type="text/css" href="css/variables.css">
</head>
<body>
<header>
</header>
<div class="app-main-wrap">
</div>
<footer>
</footer>
</body>
</html>

```

# Useful links

* [https://caniuse.com](https://caniuse.com/?search=calc).
* [CSS var()](https://www.w3schools.com/css/css3_variables.asp).
* [CSS calc()](https://developer.mozilla.org/en-US/docs/Web/CSS/calc()).
* [A Complete Guide to Flexbox](https://css-tricks.com/snippets/css/a-guide-to-flexbox/).
* [A Complete Guide to Grid](https://css-tricks.com/snippets/css/complete-guide-grid/).
* [All About Floats](https://css-tricks.com/all-about-floats/).
* [Responsive Web Design - Media Queries](https://www.w3schools.com/css/css_rwd_mediaqueries.asp).
* [Практическое применение FlexBox](https://habr.com/ru/post/242545/).


>>>>>>> 1a3be48 (ready):pz-1-6/README.md
