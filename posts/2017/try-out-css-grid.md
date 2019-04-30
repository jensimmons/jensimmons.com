---
title: Here's a Super Quick Way to Try out CSS Grid
summary: A lot of people are getting excited about CSS Grid, and want to learn it. A lot of people are also super busy. So let me teach you some very basic things about Grid.
date: 2017-08-15
tags:
  - css-grid
  - resources
---
A lot of people are getting excited about CSS Grid, and want to learn it. A lot of people are also super busy. So let me teach you some very basic things about Grid, and get you started with a 5-minute taste.

Unlike Bootstrap or any of the other layout frameworks we've been using for the last decade, CSS Grid does not get applied to the entire page with everything on it. 

You define a grid on a specific element. All of the direct children of that element will be placed on that Grid. Nothing else on the page gets involved. 

Start by thinking about what to make a Grid container, and how to structure your markup so you have the Grid items that you want. 

One example:
<pre><code>&#60;ul class="grid-container"&#62;
    &#60;li&#62;grid item&#60;/li&#62;
    &#60;li&#62;grid item&#60;/li&#62;
    &#60;li&#62;grid item&#60;/li&#62;
&#60;/ul&#62;
</code></pre>

Then apply the definition of the grid to your Grid container, in this case, the <code>&#60;ul&#62;</code>.

What is the absolutely most basic way to define a Grid? This CSS:

<pre><code>.grid-container {
    display: grid;
    grid-template-columns: 1fr 1fr 1fr 1fr;
}
</code></pre>

There are many, many, many ways to define a grid, but that's a super basic start. It will create four columns that are all the same width as each other — all one fraction of the available space. 

Playing around with this CSS is one of the best ways to figure it out. To make that easier, I set-up what you need in a CodePen: https://codepen.io/jensimmons/pen/ryGwXO

Try it out. Add more <code>1fr</code>s to the list, and see what happens. Change one of them from <code>1fr</code> to <code>2fr</code>, and see what happens. Add <code>grid-gap: 1rem;</code> to make a space of 1rem between each column.

Ta da! You are using CSS Grid.

<br>
<hr>
<br>
Now that you have a taste, you try out more by going through these basic exercises from my all-day workshop. The answers are in the JavaScript pane. Copy, paste and play.

<section>
<h1>Exercise Set 1</h1>
  <ul>
    <li><a href="http://codepen.io/jensimmons/pen/ryGwXO">Exercise 1 — Make a simple Grid</a></li>
    <li><a href="http://codepen.io/jensimmons/pen/EWRqLe">Exercise 2 — Make a ratio-based Grid</a></li>
    <li><a href="http://codepen.io/jensimmons/pen/peKmzL">Exercise 3 — Make a Responsive Grid</a></li>
    <li><a href="http://codepen.io/jensimmons/pen/jBKobz">Exercise 4 — Explicitly Place Items</a></li>
    <li><a href="http://codepen.io/jensimmons/pen/xqJKdK">Exercise 8 — Make a simple Grid</a></li>
    <li><a href="http://codepen.io/jensimmons/pen/QpBLgr">Exercise 9 — Place items on that Grid</a></li>
  </ul>
</section>

<section>
<h1>Exercise Set 2</h1>
  <ul>
    <li><a href="http://codepen.io/jensimmons/pen/XMBraw">Exercise 10 — Make the items overlap </a></li>
    <li><a href="http://codepen.io/jensimmons/pen/YZjKep">Exercise 11 — Put It All Together</a></li>
    <li><a href="http://codepen.io/jensimmons/pen/BWVeZm">Exercise 5 — Make certain Grid Items bigger</a></li>
  </ul>
</section>

<section>
<h1>Exercise Set 3</h1>
  <ul>
    <li><a href="http://codepen.io/jensimmons/pen/PpaMOq">Exercise 6 — Auto Flow Spare vs Dense</a></li>
    <li><a href="http://codepen.io/jensimmons/pen/qrKejQ">Exercise 7 — Put It All Together</a></li>
  </ul>
</section>