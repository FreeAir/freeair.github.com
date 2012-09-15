---
layout: site
type: podcast
title: "Episode #2: Encipher Group and The Android Platform"
sub_title: Encipher Group and The Android Platform
creator: Ikenna Okpala
summary: In this podcast we talk to one of the brains behind the Inye African Android tablet, Anibe Agamah, the CTO of Encipher Group. He provides answers to questions concerning the history, current status, future and mode of business of Encipher Group and Inye tablet.
tags: [mobile, tablets, software engineering, java, inye, android]
podcast:
- duration: "55:43"
  size: 51.1 MB
  location: http://pod.freeair.io/audio/episode_2_encipher_group.mp3
last_updated: 2012-08-19
---

<article class="{{ page.type }}">
 <div class="title"> {{page.title}} </div>
 <div class="date">by {{page.creator}} on {{ page.date | date: "%d %B %Y" }}</div>
 <div id="mp3_audio">
  {% for pod in page.podcast %}
  <audio id="player" name="player" src="{{pod.location}}" controls="controls"></audio>
  <span>Duration: {{pod.duration}} | File size: {{pod.size}} | <a href="{{pod.location}}" target="_blank" > Download..  </a></span>
  {% endfor %}
</div>
<div id="summary">
 <p> {{page.summary}} </p>
 <h3> Panelist: </h3>
 <ul>
  <li>Anibe Agamah (CTO Encipher Group) <a href="http://twitter.com/anibe" target="_blank" >@anibe</a> on twitter</li>
  <li>Ikenna Okpala <a href="http://twitter.com/kengimel" target="_blank" >@kengimel</a> on twitter</li>
  <li>Seyi Ogunyemi <a href="http://twitter.com/micrypt" target="_blank" >@micrypt</a> on twitter</li>
</ul>
<h3> Show Notes: </h3>
<ul>

  <li><a href=" http://enciphergroup.com/" target="_blank" >Encipher Group and The Inye</a> by Anibe</li>
  <li><a href="http://blogs.adobe.com/conversations/2011/11/flash-focus.html" target="_blank" >Adobe to More Aggressively Contribute to HTML5</a> by Anibe</li>
  <li><a href="http://alenribic.com/writings/post/raspberry-pi-in-a-haskell-cloud" target="_blank" >Raspberry Pi in a Haskell Cloud</a> by Seyi</li>
  <li><a href="https://www.djangoproject.com/weblog/2012/mar/13/py3k/" target="_blank" >Django's future, and Python 3</a> by Seyi</li>
  <li><a href="http://www.amazon.com/Elemental-Design-Patterns-Jason-Smith/dp/0321711920" target="_blank" >Elemental Design Patterns</a> by Ikenna</li>
  <li><a href="http://www.noelrappin.com/railsrx/2012/5/7/welcome.html" target="_blank" >Master Space and Time With JavaScript</a> by Ikenna</li>
  <li><a href="http://www.raspberrypi.org/" target="_blank" >Raspberry PI</a> by Ikenna</li>
  <li><a href="http://www.youtube.com/watch?v=a9xAKttWgP4" target="_blank" >Conway's Game Of Life in APL</a> by Ikenna</li>
</ul>
<div id='social'>
  <div id='twitter'>
  <a href="https://twitter.com/share" class="twitter-share-button" data-url="http://freeair.io{{page.url}}" data-via="freeairio">Tweet</a>
 <script>!function(d,s,id){var js,fjs=d.getElementsByTagName(s)[0];if(!d.getElementById(id)){js=d.createElement(s);js.id=id;js.src="//platform.twitter.com/widgets.js";fjs.parentNode.insertBefore(js,fjs);}}(document,"script","twitter-wjs");</script>
</div>

<div id='disqus'>
</div>

</div>

<div class="tags">
  {% for tag in page.tags %}
  <a href="#" >{{tag}} </a>
  {% endfor %}
</div>
</article>
