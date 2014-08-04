
title: A Little History Lesson
subtitle: From Internet to the World Wide Web
class: segue dark nobackground

---

title: Problems:
class: big
build_lists: true

How can we make computers connect and talk to one another? For this to happen we need:

- Common language at the level of bits

- Physical connection between computers

- Process for sending and processing data

---

title: Language
class: big
build_lists: true

<img src="images/ascii_t_from Computer History Museum.gif">

- Computers encode letters and numbers as sequences of 0's and 1's. Need a shared encoding system in order to share data between computers

- In 1963, ASCII encoding was developed so machines by different manufacturers could share data

- Current standard is Unicode, with most of the web encoded in UTF-8

---

title: Connection
class: big
build_lists: true

<div class="image-block">
	<figure>
		<img src="images/1971_net_map_t arpanet at launch computer history museum.gif">
		<figcaption>ARPANet at launch, 1971</figcaption>
	</figure>
	<figure>
		<img src="images/pdp-10_t-types of computers being linked - from computer history museum.jpg">
		<figcaption>Computers that built the Internet</figcaption>
	</figure>
	<figure>
		<img src="images/1992_nsfnet_backbone_t from computer history museum.gif">
		<figcaption>NSFnet backbone in 1992</figcaption>
	</figure>
</div>

- 1965: First "wide area network connection"
- 1971: ARPANet launches with 14 nodes
- 1983: ARPANet becomes public facing network, with 45 hosts
- 1988: The first WORM. The Internet has an estimated 60,000 hosts
- 1990: ARPANet shuts down, but the Internet now has 300,000 hosts 


---
title: Origin Story
class: dark nobackground quote

In the Beginning, ARPA created the ARPANET.
And the ARPANET was without form and void.
And darkness was upon the deep.
	
And the spirit of ARPA moved upon the face of the network 
	
And ARPA said, 'Let there be a protocol,' and there was a protocol. And ARPA saw that it was good.
	
And ARPA said, 'Let there be more protocols,' and it was so. And ARPA saw that it was good.
	
And ARPA said, 'Let there be more networks,' and it was so.
	
-- Danny Cohen

<footer class="source">Museum Computer Network, <a href="http://www.computerhistory.org/internet_history/">http://www.computerhistory.org/internet_history/</a></footer>

---

title: Protocols and Networks
class: big
build_lists: true

- Protocols: ways of talking

- Networks: connected machines

- Internet as the network of networks

---

title: Internet as Physical
class: big
build_lists: true

<iframe width="560" height="300" src="//www.youtube.com/embed/FB1ZZplQ_34" frameborder="0" allowfullscreen></iframe>

---

title: The World Wide Web
class: big
build_lists: true

<img src="images/berners-lee_t from computer history museum.jpg">

- 1989: Tim Berners-Lee proposes a hypertext system for sharing data
- 1992: MOSAIC web browser
- 1994: CSS is proposed as styling language. Approved in 1996.

---

title: Parts of the Web
class: big
build_lists: true

- HTTP Protocol

- HTML language

- URIs and URLs

- Linked Data

- Web Server and Client

---

title: Evolution of the Web
class: big
build_lists: true

- Web 1.0: First Generation

- Web 2.0: The Social Web

- Web 3.0: The Semantic Web

---

title: Why do we care?
class: big
build_lists: true

Helps us create a mental model of the systems we are using

Very useful when faced with new technologies

Today we will be working with: 

- Text Editor to create an HTML file and a CSS file
- A Web Browser
- Github's Web Servers

---

title: A Word about Browsers
class: big
build_lists: true

- The browser uses the HTML, CSS, Java-script, image files, etc to generate the graphical view 

- To keep things somewhat consistent, the different structural tags are styled generally consistently across browsers

- However, each browser uses different interpreters and so there is variance between browsers and between operating systems

---

title: HTML
subtitle: Let's Write a Web Page
class: segue dark nobackground

---

title: Download Code Examples
class: big
build_lists: true

