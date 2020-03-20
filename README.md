# HTML5 Exercise: Follow Along

1. Download the project by clicking on the green "Clone or download" button on the right side of the project page. Choose "Download ZIP".  Move the zip file from the download directory to your own space and extract it.

2. Open the index.html file in a text editor (notepad on widnows) and in a web browser (preferably Google Chrome). Copy the text below into the text editor. Save the file and refresh the browser to see "TA DAH!". Alo notie the title (text in the tab for the page) has changed. Change and save the text "TA DAH" in the &lt;p&gt;&lt;/p&gt; tags, save the file and refresh it in the browser to see the changes. Notice the indenting in the file. What does it tell you?
```html
<!DOCTYPE html>
<html>
	<head>
		<meta charset="utf-8"/>
		<title>Hello world!</title>
	</head>
	<body>
		<p>TA DAH!</p>
	</body>
</html>
```
2. Add your text to personalize the page
	- change the text in the <title></title> tags to something you'd like
	- add the following text in between the <body></body> tags
```html
		<!-- This is a comment -->
		<h1>Rick Wightman</h1>			<!-- TODO -->
		<hr/>
		<h2>Stuff I Like</h2>
		<!-- Unordered list
      			Want an *ordered* list? Try <ol></ol> tags instead -->
		<ul>
			<li>Playing guitar</li>			<!-- TODO -->
			<li>Jigsaw puzzles</li>			<!-- TODO -->
			<li>Programming on the Web</li>		<!-- TODO -->
		</ul>
```
3. Add an image just above the horizontal rule (&lt;hr/&gt;) tag
```html
	  <!-- Notice the filename - in this case it's in the same directory as the web page -->
		<img src="Rick.jpg"> <!-- TODO: change to your photo -->
```
4. Add a link just under your picture
```html
	  	<br/>
		<a href="https://www.github.com/wightman">Github</a> | <!-- TODO: add your stuff
										(Instagram?, snapchat?) -->
		<a href="http://cs.unb.ca">UNB Faculty of Computer Science</a> |
		<a href="http://cs.unb.ca/profs/wightman">Rick's Faculty Page</a>
		<a href="https://www.instagram.com/rick.wightman/">InstaRick</a>
```
Add some multimedia to the bottom of the page (just before the &lt;/body&gt; tag) using HTML5 media elements. 
If you have your own stuff then insert it, otherwise enjoy mine.

5. Audio:
```html
		<h2>Some Music</h2>
		<!-- This is the HTML5 GoodStuff(tm) Notice that the audio file is inside a folder named "music"
			in the same location as the html file, and so the path to the file reflects this -->
			<audio controls>
				<source src="music/River Flows In You.mp3" type="audio/mpeg">
				Your browser does not support the audio element.
			</audio>
```
6. Video:
```html
		<h2>Family Video</h2>
		<!-- More of the HTML5 GoodStuff(tm). Notice now that the pat is an address (URL) since it's on another 
			machine on the web -->
		<video width="400" controls>
			<source src="http://www.cs.unb.ca/~wightman/LittleWightmansDancing.mp4" type="video/mp4">
				Your browser does not support the HTML5 video element. <!-- TODO: add your stuff -->
		</video>
```
7. Embed a resource from somewhere else:
```html
		<br/>
		<h2>Favourite Cartoon</h2>
		<!-- Lots of people make their content available through webAPIs -->
		<iframe width="560" height="315" 
			src="https://www.youtube.com/embed/GBkT19uH2RQ" frameborder="0" allowfullscreen>
		</iframe> <!-- TODO: add your stuff -->
```
<!-- Sorry. This part isn't available because my server is online during these times. Darn you COVID-19!
8. How about something that you made somewhere else? Insert this after your picture:
```html
	  <!-- Lots of people make their content available through webAPIs -- even me! -->
<!--		<br/>
		<iframe src="http://wizards.cs.unb.ca/quoteEngine/getQuote.py" frameborder="0"></iframe>
```
-->
