---
title: "Wang Research Group - Members"
layout: gridlay
excerpt: "Wang Research Group: Members"
sitemap: false
permalink: /members/
---

# Member

<h2 style="text-align: center; padding-top: 30px">Ph.D.</h2>
<div class="col-sm-12 clearfix" style="text-align: center; ">
<div style="text-align: center;">
<div class="image-cropper">
<img class="person-pic" src="{{ site.url }}{{ site.baseurl }}/images/teampic/Jianmin_profile.png" alt="Jianmin photo"/>
</div>
<h4><b>Jianmin Wang</b></h4>
<i>Ph.D.<br>
Department of Integrative Biotechnology under the Institute of Convergence Science and Technology<br>
Yonsei University<br></i>
<a href="mailto:drugai@hotmail.com"><svg xmlns="http://www.w3.org/2000/svg" width="20" height="20" style="margin-right: 5px; margin-left: 5px; margin-top: 10px"  fill="currentColor" class="bi bi-envelope-fill" viewBox="0 0 16 16"><path d="M.05 3.555A2 2 0 0 1 2 2h12a2 2 0 0 1 1.95 1.555L8 8.414zM0 4.697v7.104l5.803-3.558zM6.761 8.83l-6.57 4.027A2 2 0 0 0 2 14h12a2 2 0 0 0 1.808-1.144l-6.57-4.027L8 9.586zm3.436-.586L16 11.801V4.697z"/></svg></a>
<a href="https://jianmin2drugai.github.io/" target="_blank" rel="noopener noreferrer" aria-label="Website">
  <svg xmlns="http://www.w3.org/2000/svg" width="20" height="20" style="margin-right: 5px; margin-left: 5px; margin-top: 10px" fill="currentColor" class="bi bi-globe" viewBox="0 0 16 16">
    <path d="M0 8a8 8 0 1 1 16 0A8 8 0 0 1 0 8m8-7a7 7 0 0 0-1.468.154c.338.473.6 1.01.784 1.594h1.368c.185-.584.446-1.121.784-1.594A7 7 0 0 0 8 1M5.734 1.748A7 7 0 0 0 1.748 5.734h2.12c.152-1.347.56-2.52 1.866-3.986m4.532 0c1.306 1.466 1.714 2.639 1.866 3.986h2.12a7 7 0 0 0-3.986-3.986M1.154 6.748A7 7 0 0 0 1 8c0 .425.038.84.111 1.242h2.45A16.3 16.3 0 0 1 3.5 8c0-.43.02-.85.06-1.252zm3.41 0A15.3 15.3 0 0 0 4.5 8c0 .442.022.873.065 1.242h2.87A15.7 15.7 0 0 0 7.5 8c0-.442-.022-.873-.065-1.252zm3.806 0A15.7 15.7 0 0 1 8.5 8c0 .442-.022.873-.065 1.242h2.87c.043-.369.065-.8.065-1.242 0-.43-.02-.85-.06-1.252zm3.925 0h-2.45c.04.402.06.822.06 1.252 0 .43-.02.85-.06 1.242h2.45A7 7 0 0 0 15 8c0-.425-.038-.84-.111-1.252M1.748 10.266a7 7 0 0 0 3.986 3.986c-1.306-1.466-1.714-2.639-1.866-3.986zm3.93 0c.184.584.446 1.121.784 1.594A7 7 0 0 0 8 15a7 7 0 0 0 1.468-.154 6.1 6.1 0 0 1-.784-1.594zm4.588 0c-.152 1.347-.56 2.52-1.866 3.986a7 7 0 0 0 3.986-3.986z"/></svg></a>
