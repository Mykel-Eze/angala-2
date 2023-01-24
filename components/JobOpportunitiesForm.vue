<!-- eslint-disable vue/singleline-html-element-content-newline -->
<template>
  <form id="job-opportunities-form" action="#" class="cfs-block">
    <div class="input-field">
      <label for="job_email" class="active">Email address</label>
      <input id="job_email" type="email" name="job_email" placeholder="Email address" required>
    </div>
    <div class="input-field">
      <label for="job_phone" class="active">Phone number</label>
      <input id="job_phone" type="tel" name="job_phone" placeholder="Phone number" required>
    </div>
    <div class="input-field">
      <label for="job_postal_address" class="active">Postal address</label>
      <input id="job_postal_address" type="text" name="job_postal_address" placeholder="Postal address" required>
    </div>
    <div class="input-field">
      <label for="job_full_name" class="active">Full name</label>
      <input id="job_full_name" type="text" name="job_full_name" placeholder="First name and last name" required>
    </div>
    <div class="input-field">
      <label for="current_work_status" class="active">Current work or status</label>
      <input id="current_work_status" type="text" name="current_work_status" placeholder="Role in the organization" required>
    </div>
    <div class="input-field">
      <label for="responsibility" class="active">Area of responsibility</label>
      <input id="responsibility" type="text" name="responsibility" placeholder="Area of responsibility" required>
    </div>
    <div class="input-field">
      <label for="job_interests_in_jaf" class="active">Describe your interest in Japtini Asset Finance?</label>
      <textarea id="job_interests_in_jaf" class="materialize-textarea" name="job_interests_in_jaf" placeholder="Write your message here" required />
    </div>
    <div class="input-field">
      <label for="position" class="active">Ideal position or area of responsibility</label>
      <input id="position" type="text" name="position" placeholder="Ideal position or area responsibility" required>
    </div>
    <div class="input-field select-field">
      <label for="job_mode_of_communication">How may we contact you</label>
      <select id="job_mode_of_communication" name="job_mode_of_communication" multiple required>
        <option value="Phone">Phone</option>
        <option value="Email">Email</option>
        <option value="Post">Post</option>
      </select>
      <img src="~/assets/images/chevron-down.svg" alt="chevron-down" class="chevron-down">
    </div>
    <div class="input-field">
      <label for="job_other_comment" class="active">Any other comment? (optional)</label>
      <textarea id="job_other_comment" class="materialize-textarea" name="job_other_comment" placeholder="Write your message here" />
    </div>

    <div class="submit-btn-wrapper">
      <button class="submit-btn">
        Send Messages
      </button>
    </div>
  </form>
</template>

<script>
export default {
  name: 'JobOpportunitiesForm'
}
</script>
