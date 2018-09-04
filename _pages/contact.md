---
layout: default
title: Contact
permalink: '/contact/'
---
<section class="wrapper style1 align-center">
	<div class="inner medium">
		<h2>Get in touch</h2>
		<form method="POST" action="http://formspree.io/rebelandrefuge@gmail.com">
      <input type="hidden" name="_subject" value="New submission!" />
      <input type="hidden" name="_next" value="http://www.rebelandrefuge.com/contact/success" />
			<div class="fields">
				<div class="field half">
					<label for="name">Name</label>
					<input type="text" name="name" id="name" value="" />
				</div>
				<div class="field half">
					<label for="email">Email</label>
					<input type="email" name="email" id="email" value="" />
				</div>
				<div class="field">
					<label for="message">Message</label>
					<textarea name="message" id="message" rows="6"></textarea>
				</div>
			</div>
			<ul class="actions special">
				<li><input type="submit" name="submit" id="submit" value="Send Message" /></li>
			</ul>
		</form>
	</div>
</section>