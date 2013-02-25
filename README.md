# grunt-link-html

> Insert css and Javascript links into html file

## Getting Started
This plugin requires Grunt `~0.4.0`

If you haven't used [Grunt](http://gruntjs.com/) before, be sure to check out the [Getting Started](http://gruntjs.com/getting-started) guide, as it explains how to create a [Gruntfile](http://gruntjs.com/sample-gruntfile) as well as install and use Grunt plugins. Once you're familiar with that process, you may install this plugin with this command:

```shell
npm install grunt-link-html --save-dev
```

One the plugin has been installed, it may be enabled inside your Gruntfile with this line of JavaScript:

```js
grunt.loadNpmTasks('grunt-link-html');
```

## The "link_html" task

### Overview
In your project's Gruntfile, add a section named `link_html` to the data object passed into `grunt.initConfig()`.

```js
grunt.initConfig({
  link_html: {
    your_target: {
      // Target-specific file lists and/or options go here.
      jsFiles: ['path/to/js/files.js']
      cssFiles: ['path/to/css/files.css']
      targetFiles: ['path/to/html/files.html']
      options: {
        cwd: 'public'
      },
    },
  },
})
```

### Options

#### options.cwd
Type: `String`
Default value: `.`

Path to where to reference all files from (maybe be used for a CDN later).

## Contributing
In lieu of a formal styleguide, take care to maintain the existing coding style. Add unit tests for any new or changed functionality. Lint and test your code using [Grunt](http://gruntjs.com/).

## Release History
_(Nothing yet)_
