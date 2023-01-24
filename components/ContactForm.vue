<!-- eslint-disable vue/singleline-html-element-content-newline -->
<template>
  <form id="contact-form" action="#" class="cfs-block">
    <div class="input-field select-field">
      <label for="category">Category</label>
      <select id="category" name="category" required>
        <option value="Business owners">Business owners</option>
        <option value="Government and public institutions">Government & public institutions</option>
        <option value="Investors and banks">Investors & banks</option>
        <option value="Others">Others</option>
      </select>
      <img src="~/assets/images/chevron-down.svg" alt="chevron-down" class="chevron-down">
    </div>
    <div class="input-field">
      <label for="email" class="active">Email address</label>
      <input id="email" type="email" name="email" placeholder="Email address" required>
    </div>
    <div class="input-field">
      <label for="phone" class="active">Phone number</label>
      <input id="phone" type="tel" name="phone" placeholder="Phone number" required>
    </div>
    <div class="input-field">
      <label for="organization_name" class="active">Name Of organization Or institution</label>
      <input id="organization_name" type="text" name="organization_name" placeholder="Organization/Institution name" required>
    </div>
    <div class="input-field">
      <label for="postal_address" class="active">Postal address</label>
      <input id="postal_address" type="text" name="postal_address" placeholder="Postal address" required>
    </div>
    <div class="input-field">
      <label for="full_name" class="active">Full name</label>
      <input id="full_name" type="text" name="full_name" placeholder="First name and last name" required>
    </div>
    <div class="input-field">
      <label for="role" class="active">Role</label>
      <input id="role" type="text" name="role" placeholder="Role in the organization" required>
    </div>
    <div class="input-field">
      <label for="area_of_focus" class="active">Sector/Area of focus</label>
      <input id="area_of_focus" type="text" name="area_of_focus" placeholder="Sector/Area of focus" required>
    </div>
    <div class="input-field">
      <label for="interests_in_jaf" class="active">Describe your interest in Japtini Asset Finance?</label>
      <textarea id="interests_in_jaf" class="materialize-textarea" name="interests_in_jaf" placeholder="Write your message here" required />
    </div>
    <div class="input-field select-field">
      <label for="mode_of_communication">How may we contact you</label>
      <select id="mode_of_communication" name="mode_of_communication" multiple required>
        <option value="Phone">Phone</option>
        <option value="Email">Email</option>
        <option value="Post">Post</option>
      </select>
      <img src="~/assets/images/chevron-down.svg" alt="chevron-down" class="chevron-down">
    </div>
    <div class="input-field">
      <label for="other_comment" class="active">Any other comment? (optional)</label>
      <textarea id="other_comment" class="materialize-textarea" name="other_comment" placeholder="Write your message here" />
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
  name: 'ContactForm'
}
</script>
