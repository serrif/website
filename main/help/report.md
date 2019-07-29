---
title: File a report
permalink: /help/report/

layout: help
sidenav: forms
---

## File a report
Filing reports helps us with our accuracy in enforcing our server policy. To begin taking action, we'll need to ask a few questions.

<form class="usa-form-large" form method="POST" action="https://formspree.io/urgent@novelmc.net">
  <fieldset id="fs-frm-inputs">
  	<label for="username">What is your username?</label>
  	<input type="username" name="username" placeholder="IGN / @DTAG#0001 / you@email.com" required="">
    <label for="full-name">Who are you reporting?</label>
  	<input type="offender" name="offender" placeholder="IGN / @DTAG#0001 / them@email.com" required="">
    <label for="staff">Are you reporting a staff member?</label>
    <select name="staff" id="staff" required="">
      <option value="Select" selected="" disabled="">Select</option>
      <option value="Yes">Yes</option>
      <option value="No">No</option>
    </select>
  	<label for="action">What did they do?</label>
    <textarea rows="5" name="action" id="action" placeholder="Describe what happened. Try to be as specific as possible. Image files must be attached using sites for image hosting." required=""></textarea>
    <label for="rule">What policy was broken?</label>
    <select name="rule" id="rule" required="">
      <option value="Select" selected="" disabled="">Select</option>
      <option value="Server policy">Server policy</option>
      <option value="Discord policy">Discord policy</option>
      <option value="Other">Other</option>
    </select>
    <label for="referral">Were you referred to file a report?</label>
    <select name="referral" id="referral" required="">
      <option value="Select" selected="" disabled="">Select</option>
      <option value="Yes">Yes</option>
      <option value="No">No</option>
    </select>
    <label for="rank">What is your rank?</label>
    <select name="rank" id="rank" required="">
      <option value="Select" selected="" disabled="">Select</option>
      <option value="Member">Member</option>
      <option value="Architect">Architect</option>
      <option value="Mod">Mod</option>
      <option value="Senior Mod">Senior Mod</option>
      <option value="Developer">Developer</option>
      <option value="Executive">Executive</option>
    </select>
    <label for="contact">How can we contact you?</label>
  	<input type="contact" name="contact" placeholder="@DTAG#0001 / you@email.com" required="">
    <input type="hidden" name="_subject" id="email-subject" value="Report Form Submission">
  <button type="submit">Submit</button>
