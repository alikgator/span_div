<!DOCTYPE html>
<html lang="en">

<head>

  <title>Exercicse on &lt;span&gt; and &lt;div&gt; elements</title>

  <style>

    .highlight {color: crimson; font-weight: bold;}

    li {
      display:inline; padding: 1em; background-color: white; margin-top: 0.5em; border: 1px dashed gray;
          }

    #background1 {background-color: yellow; padding: 2em}

    #background2 {background-color: pink; padding: 2em}

    h2, h1 {
      background-color: white; text-align: center; padding: 0.5em; border:1px dashed gray;
    }

    body {margin-left: 3em; margin-right: 2em;}

    code {background: LightGrey; font-weight: normal}

  </style>

  <meta charset="utf-8">
</head>

<body>


<h1>DIV and SPAN elements in HTML5</h1>

<div id="background1">

  <h2>Use of the <code> &lt;div></code> element </h2>

  <p>
    The <code>&lt;div></code> element is useful in HTML5 for grouping elements such as paragraphs, tables or images for styling purposes. It is not a semantic element. But it includes a paragraph break according to <a href="https://www.thoughtco.com/span-and-div-html-elements-3468185"> this site</a>. <span class="highlight">It is a container.</span>
  </p>


  <p>
    On this page I used the <code>&lt;div></code> tag to put different background colors on the two divisions. I could have also used the semantic element <code> &lt;section></code> because it is a logical and semantic divison into two chapters and both of them are <span class="highlight">block elements</span>, but here it is used for styling purposes.

  </p>

  <p>
    So the division helps to group following elements into blocks :
  </p>


    <ul>
      <li>tables</li>
      <li>images</li>
      <li>paragraphs</li>

    </ul>

</div>


<div id="background2">
  <h2> Use of the <code>&lt;span></code> element</h2>


  <p>
    The <code>&lt;span> </code> element is used for <span class="highlight">inline</span> portion of a text inside a phrase. It is used for one or two words for example in order to give them attributes such as <span class="highlight">style, class, lang, dir, id</span>, all are global attributes.
</div>



</body>

</html>
