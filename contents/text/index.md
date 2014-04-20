---
layout: main
title: Text
---

# Text

People will come to your website so they can read text that you write! You can customize the text on your site in several ways. 

You can change the color of words on your site by specifying a class and using the `color` property like so: `.blue-txt{ color: blue }`. You can also align text to the right, center, or left using the `text-align` property. Both properties are demonstrated below. In this example we'll also show you how you can use multiple properties in one tag. The syntax looks like: `<tag class="first-class second-class">Your text here!</tag>`.

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
    &lt;title&gt;Text!&lt;/title&gt;

    &lt;style&gt;
      .blue-txt{ color: blue }
      .red-txt{ color: red }
      .right-txt{ text-align: right }
      .center-txt{ text-align: center }
    &lt;/style&gt;
  &lt;/head&gt;

  &lt;body&gt;
    &lt;p class="blue-txt"&gt;I'm blue! (If I was green I would die!)&lt;/p&gt;
    &lt;p class="red-txt"&gt;I'm red!&lt;/p&gt;
    &lt;p class="right-txt"&gt;I'm on the right!&lt;/p&gt;
    &lt;p class="center-txt blue-txt"&gt;I'm in the center and blue!&lt;/p&gt;
  &lt;/body&gt;
&lt;/html&gt;</code></pre>
      </div>
    </div>
  
  </div>
  <div class="col-md-6">

    <div class="panel panel-primary">
      <div class="panel-heading">
        <h3 class="panel-title">Result</h3>
      </div>
      <div class="panel-body">
        <p style="color: blue">I'm blue! (If I was green I would die!)</p>
        <p style="color: red">I'm red!</p>
        <p class="text-right">I'm on the right!</p>
        <p style="color: blue" class="text-center">I'm in the center and blue!</p>
      </div>
    </div>

  </div>
</div>

---

<div class="row">
  <div class="col-md-1">
    <a href="../color"><button type="button" class="btn btn-primary btn-lg">Back</button></a>
  </div>
  <div class="col-md-1">
    <a href="../font"><button type="button" class="btn btn-primary btn-lg">Next</button></a>
  </div>
</div>

---