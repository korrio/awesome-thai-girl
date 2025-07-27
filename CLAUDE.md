# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Project Overview

This is a curated list of Thai social media personalities organized by university affiliation. The repository serves as a static website displaying profiles with Instagram/Facebook links, organized into categories like Net Idols, various Thai universities (Chulalongkorn, Chiang Mai, etc.), and high school students.

## Technical Architecture

- **Static HTML Website**: Single-page application using plain HTML
- **Firebase Hosting**: Deployed using Firebase with configuration in `firebase.json`
- **Structure**:
  - `public/index.html` - Main website content (identical to `README.md`)
  - `README.md` - Repository documentation (HTML format)
  - `firebase.json` - Firebase hosting configuration with SPA routing

## Development Commands

This project has no build process, linting, or testing commands as it's a simple static HTML site.

### Deployment
```bash
firebase deploy
```

## Content Management

The website content is maintained in two identical HTML files:
- `public/index.html` - Served by Firebase hosting
- `README.md` - GitHub repository display

When updating content, both files must be kept in sync manually.

## Project Structure

```
/
├── README.md          # Repository documentation (HTML format)
├── firebase.json      # Firebase hosting configuration
└── public/
    └── index.html     # Main website content
```

## Content Organization

Profiles are categorized by:
- Net Idols and others
- Chulalongkorn University
- Chiang Mai University and vicinity  
- Silpakorn University
- Thammasat University
- Other Universities
- High School

Each entry includes popularity indicators using fire emojis (:fire:) and cupid recommendations (:cupid:).