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
