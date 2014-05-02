---
layout: main
title: Font
---

# Font

Sometimes you have something to say and you need to say it <strong>boldly</strong>! Other times you need the <em>emphasis</em> that only <em>italcs</em> can offer. You can specify boldness with `font-weight: bold` and you can specify italic-ness(?) with `font-style: italic`. If you want to further manipulate how words appear on the page, you can also specify a special font! For now we're only going to cover the <span style="font-family: serif">Serif</span>, <span style="font-family: sans-serif">Sans-Serif</span>, and <span style="font-family: monospace">Monospace</span> style fonts. <span style="font-family: serif">As you can see, serif fonts have pointer details at the ends of the letters.</span><span style="font-family: monospace">In comparison, monospace fonts have the same amount of space between each letter. The space between letters is called the kearning.</span> Most of these tutorials were written in a Sans-Serif font (literally meaning without serif). You can specify the font with the `font-family` property (we'll demonstrate below).

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
    &lt;title&gt;Font!&lt;/title&gt;

    &lt;style&gt;
      .bold-txt{ font-weight: bold }
      .italic-txt{ font-style: italic }
      .serif-txt{ font-family: serif }
      .mono-txt{ font-family: monospace }
    &lt;/style&gt;
  &lt;/head&gt;

  &lt;body&gt;
    &lt;p class="bold-txt"&gt;Hulk smash!&lt;/p&gt;
    &lt;p class="italic-txt"&gt;But why does Hulk smash?&lt;/p&gt;
    &lt;p class="serif-txt"&gt;Have you ever seen a serif seraph?&lt;/p&gt;
    &lt;p class="mono-txt"&gt;There should be a front for U2 called Bonospace!&lt;/p&gt;
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
        <p><strong>Hulk smash!</strong></p>
        <p><em>But why does Hulk smash?</em></p>
        <p><span style="font-family: serif">Have you ever seen a serif seraph?</span></p>
        <p><span style="font-family: monospace">There should be a font for U2 called Bonospace!</span></p>
      </div>
    </div>

  </div>
</div>

---

<div class="row">
  <div class="col-md-1">
    <a href="../text"><button type="button" class="btn btn-primary btn-lg">Back</button></a>
  </div>
  <div class="col-md-1">
    <a href="../type-selector"><button type="button" class="btn btn-primary btn-lg">Next</button></a>
  </div>
</div>

---