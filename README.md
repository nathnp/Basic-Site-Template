# Nathan's Basic Site Template

This is a website template designed to help people get a basic landing page on the web.

This template uses [nthp.me-css](https://css.nthp.me) for its CSS.

A demo can be found at [bstdemo.nthp.me](https://bstdemo.nthp.me), the demo's `index.html` file can be found [here](https://github.com/nathnp/Basic-Site-Template/blob/Demo/index.html).

## How to Use

1. Download the latest [release](https://github.com/nathnp/Basic-Site-Template/releases)

2. Unzip the download, and open `index.html`

3. Edit `index.html` 

4. Upload both `index.html` and `pics` folder to a hosting provider. [GitHub Pages](https://docs.github.com/en/pages/getting-started-with-github-pages) is a good one to get started with

## How & What to Edit

### Title

`SITE TITLE` is the title of your site, replace `SITE TITLE` with what you want. There are two of these. The `SITE TITLE` within the `<title>` tags, will display in the browser's tab. The `SITE TITLE` within the `<h1>` tags, will display on the webpage itself.

### Nav Links

You can add links at the top of your site by editing the `nav` section. Replace `LINK` with the URL of your link (don't delete the quotes). Then replace `LINK X` with the link title.

For example
```HTML
<li>
	<a href='https://nthp.me'>My Website</a>
</li>
```

### Picture

Add a picture to the `pics` folder. Then replace `FILENAME` with the name of the picture file. Try to keep the file size small. 

Example
```HTML
<img src='/pics/profile.png' width='256' height='256'/>
```

### Body

Replace `ABOUT YOU` with a small bit about you.

#### Email

Replace `YOUR EMAIL` with your email address to have a button that will open the visitors email client, and pre fill your address. Or remove the line, if you don't want it.

### Footer

Replace `NAME` with your name in the copyright section.

## Adding More

### More Links

Extra links can be added to the nav bar easily. Simply copy the code listed in [Nav Links](https://github.com/nathnp/Basic-Site-Template/tree/Dev#nav-links) section, and paste it above `</ul>`. To add a link in your main area, follow this example using the `a` tag.
```HTML
This is a test <a href='https://nthp.me'>link</a>
```
You can also turn a link into a button, like so
```HTML
<a class='button' href='https://nthp.me'>link</a>
```
These are best used on their own line.

### More Images

Just add your image to the pics folder, and use the `img` tag.
```HTML
<img src='/pics/file.png'/>
```
If you would like to add an image from elsewhere on the web, add the image's link in the `src` field.
```HTML
<img src='https://i258.photobucket.com/albums/hh253/jimifunguzz/rick-astley-dancing.gif'/>
```

### Highlighting Text

Text can be highlighted in two main ways.
The code tag
```HTML
This is some text with <code>the code tag</code>
```
And with the mark tag
```HTML
This is some text with <mark>The mark tag</mark>
```