---
layout: page
title: Contact
front: true
permalink: /contact/
---

<p>Phasellus convallis elit id ullamcorper pulvinar. Duis aliquam turpis mauris, eu ultricies erat malesuada quis. Aliquam dapibus, lacus eget hendrerit bibendum, urna est aliquam sem, sit amet imperdiet est velit quis lorem.</p>
<div class="split style1">
	<section>
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
	</section>
	<section>
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
				<h3>Phone</h3>
				<span>(000) 000-0000</span>
			</li>
			<li>
				<h3>Social</h3>
				{% include social.html type="icons" %}
			</li>
		</ul>
	</section>
</div>