<a href="https://x.com/Jianmin4drugai"><svg xmlns="http://www.w3.org/2000/svg" width="20" height="20" style="margin-right: 10px; margin-left: 5px; margin-top: 5px"  fill="currentColor" class="bi bi-twitter-x" viewBox="0 0 24 24"><path d="M18.901 1.153h3.68l-8.04 9.19L24 22.846h-7.406l-5.804-7.584-6.64 7.584H.47l8.6-9.83L0 1.154h7.594l5.243 6.932zm-1.29 19.5h2.04L6.48 3.248H4.29z"/></svg></a>
<p></p>
</div>
</div>

<!-- Post-docs -->
<h2 style="text-align: center; padding: 30px">Postdoctoral Associates & Fellows and Research Scientists
</h2>
<div class="row">
{% for member in site.data.postdocs %}
<div class="col-sm-4 clearfix" style="text-align: center; ">
<div style="display: flex; justify-content: center;">
<div class="image-cropper">
<img class="person-pic" src="{{ site.url }}{{ site.baseurl }}/images/teampic/{{ member.photo }}" alt="{{ member.name }} photo"/>
</div>
</div>
<h4><b>{{ member.name }}</b></h4>
<i>{{ member.info }} <br> </i>
<a href="mailto:{{ member.email }}"><svg xmlns="http://www.w3.org/2000/svg" width="20" height="20" style="margin-right: 5px; margin-left: 5px; margin-top: 10px" fill="currentColor" class="bi bi-envelope-fill" viewBox="0 0 16 16"><path d="M.05 3.555A2 2 0 0 1 2 2h12a2 2 0 0 1 1.95 1.555L8 8.414zM0 4.697v7.104l5.803-3.558zM6.761 8.83l-6.57 4.027A2 2 0 0 0 2 14h12a2 2 0 0 0 1.808-1.144l-6.57-4.027L8 9.586zm3.436-.586L16 11.801V4.697z"/></svg></a>{% if member.twitter %}<a href="{{ member.twitter }}"><svg xmlns="http://www.w3.org/2000/svg" width="20" height="20" style="margin-right: 5px; margin-left: 5px; margin-top: 10px" fill="currentColor" class="bi bi-twitter" viewBox="0 0 16 16"><path d="M5.026 15c6.038 0 9.341-5.003 9.341-9.334q.002-.211-.006-.422A6.7 6.7 0 0 0 16 3.542a6.7 6.7 0 0 1-1.889.518 3.3 3.3 0 0 0 1.447-1.817 6.5 6.5 0 0 1-2.087.793A3.286 3.286 0 0 0 7.875 6.03a9.32 9.32 0 0 1-6.767-3.429 3.29 3.29 0 0 0 1.018 4.382A3.3 3.3 0 0 1 .64 6.575v.045a3.29 3.29 0 0 0 2.632 3.218 3.2 3.2 0 0 1-.865.115 3 3 0 0 1-.614-.057 3.28 3.28 0 0 0 3.067 2.277A6.6 6.6 0 0 1 .78 13.58a6 6 0 0 1-.78-.045A9.34 9.34 0 0 0 5.026 15"/></svg></a>{% endif %}{% if member.linkedin %}<a href="{{ member.linkedin }}"><svg xmlns="http://www.w3.org/2000/svg" width="20" height="20" style="margin-right: 5px; margin-left: 5px; margin-top: 10px"  fill="currentColor" class="bi bi-linkedin" viewBox="0 0 16 16"><path d="M0 1.146C0 .513.526 0 1.175 0h13.65C15.474 0 16 .513 16 1.146v13.708c0 .633-.526 1.146-1.175 1.146H1.175C.526 16 0 15.487 0 14.854zm4.943 12.248V6.169H2.542v7.225zm-1.2-8.212c.837 0 1.358-.554 1.358-1.248-.015-.709-.52-1.248-1.342-1.248S2.4 3.226 2.4 3.934c0 .694.521 1.248 1.327 1.248zm4.908 8.212V9.359c0-.216.016-.432.08-.586.173-.431.568-.878 1.232-.878.869 0 1.216.662 1.216 1.634v3.865h2.401V9.25c0-2.22-1.184-3.252-2.764-3.252-1.274 0-1.845.7-2.165 1.193v.025h-.016l.016-.025V6.169h-2.4c.03.678 0 7.225 0 7.225z"/></svg></a>{% endif %}{% if member.website %}<a href="{{ member.website }}"><svg xmlns="http://www.w3.org/2000/svg" width="20" height="20" style="margin-right: 5px; margin-left: 5px; margin-top: 10px" fill="currentColor" class="bi bi-house-fill" viewBox="0 0 16 16"><path d="M8.707 1.5a1 1 0 0 0-1.414 0L.646 8.146a.5.5 0 0 0 .708.708L8 2.207l6.646 6.647a.5.5 0 0 0 .708-.708L13 5.793V2.5a.5.5 0 0 0-.5-.5h-1a.5.5 0 0 0-.5.5v1.293z"/><path d="m8 3.293 6 6V13.5a1.5 1.5 0 0 1-1.5 1.5h-9A1.5 1.5 0 0 1 2 13.5V9.293z"/></svg></a>{% endif %}
<p>{{ member.description }}</p>
</div>
{% assign number_printed = forloop.index | modulo: 3 %}
{% if number_printed == 0 %}
</div>
<div class="row">
{% endif %}
{% endfor %}
</div>

