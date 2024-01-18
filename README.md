## Cookie Banner Widget for Elementor

This is a simple Cookie Banner widget designed for use with Elementor, a popular WordPress page builder. This widget displays a banner at the top of your website, informing users about the use of cookies and providing a link to the privacy policy. Users can accept cookies by clicking the "Accept" button.

### Installation:

1. **Download Widget JSON:**
   - Download the JSON file containing the widget configuration.

2. **Import Widget to Elementor:**
   - Log in to your WordPress admin dashboard.
   - Navigate to the page where you want to add the Cookie Banner using Elementor.
   - Edit the page with Elementor.
   - Click on the folder icon in the Elementor panel to access the templates.
   - Select "Import Templates."
   - Upload the downloaded JSON file.

3. **Adjust Settings:**
   - After importing, you can customize the widget settings using the Elementor editor.
   - Modify text, colors, and other styles as needed to match your website's design.

### Widget Styling (CSS):

The provided CSS styles control the appearance of the Cookie Banner. You can customize these styles to fit your website's theme:

```css
#cookie-banner {
    width: 100%;
    text-align: center;
    color: white;
}

#accept-cookies {
    border: none;
    text-align: center;
    text-decoration: none;
    cursor: pointer;
}

#cookie-banner a {
    color: wheat;
}
```

Feel free to adjust the width, colors, and other properties according to your preferences.

### Usage:

1. **Text Customization:**
   - Change the text inside the `<p>` tag to communicate your cookie usage policy effectively.

2. **Privacy Policy Link:**
   - Update the `href` attribute of the `<a>` tag to link to your privacy policy page.

3. **Button Text:**
   - If you prefer a different text for the acceptance button, modify the text inside the `<button>` tag.

### Important Note:

Make sure to comply with privacy regulations and guidelines when using cookies on your website. Provide accurate and comprehensive information about your cookie usage in the privacy policy.

**Disclaimer:**
This widget is a basic example, and additional functionality may be required based on your specific website requirements and local privacy laws.

Feel free to reach out for further customization or support.
