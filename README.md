# lab-assignment-1
Base project for lab assignment 1

1. Elements
	- The head
	<head>:  Defines the information about the document
	<meta>: Describe metada
	<link>: Link to an external style sheet
	<title>: Defines the title of the document
	- The body
	<body>: Defines the document's body.
	<center>: Defines the centered text.
	<table id =”hmain” border=”0” cellpadding=”0” cellspacing=”0” width=”85%” bgcolor=”#f6f6ef”>: Defines the bigger table with an id, a borde,r a cellpadding, a cellpacing, a width and a background color.
	<tbody>: Groups the body content in this table.
	<tr>: Defines a row in this table.
	- From here is the heading cell
	<td bgcolor=”ff6600”>: Defines the heading cell in this table with a background color
	<table border="0" cellpadding="0" cellspacing="0" width="100%" style="padding:2px">: Defines the headings table with a new style.
	<tbody><tr>: Groups and defines a row in the heading table
	<td style=…>: Defines each cell of the heading’s cell with a specific style
	<a href=”…”>: Defines a hyperlink with a references.
	<img src="y18.gif" width="18" height="18" style="border:1px white solid;">: Defines an image
	<span>: Used to color the heading text
	<b>: Bold text (Hacker News)
	- From here are the news cells
	<table border="0" cellpadding="0" cellspacing="0" class="itemlist">: Defines the news table
	<tbody>: Groups the body content in this table
	<tr class="athing" id"...">: Defines a row in this table with a class and a id.
	<td align="right" valign="top" class="title"><span class="rank">1.</span></td>: Defines the number's cell in this table. In this case is the number one.
	<td valign="top" class="votelinks"><center><a id="up_19378678" href="vote?id=19378678&amp;how=up&amp;goto=newest"><div class="votearrow" title="upvote"></div></a></center></td>: Defines the cell where you can vote.
	<td class="title"><a href="..." class="storylink" rel="nofollow">...</a><span class="sitebit comhead"> (<a href="..."><span class="sitestr">whowhatwhy.org</span></a>)</span></td>: Defines the cell of the new, with the title and a hyperlink with a references
	<td class="subtext">...</td>: Finally, here defines the cell where they show you how many points the news has and when it happened.
	
2. Sources
	The newest file is the HTML code
	https://news.ycombinator.com/hn.js?ok3V8Gydw5sSOFppv3U2 file is where it was programmed.
	https://news.ycombinator.com/news.css?ok3V8Gydw5sSOFppv3U2  file is where they put complementary information about colors and images
	The others 3 files are images that they use on their website.

3. Network
	Xhr request can be used to request data from a web server. A web page can update a part of the page without interrupting what the user is doing.
	The newest file was the first loaded when I press F5, then the others except for the favicon.ico file that was loaded after the page loaded.

4. Security
	The entity that emitted the certificate was COMODO RSA Domain Validation Secure Server SA. Comodo Cybersecurity delivers an innovative cybersecurity platform that renders threats useless, across the LAN, web and cloud. 
	The expiration date of the certificate is 21-08-2019.
	
	
	
	

