# Digital Business Card (Virtual Card)

A modern, responsive, and interactive digital business card built with HTML and CSS. It features a sleek glass-morphism design and allows users to easily view contact information, connect via direct links, and download a `.vcf` file directly to their device's address book.

## Features

- **Glass-Morphism UI**: A beautiful, modern aesthetic with frosted glass effects, subtle shadows, and smooth gradients.
- **Responsive Design**: Looks great on both mobile devices and desktop screens.
- **One-Click Contact Save**: Includes a direct download link to a `.vcf` (vCard) file, allowing users to instantly save your contact details to their phone (iOS and Android compatible).
- **Quick Links**: Direct links to call, email, or start a WhatsApp chat.
- **Cross-Platform Compatibility**: Uses iOS-specific webkit tags (`-webkit-backdrop-filter`) to ensure the background blur effect works perfectly on Safari and Apple devices.

## Project Structure

- `index.html`: The main structure of the digital business card.
- `style.css`: The styling file containing the layout, glass-morphism effects, and hover animations.
- `contact.vcf`: The vCard file that contains the saveable contact information (name, phone number, email, etc.).
- Image files (e.g., `me.jpg`, `123.png`): Used for the profile picture and the background wallpaper.

## How to Customize

1. **Update Profile Information**:
   - Open `index.html` and replace the name, title, phone number, email, and WhatsApp link with your own details.
   - Update the `<img src="me.jpg">` tag to point to your preferred profile picture.
   - Update the background image in `style.css` under the `.background` class (currently set to `123.png`).

2. **Update the vCard (`contact.vcf`)**:
   - Open `contact.vcf` in any text editor.
   - Modify the `FN` (Full Name), `N` (Name structure), `TEL` (Phone Number), `EMAIL`, and other fields to match your actual contact info. This ensures the correct data is saved when someone clicks the "Save Contact" button.

3. **Deploying**:
   - You can host this folder on any static web hosting service, such as GitHub Pages, Netlify, Vercel, or a traditional cPanel web server. Because it only uses standard HTML/CSS, no build step or backend server is required.

## Technologies Used

- HTML5
- CSS3 (Flexbox, CSS Animations, Backdrop Filters)

## Author
**Kamba Timothy Handy**  
*Graphics Designer, Embedded Systems Developer, Web Developer, Systems Developer*
