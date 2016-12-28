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
  title: "About me"
  url: 'http://diy2learn.github.io/chamcon/blog/'
  image: widget1_papapi_babyOnRose_302x181.jpg
  text: 'I am finishing my PhD. in CEA-Saclay under the direction of Dr. Herve xx. Since the last three years, I have had excited time exploring different advanced algorithms for multimedia retrieval.'

widget2:
  title: "Recent works"
  url: 'http://diy2learn.github.io/chamcon/papapi/'
  image: widget2_pathToSuccess.jpg
  text: 'You can find below are my recent works during my thesis and engineer. '

widget3:
  title: "My dishes"
  url: 'http://diy2learn.github.io/chamcon/mamami/'
  image: widget3_mamami_birthday-cake_302x182.jpg
  text: 'I am a big fan of cake making. It"s a great opportunity for me to live in France, the homeland of many delicious cakes. I spend my leisure time to explore different cake recipes and share the experimental outcomes with my friends and family.'


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
  url: http://tinyletter.com/papapi
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
