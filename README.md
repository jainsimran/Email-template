# Vigorate - FrontEnd Developer - Coding Challenge by Simran Jain

Email-template is a coding challenge developed by Simran Jain.
Please open the **index.html** file in any of the supported browsers to view the email template.

Github Repo: https://github.com/jainsimran/Email-template

### Responsive Layout

It follows a responsive layout using Media Queries where the width is 600px for desktop and break-point is 480px for mobile view.

### Accessibility

I followed WCAG's AA guideline for accessibility:

- Used attributes such as **role** and **alt** when needed.
- Tested accessibility test using tool like Litmus and Accessibility Insights for Web - FastPass (browser plugin).

**Note**

Following colour contrasts failed the WCAG AA test (tested on https://webaim.org/resources/contrastchecker/).

- Foreground Color - #ffffff Background Color - #4fc1e9
- Foreground Color - #ffffff Background Color - #ffce54
- Foreground Color - #ffffff Background Color - #8cc152

I used these colour contrast for this test. In a real-time situation, I will work with the design team to make sure the colours used in the email pass the WCAG AA test.

### Design Assets

I extracted the icons and images from the design using Adobe Photoshop and used CDN - https://sirv.com/ to import them into the code.

## Testing

This solution is tested on litmus -
