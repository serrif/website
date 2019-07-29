---
title: File an appeal
permalink: /appeal/

layout: info
sidenav: forms
---

## File an appeal
Filing ban appeals helps us with our accuracy in improving effective and accurate punishment. To begin taking action, we'll need to ask a few questions.

<form class="usa-form-large" form method="POST" action="https://formspree.io/help@novelmc.net">
  <fieldset id="fs-frm-inputs">
    <label for="service">Where were you banned?</label>
    <select name="service" id="service" required="">
      <option value="Select" selected="" disabled="">Select</option>
      <option value="In-game">In-game</option>
      <option value="Discord">Discord</option>
      <option value="Other">Other / all</option>
    </select>
    <label for="username">What is your username? (For both services, specify multiple).</label>
  	<input type="username" name="username" placeholder="IGN / @DTAG#0001 / you@email.com" required="">
    <label for="id">Do you have a punishment ID?</label>
  	<input type="id" name="id" placeholder="#ID123">
    <label for="reason">Why were you banned?</label>
    <textarea rows="5" name="reason" id="reason" placeholder="Please attempt to provide an explanation as to why you were banned. Try to be as detailed as possible. Include any necessary evidence." required=""></textarea>
    <label for="unban-reason">Why should you be unbanned?</label>
    <textarea rows="5" name="unban-reason" id="unban-reason" placeholder="Again, please attempt to provide an explanation as to why you think you should be unbanned. If you were banned on accident, skip this question." required=""></textarea>
    <label for="suspended">Were you suspended (banned permanently)?</label>
    <select name="suspended" id="suspended" required="">
      <option value="Select" selected="" disabled="">Select</option>
      <option value="Yes">Yes</option>
      <option value="No">No</option>
    </select>
    <label for="contact">How can we contact you?</label>
  	<input type="contact" name="contact" placeholder="@DTAG#0001 / you@email.com" required="">
    <input type="hidden" name="_subject" id="email-subject" value="Appeal Form Submission">
  <button type="submit">Submit</button>
