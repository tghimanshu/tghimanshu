# Future Plan

This document outlines the roadmap for the development of this GitHub Profile repository.

## Phase 1: Current Status (Complete)

- **Static Profile Content**: The repository currently contains a `README.md` file that displays:
    - Personal introduction and professional summary.
    - Social media links (LinkedIn, StackOverflow, Instagram).
    - List of skills and tools (Angular, AWS, Python, React, etc.).
    - Contact information.
- **Documentation**: Basic repository documentation has been added.

## Phase 2: Future Enhancements

The following features are planned for the next phase to make the profile more dynamic and engaging:

### 1. Dynamic GitHub Stats
- **Implementation**: Use [GitHub Readme Stats](https://github.com/anuraghazra/github-readme-stats) to display real-time statistics.
- **Features**:
    - Total stars earned.
    - Total commits (current year).
    - Total PRs and Issues.
    - Top languages used across repositories.

### 2. Automated Content Feeds
- **Blog Posts**: Integrate a GitHub Action to automatically fetch and display the latest blog posts from Medium or dev.to using [blog-post-workflow](https://github.com/gautamkrishnar/blog-post-workflow).
- **YouTube Videos**: If applicable, automatically list the latest YouTube videos.

### 3. Activity Tracking
- **WakaTime Integration**: Display coding activity graphs using WakaTime and a corresponding GitHub Action.
- **Profile Views Counter**: Add a visitor counter using [HITS](https://hits.seeyoufarm.com/) or similar services.

### 4. Interactive Elements
- **Badges**: Standardize the style of badges (e.g., using shields.io).
- **Streak Stats**: Display current coding streak.

### 5. CI/CD for Profile Updates
- **Validation**: Add a GitHub Action to lint the Markdown file on pull requests.
- **Self-Update**: Workflows to update the dynamic sections on a schedule (e.g., every night).
