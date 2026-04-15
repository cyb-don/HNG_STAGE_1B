Profile Card Component

A profile card built with HTML, CSS, and JavaScript. Responsive and accessible.

How to Run

1. Open index.html in a web browser. Double-click the file or right-click and select "Open with" your browser.

2. Or use a local server:
   - VS Code: Install Live Server extension, right-click index.html, select "Open with Live Server"

Files

- index.html: HTML structure with profile info, avatar, social links, hobbies, and dislikes
- profilecard.css: All styling for the card
- profilecard.js: Updates the time display every second

Features

- Responsive design that works on mobile, tablet, and desktop
- Keyboard navigation (tab through links, enter to activate)
- Screen reader support with aria-live regions
- All elements have data-testid attributes for testing
- Displays current epoch time in milliseconds
- Dark theme with good color contrast

Data-TestID Attributes

The following elements can be targeted by tests:
- test-profile-card: Main card container
- test-user-name: User name
- test-user-bio: Biography text
- test-user-time: Current time in milliseconds
- test-user-avatar: Profile image
- test-user-social-links: Social links container
- test-user-social-twitter: Twitter link
- test-user-social-github: GitHub link
- test-user-social-linkedin: LinkedIn link
- test-user-social-dribbble: Dribbble link
- test-user-hobbies: Hobbies list
- test-user-dislikes: Dislikes list

Customization

To edit the profile:
- Name: Change "Alex Rivera" in the h2 tag
- Bio: Edit the p tag with id="user-bio"
- Avatar: Replace the img src URL
- Social links: Update the href values and link text
- Hobbies/Dislikes: Edit the list items

To change colors or fonts:
- Open profilecard.css
- Update color values (currently using dark theme)
- Modify font-family if needed
- Adjust spacing and sizes as needed

No Dependencies

This project uses only HTML, CSS, and vanilla JavaScript. No frameworks or external libraries required.
