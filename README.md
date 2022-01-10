# Vigorate - FrontEnd Developer - Coding Challenge by Simran Jain

There are 2 html files:

1. index.html - Main source code for development purpose.
2. index-inline-css.html - HTML file with inlline css, ready to be sent as an email.

Github Repo: https://github.com/jainsimran/Email-template

### Responsive Layout

The template is responsive with 2 layouts:

1. Large on viewport 481px and above.
2. Small for viewport 480px and below.
   Lowest supported viewport is of 320px.

### Accessibility

I followed WCAG's AA guideline for accessibility:

- Used attributes such as **role** and **alt** when needed.
- Tested accessibility test using tool like Litmus and Accessibility Insights for Web - FastPass (browser plugin).

### Design Assets

I extracted the icons and images from the design using Adobe Photoshop and used CDN - https://sirv.com/ to host them.
I then imported them into the email template.

## Testing

This email template was tested on:

1. Gmail Web app on iOS
2. Gmail Mobile app on iOS
3. Microsoft Outlook on iOS
4. Litmust testkit that tested it across multiple email clients on various platforms and devices. Below are some of the screenshots from the test: 
- ![Apple mail](https://ompenify.sirv.com/Email%20testing/appmail.png)

### Areas to improve

1. Colors used in the design spec are not accessible. In real world scenerio, I will work with the design team to fix that. (tested on https://webaim.org/resources/contrastchecker/).
2. Fonts used in design spec are not web-safe. So, I used different set of web-safe fonts.
3. Depending on the audience, maybe this email needs internationalization.
4. Links are currently fake for the sake of this test. Ideally, they would lead to some webpage or actions.
5. Some of the older web clients and browsers have limited support for the template. This may need to be addressed depending on the targetted audience and/or company policies.
