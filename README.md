# TimeOS

<p align="center">
  <strong>A bilingual, browser-based planner for organizing tasks, time, and daily priorities.</strong>
</p>

<p align="center">
  <a href="https://unesjami.github.io/TimeOS/"><img src="https://img.shields.io/badge/Live_Demo-Open-2563eb?style=for-the-badge" alt="Live demo"></a>
  <a href="LICENSE"><img src="https://img.shields.io/badge/License-MIT-14b8a6?style=for-the-badge" alt="MIT license"></a>
  <img src="https://img.shields.io/badge/Firebase-Cloud_Data-f59e0b?style=for-the-badge" alt="Firebase">
</p>

## Overview

TimeOS is a responsive task and time-planning web application delivered from a single HTML file. It uses React in the browser, Tailwind CSS, Firebase Authentication, and Cloud Firestore. The interface supports English and Persian/Dari workflows, including Solar Hijri calendar labels.

## Implemented features

- Task organization across today, upcoming, ideas, and missed states
- Time ranges and daily planning
- English and Persian/Dari interface support
- Gregorian and Solar Hijri date handling
- Light and dark themes
- Firebase authentication and cloud data storage
- Responsive browser interface

## Technology

| Area | Implementation |
|---|---|
| UI | React 18 loaded from CDN |
| Styling | Tailwind CSS and custom CSS |
| Browser JSX | Babel Standalone |
| Authentication | Firebase Authentication |
| Data | Cloud Firestore |
| Hosting | GitHub Pages |

This repository does not currently use Next.js, Express, PostgreSQL, Prisma, LangChain, or a Node.js build pipeline.

## Run locally

```bash
git clone https://github.com/unesjami/TimeOS.git
cd TimeOS
python -m http.server 8080
```

Open `http://localhost:8080`.

## Firebase and security

The Firebase client configuration in a web application identifies the Firebase project; it is not a server secret. Access must be protected with correctly configured Authentication and Firestore Security Rules. Never rely on a client-side configuration value as an authorization boundary.

## Project structure

```text
TimeOS/
├── index.html
├── README.md
└── LICENSE
```

## Current limitations

- The application is maintained in one large HTML file.
- There is no automated test suite or build pipeline yet.
- Calendar, meeting-transcription, and AI-agent integrations are not included in the current repository.

## Roadmap

- Split UI, styles, and application logic into maintainable modules
- Add automated tests and linting
- Document Firestore collections and security rules
- Add import/export and calendar integration

## License

Released under the [MIT License](LICENSE).

## Author

Created by [Unes Jami](https://github.com/unesjami).
