# Form Validation

This code snippet demonstrates a basic form validation implementation using JavaScript and jQuery. It validates various types of form fields such as required fields, number fields, letter fields, and email fields before submitting the form.

## Usage

To use this code, follow these steps:

1. Include the jQuery library in your HTML file:

```html
   <script src="https://code.jquery.com/jquery-3.6.0.min.js"></script>
```

2. Apply the necessary HTML markup to your form fields. Add the appropriate classes to the input elements to define their validation rules. For example:

```html
<form>
  <input type="text" class="required" />
  <input type="text" class="numbers-only" />
  <input type="text" class="letters-only" />
  <input type="email" class="email-only" />
  <button type="submit">Submit</button>
</form>
```

## Validation Rules

The code supports the following validation rules based on the class names assigned to the form fields:

required: Marks a field as required and displays an error message if it's left empty.
numbers-only: Allows only numeric values in the field and displays an error message if non-numeric characters are entered.
letters-only: Allows only alphabetic characters in the field and displays an error message if non-alphabetic characters are entered.
email-only: Validates that the field contains a valid email address using a simple regular expression pattern.


## Contributing
Contributions to improve or extend this form validation code are welcome. If you have any suggestions, bug fixes, or enhancements, please feel free to submit a pull request.
