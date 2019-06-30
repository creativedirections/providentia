---
layout: index
title: # should be set by _config

lang: sc
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
    <p>Providentia Education是一家总部设在香港的教育集团，致力于为世界各地的家庭提供最好的国外学习机会。</p>
    <p>Providentia由具有国际教育和投资专业知识的多元化管理团队领导，与领先的教育工作者合作，并进行学校投资。</p>
  button:
    show: true
    url: "pages_zh-cn/offices-hk_sc"
    text: 联络我们

banner-2:
  title: ''
  desc: |
    <p><span class="noto">「學如逆水行舟，不進則退。」</span></p>
    <p><span class="motto">— 《中国谚语》</span></p>
  image_url: 'images/preschoolers.jpg'

spotlight-philosophy:
  title: 我们的理念
  content: |
    <p>我们的使命是建立一个与学校和教育工作者相关的国际领先的伙伴平台。</p>
    <p>作为企业家而非金融家，我们有一个长远的视野，我们在全球耐心地寻找最好和优良信誉的合作伙伴。</p>
    <p>迄今为止，我们在澳大利亚，香港和英国都有合作伙伴。</p>
  button:
    show: true
    url: "pages_zh-cn/our-philosophy_sc"
    text: 了解更多

banner-3:
  title: ''
  desc: |
    <p><span class="courgette">“Education is the most powerful weapon which you can use to change the world.”</span></p>
    <p><span class="motto">— nelson mandela</span></p>
  image_url: 'images/kids_football.jpeg'

spotlight-teaching:
  title: 我们的教学方法
  content: |
    <p>Providentia的学生年龄从6个月到16岁。 为了迎合这样一个多元化和庞大的学生群体，我们的教育工作者采用最成熟的教学系统，包括为我们在澳大利亚的学童提供瑞吉欧（Reggio Emilia）教学方法。</p>
    <p>我们的全球平台使我们的教育工作者能够不断分享如何处理问题的经验和方法。</p>
    <p>Providentia的教学人员专注于概念理解，并确保学生们为能够接受这样的教育而感到骄傲。</p>
  button:
    show: true
    url: "pages_zh-cn/our-teaching-methodologies_sc"
    text: 了解更多

banner-4:
  title: ''
  desc: |
    <p><span class="courgette">“Education is the passport to the future,<br>for tomorrow belongs to those who prepare for it today.”</span></p>
    <p><span class="motto">— malcolm x</span></p>
  image_url: 'images/college.jpg'

banner-school:
  title: Locate our Schools
  content: |
    <p><a href="pages_zh-cn/sparrow-early-learning-australia_sc">Sparrow儿童教育集团 | 澳大利亚</a></p>
    <p><a href="pages_zh-cn/sparrow-soccer-hongkong_sc">Sparrow足球学校 | 香港</a></p>
    <p><a href="pages_zh-cn/boundary-oak-team_sc">Boundary Oak学校 | 英国</a></p>
  image_url: 'images/World_map_blank_without_borders.png'

---
<!-- Welcome Banner -->
{% include _banner.html key='banner' style='style5' scheme='invert' color='' size='fullscreen' content_align='left' img_pos='center' %}

<!-- About Us -->
{% include _spotlight.html key='spotlight-about' style='style6' orient='' scheme='' color='' size='fullscreen' content_align='left' id='aboutus' %}

<!-- Banner 2 -->
{% include _banner.html key='banner-2' style='style5' scheme='invert' color='' size='mostscreen' content_align='left' img_pos='center' %}

<!-- Our Philosophy -->
{% include _spotlight.html key='spotlight-philosophy' style='style6' orient='' scheme='' color='' size='fullscreen' content_align='left' id='philosophy' %}

<!-- Banner 3 -->
{% include _banner.html key='banner-3' style='style5' scheme='invert' color='' size='mostscreen' content_align='left' img_pos='center' %}

<!-- Our Teaching Philosophy -->
{% include _spotlight.html key='spotlight-teaching' style='style6' orient='' scheme='' color='' size='fullscreen' content_align='left' id='teaching' %}

<!-- Banner 4 -->
{% include _banner.html key='banner-4' style='style5' scheme='invert' color='' size='mostscreen' content_align='left' img_pos='center' %}

<!-- Global school -->
{% include _spotlight.html key='banner-school' style='style1' scheme='' orient='left' size='fifty' content_align='left' img_pos='right' id='school' %}