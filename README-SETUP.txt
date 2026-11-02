# Stealthline Productions — Trust & Information Pages

This package contains starter pages for the Investment Growth Calculator website:

- `about.html`
- `privacy.html`
- `disclaimer.html`
- `terms.html`
- `methodology.html`
- `contact.html`

## Before publishing

1. Review every page with a parent or guardian.
2. Confirm that Google Analytics is actually installed and inspect its events, data streams, data-sharing settings, and data-retention setting.
3. Confirm that no calculator input values or personally identifying information are sent to Google Analytics.
4. Replace the setup notice on `contact.html` with a dedicated, monitored project contact email. Do not publish private personal contact information.
5. Keep the advertising section accurate. It currently says ads are planned but not active. Update the privacy policy and implement any required consent/notice controls before adding advertising tags.
6. Check that the actual site behavior matches every statement in the privacy policy.
7. Add links to these pages in the footer of `index.html`.

## Upload to GitHub

1. Open the `stealthline-productions` repository.
2. Select **Add file → Upload files**.
3. Upload all six `.html` files into the same root folder as `index.html` and `logo.png`.
4. Commit the changes.
5. Add the footer navigation links shown below to `index.html`.
6. Visit each page on the live site and test every link.

## Footer navigation snippet

Add this inside your existing `<footer>` element:

```html
<nav class="footer-links">
  <a href="about.html">About</a>
  <a href="methodology.html">Methodology</a>
  <a href="disclaimer.html">Disclaimer</a>
  <a href="privacy.html">Privacy Policy</a>
  <a href="terms.html">Terms of Use</a>
  <a href="contact.html">Contact</a>
</nav>
```

Optional CSS:

```css
.footer-links {
  display: flex;
  flex-wrap: wrap;
  justify-content: center;
  gap: 16px;
  margin-bottom: 15px;
}
.footer-links a {
  color: #bbb;
  text-decoration: none;
}
.footer-links a:hover {
  color: #fff;
  text-decoration: underline;
}
```

These are practical starter documents, not legal advice or a certification of compliance. Privacy and advertising requirements depend on the actual technology, settings, audience, and jurisdictions involved.
