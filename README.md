# Outbreak Response Leadership

**Leading in times of uncertainty**

This is a Quarto book project designed to help public health professionals, emergency responders, and team leaders develop effective leadership skills for outbreak response and crisis situations.

## Overview

This resource explores the challenges of leading during outbreaks and emergencies, when information is incomplete, situations change rapidly, and stakes are high. Through interactive sessions, reflective exercises, and practical examples, participants develop their own leadership approach while learning from diverse perspectives.

## Sessions

### Session 1: What Does Leadership Mean to Us?
The foundation session explores different perspectives on leadership and helps participants develop their personal leadership philosophy. Key insight: leadership means something different to each of us, and that diversity is a strength.

### Session 2: Adaptive Challenges vs. Technical Problems
Based on Ronald Heifetz's leadership framework, this session explores the critical distinction between technical problems (which can be solved with existing expertise) and adaptive challenges (which require people to learn and change). Includes real-world outbreak examples like Ebola burial practices, vaccine confidence, and multi-jurisdictional contact tracing.

### Session 3: Inclusion, Belonging, and Psychological Safety
Drawing on Amy Edmondson's research on fearless organizations, this session explores the three-level framework: diversity is a fact, inclusion is a behavior, and belonging is the emotional outcome. Emphasizes psychological safety as essential for outbreak response teams. Includes specific leader behaviors to build psychological safety, case studies comparing high and low psychological safety teams, and practical strategies for creating inclusive environments where everyone can contribute their best work.

### Session 4: Person-Centered Leading
Introduces the theory that persons act with unique traits, and understanding these traits improves leadership. Part 1 covers Influence Style Indicators (Discovery Learning International)—a framework identifying four primary influence styles: rationalizing (data/logic), asserting (decisiveness), negotiating (common ground), and inspiring (vision/values). Includes detailed descriptions of each style, practical applications for outbreak response, case studies of style clashes and resolutions, and guidance on building influence flexibility and complementary teams. Additional parts on person-centered leading will follow.

### Future Sessions
Additional sessions will be added to cover:
- Leading with incomplete information
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
│       └── publish.yml                    # GitHub Actions deployment workflow
├── _quarto.yml                            # Project configuration
├── index.qmd                              # Welcome/introduction page
├── session-01-leadership-meaning.qmd      # Session 1: What does leadership mean
├── session-02-adaptive-challenges.qmd     # Session 2: Adaptive vs technical
├── session-03-inclusion-belonging.qmd     # Session 3: Inclusion and psychological safety
├── session-04-person-centered-leading.qmd # Session 4: Person-centered leading
├── styles.css                             # Custom styling
├── images/                                # Image assets
│   └── README.md                          # Image requirements
└── README.md                              # This file
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
