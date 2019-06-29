---
layout: index
title: # should be set by _config

lang: en
lang-ref: home.md

banner:
  desc: |
    <p><span class="courgette">“Knowledge is power. Information is liberating.<br>Education is the premise of progress, in every society, in every family.”</span></p>
    <p><span class="motto">— kofi annan</span></p>
  image_url: '../images/home_banner.png'

spotlight-about:
  title: Providentia Education
  content: |
    <p><h3 class="courgette">Our Heritage, Their Future</h3></p>
    <p>Providentia Education is a Hong Kong-headquartered education group focused on curating and bringing the best of international learning opportunities to families around the world.</p>
    <p>Led by a diverse management team with international education and investment expertise, Providentia partners with leading educators and invests in schools.</p>
    <p>By building a preeminent family of world-class educators and students, Providentia promotes the boundless exchange of ideas and inspiration within our network of schools.</p>
    <p>We warmly welcome new enquiries and discussions with potential new partners.  Please scroll down to discover more about our education and investment philosophy and contact details.</p>
  button:
    show: true
    url: "/pages/offices-hk"
    text: contact us

banner-2:
  title: ''
  desc: |
    <p><span class="noto">“学如逆水行舟，不进则退。”</span></p>
    <p><span class="motto">— chinese proverb</span></p>
  image_url: '../images/preschoolers.jpg'

spotlight-philosophy:
  title: Our Philosophy
  content: |
    <p>Our mission is to build a leading international partnership of schools and educators.</p>
    <p>As entrepreneurs and not financiers, we have a long-term  horizon and have been patiently seeking the best and most reputable partners in our global search. </p>
    <p>To date, we have partners in Australia, Hong Kong, and the United Kingdom.</p>
  button:
    show: true
    url: "/pages/our-philosophy"
    text: learn more

banner-3:
  title: ''
  desc: |
    <p><span class="courgette">“Education is the most powerful weapon which you can use to change the world.”</span></p>
    <p><span class="motto">— nelson mandela</span></p>
  image_url: '../images/kids_football.jpeg'

spotlight-teaching:
  title: Our Teaching Methodologies
  content: |
    <p>Providentia’s family of students ranges from 6 months to 16 years old. In order to cater to such a diverse and large group of students, our educators employ the most proven systems for teaching, including the Reggio Emilia approach for our younger students in Australia.</p> 
    <p>Our global reach allows our educators to constantly share experiences and approaches on how to deal with issues.</p>
    <p>Providentia’s teaching staff focus on conceptual understanding and ensure pupils take pride in the quality of their work.</p>
  button:
    show: true
    url: "/pages/our-teaching-methodologies"
    text: learn more

banner-4:
  title: ''
  desc: |
    <p><span class="courgette">“Education is the passport to the future,<br>for tomorrow belongs to those who prepare for it today.”</span></p>
    <p><span class="motto">— malcolm x</span></p>
  image_url: '../images/college.jpg'

banner-school:
  title: Locate our Schools
  content: |
    <p><a href="/pages/sparrow-early-learning-australia">sparrow early learning, australia</a></p>
    <p><a href="/pages/sparrow-soccer-hongkong">sparrow soccer school, hong kong</a></p>
    <p><a href="/pages/boundary-oak-team">boundary oak school, united kingdom</a></p>
  image_url: '../images/World_map_blank_without_borders.png'

---
<!-- Welcome Banner -->
{% include _banner.html key='banner' style='style5' scheme='invert' color='' size='fullscreen' content_align='left' img_pos='left' %}

<!-- About Us -->
{% include _spotlight.html key='spotlight-about' style='style6' orient='' scheme='' color='' size='fullscreen' content_align='left' id='aboutus' %}

<!-- Banner 2 -->
{% include _banner.html key='banner-2' style='style5' scheme='invert' color='' size='mostscreen' content_align='left' img_pos='left' %}

<!-- Our Philosophy -->
{% include _spotlight.html key='spotlight-philosophy' style='style6' orient='' scheme='' color='' size='fullscreen' content_align='left' id='philosophy' %}

<!-- Banner 3 -->
{% include _banner.html key='banner-3' style='style5' scheme='invert' color='' size='mostscreen' content_align='left' img_pos='left' %}

<!-- Our Teaching Philosophy -->
{% include _spotlight.html key='spotlight-teaching' style='style6' orient='' scheme='' color='' size='fullscreen' content_align='left' id='teaching' %}

<!-- Banner 4 -->
{% include _banner.html key='banner-4' style='style5' scheme='invert' color='' size='mostscreen' content_align='left' img_pos='left' %}

<!-- Global school -->
{% include _spotlight.html key='banner-school' style='style1' scheme='' orient='left' size='fifty' content_align='left' img_pos='right' id='school' %}
