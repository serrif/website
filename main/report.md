---
title: File a report
permalink: /report/

layout: file
---

## File a report
<form class="usa-form-large" action="https://formspree.io/support@novelmc.net" method="POST">
  <input type="hidden" name="_subject" value="Report for support@novelmc.net" />
  <fieldset>
    <label for="submitter-name">Your username, Discord tag, or email</label>
    <input id="submitter-name" name="submitter-name" type="text">

    <label for="offender-name">Offender's username, Discord tag, or email</label>
    <input id="offender-name" name="offender-name" type="text">

    <label for="report-text">What did they do?</label>
    <input id="report-text" name="report-text" rows="7" type="text">

    <div>
      <div class="usa-input-grid usa-input-grid-small">
        <label for="rank">Your rank</label>
        <select id="state" name="state">
          <option value>- Select -</option>
          <option value="OP">Member</option>
          <option value="ART">Architect</option>
          <option value="MOD">Mod</option>
          <option value="SRM">Senior Mod</option>
          <option value="DEV">Developer</option>
          <option value="EXEC">Executive</option>
      </div>

  </fieldset>
  <button type="submit">Submit report</button>
</form>
