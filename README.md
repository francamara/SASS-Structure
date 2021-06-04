# SASS-Structure

This is a repo to download and use as a basic structure for a project to be used with SASS.

**Expect future updates**

## Feel free to use it!

I made this for myself, but after my colleage [Rahul Kumar](https://github.com/dlkumaar) told me it was useful for him, I thought it was a good idea to make a generic template to be used in any project.

## How to use?

Download the file as a `.zip`, then insert it in your project however you may need it.

A basic use of it (for a typical html, css and javascript project) would be to have a project structure like this

```bash
/style/
..../sass/
/index.html
```

Then move on the terminal to the `style` folder

```bash
cd style/
```

And start compiling your `sass` code into a `css` file

```bash
sass --watch sass:css
```

This will create a `css` folder, if it doesnt exists, and the style folder will look like this

```bash
/style/
..../css/
..../sass/
/index.html
```

And finally to link the compiled `main.css` file in the `index.html` add the following line in your `<head>` section

```bash
<link rel="stylesheet" href="style/css/main.css">
```

## License

[MIT](https://choosealicense.com/licenses/mit/)
