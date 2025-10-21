# Password Generator

A simple, fast, and secure one-page password generator built with HTML, CSS, and JavaScript. Generate strong passwords with customizable options.

## Features

- **Adjustable Password Length**: Generate passwords between 6 and 20 characters
- **Multiple Character Types**:
  - Uppercase letters (A-Z)
  - Lowercase letters (a-z)
  - Numbers (0-9)
  - Special characters (!@#$%^&*...)
- **Copy to Clipboard**: One-click copy functionality with visual feedback
- **Responsive Design**: Works on desktop, tablet, and mobile devices
- **Real-time Updates**: Length slider updates the display instantly
- **Input Validation**: Ensures at least one character type is selected

## How to Use

1. Open `index.html` in your web browser
2. Select your preferred options:
   - Adjust the password length using the slider (6-20 characters)
   - Check/uncheck character types you want to include
3. Click "Generate Password" or press Enter to generate a new password
4. Click the "Copy" button to copy the password to your clipboard
5. Generated password will be confirmed with a "Copied to clipboard!" message

## Customization

You can modify the special characters used by editing the `charSets.special` string in the JavaScript section. Currently includes: `!@#$%^&*()_+-=[]{}|;:,.<>?`

## Browser Compatibility

- Chrome/Edge (latest)
- Firefox (latest)
- Safari (latest)
- Mobile browsers

## Security Notes

- Passwords are generated locally in your browser
- Nothing is sent to any server
- Your passwords are never stored or logged
- Generate a new password for each account

## No Dependencies

This is a standalone HTML file with no external dependencies or frameworks required.
