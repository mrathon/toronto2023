---
title: "About"
bg: clrnew
color: about
fa-icon: info-circle
iconclr: '#428bca'
titleclr: '#428bca'
---

# A hackathon for comparable MRI

<p style ="text-align: center; font-weight: bold; font-size:24px;"> To promote reproducibility, collaboration, and standards through open source practices in magnetic resonance. From scanner to publication.</p>

<br><br>
<center><h4>Comparable MRI</h4>

 <p>This year's MRathon aims to bring together experts to share knowledge and collaborate on new solutions for ensuring consistency and comparability in MRI measurements. This includes efforts in image acquisition, reconstruction, post-processing, and publication.</p>
 
 <h4>A sprint to push boundaries, not necessarily for code, but for collective creativity.</h4>

 <p>Even though we do not anticipate an intense coding marathon after a busy ISMRM annual meeting, those who would like to work on a coding project are welcome to submit their project idea for making MRI reproducible!</p>

 </center>

<br><br>

<div class="row partners">
{% for item in site.data.projects.projects %}
  <div class="col s12 partner valign">
    <h4 style="color: #486a89; text-align: left"> {{ item.title }}  </h4>
    <a href="{{ item.url }}" target="blank"><img src="img/projects/{{ item.image }}"/></a>
    
  </div>
  {% endfor %}
  </div>




