# Framer.js Template
#### A local development environment for Framer.js prototypes.
This is a simple node/gulp.js build designed to help make developing Framer.js prototypes a bit easier.

## Features
- `index.html` automatically refreshes whenever changes are saved to `app.js`
- Prototypes are accessible to other devices on your local network (use `ifconfig` to get the IP)
  * These devices are also automatically refreshed when changes are made to `app.js`
- Tisho Georgiev’s [Framer Presentation Templates](https://github.com/tisho/framer-templates)
- CoffeeScript compilation

## Installation
You'll need to have node & grunt.js installed ([this guide](http://travismaynard.com/writing/getting-started-with-gulp) is a good starting point).

1. `git clone --depth=1 git@github.com:jenbennings/framer-template.git myawesomeprototypedir` to download a lean version of the repo
2. `rm -rf !$/.git` to remove git (optional)
3. `npm install` to grab the node dependencies
4. Run the `gulp` command
5. It's happening!

![](http://i.imgur.com/vv49C.gif)

## To-do

~~- Add gulp-coffee to gulp tasks~~
- Learn coffeescript :bowtie: