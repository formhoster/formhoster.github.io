---
layout: page
title: Basic Contact Form Demo
permalink: /contact-demo/
formhoster_url: https://hub.formhoster.com/basic-contact-form/11
formhoster_endpoint: https://hub.formhoster.com/forms/submit/11
---


<form action="https://hub.formhoster.com/forms/submit/11" method="POST">
<input type="hidden" name="success_url" id="_success_url" value="https://hub.formhoster.com/pub/success">
<input type="hidden" name="pm_user" id="pm_user" value="pfaffman">
<!-- <input type="hidden" name="debug_mode" id="debug_mode" value=True> -->
<div class="form-group">
  <label for="name">Name</label>
  <input type="text" id="name" name="name" placeholder="Your name placeholder" required>
</div>
<div class="form-group">
  <label for="email">Email</label>
  <input type="text" id="email" name="email" placeholder="Your email placeholder" required>
</div>
<div class="form-group">
  <label for="message">Tell us more about what you need</label>
  <textarea id="message" name="message" placeholder="Your message goes here" style="height:8rem"></textarea>
</div>
<input class="button" type="submit" value="Submit">
</form>
