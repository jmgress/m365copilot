# M365 Copilot Presentation

A presentation about using Microsoft 365 Copilot to supercharge workplace productivity, created with [Marp](https://marp.app/) and automatically deployed to [GitHub Pages](https://jmgress.github.io/m365copilot/).

## About This Presentation

This slide deck showcases how M365 Copilot and AI can transform the way we work. The presentation itself was created using GitHub Copilot, demonstrating the practical capabilities of AI-assisted development.

**Topics covered:**

- M365 Copilot fundamentals and capabilities
- AI adoption strategies and change management
- Practical applications across the workplace
- Best practices for AI integration

## Features

- **Automated Deployment**: GitHub Actions workflow automatically builds and publishes to GitHub Pages
- **Custom Themes**: Three custom Marp themes (default, gaia, uncover) with branding
- **Responsive Design**: Slides are optimized for presentation and web viewing
- **Custom Favicon**: Branded favicon for the deployed site
- **Speaker Notes**: HTML comments include additional context for presenters

## Viewing the Presentation

- **Live Site**: [https://jmgress.github.io/m365copilot/](https://jmgress.github.io/m365copilot/)
- **Source**: `slides/Slides.md`

## Local Development

1. **Open in VS Code**:

   ```bash
   code .
   ```

2. **Install Marp Extension**:
   - Install [Marp for VS Code](https://marketplace.visualstudio.com/items?itemName=marp-team.marp-vscode)

3. **Preview Slides**:
   - Open `slides/Slides.md`
   - Click the Marp preview icon or use `Ctrl+Shift+V` (Windows/Linux) or `Cmd+Shift+V` (Mac)

4. **Export Options**:
   - PDF, PowerPoint, or HTML from the Marp extension

## Project Structure

```text
m365copilot/
├── .github/
│   ├── copilot-instructions.md    # GitHub Copilot workspace instructions
│   └── workflows/
│       └── marp-pages.yml          # GitHub Actions deployment workflow
├── .vscode/
│   └── settings.json               # Copilot commit message settings
├── slides/
│   ├── Slides.md                   # Main presentation content
│   ├── bespoke-template.html       # Custom HTML template with favicon
│   ├── img/                        # Images and assets
│   └── themes/                     # Custom Marp themes
│       ├── custom-default.css
│       ├── custom-gaia.css
│       └── custom-uncover.css
├── favicon.png                     # Site favicon
└── README.md
```

## GitHub Pages Deployment

The site automatically deploys when changes are pushed to the `main` branch:

1. GitHub Actions builds the Marp slides to HTML
2. Copies themes, images, and favicon to the build directory
3. Injects favicon link into the HTML
4. Deploys to GitHub Pages

**Manual Deployment**: Go to Actions tab → "Deploy marp site to Pages" → "Run workflow"

## Customization

### Updating Content

Edit `slides/Slides.md` with your presentation content. Use Marp-flavored Markdown with frontmatter:

```markdown
---
marp: true
theme: custom-default
paginate: true
footer: 'Your Name | Your Title'
---
```

### Changing Themes

Modify the theme in the frontmatter or edit the CSS files in `slides/themes/`.

### Updating Favicon

Replace `favicon.png` with your own 32x32 PNG image.

## Technologies

- **Marp**: Markdown presentation ecosystem
- **GitHub Pages**: Free static site hosting
- **GitHub Actions**: Automated build and deployment
- **GitHub Copilot**: AI-assisted content creation

## Author

**James Gress**  
AI Director @ Accenture  

- LinkedIn: [jamesgress](https://linkedin.com/in/jamesgress/)
- GitHub: [jmgress](https://github.com/jmgress)
- X.com: [@jmgress](https://x.com/jmgress)
- Meetup: [Tampa Bay Generative AI Meetup](https://www.meetup.com/tampa-bay-generative-ai-meetup/)

## License

This repository is licensed under the [MIT License](LICENSE).

## Resources

- [Marp Official Documentation](https://marpit.marp.app/markdown)
- [Marp for VS Code](https://marketplace.visualstudio.com/items?itemName=marp-team.marp-vscode)
- [GitHub Pages Documentation](https://docs.github.com/en/pages)
- [CommonMark Markdown Syntax](https://commonmark.org/help/)
