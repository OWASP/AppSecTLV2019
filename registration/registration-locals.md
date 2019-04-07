---
title: Registration For Locals
---

<a class="registerbutton" href="https://knasim.herokuapp.com/owasp2019/Locals/register">Register now</a>

*If you are an international visitor, please use the
[registration page for international visitors](/registration/registration-international).*

## Training

The event offers attendees _three, two or one day_ intense training courses by leading cyber, internet, application security specialists from the 26-28 May, 2019 in Tel Aviv. Further information regarding the training program and how to book will be available shortly.

<table>
	<thead>
		<tr><th>Course title</th><th>Length</th><th>Days</th><th>Cost</th></tr>
	</thead>
	<tbody>
{% for training in site.data.trainings %}
    <tr>
    	<td><strong><a href="{{training.url}}">{{training.title}}</a></strong> with {{training.trainers}} </td>
     	<td>{{training.duration}} </td>
    	<td>{{training.days | replace: "/", "/<wbr>"}} </td>
    	<td class="price">{{training.localprice}}</td>
    </tr>
{% endfor %}
	</tbody>
</table>

## Conference Program

Following the training program, Global Appsec Tel Aviv 2019 will provide attendees with exceptional conference keynotes and seminars led by industry security experts and leaders.
Don’t miss this opportunity to join your fellow colleagues to learn, network and enjoy the many unique experiences that Global Appsec Tel Aviv 2019 has to offer.
There are several registration options:

<table>
  <thead>
    <tr>
      <th><em>Registration Type</em></th>
      <th><em>Fee</em> *</th>
      <th><em>Details</em></th>
      <th> </th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>Non-Member Conference</td>
      <td class="price">2775 NIS</td>
      <td>Includes conference program for two days, coffee breaks, lunch, expo, and networking event ticket</td>
      <td>Available Now</td>
    </tr>
    <tr>
      <td>Member Conference</td>
      <td class="price">2565 NIS</td>
      <td>Includes conference program for two days, coffee breaks, lunch, expo, and networking event ticket</td>
      <td>Available Now</td>
    </tr>
    <tr>
      <td>Student</td>
      <td class="price">535 NIS</td>
      <td>Includes conference program for two days, coffee breaks, lunch, and expo. <strong>Networking event ticket is not included</strong>.</td>
      <td>Available Now</td>
    </tr>
    <tr>
      <td>Networking Event Ticket Only</td>
      <td class="price">535 NIS</td>
      <td>Additional conference event tickets can be purchased.</td>
      <td>Available Now</td>
    </tr>
  </tbody>
</table>


* Note: If you receive a discount code, select the registration category first, then enter the discount code and the fee will be modified based on the code.

*	Student Tickets – Students must present a valid student ID and proof of affiliation at an accredited university to pick up the ticket (Limited tickets available).
*	No refunds or replacements for loss of badge
* Prices include VAT
*	Groups discounts are available for 10+ ticket batches
*	Vendor discounts are available, email Kelly for details.
*	Tickets / Conference Registration and Training Registration are nonrefundable and nontransferable.
* OWASP is not responsible for any additional foreign transaction fees related to the processing of the registration.

<a class="registerbutton" href="https://knasim.herokuapp.com/owasp2019/Locals/register">Register now</a>
