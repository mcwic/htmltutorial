---
layout: main
title: Color
---

# CSS

You've come a long way if you've made it this far! Believe it or not, you've got the basics of HTML down pretty well! HTML creates the skeleton of a web page, but there are nearly endless ways to style your page! In order to specify this styling, we need to introduce a new language: CSS (an acronym for Cascading Style Sheets).

CSS can be written inside of the `<head>` within the `<style>` tag. The first CSS element we're going to learn about is the "class." You can specify a class with a period (`.`) and the following syntax: `.class-name{ property: value }`. We'll show you some properties and what values you can assign to them soon.

Below, we're going to define the `blue-background` class, and then assign that class to a certain HTML tag. The class of a tag is specified inside the begining of the tag with the following syntax: `<tag class="blue-background">Your text here!</tag>`.

The first CSS property we're going to show you is `background-color`, the effects of which are demonstrated below. Instead of using a color, you can also use an image with the similarly named `background-image` property.


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
    &lt;title&gt;CSS!&lt;/title&gt;
    &lt;style&gt;
      .blue-back{ background-color: blue }
      .yellow-back{ background-color: yellow }
      .red-back{ background-color: red }
      .old-map{ background-image: url(old_map.png) }
    &lt;/style&gt;
  &lt;/head&gt;

  &lt;body&gt;
    &lt;h2 class="blue-back"&gt;I'm surrounded by blue!&lt;/h2&gt;
    &lt;h2 class="yellow-back"&gt;I'm surrounded by yellow!&lt;/h2&gt;
    &lt;h2 class="red-back"&gt;I'm surrounded by red!&lt;/h2&gt;
    &lt;h2 class="old-map"&gt;I could be a map!&lt;/h2&gt;
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
        <h2 style="background-color: blue">I'm surrounded by blue!</h2>
        <h2 style="background-color: yellow">I'm surrounded by yellow!</h2>
        <h2 style="background-color: red">I'm surrounded by red!</h2>
        <h2 style="background-image: url(old_map.png)">I could be a map!</h2>
      </div>
    </div>

  </div>
</div>

---

<div class="row">
  <div class="col-md-1">
    <a href="../images"><button type="button" class="btn btn-primary btn-lg">Back</button></a>
  </div>
  <div class="col-md-1">
    <a href="../text"><button type="button" class="btn btn-primary btn-lg">Next</button></a>
  </div>
</div>

---