# Conference Registration Form

This project is a simple and semantic HTML form for registering to a conference.  
It includes all required sections, form controls, validations, and accessibility considerations, based on a structured task specification.

## ✅ Features

- Semantic structure using `<header>`, `<main>`, `<section>`, and `<fieldset>`
- Grouped form sections:
  - Personal Information
  - Ticket & Workshops (including nested fieldsets)
  - Payment Details
  - Agreements
- Proper use of `<label>` with `for` and `id` for accessibility
- Input validations using HTML attributes (`required`, `pattern`, `minlength`, `maxlength`)
- Phone, email, credit card, and CVV inputs with appropriate constraints
- Support for optional workshop selection and diet preferences
- Uploads and terms agreement (based on ticket type – JS could be added)
- Minimal, clean layout with no styling – ready for CSS

## 📁 File Structure

```
project-folder/
│
├── index.html   # Main form file (fully working)
```

## 🚀 How to Use

1. Open `index.html` in any modern browser.
2. Fill in the form fields.
3. Click **Send Data** to submit the form to the following endpoint:
   ```
   https://helper-htmlform-for-students.onrender.com/form-data
   ```
4. The data will be sent using `POST` method.

## ⚠️ Notes

- Credit card field accepts **13–19 digits**, with optional spaces every 4 digits.
- Expiry date must be this month or later.
- CVV is 3–4 digits and hidden on input (`type="password"`).
- Student ID upload logic is assumed to be handled separately if needed.
- No JavaScript is used – this is a pure HTML solution.

## 🧑‍💻 Author

Built as part of a front-end exercise to practice form structure, validation, and semantic HTML.
