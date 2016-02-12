## Gulp Starter Kit

A Yeoman generator to start new projects.

> [Yeoman](http://yeoman.io/) is used as main scaffolding system
> [Gulp](http://gulpjs.com/) the task automation tool,
> [Node.js](https://nodejs.org/) Containing
> modern web development tools such as 
> [Babel](http://babeljs.io/) and [BrowserSync](http://www.browsersync.io/).
> Helping you to stay productive following the best practices. A solid starting
> point for both professionals and newcomers to the industry.

### Directory Layout

```
.
├── /app/                       # The source code of the application
│   ├── /assets/                # The main folder for assets
│   ├── /components/            # The application components
│   ├── /data/                  # Json file containing data shared with the templates
│   ├── /layouts/               # The application handlebars layouts
│   └── /pages/                 # The application pages
├── /node_modules/              # 3rd-party libraries and utilities
│── .eslintrc                   # The configuration file from eslint
│── .gitignore                  # Git ignore rules
│── bower.json                  # The main bower dependencies file
│── gulpfile.js                 # The Gulp task manager configuration
│── package.json                # The node.js modules dependencies file
└── README.md                   # Important information related
```

### Getting Started

Just clone the repo:

```shell
$ git clone -o https://jpgcode@bitbucket.org/jpgcode/starterkit-2.0.git
$ cd MyApp
$ npm install                   # Install Node.js components listed in ./package.json
$ bower install                 # Install Bower dependencies listed in ./bower.json
```

### Sub generators

You can easily create a page or component using the sub generators

```shell
$ yo sk:page                    # Create a new page
$ yo sk:component               # Create a new component
```

### Development server

```shell
$ gulp serve                     # Start the static node.js server and runs it in browser
```

This will start a light-weight development server with "live reload" and
synchronized browsing across multiple devices and browsers.

### Generate dist files

```shell
$ gulp build                    # This will generate a dist folder
```

---
Made with ♥ by Jose Pablo Granados ([@jpgcode](https://twitter.com/jpgcode))# gulpAssemble
