# Timothy Serewicz Website

Clean static website for Timothy Serewicz's CTO, technology executive, fractional CTO, advisory, AI governance, and technology due diligence positioning.

## Structure

- `index.html` - home page
- `work-with-me.html` - engagement areas and advisory services
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

## Build and Manual Deployment

No build step is required. The site is plain HTML, CSS, images, and static assets.

To deploy manually through cPanel:

1. Preview the site locally and confirm links, copy, images, and responsive layout.
2. In cPanel File Manager or FTP, open the website document root, commonly `public_html`.
3. Upload the updated `.html` files, `styles.css`, the `images/` directory, and the `assets/` directory.
4. Replace existing files when prompted.
5. Visit `https://serewicz.com` and key pages directly, including `/work-with-me.html`, to confirm the upload.

Do not add GitHub Actions or deployment automation unless the deployment model changes.

## Design Principles

- Executive tone
- Fast loading
- Mobile responsive
- Accessible navigation
- No frameworks
- No JavaScript unless needed
- No stock-photo-heavy design
