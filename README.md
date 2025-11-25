## LinkedEarth Quarto Website

This is the official LinkedEarth website built with [Quarto](https://quarto.org), an open source scientific and technical publishing system.

Originally forked from the [Masiello group](https://faculty.washington.edu/masiello/)'s repository and adapted for LinkedEarth.

## About LinkedEarth

LinkedEarth is a community-driven platform for paleoclimate data sharing, analysis, and collaboration.

## Site Structure

The website includes the following sections:
- **About**: Information about LinkedEarth and its mission
- **Data**: Data repositories and resources
- **Tools**: Software packages and analysis tools
- **Community**: Team members and how to get involved
- **Training**: Workshops, tutorials, and educational materials

## Development

### Adding Publications
Use `just newpub` for creation of new directory and input prompts for new record.

### Adding New People
Use `just newperson` for creation of new directory and input prompts for new record.

### Local Development
```bash
quarto preview
```

### Building the Site
```bash
quarto render
```

### Deployment

- GitHub Pages deployment via GitHub Actions
- Site URL: https://linkedearth.github.io/quarto_website/
- Repository: https://github.com/LinkedEarth/quarto_website

