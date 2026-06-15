# Timothy Serewicz Website

Clean static website for Timothy Serewicz's CTO, technology executive, fractional CTO, advisory, AI governance, and technology due diligence positioning.

## Structure

- `index.html` - home page
- `speaking.html` - speaking and industry engagements
- `contact.html` - contact and inquiry links
- `styles.css` - shared site styling

## Local Preview

Open `index.html` directly in a browser, or run a simple local server:

```bash
python3 -m http.server 8080
```

Then visit:

```text
http://localhost:8080
```

## Maintenance

This site intentionally uses plain HTML and CSS only.

To update content:

1. Edit the relevant `.html` file.
2. Keep navigation links consistent across pages.
3. Use concise executive copy.
4. Avoid confidential client names or private company details.
5. Keep placeholder links updated as real URLs become available.

Configured contact and asset links:

- Email: `mailto:Tim@Serewicz.com`
- Schedule a Conversation: `https://calendar.app.google/2KmjiyNZjh3FSQUy7`
- GitHub: `https://github.com/serewicz`
- LinkedIn: `https://www.linkedin.com/in/serewicz/`

## Updating Assets

Headshot:
Replace `images/headshot.jpg` with a new file using the same filename.

Contact Links:
Update schedule, GitHub, LinkedIn, and email links directly in the HTML files.

## Deployment

The site can be deployed on GitHub Pages, Netlify, Vercel, Cloudflare Pages, or any static web host.

For GitHub Pages:

1. Push the repository to GitHub.
2. Open repository settings.
3. Go to Pages.
4. Select the `main` branch and root directory.
5. Save the configuration.

No build step is required.

## Design Principles

- Executive tone
- Fast loading
- Mobile responsive
- Accessible navigation
- No frameworks
- No JavaScript unless needed
- No stock-photo-heavy design
