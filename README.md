# web-design

Run `npm start` to run Gulp. Your finished site will be created in a folder called `docs`, viewable [here](http://localhost:8000).  
To create compressed, production-ready assets, run `npm run build`.

The `docs` folder contains the CSS and JS files that can be used for any website hosted on `dappsociety.github.io`. To include the CSS & JS into a website reference it like this:

```html
<head>
  <link rel="stylesheet" href="https://dappsociety.github.io/web-design/assets/css/app.css">
</head>
<body>
...
  <script src="https://dappsociety.github.io/web-design/assets/js/app.js"></script>
</body>

```

Or you could copy the files from `docs/assets/` directly.

#### Commits on `master` affecting the `docs` folder should only be made when the whole code in `docs` works perfectly.

**Development should stay on `dev` and branches based on `dev`**
