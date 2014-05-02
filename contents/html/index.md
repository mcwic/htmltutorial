---
layout: main
title: Starting HTML
---

# HTML

Open up your text editor and type the following code. Save the file you just created as `page.html`. Now open `page.html` with a web browser. As a result of the code in the left panel, you should see the page in the right panel.

You can also test out all of the following code in your browser by using this very handy tool: [http://www.w3schools.com/html/tryit.asp?filename=tryhtml_basic](http://www.w3schools.com/html/tryit.asp?filename=tryhtml_basic)

<br></br>

<div class="row">
  <div class="col-md-6">

    <div class="panel panel-primary">
      <div class="panel-heading">
        <h3 class="panel-title">Code</h3>
      </div>
      <div class="panel-body">
        <pre><code>&lt;!DOCTYPE html&gt;
&lt;html&gt;
	&lt;head&gt;
		&lt;title&gt;Title of my first page&lt;/title&gt;
	&lt;/head&gt;

	&lt;body&gt;
		My first page!
	&lt;/body&gt;
&lt;/html&gt;
</code></pre>
			</div>
		</div>  
	</div>

	<div class="col-md-6">

    <div class="panel panel-primary">
      <div class="panel-heading">
        <h3 class="panel-title">Result</h3>
      </div>
      <div class="panel-body">
      	My first page!
      </div>
    </div>

  </div>

</div>

---

You've just written you first web page! You deserve some explanation though: what exactly happened between writing the code and text appearing in you browser?

HTML is an acronym for HyperText Markup Language, but what do any of those words mean? The best illustration of HyperText may be the front page of [Wikipedia](https://en.wikipedia.org/wiki/Main_Page). You can click on a featured article, then that article has many other links you can click to other Wikipedia entries. The essence of HyperText is the ability to link between different text documents.

HTML files are composed of tags. The code for a tag looks like this: `<startTag></endTag>`. Tags shape the content of a web page. There are five different tags in the example above, let's go through each of them.

1. The `<!DOCTYPE html>` tag is a message to your browser: "Hey Browser! You're about to read some sweet HTML!" Many tags come in pairs with beginning tag: `<tag>` and an ending tag `</tag>`. The ending tag is the same as the begining tag except the name of the tag starts with a `/`. Notice that `<!DOCTYPE html>` doesn't have an ending tag.

2. When the browser sees the `<html>` tag it is an indication to the browser to start reading HTML code. `</html>` tells the browser that it can stop reading HTML code.

3. Between the `<head>` and `</head>` tags you put lots of goodies. The `<head>` section of an HTML file contains information about the page that won't be displayed in your browser. For now the only piece of information we've put in the head is the `<title>` tag. Whatever text you write inbetween `<title>` and `</title>` will appear in the menu bar of your web browser!

4. And finally, the `<body>` tag contains what will actually appear in your web browser! There are tags you can put in between `<body>` and `</body>`, which we'll be getting into next.

---

<div class="row">
	<div class="col-md-1">
		<a href="../start"><button type="button" class="btn btn-primary btn-lg">Back</button></a>
	</div>
	<div class="col-md-1">
		<a href="../paragraphs"><button type="button" class="btn btn-primary btn-lg">Next</button></a>
	</div>
</div>

---