---
title: The benefits of learning how to code layouts with CSS
summary: [Summary goes here]
date: 2017-02-28
tags:
  - css
---
Yesterday, I wrote about CSS Grid. Ted Mazer responded by asking <a href="https://twitter.com/tedmazer/status/836533811676647424">on Twitter</a>: “As a beginning front end developer, is it going to be beneficial to jump right into becoming proficient at this layout style?” 

I replied to him on Twitter, (spoiler alert: “yes”), but I have a better answer that’s longer than 140 characters... so, time for a quick morning blog post.

<p style="text-align:center;">• • •</p>

In the beginning, we webmasters used HTML for everything — including styling font colors and doing layout. HTML tables were the one tool we had, and we abused it like crazy. Dark days for code. Bright days for funky, punk rock designs.

After a while, we realized abusing HTML to do styling was horrible. Especially maintaining a site over time. It made redesigning impossible. And quickly got out of control. CSS was invented. We separated content from styling. And we web designers learned how to use floats to do layout. 

Sadly, floats weren’t really a good solution. They are perfect as intended — to float a photo to the side and wrap text around it, for example. But we’ve been using floats to do the whole page layout. And that’s also giant a hack. 

We forged ahead, inventing and teaching each other a few hand-coded techniques for making a handful of layouts. We iterated on those techniques, finely honing them, making them slightly better and better. Search the web for “<a href="https://duckduckgo.com/?q=holy+grail+layout&t=osx&ia=web">holy grail layout</a>”, and you’ll see the trail of evidence. 

But we wanted more options for layouts. So we front-end developers started emerging with new layout patterns, and code libraries for getting each one done. These layouts were too complicated to teach people to hand-code. It was more helpful to make a framework, and pass that around. It started in 2006, with Yahoo YUI. Then came 960 Grid. And then a bunch of variations on 960 Grid. When responsive design hit the scene, a gazillion 12- and 16-column layout frameworks popped up, all handling RWD slightly differently. Then folks leveraged complex  Sass formulas to make powerful toolkits… the list of layout frameworks goes on and on. There are hundreds of options. 

Bootstrap is possibly the most popular such framework, offering a handful of familiar layouts to choose from. There’s the one with the hero graphic at the top, followed by the large centered paragraph, and the three columns of icons — you’ve seen the results of this everywhere. We are completely bored with what happens when <a href="http://www.piedpiper.com">the whole industry</a> reaches for the same two or three templates. 

Get ready for all of that to go away. It’s time to go back to hand-coding layouts for each project. Of course, make reusable code for yourself and your company. Of course, create style guides and limit code chaos. Of course, use a starter-kit of some kind so you aren't beginning each project staring at a blank page. But it’s time to stop assuming your page layout design process looks like this: 1) Pick a third-party framework; 2) Pick one of the layouts that comes with that framework; 3) Limit all your ideas to what that framework can do.

We don't need that crutch anymore. 

I know a <em>lot</em> of people will think the “best” way to use CSS Grid will be to download the new version of Bootstrap (version 5! now with Grid!), or to use any one of a number of CSS Grid layout frameworks that people are inevitably going to make later this year (despite Rachel Andrew and I begging everyone not to). But I don’t. The more I use CSS Grid, the more convinced I am that there is no benefit to be had by adding a layer of abstraction over it. CSS Grid is the layout framework. Baked right into the browser.

I’m tired of every website looking the same. I believe in the power of graphic design to elevate a project. To make it stand out. To give it a unique voice, to help its readers / users / viewers understand what is happening. I don’t want to paint-by-numbers, I want to paint. 

It’s time to design layouts like we design everything else — typography, color — unique to each project. 

How will this be possible? Because now, <em>finally,</em> we have real tools for layout. CSS properties that were created to do layout. CSS Grid, Flexbox, Alignment, Writing Modes, Multicolumn, along with, yes, Floats, Positioning, Inline Block, Display Table — just to name a few. 

People sometime ask “which one is the best one?”, as if we will pick only one CSS property to create a layout, as if it’s similar to picking only one framework. You don't use Suzy and Bootstrap — why would you use Flexbox <em>and</em> Grid? Well — that is exactly what’ll do. You will use a combination of all of these properties on every project. You’ll code this part with Grid, this part with Flexbox. Over here, a simple Float will do the trick. Over there a Grid nested inside a second Grid will get it done. All the while thinking through what happens in the browsers that don’t support Grid yet, creating elegant fallbacks by using Feature Queries. 

The challenge is to learn all of these tools. Not only do we need to learn the new ones, like Grid, but most of us have to go back and learn the old ones. We’ve been using frameworks so much, we are rusty now when it comes to knowing how to use a float. Plus `box-sizing: border-box` changed everything, and made a lot of the old problems go away when we weren’t looking. (If you don’t know what that is, start <a href="https://www.paulirish.com/2012/box-sizing-border-box-ftw/">there</a>.)

It’s not just front-end developers who have a lot to learn — designers do, too. Most of the current design practices assume the page layout is already set. We’ll just pick from these handful of templates. Those designers who are more innovative, it’s likely you've been told over and “we can't do that on the web”, and you've listened. Now we don’t even remember the graphic design ideas we use to have. We stopped being creative. We submitted to the constraints of the float.

Now designers can open their minds to a world of possibilities. There are a lot of new ones. And there are new constraints. Not everything is possible. We need to explore CSS Grid until we understand what it wants to do, what it can be forced into doing, and what it refuses to do. Many designers may not ever learn to code CSS, but you need to understand CSS well enough to understand our artistic medium.

Many of us are newer to this industry, and were not around when layouts were hand-coded. Many people have only ever used a framework. It will be hardest for you to change your thinking. Developers will need to invest some time to learn how to use CSS to do layouts, and to undo all the habits from frameworks. 

In many ways, perhaps it’s the people who are brand new to the industry who have the most potential. You might think, “well, I know nothing! I have to learn it all at once!” Yes, you do. And, actually, so do most of us. You at least don’t have to unlearn anything. 

If I were a scrappy young designer or front-end developer, I would jump all over this layout stuff and learn it as fast as I could. I expect that later this year and throughout 2018 there will be a lot of demand for people who know how to hand-code a layout. Those folks who can imagine an innovative page design and make it happen — you will have a lot of control over the future of your career. You’ll stand out. You’ll get work. You’ll be able to be picky about where you work, and raise your rates.

How do you learn all this? Where do you start? Well, read my post about <a href="http://jensimmons.com/post/feb-27-2017/learn-css-grid">Learning Grid</a>, and especially take a look at Rachel Andrew’s <a href="https://thecssworkshop.com">CSS Workshop</a>, where she goes through everything CSS for layout. Most of all, start coding demos. Play. Experiment. Learn by doing. 

We stopped taking risks at some point. Everything online seems so polished and perfect. The frameworks do make a new project look snazzy right away. All that polish, all those rounded-corner images. But we’ve got to break away from that, if we want to make great work, great designs. If we can dare to make mistakes, and learn to play and experiment again, we can push this industry to a whole new level, and truly start to understand the web as a graphic design medium.

You can find my experiments at <a href="http://labs.jensimmons.com">labs.jensimmons.com</a>. I'd love to see yours.
