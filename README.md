<!doctype html>
<html>
<head>

<link rel="stylesheet" type="text/css" href="tag.css">

<!-- tag structure -->
<!-- tag frameset-->

<!--cols-->
<!-- <frameset cols="20%,40%,40%">
	<frame src="/html/a.html"></frame>
	<frame src="/html/b.html"></frame>
	<frame src="/html/c.html"></frame>
</frameset> -->

<!--rows-->
<!-- <frameset rows="50%,50%">
<frame src="/.html"></frame>
</rameset>
 -->

<!--cols rows-->
<!-- <frameset cols="25%,25%,*">
<frame src=""></frame>
	<frameset rows="50%,50%">
	<frame src=""></frame>
	<frame src=""></frame>
	</frameset>
</frameset> -->

<!--noframes-->
<!-- <noframes>
<body>browser can not deal frames</body>
</noframes> 
-->

<!-- noresize protype, can not change the frame size-->

<!-- use frame and a#name to jump use js and a.name to change the src
<frameset cols="20%,80%">
<frame src=".html"></frame>
<frame src=".html#a.name"></frame>
</frameset>
-->








</head>
<body >
<!-- tag p -->
<!-- browser will ignore space and new line-->
<p>
   There is four space behind me    . 
   I am in a new line in the htmlfile.</br>
   <xmp></br></xmp>can create a new line.<xmp> a new line?</xmp>
</p>
<!-- tag h -->
<!-- there is just 6 types of heading -->
<h1>This is heading 1</h1>
<h2>This is heading 2</h2>
<h3 ><a name="c4">This is heading 3</a></h3>
<h4>This is heading 4</h4>
<h5>This is heading 5</h5>
<h6>This is heading 6</h6>
<p>heading is not just for bold words. You can use it when coding css </p>
<!-- tag h align-->
<h1 align="center">This is heading 1</h1>
<!--tag hr-->
<!--this is horizon line-->
<p>tag hr is used for horizon line</p>
<hr/>
<p>This is a paragraph</p>
<hr/>
<p bgcolor = "red">This is a paragraph</p>
<hr/>

<!-- tag b-->
<b>This text is bold</b>
<!-- tag strong-->
<strong>This text is strong</strong>
<!-- tag big-->
<big>This text is big</big>
<!--tag emphasized-->
<em>This text is emphasized</em>
<!--tag italic-->
<i>This text is italic</i>
<!--tag small-->
<small>This text is small</small>
<!--tag subscript-->
<p>This text contains <sub>subscript</sub></p>
<!--tag supscript-->
<P>This text contains <sup>supscript</sup></P>

<!-- tag pre-->
<pre>Tag pre can be used for      
 space and     enter
</pre>

<!--those tags use for computer coding-->
<!--inline element-->
<!-- tag code-->
<code>Computer Code</code>
</br>
<!-- tag kbd-->
<kbd>Keyboard input</kbd>
</br>
<!-- tag tt-->
<tt>Teletype text</tt>
</br>
<!--tag samp-->
<samp>Sample text</samp>
</br>
<!-- tag var-->
<var>Computer variable</var>
</br>

<!-- tag addr-->
<address>mmmm</address>

<!--tag abbr
use title to show all message
ie5 just support acronym
Netscape 6support abbr and acronym-->
<abbr title="World Wide Web">www</abbr>

<!-- tag bdo   inline element
	bi-directional override 
-->
</br>
<bdo dir = "rtl">read it in another direction</bdo>


<!-- tag blockquote    block element 
will add tag-space and padding
-->
<blockquote>this is blockquote</blockquote>
<!-- tag q    inline element
-->
<q>sss</q>

<!-- tag del  inline element
delete text
-->
<del>this tag is used for deleting text</del>

<!-- tag ins  inline element
	underline text
-->
<ins>this is used for underline tet</ins>


<!-- links tag-->
<!-- tag a -->
<a href="">this is a link </a>
</br>
<a href="" target="_blank"><img src=""/></a>
</br>
<p>target protype is used to set where to open the link, _blank means open it in a new window, _top means open it in this window</p>
</br>
<a href="#c4">click me to jump to another position in this window</a>
</br>
<a href="mailto:email address?subject=">sent address</a>
<a href="mailto:email address?cc=some@microsoft.com&bcc=some@microsoft.com&subject=summer,&body=you,,">sent address</a>


<!--form-->
<!-- unorder form-->
<!-- tag ul
	tag li
-->
<ul>
	<li>this is list one</li>
	<li>this is list two</li>
	<li>this is list three</li>
	<li>this is list four</li>
