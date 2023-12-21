# Nathan's Basic Site Template

This is a website template designed to help people get a basic landing page on the web.

## How to Use

1. Download the latest [release](https://github.com/nathnp/Basic-Site-Template/releases)

2. Unzip the download, and open `index.html`

## How & What to Edit

### Title

`SITE TITLE` is the title of your site, replace `SITE TITLE` with what you want.

### Nav Links

You can add links at the top of your site by editing the `nav` section. Replace `LINK` with the URL of your link (don't delete the quotes). Then replace `LINK X` with the link title.

For example
```HTML
<li>
	<a href='https://nthp.me'>My Website</a>
</li>
```

### Picture

Add a picture to the `pics` folder. The replace `FILENAME` with the name of the picture file. Try to keep the file size small. 

Example
```HTML
<img src='/pics/profile.png' width='256' height='256'/>
```

### Body

Replace `ABOUT YOU` with a small bit about you.

### Footer

Replace `NAME` with your name in the copyright section.

## Adding More

### More Links

Extra links can be added to the nav bar easily. Simply copy the code listed in [Nav Links](https://github.com/nathnp/Basic-Site-Template/tree/Dev#nav-links) section, and paste it above `</ul>`. To add a link in your main area, follow this example using the `a` tag.
```HTML
This is a test <a href='https://nthp.me'>link</a>
```
### More Images

Just add your image to the pics folder, and use the `img` tag.
```HTML
<img src='/pics/file.png'/>
```
If you would like to add an image from elsewhere on the web, add the image's link in the `src` field.
```HTML
<img src='https://i258.photobucket.com/albums/hh253/jimifunguzz/rick-astley-dancing.gif'/>
```
