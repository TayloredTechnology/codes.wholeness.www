+++
description = ""
title = "Contact Wholeness"
draft = false

+++
<fieldset>
  <legend>Contact Us</legend>
  <!--
  <div class="typeform-widget" data-url="https://tayloredtechnology.typeform.com/to/MVyvyF" data-transparency="50" data-hide-headers=true data-hide-footer=true style="width: 100%; height: 500px;" > </div> <script> (function() { var qs,js,q,s,d=document, gi=d.getElementById, ce=d.createElement, gt=d.getElementsByTagName, id="typef_orm", b="https://embed.typeform.com/"; if(!gi.call(d,id)) { js=ce.call(d,"script"); js.id=id; js.src=b+"embed.js"; q=gt.call(d,"script")[0]; q.parentNode.insertBefore(js,q) } })() </script> <div style="font-family: Sans-Serif;font-size: 12px;color: #999;opacity: 0.5; padding-top: 5px;" > powered by <a href="https://www.typeform.com/examples/forms/contact-form-template/?utm_campaign=MVyvyF&amp;utm_source=typeform.com-9571695-Basic&amp;utm_medium=typeform&amp;utm_content=typeform-embedded-contactform&amp;utm_term=EN" style="color: #999" target="_blank">Typeform</a> </div>
  -->
    <form name="contact" action="thank-you" class="form" netlify>

      <div class="form-item">
          <input type="text" name="firstName" autofocus="true" autocomplete="off" placeholder="Enter your first name…">
      </div>

      <div class="form-item">
          <input type="text" name="lastName" autofocus="true" autocomplete="off" placeholder="Enter your last name…">
      </div>

      <div class="form-item">
        <span id="user-email-validation-error"></span>
        <input type="email" name="email" autofocus="true" autocomplete="off" placeholder="Enter your email address…">
      </div>

      <div class="form-item">
        <input type=“text” name=“phone” autofocus="true" autocomplete="off" placeholder="Enter your phone number…">
      </div>

      <div class=“form-item”>
          <textarea rows=“4” autofocus="true" autocomplete="off" placeholder="Enter your message…"></textarea>
      </div>

      <div class="form-item">
          <button>Send Message</button>
      </div>

  </form>
</fieldset>
