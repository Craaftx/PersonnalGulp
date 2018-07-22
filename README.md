# Personnal Gulp Workflow

Here is it ! This workflow **Gulp** help front developer to make some repetitive tasks and create a better developpement environnement :

#### FEATURES :
> gulp-less: **Transform LESS to CSS**
> gulp-autoprefixer: **Prefix CSS**
> gulp-clean-css: **Minify CSS**
> gulp-rename: **Rename file with .min**
> gulp-uglify: **Minify Javascript**
> gulp-concat: **Concat files**
> gulp-imagemin: **Optimize images**
> gulp-html-extend: **Allow to create HTML Layout like Pug or Mustache**
> gulp-inject: **Used to inject CSS and JS in HTML layout**
> gulp-clean: **Used to clean tmp files**
> gulp-sync: **Allow sync tasks**

<br>
#### FILE STRUCTURE :
```
/root
├── /src
│     ├── /assets
│     │      ├── /css                   // LESS Files
│     │      ├── /img                  // The images that will be optimized
│     │      ├── /js                      // Javascript Files
│     │      └── /vendor             // Vendors like Bootstrap
│     └── /pages
│             ├── /components    // HTML Components (ex : navbar)
│             ├── /layouts             // HTML Layouts
│             └── .html_files          // HTML Files are created in pages directory
│
└── /dist      // Production project deposed here
```

<br>
#### REALTIME ?
You can use `gulp watch` who will continuously monitor all changes made to the LESS and HTML files and automatically launch the corresponding tasks in real time.

In addition, I use Visual Studio Code with the [Live Server](https://github.com/ritwickdey/vscode-live-server)  extension to have real-time changes on my browser when I develop.

<br>
#### TODO
- Add images injection like CSS and JS files
- Increase realtime fonctionnality
- Be like [this](https://coub.com/view/17c0vx)

<br>
## Built With
* [Gulp](https://gulpjs.com/) - Gulp is a toolkit for automating painful or time-consuming tasks in your development workflow, so you can stop messing around and build something. 