Go to [https://github.com/jerielizabeth](https://github.com/jerielizabeth)

Click on “Repositories” 

Select “HILT Code Examples” and Download Zip File

---
title: Headers

<pre class="prettyprint" data-lang="html">
	&lt;h1>Top-Level Header&lt;/h1>
	&lt;h2>Second-Level Header&lt;/h2>
	&lt;h3>Third-Level Header&lt;/h3>
	&lt;h4>Forth-Level Header&lt;/h4>
	&lt;h5>Fifth-Level Header&lt;/h5>
	&lt;h6>Sixth-Level Header&lt;/h6>
</pre>

---
title: Standard Text Encodings

<pre class="prettyprint smaller" data-lang="html">
	&lt;p>Paragraphs text:&lt;/p>
	&lt;p>Lorem ipsum dolor &lt;em>sit amet&lt;/em>, 
	elitr concludaturque eu usu. Errem impedit facilis eu eam. 
	&lt;strong>Graeco tacimates elaboraret&lt;/strong> no vis. 
	&lt;a href="http://www.google.com">Link to Google&lt;/a>
	Id quando nominati constituto vim. Vero accusam eum ex.&lt;/p>

	&lt;blockquote>"Begin at the beginning," the King said, very gravely, 
	"and go on till you come to the end: then stop."&lt;/blockquote>

	&lt;ol>
		&lt;li>Ordered List&lt;/li>
	&lt;/ol>

	&lt;ul>
		&lt;li>Unordered List&lt;/li>
	&lt;/ul>
</pre>

---

title: Figures and Images

<pre class="prettyprint smaller" data-lang="html">

	&lt;figure>
		&lt;img src="images/sf.jpg" 
		alt="Moon setting over the San Francisco skyline. By Joe Parks">
		&lt;figcaption>Caption for Image. &lt;a href="https://www.flickr.com/photos/parksjd/9123367798/in/photolist-eUcDoN-dzScgx-9r1YWE-
		b7HmjZ-9m6gmu-9PjGgs-4X6kq9-7KSe8f-byfTLj-by84f2-8Vhmf1-hzdUHF-9rRADb-
		c19dku-5J8WZy-aZFbdV-843wiR-9qySWt-9mA9Bp-b5oKxa-73PK9s-fB4tzX-bzqxbU-hUiq2E-
		keLDPc-5TTbt5-avV3Lf-bDDP7j-2BrmVP-boqx9M-2AzJfG-btG3uS-96UofT-ex6mwr-7TM3AZ-
		awUjwp-bzriGg-b2gwmx-9vW7sq-abiUne-aL8Pz2-9cnhG7-7EbheV-bj88k4-9qs6H6-bjSzTU-
		hEkAuS-bc1rQr-byRJwp-eXFM6v">Image by Joe Parks&lt;/a>.&lt;/figcaption>
	&lt;/figure>

</pre>

---

title: Code

<pre class="prettyprint" data-lang="html">

	&lt;pre>
		The formatting of the text 
			within the "pre" tag is preserved.
	&lt;/pre>

</pre>

---
title: Tables

<pre class="prettyprint" data-lang="html">
	&lt;table>
		&lt;tr>
			&lt;th>Title of Column&lt;/th>
			&lt;th>Title of Column&lt;/th>
			&lt;th>Title of Column&lt;/th>
		&lt;/tr>
		&lt;tr>
			&lt;td>Data Element&lt;/td>
			&lt;td>Data Element&lt;/td>
			&lt;td>Data Element&lt;/td>
		&lt;/tr>
		&lt;tr>
			&lt;td>More Data&lt;/td>
			&lt;td>More Data&lt;/td>
			&lt;td>More Data&lt;/td>
		&lt;/tr>
	&lt;/table>

</pre>

---

title: Structuring the HTML Page

<pre class="prettyprint" data-lang="html">

&lt;!DOCTYPE html> 

&lt;html lang="en"> 

  &lt;head> 

    &lt;meta charset=utf-8> 
    &lt;title>A simple HTML5 page layout&lt;/title>
    &lt;link rel="stylesheet" type="text/css" href="#"> 
  &lt;/head>

  &lt;body> 
    
  &lt;/body>
  	
&lt;/html> 

</pre>
---
title: Putting it all together

[https://github.com/jerielizabeth/HILT-Code-Examples/blob/master/html/internal_structure.html](https://github.com/jerielizabeth/HILT-Code-Examples/blob/master/html/internal_structure.html)

---
title: A Few Things to Consider
class: big
build_lists: true

- Web browser will display text even without HTML tags

- Descriptive HTML tags have advantages for both human and computer readers

- Best practice is to separate structure from presentation

- Browsers may be forgiving, but don't create code that looks like this: [http://documents.adventistarchives.org/Periodicals/Forms/AllItems.aspx?RootFolder=%2fPeriodicals%2fAmSn&FolderCTID=0x012000DDAC5B94CFBD234AB142FC5C311C732700042C85EA7C1C1A4DB8D75C62A7517A6E](http://documents.adventistarchives.org/Periodicals/Forms/AllItems.aspx?RootFolder=%2fPeriodicals%2fAmSn&FolderCTID=0x012000DDAC5B94CFBD234AB142FC5C311C732700042C85EA7C1C1A4DB8D75C62A7517A6E)

---

title: Now it's Your Turn
class: big
build_lists: true

- Create a Folder for the course

- Create a Folder for your web pages inside the course folder

- Using your text editor, create an HTML template with basic structural elements. Save as template.html 

- Use that template to create your CV or personal page. Save as index.html

---

title: Git and Github
class: segue dark nobackground

---

title: What is Git?
class: big
build_lists: true

Git is a version control system

- Keep track of versions of documents

- Maintain multiple versions across multiple locations 

- Runs in the command line or terminal

---

title: What is Github?
class: big
build_lists: true

Github is a social network, hosting platform, and graphical interface of coders using Git.

[github.com](http://www.github.com)


---

title: Key Concepts and Terms
class: big
build_lists: true

- Repository
- Origin
- Clone
- Fork
- Pull
- Push
- Merge
- Branch

---

title: Use Git and Github to Save Your Web Page
class: big
build_lists: true

Step One: We need to tell git that our folder is a git repo.

Step Two: Create the repo (the folder) on Github.

Step Three: Tell your local repository about the one on Github’s servers.

Step Four: Push your local files up to the git repository

---
title: Use Git and Github to Publish Your Web Page
class: big
build_lists: true

Step One: Create the gh-pages branch

Step Two: Remove the template.html file from gh-pages

Step Three: Push up to Github as gh-pages branch

Step Four: Wait a few moments and go to [username].github.io/[repo-name]. 

Step Five: Marvel at your greatness.
---

title: CSS
subtitle: Making Websites Beautiful
class: segue dark nobackground

---

title: Why CSS
class: big
build_lists: true

- Control over the web page display

- Split between structure and presentation

---

title: Ways to Add CSS to a Web Page
class: big
build_lists: true

Inline Citation:
<pre class="prettyprint smaller" data-lang="html">
&lt;body STYLE="background: #000000; color: #80c0c0">
</pre>

Internal Style Sheets:
<pre class="prettyprint smaller" data-lang="html">
&lt;html>
&lt;head>
&lt;title>I am an internal style sheet</title>
&lt;style>
  &lt;!--
    body { background: #000000; color: #80c0c0 }
  -->
&lt;/style>
&lt;/head>
</pre>

External Style Sheets
---

title: Why the Cascade in CSS?
class: big
build_lists: true

Styles cascade down the document

- Set styles on generic and top-level tags, and those will apply to all nested instances

- The last style the computer processes is the style it will apply

- Work from generic to specific

---

title: Common Identifiers
class: big
build_lists: true

- font-family:

- font-size:

- width:

- float:

- padding:

- margin:

- border:

For more, look at [http://dochub.io/#css/](http://dochub.io/#css/)
---

title: Adding CSS to the internal_structure.html file
class: big
build_lists:true

See CSS styling in action

[https://github.com/jerielizabeth/HILT-Code-Examples/tree/master/css](https://github.com/jerielizabeth/HILT-Code-Examples/tree/master/css)

---

title:The Browser Reset
class: big
build_lists:true

To avoid spending time fixing bugs caused by the browser default styling, it is common practice to "reset" the default styles

Eric Meyer's reset is a standard option

[http://meyerweb.com/eric/tools/css/reset/](http://meyerweb.com/eric/tools/css/reset/)

---

title: Add Styles to Your Web Page
class: big
build_lists: true

Check to make sure you're working on the gh-pages branch

1. Create a folder inside your website folder named "css"

2. Create a file "style.css" and save it in the css folder

3. Add a link to the style sheet in your index.html file

---

title: Push your Styles to Github
class: big
build_lists: true

Give it a try