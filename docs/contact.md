---
hide:
  - footer
---
<section id="contact">
	<div class="inner">
		<section>
			<form action="https://formspree.io/{{ site.email }}" method="POST">
				<div class="field half first">
					<label class = "contact_labels" for="name">Name</label>
					<input type="text" name="name" id="name" />
				</div>
				<div class="field half">
					<label class="contact_labels" for="email">Email</label>
					<input type="text" name="_replyto" id="email" />
				</div>
				<div class="field">
					<label class = "contact_labels" for="message">Message</label>
					<textarea name="message" id="message" rows="6"></textarea>
				</div>
				<ul class="actions">
					<li class="contact_buttons"><input type="submit" value="Send Message" class="special" /></li>
					<li class="contact_buttons"><input type="reset" value="Clear" /></li>
				</ul>
			</form>
		</section>
	</div>
</section>