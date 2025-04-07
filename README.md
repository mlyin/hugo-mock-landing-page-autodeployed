# StudySync - Student Collaboration Platform
A modern landing page for StudySync, a student collaboration platform built with Hugo, created for CIS3500: Software Engineering HW2.

## Overview
StudySync is a comprehensive platform designed to enhance student learning through collaboration. This project demonstrates the landing page for StudySync, featuring:
- Clean, responsive design using Bootstrap
- Automated deployment workflow via GitHub Actions
- Contact form integration for user inquiries
- GitHub integration for issue tracking and collaboration
- Modern UI showcasing key platform features

## Key Features
- Study group creation and management
- Virtual study sessions with calendar integration
- Real-time collaborative note-taking
- AI-powered study recommendations
- Course material sharing and organization
- Progress tracking and analytics
- Smart scheduling and planning tools

## Setup and Development

### Prerequisites
- Hugo (latest version)
- Git
- GitHub account

### Local Development
1. Clone the repository:
```bash
git clone https://github.com/mlyin/hugo-mock-landing-page-autodeployed.git
cd hugo-mock-landing-page-autodeployed
```

2. Start the Hugo development server:
```bash
hugo server -D
```

3. Visit `http://localhost:1313` to view your site locally.

### Project Structure
- `content/` - Contains all content files (markdown)
- `layouts/` - Custom layout templates
- `static/` - Static assets (images, CSS, JS)
- `config.toml` - Hugo configuration file
- `themes/` - Hugo theme files
- `assets/` - Additional assets for the site

## Deployment
This project uses GitHub Actions for automated deployment. The workflow:
1. Builds the Hugo site
2. Deploys to GitHub Pages
3. Automatically updates when changes are pushed to the main branch

For detailed information about the deployment workflow, see the `github-actions-workflow-explanation.pdf` file in the repository.

## Getting Help
If you need assistance with this project:
1. Check the [Hugo documentation](https://gohugo.io/documentation/)
2. Open an issue on the [GitHub repository](https://github.com/mlyin/hugo-mock-landing-page-autodeployed/issues)
3. Contact the maintainer through the contact form on the site

## User Stories
For detailed information about planned features and user stories, see the `USER-STORIES.md` file in the repository.

## License
This project is part of a course assignment and is not intended for commercial use.
