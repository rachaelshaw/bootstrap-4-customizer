# Quick Bootstrap 4 Customizer
A quick way to compile custom-themed [Bootstrap 4](http://getbootstrap.com/) css.

## To use:

#### 1. Install `node-sass`:

```
$ npm install -g node-sass
```

#### 2. Customize:

Clone this repo, then add your variable overrides to `scss/custom.scss` to update colors/fonts/etc. for this project. (See the [Bootstrap 4 theming docs](http://getbootstrap.com/docs/4.0/getting-started/theming/))
 for more info.

> Note: the scss included here is from Bootstrap v4.0.0-beta.2, so if you need to compile from a different version, just replace the contents of the folder with the contents of `scss/bootstrap-scss` from the proper [release](https://github.com/twbs/bootstrap/releases).

#### 3. Build:
`cd` into this project's directory on the command line, then run:

```
$ npm run compile
```

#### 4. Use:

Your freshly-compiled, custom-themed bootstrap.css file will be generated in `css/bootstrap.css`.
