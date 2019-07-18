---
title: File a report
permalink: /report/

layout: file
---

## File a report
Filing reports helps us with our accuracy in enforcing our server policy. To begin taking action, we'll need to ask a few questions.
<form class="usa-form-large" form method="POST" action="https://formspree.io/urgent@novelmc.net">
  <fieldset id="fs-frm-inputs">
  	<label for="full-name">What is your username?</label>
  	<input type="username" name="username" placeholder="IGN / @DTAG#0001 / you@email.com">
    <label for="full-name">Who are you reporting?</label>
  	<input type="username" name="username" placeholder="IGN / @DTAG#0001 / you@email.com">
    <label for="staff">Are they a staff member?</label>
    <select name="staff" id="staff" required="">
      <option value="Select" selected="" disabled="">Select</option>
      <option value="No">No</option>
      <option value="Yes">Yes</option>
    </select>
  	<label for="message">What did they do?</label>
    <textarea rows="5" name="message" id="message" placeholder="Describe what happened. Try to be as specific as possible." required=""></textarea>
    <input type="hidden" name="_subject" id="email-subject" value="Report Form Submission">
  <button type="submit">Submit</button>
</form>
