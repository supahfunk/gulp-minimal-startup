# README

## Features

- Gulp setup with the following setup:
    - SCSS compiling using libsass (including autoprefixer and minifier: 'last 2 versions', 'Explorer >= 10', 'Android >= 4.1', 'Safari >= 7', 'iOS >= 7')
    - Auto-refreshing dev server using gulp-livereload on localhost:8080 (change your port if you want)
    - Javascript compiled with Babel
    - Code into *src* folder, compiled into *dist*

## Installation

1. Check you have the required dependencies: Node ≥ v0.10 & npm ≥ 2.1.5 `node -v && npm -v`
2. Clone the project `git clone https://github.com/supahfunk/gulp-minimal-startup.git`
3. Install NodeJS dependencies `npm install -d` or if you prefer `yarn install`

## Usage

1. Compile files, start watching files, and start dev server `gulp start`
2. Open the dev server in your brower `localhost:8080` also available on the network using `ComputerName.local:8080`

## Hint

- Be sure that you have installed Ruby & Python (Windows)
- Try `npm install gulp-sass --save-dev` if something goes wrong with Gulp-Sass module

## License

supahfunk/gulp-minimal-startup is released under the MIT license.
"# gulp-startup" 