<!-- Grad students -->
---
<h2 style="text-align: center; padding: 30px">Graduate Students</h2>
<div class="row">
{% for member in site.data.grad_students %}
<div class="col-sm-4 clearfix" style="text-align: center; ">
<div style="display: flex; justify-content: center;">
<div class="image-cropper">
<img class="person-pic" src="{{ site.url }}{{ site.baseurl }}/images/teampic/{{ member.photo }}" alt="{{ member.name }} photo"/>
</div>
</div>
<h4><b>{{ member.name }}</b></h4>
<i>{{ member.info }} <br> </i>
<a href="mailto:{{ member.email }}"><svg xmlns="http://www.w3.org/2000/svg" width="20" height="20" style="margin-right: 5px; margin-left: 5px; margin-top: 10px" fill="currentColor" class="bi bi-envelope-fill" viewBox="0 0 16 16"><path d="M.05 3.555A2 2 0 0 1 2 2h12a2 2 0 0 1 1.95 1.555L8 8.414zM0 4.697v7.104l5.803-3.558zM6.761 8.83l-6.57 4.027A2 2 0 0 0 2 14h12a2 2 0 0 0 1.808-1.144l-6.57-4.027L8 9.586zm3.436-.586L16 11.801V4.697z"/></svg></a>{% if member.twitter %}<a href="{{ member.twitter }}"><svg xmlns="http://www.w3.org/2000/svg" width="20" height="20" style="margin-right: 5px; margin-left: 5px; margin-top: 10px" fill="currentColor" class="bi bi-twitter" viewBox="0 0 16 16"><path d="M5.026 15c6.038 0 9.341-5.003 9.341-9.334q.002-.211-.006-.422A6.7 6.7 0 0 0 16 3.542a6.7 6.7 0 0 1-1.889.518 3.3 3.3 0 0 0 1.447-1.817 6.5 6.5 0 0 1-2.087.793A3.286 3.286 0 0 0 7.875 6.03a9.32 9.32 0 0 1-6.767-3.429 3.29 3.29 0 0 0 1.018 4.382A3.3 3.3 0 0 1 .64 6.575v.045a3.29 3.29 0 0 0 2.632 3.218 3.2 3.2 0 0 1-.865.115 3 3 0 0 1-.614-.057 3.28 3.28 0 0 0 3.067 2.277A6.6 6.6 0 0 1 .78 13.58a6 6 0 0 1-.78-.045A9.34 9.34 0 0 0 5.026 15"/></svg></a>{% endif %}{% if member.linkedin %}<a href="{{ member.linkedin }}"><svg xmlns="http://www.w3.org/2000/svg" width="20" height="20" style="margin-right: 5px; margin-left: 5px; margin-top: 10px"  fill="currentColor" class="bi bi-linkedin" viewBox="0 0 16 16"><path d="M0 1.146C0 .513.526 0 1.175 0h13.65C15.474 0 16 .513 16 1.146v13.708c0 .633-.526 1.146-1.175 1.146H1.175C.526 16 0 15.487 0 14.854zm4.943 12.248V6.169H2.542v7.225zm-1.2-8.212c.837 0 1.358-.554 1.358-1.248-.015-.709-.52-1.248-1.342-1.248S2.4 3.226 2.4 3.934c0 .694.521 1.248 1.327 1.248zm4.908 8.212V9.359c0-.216.016-.432.08-.586.173-.431.568-.878 1.232-.878.869 0 1.216.662 1.216 1.634v3.865h2.401V9.25c0-2.22-1.184-3.252-2.764-3.252-1.274 0-1.845.7-2.165 1.193v.025h-.016l.016-.025V6.169h-2.4c.03.678 0 7.225 0 7.225z"/></svg></a>{% endif %}{% if member.website %}<a href="{{ member.website }}"><svg xmlns="http://www.w3.org/2000/svg" width="20" height="20" style="margin-right: 5px; margin-left: 5px; margin-top: 10px" fill="currentColor" class="bi bi-house-fill" viewBox="0 0 16 16"><path d="M8.707 1.5a1 1 0 0 0-1.414 0L.646 8.146a.5.5 0 0 0 .708.708L8 2.207l6.646 6.647a.5.5 0 0 0 .708-.708L13 5.793V2.5a.5.5 0 0 0-.5-.5h-1a.5.5 0 0 0-.5.5v1.293z"/><path d="m8 3.293 6 6V13.5a1.5 1.5 0 0 1-1.5 1.5h-9A1.5 1.5 0 0 1 2 13.5V9.293z"/></svg></a>{% endif %}
<p>{{ member.description }}</p>
</div>
{% assign number_printed = forloop.index | modulo: 3 %}
{% if number_printed == 0 %}
</div>
<div class="row">
{% endif %}
{% endfor %}
</div>


