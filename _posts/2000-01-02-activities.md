---
title: "About"
bg: clrnew
color: about
fa-icon: info-circle
iconclr: '#428bca'
titleclr: '#428bca'
---

# A hackathon for comparable MRI

<p style ="text-align: center; font-weight: bold; font-size:24px;"> To promote reproducibility, collaboration, and standards through open source practices in magnetic resonance. </p>

<br><br>

<p style ="text-align: center; font-style: italic; font-size:18px;"><a href="https://www.gnu.org/philosophy/hackathons.en.html" target="blank">"Hackathons are an accepted method of giving community support to digital development projects. The community invites developers to join an event which offers an encouraging atmosphere, some useful resources, and the opportunity to work on useful projects." - Richard M. Stallman</a></p> 

<center><p style ="text-align: center; font-weight: bold; font-size:18px;">If you’ve never been to a hackathon, <a href="https://www.ohbmbrainmappingblog.com/blog/ohbm-hackathon-2017-a-first-timers-perspective">read this first timer’s perspective.</a></p></center>

<br><br>

<div class="row partners">
{% for item in site.data.projects.projects %}
  <div class="col s12 partner valign">
    <h4 style="color: #486a89; text-align: left"> {{ item.title }}  </h4>
    <a href="{{ item.url }}" target="blank"><img src="img/projects/{{ item.image }}"/></a>
    
  </div>
  {% endfor %}
  </div>




