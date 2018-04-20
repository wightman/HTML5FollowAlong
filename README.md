# HTML5 Exercise: Follow Along

1. Download the project by clicking on the green "Clone or download" button on the right side of the project page. Choose "Download ZIP".  Move the zip file from the download directory to your own space and extract it.

2. Open the index.html file in a text editor (notepad on widnows) and in a web browser (preferably Google Chrome). You should see the starter text show below in the text editor. Change and save the text "TA DAH" in the p-tags, save the file and refresh it in the browser to see the changes. Notice the indenting in the file. What does it tell you?
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
```html
<html>
	<head>
		<meta charset="utf-8"/>
		<title>It's me, Rick!</title> 		<!-- TODO -->
	</head>
	<!-- This is a comment -->
	<body>
		<h1>Rick Wightman</h1>			<!-- TODO -->
		<hr/>
		<h2>Stuff I Like</h2>
		<!-- Unordered list
      			Want an *ordered* list? Try <ol></ol> tags instead -->
		<ul>
			<li>Playing guitar</li>			<!-- TODO -->
			<li>Jigsaw puzzles</li>			<!-- TODO -->
			<li>Programming on the Web</li>	<!-- TODO -->
		</ul>
  </body>
</html>
```
3. Add an image just above the horizontal rule
```html
<!-- Relative reference to a file - in this case it's
			 in the same directory as the web page -->
	<img src="Rick18.jpeg"> <!-- TODO: add your photo -->
```
4. Add a link just under your picture
```html
<a href="https://www.facebook.com/theWightStuff">Facebook</a> <!-- TODO: add your stuff 
								(Instagram?, snapchat?) -->
<a href="https://twitter.com/wightman">Twitter</a>
<a href="http://linkedin.com/in/rick-wightman-25904a91">LinkedIn</a>
```
Add some multimedia to the bottom of the page using HTML5 media elements. If you have your own stuff,
insert it, otherwise enjoy mine.

5. Audio:
```html
<h2>Some Music</h2>
<!-- This is the HTML5 GoodStuff(tm) Notice that the audio file is in a folder named "music" 
	in the same location as the html file-->
<audio controls>
<source src="music/RiverFlowsInYou.mp3" type="audio/mpeg"> <!-- TODO: add your stuff -->
	Your browser does not support the HTML5 audio element.
</audio>
```
6. Video:
```html
<h2>Family Video</h2>
<!-- More of the HTML5 GoodStuff(tm) -->
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
8. How about something that you made somewhere else? Insert this after your picture:
```html
<!-- Lots of people make their content available through webAPIs -- even me! -->
	<iframe src="http://wizards.cs.unb.ca/quoteEngine/getQuote" frameborder="0"></iframe>
```
