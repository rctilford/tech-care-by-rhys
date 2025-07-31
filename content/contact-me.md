---
title: "Get In Touch"
layout: "simple"
---

<div class="bg-primary-50 p-6 rounded-lg">
<form
  action="https://formspree.io/f/mgvzazed"
  class="fs-form"
  target="_top"
  method="POST"
>
  <div class="space-y-3">
    <label class="text-sm text-gray-600 mb-4" for="name">Your Name</label>
    <input class="w-full px-4 py-2 border border-gray-300 rounded-lg focus:ring-2 focus:ring-primary-500 focus:border-primary-500" id="name" name="name" required />
  </div>
  <div class="space-y-3">
    <label class="text-sm text-gray-600 mb-4" for="email">Email</label>
    <input class="w-full px-4 py-2 border border-gray-300 rounded-lg focus:ring-2 focus:ring-primary-500 focus:border-primary-500" id="email" name="email" required />
  </div>
  <div class="space-y-3">
    <label class="text-sm text-gray-600 mb-4" for="message">Message</label>
    <textarea
      class="w-full px-4 py-2 border border-gray-300 rounded-lg focus:ring-2 focus:ring-primary-500 focus:border-primary-500"
      id="message"
      name="message"
      placeholder="What would you like to discuss?"
      required
    ></textarea>
  </div>
  <div class="fs-button-group">
    <button class="w-full px-4 py-2 bg-primary-600 text-white rounded-lg hover:bg-primary-700 transition-colors duration-200" type="submit">Submit</button>
  </div>
</form>
</div>