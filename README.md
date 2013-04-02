CSS3-Tooltips
=============

Pure CSS3 tooltips. No images. No js. 
[Here the demo](http://horaciobella.com/tooltips).

## Usage

First add the .css file.

```html
<link rel="stylesheet" href="tooltips.css" type="text/css" media="screen" />
```

Use this HTML structure to create tooltips:

```html
<a href="#">
	Lorem ipsum
	<span class="tooltip">
		Lorem ipsum dolor sit amet		
	</span>
</a>
```
			
Don't use block elements inside the tooltip. To do so, you have to change the span structure for divs.

## Browsers

### General problems

- The tooltip position is relative to the link, not the cursor.
- Some CSS properties, such as display:none, cause problems with the transition.
- It's not possible to place the tooltip above the link in a dynamic way.

### Internet Explorer
- Everything works correctly from version 9.

## Credits

These tooltips were made by Horacio Bella ([horaciobella.com](http://horaciobella.com)) in the beautiful, creative space provided by Beew ([holabeew.com](http://holabeew.com)) in Rosario, Argentina. They were released to use for free. You can follow me on Twitter ([@horaciobella](http://horaciobella.com)) or contact me by any other mean listed on my site.

Did you like these tooltips? Please [tweet this](http://www.twitter.com/home/?status=Pure+CSS3+tooltips+http://bit.ly/eZiW0K+by+@horaciobella) :-)
