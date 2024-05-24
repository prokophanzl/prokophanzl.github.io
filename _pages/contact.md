---
layout: page
title: Get in touch
description: 'Dann comes with a built-in contact form, that you can use with Formspree service to handle up to 50
submissions per month for free. You could also easily switch to another contact form service if you want.'
permalink: /contact/
---

<div class="form-box">
	<form action="https://formspree.io/f/xbjnekej" method="POST">
		<div class="form__group">
			<label class="form__label screen-reader-text" for="form-name">Your Name</label>
			<input class="form__input" id="form-name" type="text" name="name" placeholder="Name" required />
		</div>
		<div class="form__group">
			<label class="form__label screen-reader-text" for="form-email">Your Email</label>
			<input class="form__input" id="form-email" type="email" name="email" placeholder="Email" required />
		</div>
		<div class="form__group">
			<label class="form__label screen-reader-text" for="form-text">Your Message</label>
			<textarea class="form__input" id="form-text" name="text" rows="7" placeholder="Message" required></textarea>
		</div>
		<div class="form__group">
			<button class="button button--primary" type="submit">Send Message</button>
		</div>
	</form>
</div>
