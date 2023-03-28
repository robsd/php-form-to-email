# php-form-to-email 📨

A PHP script which sends form submissions to an email address of choice and offers a simple captcha to help prevent abuse.

## Installing on your own site

1. Create a `<form action="form-to-email/submit.php" method="post"></form>` element, fill it with inputs e.g. `<input type="text" name="first_name">` and make sure it can submit e.g. `<button type="submit">Submit Form</submit>`.
2. Copy the captcha question `<label id="captcha"></label>` and input `<input type="num" name="captcha-response">` elements inside the `<form...` element you just made above.
3. Copy the hidden captcha solution element `<input type="hidden" name="captcha-solution">` inside the `<form...` element you just made above.
4. Copy the `<script src="form-to-email/js/script.js"></script>` declaration somewhere near the bottom of the page.
5. Copy the **form-to-email** folder.
6. Replace the `your@email.example` at the top of **form-to-email/submit.php** with an email address where you want the form submissions to go to.
7. That's it! Go try out your new form.

## Need a hint?

See the **example.html** file for how to create the elements and declare the JavaScript.

## Support my work

If you like this repo or used any of the code, please star ⭐ it and consider supporting me below...

[![ko-fi](https://ko-fi.com/img/githubbutton_sm.svg)](https://ko-fi.com/F1F34TIDQ)