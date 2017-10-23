---
#
# Use the widgets beneath and the content will be
# inserted automagically in the webpage. To make
# this work, you have to use › layout: frontpage
#
layout: frontpage
header:
  image_fullwidth: mysticalfog.jpeg
widget1:
  title: "Blog & Info"
  url: 'https://nearlysacred.github.io/blog/'
  image: widget-1-302x182.jpg
  text: 'We cover a little bit of everything metaphysical here--from Sacred Geometry to things we are interested in--to our newest podcasts. If you want a quick way to 
get up to speed, this is the spot to click. '
widget2:
  title: "Who We Are"
  url: 'http://nearlysacred.github.io/nearlysacred.github.io/info/'
  text: 'So you want to know more about us eh? Your wish is granted. Simply follow the below link, and find all the information about the hosts of Nearly Sacred that you ever dreamed or dared to know.'
  video: '<a href="#" data-reveal-id="videoModal"><img src="http://phlow.github.io/feeling-responsive/images/start-video-feeling-responsive-302x182.jpg" width="302" height="182" alt=""/></a>'
widget3:
  title: "Podcasts"
  url: 'https://github.com/Phlow/feeling-responsive'
  image: widget-github-303x182.jpg
  text: 'So you just want to cut to it do you? You can find our podcasts here.There are plenty to pick from. All you have to do is decide what interests you the most!'
#
# Use the call for action to show a button on the frontpage
#
# To make internal links, just use a permalink like this
# url: /getting-started/
#
# To style the button in different colors, use no value
# to use the main color or success, alert or secondary.
# To change colors see sass/_01_settings_colors.scss
#
callforaction:
  url: https://tinyletter.com/feeling-responsive
  text: Inform me about new updates and features ›
  style: alert
permalink: /index.html
#
# This is a nasty hack to make the navigation highlight
# this page as active in the topbar navigation
#
homepage: true
---

<div id="videoModal" class="reveal-modal large" data-reveal="">
  <div class="flex-video widescreen vimeo" style="display: block;">
    <iframe width="1280" height="720" src="https://www.youtube.com/embed/3b5zCFSmVvU" frameborder="0" allowfullscreen></iframe>
  </div>
  <a class="close-reveal-modal">&#215;</a>
</div>
