# Testing

Return back to the [README.md](README.md) file.

## Code Validation

[The W3C Markup Validation Service](https://validator.w3.org/) and [The W3C CSS Validation Service](https://jigsaw.w3.org/css-validator/) were used to validate every page of the project to ensure there were no syntax errors. The results clearly showed that the website stays in compliance with the standards and recommendations set by the World Wide Web Consortium.

### HTML Validation

I have used the recommended [HTML W3C Validator](https://validator.w3.org) to validate all of my HTML files. No errors or warnings were found.

| Page | W3C URL | Screenshot | Notes |
| --- | --- | --- | --- |
| Home | [W3C](https://validator.w3.org/nu/?doc=https%3A%2F%2FNataliaCzeladka.github.io%2Fcelestial-buddies%2Findex.html) | ![index.html validation](docs/index.html_validation.png) | Pass: No Errors |
| Events | [W3C](https://validator.w3.org/nu/?doc=https%3A%2F%2FNataliaCzeladka.github.io%2Fcelestial-buddies%2Fevents.html) | ![events.html validation](docs/events.html_validation.png) | Pass: No Errors |
| Resources | [W3C](https://validator.w3.org/nu/?doc=https%3A%2F%2FNataliaCzeladka.github.io%2Fcelestial-buddies%2Fresources.html) | ![resources.html validation](docs/resources.html_validation.png) | Pass: No Errors |
| Form | [W3C](https://validator.w3.org/nu/?doc=https%3A%2F%2FNataliaCzeladka.github.io%2Fcelestial-buddies%2Fform.html) | ![form.html validation](docs/form.html_validation.png) | Pass: No Errors |

### CSS Validation

I have used the recommended [CSS Jigsaw Validator](https://jigsaw.w3.org/css-validator) to validate my CSS file. No errors were found.

| File | Jigsaw URL | Screenshot | Notes |
| --- | --- | --- | --- |
| style.css | [Jigsaw](https://jigsaw.w3.org/css-validator) | ![style.css validation](docs/style.css_validation.png) | Pass: No Errors |

## Browser Compatibility

I have tested my deployed project on multiple browsers to check for compatibility issues.
| Browser | Screenshot | Notes |
| --- | --- | --- |
| Chrome | ![screenshot](docs/chrome.png) | Works as expected |
| Firefox | ![screenshot](docs/firefox.png) | Works as expected |
| Edge | ![screenshot](docs/edge.png) | Works as expected |
| Opera | ![screenshot](docs/opera.png) | Works as expected |

## Responsiveness

I have tested my deployed project on multiple devices to check for responsiveness issues. It responds well to different screen sizes ensuring that users can access and navigate the content effortlessly, regardless of their chosen device. No design or functionality issues found.

| Device | Screenshot | Notes |
| --- | --- | --- |
| Mobile (DevTools) | ![screenshot](docs/mobile.png) | Works as expected |
| Tablet (DevTools) | ![screenshot](docs/tablet.png) | Works as expected |
| Desktop | ![screenshot](docs/chrome.png) | Works as expected |

## Lighthouse Audit

I have tested my deployed project using the Lighthouse Audit tool to check for any major issues. Inital scores were quite low, because the website contained images in jpeg format. The reccommended format is webp, so I have converted all of my jpeg image files to webp files. It has greatly improved the performance.

| Page | Size | Screenshot | Notes |
| --- | --- | --- | --- |
| Home | Mobile | ![screenshot](docs/lighthouse_home_mobile.png) | Few warnings |
| Home | Desktop | ![screenshot](docs/lighthouse_home_desktop.png) | Some minor warnings |
| Events | Mobile | ![screenshot](docs/lighthouse_events_mobile.png) | Few warnings |
| Events | Desktop | ![screenshot](docs/lighthouse_events_desktop.png) | Some minor warnings |
| Resources | Mobile | ![screenshot](docs/lighthouse_resources_mobile.png) | Few warnings |
| Resources | Desktop | ![screenshot](docs/lighthouse_resources_desktop.png) | Some minor warnings |
| Join Us | Mobile | ![screenshot](docs/lighthouse_form_mobile.png) | Few warnings |
| Join Us | Desktop | ![screenshot](docs/lighthouse_form_desktop.png) | Some minor warnings |

## User Stories Testing

## Fixed Bugs

- I have initially created my header by combining the background image and the text together in the Shutterstock's editor. Then I realised that having it merged into one image will cause a lot of issues with responsiveness in the later stages of the site development and I gave up on this idea.

![Header initial sketch](docs/shutterstock_editor.jpg)

- At some point I had two `<h1>` headings in the index.html file: one in the header and one in the introduction. The second one got changed to `<h2>`.

- I have initially written a lot of separate CSS declarations for various elements or classes changing background colour to black and font colour to white. Then I realised that it would be much easier and code efficient to replace it with one declaration for the entire body: `body {background-color: #000;
    color: #fff;}`

- I have assigned `class="active"` to an `<a>` instead of `<li>` in the navigation bar, what resulted in the active tab changing colour to `#15418c` only in the middle. It wasn't visible on the big screen sizes. I have noticed this bug quite late in the process, when I was trying to figure out how to make a navbar responsive on smaller devices, and I used Flexbox for this purpose.

## Unfixed Bugs

There are no remaining bugs that I am aware of.