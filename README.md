# Portfolio Hub

A showcase portfolio site for developers, engineers, and creative professionals. 

![Portfolio Hub preview](/.git/poetry.png?raw=true)

## Overview

This project is a minimalist, responsive portfolio website hosted on Cloudflare Workers Pages. It provides a clean, modern interface to showcase personal and professional work, projects, and skills.

## Key Features

- **Responsive Design**: Optimized for desktop, tablet, and mobile viewing
- **Fast Loading**: Powered by Cloudflare Workers Pages for sub-second load times
- **GitHub Integration**: Automatically syncs README content from linked GitHub repositories
- **Project Showcase**: Feature project cards with descriptions, technologies, and links
- **Dark Mode Support**: Automatic theme detection based on system preferences
- **SEO Optimized**: Structured data markup for better search engine visibility

## Live Demo

[Live Site](https://portfolio-hub.shepdogg6t7.workers.dev)

## Quick Start

### Prerequisites

- Cloudflare Workers Pages account
- GitHub repository with a `README.md` file (optional, for auto-sync)

### Running Locally

```bash
# Clone the repository
cd portfolio-hub

# Install dependencies (if any)
# npm install  # or your preferred package manager

# Preview locally
wrangler pages dev public
```

### Deployment

This site is automatically deployed via GitHub Actions to Cloudflare Workers Pages. Changes to the `README.md` file will automatically trigger a new deployment.

## Project Structure

```
portfolio-hub/
├── public/
│   ├── index.html
│   └── wrangler.jsonc
├── .gitignore
├── wrangler.jsonc
```

- `public/`: Static site assets
- `wrangler.jsonc`: Cloudflare Workers Pages configuration
- `.gitignore`: Gitignore file to exclude sensitive files

## Technologies Used

- **Frontend**: HTML5, CSS (Tailwind CSS), JavaScript
- **Hosting**: Cloudflare Workers Pages
- **CI/CD**: GitHub Actions (automatic deployment on commits)

## Contributing

Contributions are welcome! Please follow the existing code style and contribute via pull requests.

## License

This project is licensed under the MIT License - see the LICENSE file for details.

## Contact

For questions or collaboration opportunities, reach out via GitHub or email.

---
*This portfolio site is part of the portfolio-hub organization.*
