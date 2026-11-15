# Solmara Club website

Link-in-bio site for Solmara Club. Move. Explore. Create.

- `index.html` is the whole site (HTML, CSS and JS in one file).
- `img/` holds the logo, club photos, sock mockups and event posters.
- Tabs: home, `#past-events`, `#join-us` (email sign-up).

## Email sign-ups
The form on `#join-us` adds each sign-up to Brevo (form "Solmara website" -> list "Website sign-ups").
See and export contacts at app.brevo.com -> Contacts -> Lists. The thank-you email is Brevo's "simple confirmation" on that form.
Keep reCAPTCHA off on the Brevo form; the site uses a hidden honeypot field against bots.

## Edit in VS Code
Open this folder, install the **Live Server** extension, right-click `index.html` → "Open with Live Server".
