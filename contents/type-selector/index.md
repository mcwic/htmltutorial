---
layout: main
title: Type Selector
---

# Type Selector

When writing CSS, you don't have to specify a class. In fact, you can modify all of the HTML tags of a specific type by using a type selector. Type selectors will change every instance of a paragraph `<p>` to have a red text color if you specify `p { color: blue }` in your CSS. 

Some type selectors have "pseudo-classes." A pseudo-class is tied to a type selector, and unlike regular classes they are usually defined for you. The syntax of a pseudo class is `type-selector:pseudo-class { /* Some properties & values here */ }`. An example of using a pseudo class is illustrated below with the link tag (`<a>`). 

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
    &lt;title&gt;Type Selectors!&lt;/title&gt;
    &lt;style&gt;
      p { color: red }
      a:hover { color: blue }
      a:visted { color: purple }
    &lt;/style&gt;
  &lt;/head&gt;

  &lt;body&gt;
    &lt;p&gt;Roses are red.&lt;/p&gt;
    &lt;p&gt;Violets are... wait they're also red?!?&lt;/p&gt;
    &lt;a href="http://www.dominosugar.com/"&gt;Sugar is sweet, &lt;/a&gt;
    &lt;a href="http://mcwic.github.io/htmltutorial/"&gt;And this link isn't blue!&lt;/a&gt;
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
        <p style="color: red">Roses are red.</p>
        <p style="color: red">Violets are... wait they're also red?!?</p>
        <a href="http://www.dominosugar.com/">Sugar is sweet, </a>
        <a style="color:purple" href="http://mcwic.github.io/htmltutorial/">And this link isn't blue!</a>
      </div>
    </div>

  </div>
</div>

---

<div class="row">
  <div class="col-md-1">
    <a href="../font"><button type="button" class="btn btn-primary btn-lg">Back</button></a>
  </div>
  <div class="col-md-1">
    <a href="../span"><button type="button" class="btn btn-primary btn-lg">Next</button></a>
  </div>
</div>

---