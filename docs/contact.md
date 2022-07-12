---
hide:
  - footer
---
# <img src="../assets/raccoon.png" style="height:30px;"> contact 

just in case you wanted to drop a line or send a description of your adorably cute dog/cat/ferret/parakeet/raccoon: 

<div style="font-size:80%">
<span style="color:red;">*</span> indicates a required field.
</div>

<section id="contact">
	<div class="inner">
		<section>
			<form action="https://formspree.io/{{ site.email }}" method="POST">
				<div class="field half first">
					<label class = "contact_labels" for="name">Name</label>
					<input type="text" name="name" id="name" required/>
				</div>
				<div class="field half">
					<label class="contact_labels" for="email">Email</label>
					<input type="text" name="_replyto" id="email" required/>
				</div>
				<div class="field">
					<label class = "contact_labels" for="message">Message</label>
					<textarea name="message" id="message" rows="6" required></textarea>
				</div>
				<ul class="actions">
					<li class="contact_buttons"><input type="submit" value="Send Message" class="special" /></li>
					<li class="contact_buttons"><input type="reset" value="Clear" /></li>
				</ul>
			</form>
		</section>
	</div>
</section>