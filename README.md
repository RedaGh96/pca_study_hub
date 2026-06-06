# PCA Study Hub

A static HTML study app for preparing for the **Google Cloud Professional Cloud Architect (PCA)** exam.

This project organizes PCA concepts into topic-focused study pages with:
- Interactive flashcards
- Exam-style multiple-choice Q&A
- Lightweight navigation between domains
- Dark and light theme support
- Mobile-friendly layouts for quick revision

## Features

- Topic-based HTML pages for focused PCA study
- Flashcards with concise exam-oriented explanations
- Exam-style Q&A blocks for practice
- Theme toggle with saved preference behavior
- Responsive card-based layout for desktop and mobile use
- Fully static app, easy to host anywhere

## Topics Covered

- Compute
- Networking
- Security & IAM
- Storage
- Data & Analytics
- Operations & Monitoring

Depending on the final file set in the repo, you can also include additional overview or general index pages.

## Project Structure

Example structure:

```bash
.
├── index.html
├── pca_compute.html
├── pca_networking.html
├── pca_security_iam.html
├── pca_storage.html
├── pca_data_analytics.html
├── pca_operations_monitoring.html
└── assets/
```

Each topic page follows a similar structure:
- Header with page title
- Theme toggle
- Tabs for Flashcards and Exam Q&A
- Interactive cards and answer feedback

## Purpose

The goal of this project is to create a fast, simple, and practical PCA revision app that helps learners review high-signal Google Cloud architecture patterns without requiring a backend or build process.

It is designed for:
- Self-study
- Last-minute revision
- Topic-by-topic exam practice
- Quick lookup of common PCA service-selection patterns

## Tech Stack

- HTML
- CSS
- JavaScript

No framework or backend is required. The app runs directly in the browser.

## How to Run

### Option 1: Open locally
Open `index.html` directly in your browser.

### Option 2: Use VS Code Live Server
If you use VS Code, install the **Live Server** extension and run the project locally for easier navigation.

### Option 3: Host as a static site
You can deploy this project easily to:
- GitHub Pages
- Netlify
- Cloudflare Pages
- Vercel (static deployment)

## GitHub Pages Deployment

If your repo contains the static files at the root:

1. Push the project to GitHub.
2. Open the repository settings.
3. Go to **Pages**.
4. Set the source branch, usually `main`.
5. Select the root folder.
6. Save and wait for the site to publish.

## Use Cases

This app is useful for:
- Practicing PCA service selection
- Reviewing architecture trade-offs
- Learning security, networking, and storage patterns
- Studying from a phone, tablet, or laptop
- Building a personal cloud certification knowledge base

## Notes

- This project is intended as a study aid.
- Content is organized for speed and recall rather than as official exam documentation.
- It works best as a lightweight revision companion alongside official Google Cloud learning resources.

## Future Improvements

Possible enhancements:
- Add search across cards and questions
- Track progress across topics
- Randomized quiz mode
- Tag-based filtering by service or domain
- Shared CSS/JS to reduce duplication across pages
- Better homepage navigation and study path guidance

## License

Add your preferred license here, for example:

MIT License