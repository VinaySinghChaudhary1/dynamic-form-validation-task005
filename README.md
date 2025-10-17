# dynamic-form-validation-task005
TDS generated repo


## 🌀 Round 1 (2025-10-17)

**Brief:** Create a responsive contact form with a title 'Secure Contact' using Bootstrap/Tailwind CSS. The form must contain two required input fields: 'Email' (ID: #input-email) and 'Message' (ID: #input-message), and a submit button (ID: #submit-form). Apply modern card styling (rounded, shadow) to the entire form container.

**Checks:**
- !!document.querySelector('form#contact-form')
- !!document.querySelector('#input-email')
- !!document.querySelector('#input-message')
- !!document.querySelector('#submit-form')
- document.querySelector('#input-email').getAttribute('required') !== null
- document.querySelector('#input-message').tagName === 'TEXTAREA' || document.querySelector('#input-message').type !== 'text'
- document.querySelector('form#contact-form').className.includes('shadow') && document.querySelector('form#contact-form').className.includes('rounded')

**Status:** ✅ Completed

**Pages URL:** [https://vinaysinghchaudhary1.github.io/dynamic-form-validation-task005/](https://vinaysinghchaudhary1.github.io/dynamic-form-validation-task005/)

---


## 🔁 Round 2 Update (2025-10-17)

**Brief:** Enhance the contact form with real-time feedback. Below the #input-email, add an error message container (ID: #email-error). This container must initially be hidden. On invalid email input (e.g., missing '@' symbol), the error message should appear. Upon successful submission (when both fields are valid), the form should disappear and be replaced by a large, green 'Success Message' container (ID: #submission-success) that slides in smoothly using a CSS transition.

**Checks:**
- !!document.querySelector('#input-email')
- !!document.querySelector('#email-error')
- !!document.querySelector('#submission-success')
- document.querySelector('#email-error').style.visibility === 'hidden' || document.querySelector('#email-error').style.display === 'none'
- document.querySelector('#submission-success').textContent.includes('Success') || document.querySelector('#submission-success').textContent.includes('Submitted')
- window.getComputedStyle(document.querySelector('#submission-success')).transition.includes('transform') || window.getComputedStyle(document.querySelector('#submission-success')).transition.includes('opacity')
- document.querySelector('#email-error').className.includes('text-red')

**Status:** ✅ Redeployed

**Pages URL:** [https://VinaySinghChaudhary1.github.io/dynamic-form-validation-task005/](https://VinaySinghChaudhary1.github.io/dynamic-form-validation-task005/)

> ⏳ **Note:** GitHub Pages may take around 10 minutes to fully render and reflect all updates for this round.

---
