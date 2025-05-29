# Student Details Form

This is a simple HTML and JavaScript-based student registration form. It allows users to input their personal information and displays it after submission. The submitted data is also stored in the browser's `localStorage`.

## 📋 Features

* Input fields for:

  * First Name
  * Surname
  * Date of Birth
  * Gender (Male/Female/Others)
  * Phone Number
  * Address
* Styled using basic CSS for readability and alignment.
* Upon form submission:

  * Data is saved to `localStorage`.
  * Entered details are displayed on the screen.
* Prevents page reload on form submission using JavaScript `event.preventDefault()`.

## 💻 Technologies Used

* HTML5
* CSS3
* JavaScript

## 📦 How to Use

1. Open the `index.html` file in any modern web browser.
2. Fill in the form with your details.
3. Click on the "Submit" button.
4. Your submitted details will be displayed below the form.
5. The same details are stored in the browser's `localStorage` for future reference.

## 📁 File Structure

```
student-details-form/
├── index.html   # Main HTML file with embedded CSS and JavaScript
```

## 📝 Notes

* The gender field is handled using radio buttons.
* Data is not sent to a server—this is purely client-side.
* `localStorage` is used for persistence across browser sessions (until manually cleared).

feel free to share your queries here aravindboini1225@gmail.com.
