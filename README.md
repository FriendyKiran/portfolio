# Kiran Babu Athina — Portfolio

Personal portfolio of **Kiran Babu Athina**, Machine Learning & AI Engineer (M.S. Data Science, Texas A&M).
Agentic RAG, LLM fine-tuning, multimodal models, and production ML pipelines.

**Live site:** https://portfolio-kiran-13d2.vercel.app

## Sections

- **Hero**: name, role, and typing animation
- **About**: short bio and headline numbers
- **Experience**: vertical timeline that fills in as you scroll, with company logos
- **Skills**: grouped by category with tab filters
- **Projects**: impact numbers, animated previews on hover, and a filter bar (ML / Web / Data / Research)
- **Publications**: from Google Scholar, with citation count
- **Education**: degrees and certifications
- **Contact**: inline contact form plus email, LinkedIn, GitHub, and Scholar links

## Built with

Plain **HTML, CSS, and JavaScript** in a single `index.html` file. There are no frameworks and no build step.

- Font: [Space Grotesk](https://fonts.google.com/specimen/Space+Grotesk) (Google Fonts)
- Icons: [Font Awesome](https://fontawesome.com) (CDN)
- Light and dark themes that follow the system setting, with a manual toggle
- Responsive layout for desktop, tablet, and mobile, and it respects `prefers-reduced-motion`

## Files

```
index.html         the whole site: markup, <style>, and <script>
formal image.jpg   profile photo used in the hero
```

## Run locally

Open `index.html` in a browser, or serve the folder:

```bash
python -m http.server 8000
# then visit http://localhost:8000
```

## Editing

Every section in `index.html` is marked with a `SECTION:` comment.

| To change | Edit |
|---|---|
| Colors, fonts, spacing | CSS variables in the `:root` block (dark theme) and the two light-theme blocks below it |
| Hero typing phrases | `TYPING_PHRASES` in the `<script>` |
| Project filters | `data-tags` on each project card (`ml`, `web`, `data`, `research`) |
| Contact form delivery | Set `FORM_ENDPOINT` to a [Formspree](https://formspree.io) URL. While it's empty, the form opens the visitor's email app. |

## Deployment

Hosted on **Vercel**, connected to this repository. Every push to `main` redeploys the site automatically.

## Contact

- Email: [kiranathina8@gmail.com](mailto:kiranathina8@gmail.com)
- LinkedIn: [linkedin.com/in/athinakiranbabu](https://www.linkedin.com/in/athinakiranbabu)
- GitHub: [github.com/FriendyKiran](https://github.com/FriendyKiran)
- Google Scholar: [Kiran Babu Athina](https://scholar.google.com/citations?user=wWen3jgAAAAJ&hl=en)