---
<h2 style="text-align: center; padding: 30px">Undergraduate and Postgraduate Researchers</h2>
<div class="row">
{% for member in site.data.undergrads %}
<div class="col-sm-4 clearfix" style="text-align: center; ">
<div style="display: flex; justify-content: center;">
<div class="image-cropper">
<img class="person-pic" src="{{ site.url }}{{ site.baseurl }}/images/teampic/{{ member.photo }}" alt="{{ member.name }} photo"/>
</div>
</div>
<h4><b>{{ member.name }}</b></h4>
<i>{{ member.info }} <br> </i>
<a href="mailto:{{ member.email }}"><svg xmlns="http://www.w3.org/2000/svg" width="20" height="20" style="margin-right: 5px; margin-left: 5px; margin-top: 10px" fill="currentColor" class="bi bi-envelope-fill" viewBox="0 0 16 16"><path d="M.05 3.555A2 2 0 0 1 2 2h12a2 2 0 0 1 1.95 1.555L8 8.414zM0 4.697v7.104l5.803-3.558zM6.761 8.83l-6.57 4.027A2 2 0 0 0 2 14h12a2 2 0 0 0 1.808-1.144l-6.57-4.027L8 9.586zm3.436-.586L16 11.801V4.697z"/></svg></a>{% if member.twitter %}<a href="{{ member.twitter }}"><svg xmlns="http://www.w3.org/2000/svg" width="20" height="20" style="margin-right: 5px; margin-left: 5px; margin-top: 10px" fill="currentColor" class="bi bi-twitter" viewBox="0 0 16 16"><path d="M5.026 15c6.038 0 9.341-5.003 9.341-9.334q.002-.211-.006-.422A6.7 6.7 0 0 0 16 3.542a6.7 6.7 0 0 1-1.889.518 3.3 3.3 0 0 0 1.447-1.817 6.5 6.5 0 0 1-2.087.793A3.286 3.286 0 0 0 7.875 6.03a9.32 9.32 0 0 1-6.767-3.429 3.29 3.29 0 0 0 1.018 4.382A3.3 3.3 0 0 1 .64 6.575v.045a3.29 3.29 0 0 0 2.632 3.218 3.2 3.2 0 0 1-.865.115 3 3 0 0 1-.614-.057 3.28 3.28 0 0 0 3.067 2.277A6.6 6.6 0 0 1 .78 13.58a6 6 0 0 1-.78-.045A9.34 9.34 0 0 0 5.026 15"/></svg></a>{% endif %}{% if member.linkedin %}<a href="{{ member.linkedin }}"><svg xmlns="http://www.w3.org/2000/svg" width="20" height="20" style="margin-right: 5px; margin-left: 5px; margin-top: 10px"  fill="currentColor" class="bi bi-linkedin" viewBox="0 0 16 16"><path d="M0 1.146C0 .513.526 0 1.175 0h13.65C15.474 0 16 .513 16 1.146v13.708c0 .633-.526 1.146-1.175 1.146H1.175C.526 16 0 15.487 0 14.854zm4.943 12.248V6.169H2.542v7.225zm-1.2-8.212c.837 0 1.358-.554 1.358-1.248-.015-.709-.52-1.248-1.342-1.248S2.4 3.226 2.4 3.934c0 .694.521 1.248 1.327 1.248zm4.908 8.212V9.359c0-.216.016-.432.08-.586.173-.431.568-.878 1.232-.878.869 0 1.216.662 1.216 1.634v3.865h2.401V9.25c0-2.22-1.184-3.252-2.764-3.252-1.274 0-1.845.7-2.165 1.193v.025h-.016l.016-.025V6.169h-2.4c.03.678 0 7.225 0 7.225z"/></svg></a>{% endif %}{% if member.website %}<a href="{{ member.website }}"><svg xmlns="http://www.w3.org/2000/svg" width="20" height="20" style="margin-right: 5px; margin-left: 5px; margin-top: 10px" fill="currentColor" class="bi bi-house-fill" viewBox="0 0 16 16"><path d="M8.707 1.5a1 1 0 0 0-1.414 0L.646 8.146a.5.5 0 0 0 .708.708L8 2.207l6.646 6.647a.5.5 0 0 0 .708-.708L13 5.793V2.5a.5.5 0 0 0-.5-.5h-1a.5.5 0 0 0-.5.5v1.293z"/><path d="m8 3.293 6 6V13.5a1.5 1.5 0 0 1-1.5 1.5h-9A1.5 1.5 0 0 1 2 13.5V9.293z"/></svg></a>{% endif %}
<p>{{ member.description }}</p>
</div>
{% assign number_printed = forloop.index | modulo: 3 %}
{% if number_printed == 0 %}
</div>
<div class="row">
{% endif %}
{% endfor %}
</div>

## Lab Alumni
<i>Graduate students, postdoctoral associates & fellows, research scientists</i>
{% for member in site.data.alumni %}
{% if member.link %}
- [{{ member.name }}]({{ member.link }}) ({{ member.previous }}) {% if member.current %} &rarr; {{ member.current }} {% endif %}
{% else %}
- {{ member.name }} ({{ member.previous }}) {% if member.current %} &rarr; {{ member.current }} {% endif %}
{% endif %}
{% endfor %}

<i>Undergraduate students</i>
{% for member in site.data.alumni_ug %}
{% if member.link %}
- [{{ member.name }}]({{ member.link }}) ({{ member.previous }}) {% if member.current %} &rarr; {{ member.current }} {% endif %}
{% else %}
- {{ member.name }} ({{ member.previous }}) {% if member.current %} &rarr; {{ member.current }} {% endif %}
{% endif %}
{% endfor %}
