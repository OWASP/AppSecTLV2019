---
title: Trainings
---

The event offers attendees _three, two or one day_ intense training courses by leading cyber, internet, application security specialists from the 26-28 May, 2019 in Tel Aviv. 

To register for the trainings, go to the [registration page](/registration/).

<table>
	<thead>
		<tr><th>Course title</th><th>Length</th><th>Days</th></tr>
	</thead>
	<tbody>
{% for training in site.data.trainings %}
    <tr>
    	<td><strong><a href="{{training.url}}">{{training.title}}</a></strong> with {{training.trainers}} </td>
     	<td>{{training.duration}} </td>
    	<td>{{training.days | replace: "/", "/<wbr>"}} </td>
    </tr>
{% endfor %}
	</tbody>
</table>

