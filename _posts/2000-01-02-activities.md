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

<center>
<p style ="text-align: center;  font-size:20px;">This year's MRathon aims to bring together experts to share knowledge and collaborate on new solutions for ensuring consistency and comparability in MRI measurements. This includes efforts in image acquisition, reconstruction, post-processing, and publication.</p>
 </center>
<hr>
 <h3>A stellar list of speakers</h3>

 <p style ="text-align: center;  font-size:20px;"> Each day of the event will kick off with presentations from experts who specialize in implementing cutting-edge research into open-source projects.</p>

<div class="team" style="margin-top:10px;">
<div class="row">
{% for person in site.data.committee.speakers %}
<div class="col-sm-2">
<center>
<div class="team-player">
    <img src="img/organization/{{ person.image }}" alt="Thumbnail Image" class="img-raised img-circle" style="width:100px;height:100px;border-radius: 50%;">
    <h5 class="title" style="color: black;">{{ person.name }}<br>
        <small class="text-muted" style="color: black;">{{ person.affiliation }}</small>
    </h5>
    <!-- <p style="color: darkgray;"> {{ person.affiliation }}</p> -->
</div>
</center>
</div>
  {% endfor %}

<div>
<div>
<hr>
<center>
 <h3>A sprint to push boundaries for collective creativity</h3>

 <p style ="text-align: center;  font-size:20px;">Even though we do not anticipate an intense coding marathon after a busy ISMRM annual meeting, those who would like to work on a coding project are welcome to submit their project idea for making MRI reproducible!</p>
</center>