# README

## Email Form

This is a simple HTML form designed for contacting a service or individual via email. The form is styled with CSS for a visually appealing and responsive user interface.

### Usage

1. Clone or download the repository.

   ```bash
   git clone <repository-url>
   ```

2. Open the `index.html` file in a web browser.

### Features

- **Contact Form**: Easily customizable form for users to enter their name, email, and message.
- **Submission**: Form data is submitted to the specified API endpoint (`https://api.web3forms.com/submit`) using the POST method.
- **Styling**: The form is styled using the provided `style.css` file, creating an engaging and user-friendly interface.

### How to Customize

1. **Access Key**: Replace the value of the `access_key` input field in the form with your own API access key.

   ```html
   <input type="hidden" name="access_key" value="your-access-key">
   ```

2. **Images**: Customize the images used in the form by replacing the `src` attribute of the `<img>` tags.

   ```html
   <img src="path-to-your-image" alt="">
   ```

3. **Styles**: Adjust the styles in the `style.css` file to match your branding or preferences.

### Styling Information

The CSS styles are defined in the `style.css` file. The design is responsive, ensuring a seamless experience on various devices.

#### Color Scheme

- Background: Linear gradient from #20124d to #c1558b
- Accent Color: #f8971c
- Text Color: #ffffff

### Responsive Design

The form layout adjusts for smaller screens (max-width: 800px), providing a mobile-friendly experience.

### Credits

- Icons: [Font Awesome](https://fontawesome.com/)
- Fonts: [Google Fonts - 'Outfit'](https://fonts.google.com/specimen/Outfit)

Feel free to modify and adapt this code to suit your specific needs. If you have any questions or feedback, please [contact us](mailto:your-email@example.com).

**Note:** Ensure that you comply with API usage terms and conditions when using the provided API endpoint.
