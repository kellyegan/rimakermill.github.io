---
layout: page
title: Contact
front: true
index: 3
permalink: /contact/
---

<p>You can contact us through email or our social media accounts. The best way to meet the members is to stop by our space on Wednesdays or Fridays from 7–10pm.</p>

<div class="split style1">
<!--	<section>
		<form method="post" action="#">
			<div class="field half first">
				<label for="name">Name</label>
				<input type="text" name="name" id="name" />
			</div>
			<div class="field half">
				<label for="email">Email</label>
				<input type="text" name="email" id="email" />
			</div>
			<div class="field">
				<label for="message">Message</label>
				<textarea name="message" id="message" rows="5"></textarea>
			</div>
			<ul class="actions">
				<li><a href="" class="button submit">Send Message</a></li>
			</ul>
		</form>
	</section> -->

  <section>
		<img src="/assets/images/RIMM-map.svg" alt="Map of area near Rhode Island Maker Mill, just off I-95 exit 29" height="480px" />
	</section>
	<address>
		<ul class="contact">
			<li>
				<h3>Address</h3>
				<span>{{ site.address.street }}<br />
				{{ site.address.city }}, {{ site.address.state }} {{ site.address.zip }}</span>
			</li>
			<li>
				<h3>Email</h3>
				<a href="#">{{ site.email }}</a>
			</li>
			<li>
				<h3>Social</h3>
				{% include social.html type="icons" %}
			</li>
		</ul>
	</address>
</div>
