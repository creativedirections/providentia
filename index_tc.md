---
layout: index
title: # should be set by _config

lang: tc
lang-ref: index.md

banner:
  desc: |
    <p><span class="courgette">“Knowledge is power. Information is liberating.<br>Education is the premise of progress, in every society, in every family.”</span></p>
    <p><span class="motto">— kofi annan</span></p>
  image_url: 'images/home_banner.png'

spotlight-about:
  title: Providentia教育
  content: |
    <p><h3 class="courgette">Our Heritage, Their Future</h3></p>
    <p>Providentia Education是一家總部設在香港的教育集團，致力於為世界各地的家庭提供最好的國外學習機會。</p>
    <p>Providentia由具有國際教育和投資專業知識的多元化管理團隊領導，與領先的教育工作者合作，並進行學校投資。</p>
  button:
    show: true
    url: "pages_zh-hk/offices-hk_tc"
    text: 聯絡我們

banner-2:
  title: ''
  desc: |
    <p><span class="noto">「學如逆水行舟，不進則退。」</span></p>
    <p><span class="motto">— 《中國諺語》</span></p>
  image_url: 'images/preschoolers.jpg'

spotlight-philosophy:
  title: 我們的理念
  content: |
    <p>我們的使命是建立一個與學校和教育工作者相關的國際領先的夥伴平台。</p>
    <p>作為企業家而非金融家，我們有一個長遠的視野，我們在全球耐心地尋找最好和優良信譽的合作夥伴。</p>
    <p>迄今為止，我們在澳大利亞，香港和英國都有合作夥伴。</p>
  button:
    show: true
    url: "pages_zh-hk/our-philosophy_tc"
    text: 瞭解更多

banner-3:
  title: ''
  desc: |
    <p><span class="courgette">“Education is the most powerful weapon which you can use to change the world.”</span></p>
    <p><span class="motto">— nelson mandela</span></p>
  image_url: 'images/kids_football.jpeg'

spotlight-teaching:
  title: 我們的教學方法
  content: |
    <p>Providentia的學生年齡從6個月到16歲。 為了迎合這樣一個多元化和龐大的學生群體，我們的教育工作者採用最成熟的教學系統，包括為我們在澳大利亞的學童提供瑞吉歐（Reggio Emilia）教學方法。</p>
    <p>我們的全球平台使我們的教育工作者能夠不斷分享如何處理問題的經驗和方法。</p>
    <p>Providentia的教學人員專注於概念理解，並確保學生們為能夠接受這樣的教育而感到驕傲。</p>
  button:
    show: true
    url: "pages_zh-hk/our-teaching-methodologies_tc"
    text: 瞭解更多

banner-4:
  title: ''
  desc: |
    <p><span class="courgette">“Education is the passport to the future,<br>for tomorrow belongs to those who prepare for it today.”</span></p>
    <p><span class="motto">— malcolm x</span></p>
  image_url: 'images/college.jpg'

banner-school:
  title: Locate our Schools
  content: |
    <p><a href="pages_zh-hk/sparrow-early-learning-australia_tc">Sparrow兒童教育集團 | 澳大利亞</a></p>
    <p><a href="pages_zh-hk/sparrow-soccer-hongkong_tc">Sparrow足球學校 | 香港</a></p>
    <p><a href="pages_zh-hk/boundary-oak-team_tc">Boundary Oak學校 | 英國</a></p>
  image_url: 'images/World_map_blank_without_borders.png'

---
<!-- Welcome Banner -->
{% include _banner.html key='banner' style='style5' scheme='invert' color='' size='fullscreen' content_align='left' img_pos='center' %}

<!-- About Us -->
{% include _spotlight.html key='spotlight-about' style='style6' orient='' scheme='' color='' size='halfscreen' content_align='left' id='aboutus' %}

<!-- Banner 2 -->
{% include _banner.html key='banner-2' style='style5' scheme='invert' color='' size='halfscreen' content_align='left' img_pos='center' %}

<!-- Our Philosophy -->
{% include _spotlight.html key='spotlight-philosophy' style='style6' orient='' scheme='' color='' size='halfscreen' content_align='left' id='philosophy' %}

<!-- Banner 3 -->
{% include _banner.html key='banner-3' style='style5' scheme='invert' color='' size='halfscreen' content_align='left' img_pos='center' %}

<!-- Our Teaching Philosophy -->
{% include _spotlight.html key='spotlight-teaching' style='style6' orient='' scheme='' color='' size='halfscreen' content_align='left' id='teaching' %}

<!-- Banner 4 -->
{% include _banner.html key='banner-4' style='style5' scheme='invert' color='' size='halfscreen' content_align='left' img_pos='center' %}

<!-- Global school -->
{% include _spotlight.html key='banner-school' style='style1' scheme='' orient='left' size='fifty' content_align='left' img_pos='right' id='school' %}