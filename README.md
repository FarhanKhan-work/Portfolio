# Farhan Khan Portfolio

Live site: https://farhankhan-work.github.io/portfolio/
Repo: https://github.com/FarhanKhan-work/portfolio

## Pages
- index.html: Home page with intro and cards
- about.html: About me, photo and intro video (with controls and poster)
- projects.html: 5 projects, each in an article tag
- contact.html: Contact form with HTML5 validation, sent through Formspree
- thanks.html: Thank you page

## Responsive design
No flexbox is used. Layout uses inline-block, floats and percentage widths.
The main container is 90% wide with a max of 1100px so it stays fluid.

Each screen size has its own CSS file, loaded with a media query on the link tag:

| File | Screen size | Why |
|---|---|---|
| phone.css | up to 599px | Phones. Everything stacks in one column, buttons go full width |
| tablet.css | 600px to 1023px | Tablets like iPad (768px). Two cards per row, logo left and menu right |
| desktop.css | 1024px and up | Laptops and desktops. Three cards per row, bigger text |

style.css holds the shared styles for every size.

## Gradients
- Angled linear gradient: `linear-gradient(135deg, #3B2418, #8E3417)` on the intro section of the Home page (index.html)
- Plain linear gradient: `linear-gradient(#8E3417, #3B2418)` on the banner of the About, Projects, Contact and Thanks pages

## Colour scheme (fall theme)
Made with Adobe Color.

| Colour | Hex | Used for |
|---|---|---|
| Bark brown | #3B2418 | Header, footer, text |
| Maple red | #8E3417 | Headings, gradients |
| Burnt orange | #A3470F | Buttons, links |
| Mustard gold | #E0A93B | Active menu, borders |
| Cream | #FBF4E8 | Background |

## Form validation
- Name: required, at least 2 characters
- Email: type="email", required
- Phone: type="tel" with pattern for 10 digits
- Comments: required, at least 10 characters
- Robot check: pattern only accepts Fall or Autumn

## Testing
| Test | Tool | Result |
|---|---|---|
| HTML | validator.w3.org | ADD |
| CSS | jigsaw.w3.org/css-validator | ADD |
| Accessibility | wave.webaim.org | ADD |
| Links | validator.w3.org/checklink | Checked |
| Spelling | VS Code Code Spell Checker | Checked |

## Credits
- Formspree (formspree.io) handles sending the contact form to my email
- I used Claude (AI) to help explain concepts and guide me through parts of the code