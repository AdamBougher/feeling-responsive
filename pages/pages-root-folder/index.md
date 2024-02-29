---
#
# Use the widgets beneath and the content will be
# inserted automagically in the webpage. To make
# this work, you have to use › layout: frontpage
#
layout: frontpage
header:
  image_fullwidth: header_unsplash_12.jpg
widget1:
  title: "Blog & Portfolio"
  url: '/blog'
  image: widget-1-302x182.jpg
  text: 'Read the latest News and Announcements from the studio!'
widget2:
  title: "Why are we?"
  url: '/info/'
  text: '<em>71 North</em> Office of Innovation.<br/>1. incubator <br/>2. coworking facility. <br/>3. meeting venue.<br/>4. explore collaborative innovation.<br/>'
widget3:
  title: "Checkout the office of innovation"
  url: 'https://innovation.niu.edu/71-north-partnership-studio/'
  image: widget-github-303x182.jpg
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
  url: https://calendar.niu.edu/search/events?event_types%5B%5D=35990969342017
  text: Go To Our Calender And See What's happening ›
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
