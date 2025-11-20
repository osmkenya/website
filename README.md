# Official website for OpenStreetMap Kenya
[![LICENSE](https://img.shields.io/badge/license-MIT-lightgrey.svg)](https://github.com/raviriley/agency-jekyll-theme/blob/master/LICENSE.txt)

Built with the [Agency Jekyll Theme](https://github.com/raviriley/agency-jekyll-theme) and optimized for GitHub Pages.

## About OSM Kenya

We are a local OpenStreetMap community, dedicated to building an open, collaborative map of Kenya. We bring together mappers, developers, GIS professionals, and community members who are passionate about open data and its potential to drive positive change across Kenya. Our mission is to create and maintain a comprehensive, freely available map of Kenya through community collaboration, while building local capacity in mapping and geospatial technologies.

## Contributing to this project

We welcome contributions from the OSM Kenya community! Whether you're fixing bugs, adding features, or suggesting new ideas, your help is appreciated.

### How to Contribute

1. **Fork the repository** and create your branch from `main`
2. **Make your changes** with clear, descriptive commit messages
3. **Test your changes** thoroughly
4. **Submit a pull request** with a clear description of your changes

### Contribution Guidelines

- Follow the existing code style and conventions
- Write clear, descriptive commit messages
- Update documentation as needed
- Test your changes before submitting
- Be respectful and constructive in all interactions

### Types of Contributions

- **Bug fixes**: Found a bug? Submit a fix!
- **Features**: Have an idea for a new feature? Discuss it in an issue first
- **Documentation**: Improve or translate documentation
- **Design**: Enhance the UI/UX
- **Content**: Add or improve content about OSM Kenya activities

## Customizing Content

### Project Structure

```
├── _data/              # Data files (YAML) for site content
│   ├── navigation.yml  # Navigation menu configuration
│   ├── sitetext.yml    # All site text content
│   └── style.yml       # Color and style customization
├── _includes/          
│   ├── custom_head.html
│   └── register.html
├── _layouts/
│   └── home.html
├── _portfolio/         # Project items (one file per item)
├── assets/
│   ├── css/
│   ├── img/
│   └── js/            # Images and graphics
├── _config.yml        # Jekyll configuration
├── index.md           # Homepage
├── legal.md           # Legal/privacy policy page
└── README.md          # This file
```

### Key Files

- **`_config.yml`** - Site-wide settings (title, description, URL, social media links)
- **`_data/sitetext.yml`** - All text content for the website (easy to edit!)
- **`_data/navigation.yml`** - Navigation menu items
- **`_data/style.yml`** - Colors, fonts, and styling
- **`_portfolio/`** - Add `.md` files here for each project/initiative you want to showcase
- **`assets/img/`** - OSM Kenya images
  
### Editing Site Text

All site content is managed through YAML files in the `_data/` directory, making it easy to update without touching HTML:

**`_data/sitetext.yml`** - Edit this file to change:
- Header tagline and description
- What we do content
- Project descriptions
- About/timeline section
- Contact information
- Footer content

**Example:**
```yaml
header:
  title: Welcome to OpenStreetMap Kenya!
  text: Mapping Kenya, Together
  button: Learn More
  buttonlink: "#services"
```

### Adding Community Project Items

Create a new markdown file in the `_portfolio/` directory:

**`_portfolio/01-nairobi-mapathon.md`**
```yaml
---
title: Nairobi Mapathon 2024
subtitle: Community Mapping Event
image: assets/img/portfolio/nairobi-mapathon.jpg
alt: Mappers at work in Nairobi

caption:
  title: Nairobi Mapathon
  subtitle: Community Event
  thumbnail: assets/img/portfolio/nairobi-mapathon-thumb.jpg
---
Use this area to describe your project. Lorem ipsum dolor sit amet, consectetur adipisicing elit. Est blanditiis dolorem culpa incidunt minus dignissimos deserunt repellat aperiam quasi sunt officia expedita beatae cupiditate, maiores repudiandae, nostrum, reiciendis facere nemo!
```

### Customizing Colors and Styles

Edit `_data/style.yml` to change:
- Primary brand colors
- Header background image
- Fonts and typography

## Support

If you have questions, suggestions, or need help:
- Open an issue in this repository
- Reach out through our community group
- Email us at [osmkenya@gmail.com]

---

**Made with ❤️ by the OSM Kenya Community**

*Mapping Kenya, Together*
