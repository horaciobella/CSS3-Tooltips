CSS3-Tooltips
=============

Pure CSS3 tooltips. No images. No js.

# Usage

First add the .css file.

```<link rel="stylesheet" href="tooltips.css" type="text/css" media="screen" />```

Use this HTML structure to create tooltips:

```<a href="#">

	Lorem ipsum — the content of the link
	
	<span class="tooltip"> — start of the tooltip
	
		Lorem ipsum dolor sit amet — the content of the tooltip
		
	</span> — end of the tooltip
	
</a>```
			
Don't use block elements inside the tooltip. To do so, you have to change the span structure for divs.

# Browsers

## General problems

The tooltip position is relative to the link, not the cursor.

Some CSS properties, such as display:none, cause problems with the transition.

It's not possible to place the tooltip above the link in a dynamic way.

## Internet Explorer
Everything works correctly from version 9.
