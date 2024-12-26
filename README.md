# Email Signature

![Email Signature Example](https://raw.githubusercontent.com/ejcontrerast/emailSignature/main/public/emailSignature.png)


This project provides a customizable HTML email signature template. The signature includes a profile image, contact information, and social media links.

## Features

- Profile image with a circular border
- Contact information including phone number, email, and website
- Social media links (LinkedIn)
- Responsive design

## Usage

To use this email signature, follow these steps:

1. Clone the repository to your local machine.
2. Open the `signature.html` file in a text editor.
3. Customize the content as needed (see below for details).
4. Copy the HTML code and paste it into your email client's signature settings.

## Customization

You can personalize the email signature by editing the `signature.html` file. Here are the sections you can customize:

### Profile Image

Replace the `src` attribute of the `<img>` tag with the URL of your profile image.

```html
<img src="https://your-image-url.com" alt="Your Name" width="130" height="130" style="border-radius: 50%; margin-right: 20px;">

### Name and Professional Profile
Edit the text inside the <p> tags with id="name" and id="professionalProfile" to reflect your name and professional title.

    <p id="name" class="content" style="font-size: 20px; font-weight: bold; color: #00470a; margin-top: 0; margin-bottom: 0; position: relative;">
    YOUR NAME
</p>
<p id="professionalProfile" class="content" style="z-index: 1;font-size: 14px;color: #00470a; margin-top: 2px; padding-top: 0;">
    YOUR PROFESSIONAL TITLE
</p>

### Contact Information
Update the href attributes and text content of the <a> tags with id="phone", id="email", id="website", and id="linkedin" to include your contact details.

<a id="phone" href="tel:+1234567890" style="text-decoration: none; color: #00470a; display: inline-flex; justify-content: center; align-items: center;">
    <img src="https://your-phone-icon-url.com" alt="Phone" width="18" height="18" style="padding-right: 5px;">
    +1 (234) 567-890
</a>

<a id="email" href="mailto:your-email@example.com" style="text-decoration: none; color: #00470a; display: inline-flex; justify-content: center; align-items: center;">
    <img src="https://your-email-icon-url.com" alt="Email" width="18" height="18" style="padding-right: 5px;">
    your-email@example.com
</a>

<a id="website" href="https://your-website.com" style="text-decoration: none; color: #00470a; display: inline-flex;justify-content: center; align-items: center;">
    <img src="https://your-website-icon-url.com" alt="Website" width="18" height="18" style="padding-right: 5px;">
    your-website.com
</a>

<a id="linkedin" href="https://linkedin.com/in/your-profile" style="text-decoration: none; color: #00470a; display: inline-flex; justify-content: center; align-items: center;">
    <img src="https://your-linkedin-icon-url.com" alt="LinkedIn" width="18" height="18" style="padding-right: 5px;">
    your-linkedin-profile
</a>




