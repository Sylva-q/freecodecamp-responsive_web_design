# Registration-form
Learn HTML forms by building a signup page. Learn how to control what types of data people can type into the form, and some new CSS tools for styling.

Summary:
1. Set up the basic form structure
   Include a <form> with appropriate action and method attributes.

2. Structure fieldsets, legends, labels & inputs
- Wrap related fields inside <fieldset> with a <legend>.
- Link <label> to inputs using for="id" on labels and id="…" on the inputs.

3. Add different input types
- Text inputs for name fields (first, last, email).
- Email (type="email"), password (type="password", plus pattern) with validation.
- File input for profile picture – remember id and linking label correctly.
- Number input (type="number") with min and max attributes.
- Dropdown <select> element.
- Textarea for multi-line text input.

4. Add terms & conditions with link
- Use a checkbox with required attribute.
- Wrap the checkbox and link within a single <label> like:

```
<label for="terms">
  <input id="terms" type="checkbox" required> I accept the <a href="…">terms and conditions</a>
</label>
```

  * Ensure no extra spaces and the <a> wraps exactly the text terms and conditions.

5. Style the form with CSS
   - Set background, text color, font, spacing.
   - Change borders of fieldsets.
   - Style input, textarea and select for consistent look.
