---
layout: container
title: Contact
permalink: '/contact/'
---
<div class='row'>
	<div class="col-8">
		<h2 class="mt-5">Get in touch</h2>

		<form class="mt-5" method="POST" action="http://formspree.io/rebelandrefuge@gmail.com">
		  <input type="hidden" name="_subject" value="New submission!" />
		  <input type="hidden" name="_next" value="http://www.rebelandrefuge.com/contact/success" />
			<div class="fields">
				<div class="form-group">
					<label for="name">Name</label>
					<input type="text" name="name" id="name" class='form-control' value="" />
				</div>
				<div class="form-group">
					<label for="email">Email</label>
					<input type="email" name="email" id="email" class='form-control' value="" />
				</div>
				<div class="form-group">
					<label for="message">Message</label>
					<textarea name="message" id="message" class='form-control' rows="6"></textarea>
				</div>
			</div>
			<input type="submit" name="submit" id="submit" class="btn btn-primary" value="Send Message" />
		</form>
	</div>
</div>
