---
#
# Use the widgets beneath and the content will be
# inserted automagically in the webpage. To make
# this work, you have to use › layout: frontpage
#
layout: frontpage
header:
  image_fullwidth: /other/all-champs.jpg
widget1:
  title: "Karakterler"
  url: 'https://contestofchamps-tr.github.io/blog/'
  image: /other/widget-character-302x182.jpg
  text: 'Contest of Champions oyununda 6 farklı sınıfa ayrılmış birçok karakter vardır. Bu karakterler 1-5 aralığında yıldız sayısına sahiptir. Bu bölümde 4-yıldız karakterler baz alınarak yazılmış karakter özelliklerine ulaşabilirsiniz.'
widget2:
  title: "İttifaklar"
  image: /other/widget-alliance-302x182.jpg
  url: 'https://contestofchamps-tr.github.io/ittifaklar/'
  text: 'Marvels contest of Champions oyununda daha önce kurulmuş ittifaklara katılabilir veya siz ittifak kurabilirsiniz.</br>Bu bölümde ittifak dahilinde, ittifak olarak katılabileceğiniz macera, savaş ve müsabakalar tanıtılmaktadır.'
widget3:
  title: "Oyunu indirin"
  url: 'https://contestofchamps-tr.github.io/indir-download/'
  image: /other/widget-download-302x182.jpg
  text: '2014 Aralık ayında çıkan oyunun 11.0 versiyonu halihazırda kullanılmaktadır. </br>Bağlantıya tıklayarak ulaşacağınız sayfada kullanmış olduğunuz dokunmatik ekrana sahip akıllı cihazınıza oyunu kurmanızı sağlayacak bağlantılara erişebilirsiniz.'
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
# callforaction:
#   url: https://tinyletter.com/feeling-responsive
#   text: Inform me about new updates and features ›
#   style: alert
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