</ul>

<!-- order table-->
<!-- tag ol-->
<ol>
	<li>this is first</li>
	<li>this is second</li>
	<li>this is third</li>
</ol> 
<!-- protype start-->
<ol start="101">
	<li>this is first</li>
	<li>this is second</li>
	<li>this is third</li>
</ol> 
<!-- protype type
ol type can determine the number  
ul type can determne the symbol
-->
<ol type="a">
	<li>this is first</li>
	<li>this is second</li>
	<li>this is third</li>
</ol>
<ol type="A">
	<li>this is first</li>
	<li>this is second</li>
	<li>this is third</li>
</ol>
<ol type="I">
	<li>this is first</li>
	<li>this is second</li>
	<li>this is third</li>
</ol>
<ol type="i">
	<li>this is first</li>
	<li>this is second</li>
	<li>this is third</li>
</ol>
<!-- ul or ol can be used in an table-->
<ol type="1.1">
	<li>this is first</li>
	<ol type="i">
	<li>this is first</li>
	<li>this is second</li>
	<li>this is third</li>
</ol>
	<li>this is second</li>
	<li>this is third</li>
</ol>
<dl>
<dt>1</dt>
<dt>8</dt>
<dd>2</dd>
<dd>3</dd>
<dt>1</dt>
<dd>2</dd>
<dt>4</dt>
<dd>3</dd>
</dl>


<!--form-->
<!--type text-->
<form>
	E-mail<input type="text">
</form>
<!-- type password-->
<form>
	input your password<input type="password">
</form>
<!-- type checkbox-->
<form>
	do you like china<input type="checkbox">
</form>
<!-- type radio and type name 
	if input have the same name and they have radio type,then you can just choose one checkbox
-->
<form>
	0-18<input type="radio" name="age">
	19-30<input type="radio" name="age">
	31-50<input type="checkbox"name="age">
</form>
<!--tag button-->
<form>
	<input type="button" value="click me">

</form>

<!-- tag select
	 tag option
-->
<form>
	<select name="section">
		<option value="1">one</option>
		<option value="2">two</option>
		<option value="3">three</option>
	</select>
</form>
<!--tag textarea-->
	<textarea col="30",row="1000">23</textarea>
<!-- tag fieldset-->
<!-- tag legend-->
<fieldset>
	<legend>your information</legend>
	hright<input type="text">
	weight<input type="text">
</fieldset>


<!-- table-->
<!-- tr td-->
<!-- type border determine border width
	if border is 0 or there is no border then the table have no border
	cellpaading
	bgcolor
	background
	align
	frame= above below box vside hside
-->
</br>
<table frame="vsides" cellpadding="20"  >
	<tr>
		<td align="right">1</td>
		<td>300</td>
		<td>500</td>
	</tr>
	<tr>
		<td>200</td>
		<td>300</td>
		<td>400</td>
		<td>600</td>
	</tr>
	<tr>
		<td>900</td>
	</tr>
</table>
<!-- tag th
	 tag t
-->
<table border="20">
	<tr>
	<th>1</th>
	<th>2</th>
	</tr>
	<tr>
	<td>2</td>
	<td>3</td>
	</tr>
</table>
<!-- tag th
	-->
<table>
	<tr>
		<th>姓名</th>
		<td>x</td>
	</tr>
	<tr>
		<th>年纪</th>
		<td>18</td>
	</tr>
</table>

<table border="1">
	<caption>caotion</caption>
	<tr>
		<th>
			name
	</th>
	<td>23</td>
</tr>
</table>
<table border="1">
	<tr>
		<th>name</th>
		<th colspan="3">age</th>
	</tr>
	<tr>
		<td>1</td>
		<td>1</td>
		<td>3</td>	
	</tr>
</table>
<table border="2">
	<tr>
		<th>name</th>
		<td>bob</td>
	</tr>
	<tr>
		<th rowspan="2">age</th>
		<td>2</td>	
	</tr>
		<tr><td>2</td></tr>
</table>


<form action="MAILTO:sdf@qq.com" method="post" enctype="text/plain">
	First name:</br>
	<input type="text" value="bob">
	</br>
	E-mail:</br>
	<input type="text" value="xxx@job.com">
	</br>
	your contant
	</br>
	<input type="text" value="show me your message">
	</br>
	<input type="submit" value="send">
	<input type="reset" value="reset"></input>

</form>

<script src = "js_stack.js"></script>
<script src = "queue.js"></script>
<script src = "thornBird.js"></script>

</body>







</html>
