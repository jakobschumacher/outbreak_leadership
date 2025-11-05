# Outbreak Response Leadership

**Leading in times of uncertainty**

This is a Quarto book project designed to help public health professionals, emergency responders, and team leaders develop effective leadership skills for outbreak response and crisis situations.

## Overview

This resource explores the challenges of leading during outbreaks and emergencies, when information is incomplete, situations change rapidly, and stakes are high. Through interactive sessions, reflective exercises, and practical examples, participants develop their own leadership approach while learning from diverse perspectives.

## Sessions

### Session 1: What Does Leadership Mean to Us?
The foundation session explores different perspectives on leadership and helps participants develop their personal leadership philosophy. Key insight: leadership means something different to each of us, and that diversity is a strength.

### Future Sessions
Additional sessions will be added to cover:
- Leading with incomplete information
- Building and maintaining team cohesion under stress
- Communication strategies during crises
- Decision-making in high-stakes situations
- Self-care and resilience for leaders

## Deployment

This project is configured to automatically deploy to GitHub Pages using GitHub Actions.

### Automatic Deployment

The book automatically builds and deploys when you push to the `main` branch. The workflow:

1. Checks out the repository
2. Sets up Quarto
3. Renders the book
4. Deploys to GitHub Pages

### Setting Up GitHub Pages

To enable deployment:

1. Go to your repository settings on GitHub
2. Navigate to **Settings > Pages**
3. Under "Build and deployment":
   - Set **Source** to "GitHub Actions"
4. Push changes to the `main` branch to trigger deployment

The site will be available at: `https://<username>.github.io/<repository-name>/`

### Local Development

This project uses [Quarto](https://quarto.org/), an open-source scientific and technical publishing system.

#### Prerequisites

- [Quarto](https://quarto.org/docs/get-started/) installed on your system

#### Building Locally

```bash
# Preview the book (with live reload)
quarto preview

# Render the book
quarto render
```

The rendered book will be in the `_book/` directory.

## Project Structure

```
outbreak_leadership/
├── .github/
│   └── workflows/
│       └── publish.yml              # GitHub Actions deployment workflow
├── _quarto.yml                      # Project configuration
├── index.qmd                        # Welcome/introduction page
├── session-01-leadership-meaning.qmd # First session
├── styles.css                       # Custom styling
├── images/                          # Image assets
│   └── README.md                    # Image requirements
└── README.md                        # This file
```

## Images

The project requires certain images to be added to the `images/` directory. See `images/README.md` for details on required images and where to obtain them.

## SEO Optimization

This project includes SEO-friendly features:
- Semantic HTML structure
- Descriptive metadata and keywords
- Open Graph tags for social sharing
- Mobile-responsive design
- Accessible content structure

## Contributing

This is a learning resource designed to evolve based on real-world experiences and feedback. Contributions, suggestions, and improvements are welcome.

## License

[Specify your license here]

## About

This resource is designed for those who lead in the challenging context of outbreak response, where uncertainty is constant and the need for effective leadership is critical.
