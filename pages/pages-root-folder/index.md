---
#
# Use the widgets beneath and the content will be
# inserted automagically in the webpage. To make
# this work, you have to use › layout: frontpage
#
layout: frontpage
# header:
#   image_fullwidth: header_unsplash_12.jpg
widget1:
  title: "About GPC"
  url: '/about/'
  image: widget-1-302x182.jpg
  text: 'This will link to the About page which gives more information about GPC. The image will be changed to something more fitting.'
widget2:
  title: "Blog Posts"
  url: '/blog/'
  image: widget-1-302x182.jpg
  text: 'This will link to the blog page. The image will be changed to something more fitting.'
widget3:
  title: "GPC in the Media"
  url: '/media/'
  image: widget-1-302x182.jpg
  text: 'This will link to the media page. The image will be changed to something more fitting.'
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
  url: /donate/
  text: Donate to GPC ›
  style: alert
permalink: /index.html
#
# This is a nasty hack to make the navigation highlight
# this page as active in the topbar navigation
#
homepage: true
---
<!-- 
<div id="videoModal" class="reveal-modal large" data-reveal="">
  <div class="flex-video widescreen vimeo" style="display: block;">
    <iframe width="1280" height="720" src="https://www.youtube.com/embed/3b5zCFSmVvU" frameborder="0" allowfullscreen></iframe>
  </div>
  <a class="close-reveal-modal">&#215;</a>
</div> -->
