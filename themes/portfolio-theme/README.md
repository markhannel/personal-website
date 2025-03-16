# Portfolio Theme for Hugo

A clean and modern portfolio theme for Hugo, perfect for personal websites and project showcases.

## Features

- Responsive design
- Clean and modern UI
- Project showcase
- Social media links
- Tag support
- Customizable hero section
- Mobile-friendly navigation

## Installation

### Option 1: Clone the Repository

```bash
cd your-hugo-site
git clone https://github.com/yourusername/portfolio-theme themes/portfolio-theme
```

### Option 2: Add as a Submodule

```bash
cd your-hugo-site
git submodule add https://github.com/yourusername/portfolio-theme themes/portfolio-theme
```

## Configuration

1. Copy the example configuration file to your site's root directory:

```bash
cp themes/portfolio-theme/exampleSite/config.toml .
```

2. Update the configuration file with your information:

```toml
baseURL = "https://yoursite.com"
languageCode = "en-us"
title = "Your Name"
theme = "portfolio-theme"

[params]
  description = "Your site description"
  
  [params.hero]
    title = "Hi, I'm Your Name"
    subtitle = "Your tagline here"
  
  [params.social]
    github = "yourusername"
    linkedin = "yourusername"
    twitter = "yourusername"
```

## Content Structure

```
content/
├── _index.md
├── about.md
├── contact.md
└── projects/
    ├── _index.md
    ├── project1.md
    └── project2.md
```

### Creating a Project

Create a new project with:

```bash
hugo new projects/my-project.md
```

Example project front matter:

```yaml
---
title: "My Project"
date: 2024-03-12
tags: ["web", "javascript", "react"]
projectUrl: "https://github.com/yourusername/project"
---

Project description goes here...
```

## Customization

### Colors

The theme uses CSS variables for colors. You can override them in your site's custom CSS:

```css
:root {
    --primary-color: #2563eb;
    --text-color: #1f2937;
    --bg-color: #ffffff;
    --nav-bg: #f8fafc;
    --border-color: #e5e7eb;
}
```

## Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

## License

This theme is released under the MIT license. See [LICENSE](LICENSE) for more information. 