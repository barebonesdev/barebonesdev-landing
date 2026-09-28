# BareBones Dev — Landing Site

A simple, modern static landing site for **BareBones Dev**, showcasing our apps:

- **Power Planner** — homework planner for students ([powerplanner.net](https://powerplanner.net/))
- **Auto Assistant** — car maintenance tracker ([Microsoft Store](https://apps.microsoft.com/detail/9wzdncrdf53v))
- **WA Driver License Appointment Finder** — has its own dedicated landing page and privacy policy under `apps/wa-driver-license-appointment-finder/` ([Microsoft Store](https://apps.microsoft.com/detail/9NKWLWTKP0L4))
- **Roam Apps** — outdoor adventure app suite ([roamapps.com](https://roamapps.com/))

## Structure

```
index.html                                        Home page
apps/wa-driver-license-appointment-finder/
  index.html                                       App landing page
  privacy.html                                      Privacy policy
assets/
  css/styles.css                                    Shared styles
  js/main.js                                         Mobile nav toggle
  img/favicon.svg                                    Favicon / logo mark
.nojekyll                                            Disables Jekyll processing on GitHub Pages
```

No build step, framework, or dependencies are required — it's plain HTML/CSS/JS.

## Deploying to GitHub Pages

1. Push this repository to GitHub.
2. In the repo, go to **Settings → Pages**.
3. Under **Build and deployment**, set **Source** to `Deploy from a branch`.
4. Choose the `main` branch and the `/ (root)` folder, then save.
5. GitHub will publish the site at `https://<username>.github.io/<repo>/`.

Since the site uses relative links throughout, it works whether it's hosted at the root of a domain or under a repo subpath.

## Updating content

- To add a new app card, copy an `.app-card` block in `index.html` and update the icon, copy, and link.

