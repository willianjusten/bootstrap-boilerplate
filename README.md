#BOOTSTRAP BOILERPLATE

A simple boilerplate to create projects with Jade, Bootstrap-Sass and Gulp.

Maybe you want to read about them:
- [GulpJS](http://gulpjs.com/)
- [Jade](http://jade-lang.com/)
- [Twitter Bootstrap](http://getbootstrap.com/)
- [Compass](http://compass-style.org/)

## Getting Started

### Installation

First of all, install the dependencies to run this boilerplate.

- [NodeJS](http://nodejs.org/)
- [GulpJS](http://gulpjs.com/)


```sh
# Clone this repository
$ git clone git://github.com/willianjusten/bootstrap-boilerplate.git new_project
$ cd new_project

# install dependencies
$ npm install
```

With the commands above, you have everything to start.

### Folders and Files

```sh
new_project -
	/build -
		/css
			main.css
		/img
		/js
			main.js
		.htaccess
	/src -
		/img
		/js
			/bootstrap
			main.js
		/sass
			/bootstrap
			main.css
		/templates
		.editorconfig
		gulpfile.js
		package.json
```

### Tasks

- `gulp`: Initialize watch for changes and a server(localhost:8080)
- `gulp js`: execute js files
- `gulp jade`: compile jade files
- `gulp compass`: compile sass files
- `gulp imagemin`:compress image files
- `gulp connect`: inicialize a server
- `gulp watch`: call for watch files
- `gulp -p`: minify all files for production
