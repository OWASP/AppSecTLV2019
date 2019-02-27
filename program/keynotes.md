---
title: Keynotes
---

<div class="keynote-full">
	
	<ul>
	{% for speaker in site.data.keynotespeakers %}
		{% if speaker.name %}
		<li>
			<img style="background-image: url(/assets/images/keynotes/{{speaker.image | default: 'owasp_logo.png'}});{{speaker.style}};">
			<h4>{{speaker.name}}</h4>
			<p>
				{{speaker.bio}}
			</p>
		</li>
		{% endif %}
	{% endfor %}
	</ul>
</div>