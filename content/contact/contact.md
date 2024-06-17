---
layout: layouts/base.njk
eleventyNavigation:
  key: Contact
  order: 4
---
# Contact Me

<form>
<div class="row">
  <div class="col">
    <label for="firstNameInput" class="form-label">First Name</label>
    <input type="text" class="form-control" id="firstNameInput" aria-label="First name">
  </div>
  <div class="col">
    <label for="lastNameInput" class="form-label">Last Name</label>
    <input type="text" class="form-control" id="lastNameInput" aria-label="Last name">
  </div>
</div>
  <div class="mb-3">
    <label for="exampleInputEmail1" class="form-label">Email address</label>
    <input type="email" class="form-control" id="exampleInputEmail1" aria-describedby="emailHelp">
    <div id="emailHelp" class="form-text">We'll never share your email with anyone else.</div>
  </div>
  <div class="mb-3">
    <label for="textArea" class="form-label">Message</label>
    <textarea class="form-control" id="textArea" rows="3"></textarea>
  </div>
  <div class="mb-3">
    <div class="form-check">
      <input class="form-check-input" type="checkbox" value="" id="flexCheckDefault">
      <label class="form-check-label" for="flexCheckDefault">
      I agree to the Terms and Conditions.
      </label>
    </div>
  </div>
  <div class="col-12">
    <button class="btn btn-primary" type="submit">Submit</button>
  </div>
</form>
 