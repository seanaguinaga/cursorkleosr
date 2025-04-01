# Project Configuration (LTM)

*This file contains the stable, long-term context for the project.*
*It should be updated infrequently, primarily when core goals, tech, or patterns change.*

---

## Core Goal

*(Define the primary objective and purpose of this project here. E.g., "Create a web application for managing personal tasks...")*

---

## Tech Stack

*   **Frontend Framework:** Angular 17, Ionic 8, TypeScript
*   **Mobile:** Cordova hybrid app supporting iOS and Android platforms, Apple Watch support
*   **UI Components:** Ionic components, Mobiscroll, Swiper, Lottie animations
*   **State Management:** @ionic/storage-angular, cordova-sqlite-storage
*   **Internationalization:** Transloco, cordova-plugin-globalization
*   **Data Visualization:** D3.js
*   **Testing:** Jasmine, Karma, Storybook
*   **Monitoring/Analytics:** Sentry, Firebase, Amplitude, LogRocket
*   **Authentication:** Firebase Auth, Facebook integration
*   **Utilities:** RxJS, Moment.js, Lodash-es, Fuse.js
*   **Development Tools:** ESLint, Prettier, Husky

---

## Critical Patterns & Conventions

*(Document any non-standard but crucial design patterns, architectural decisions, or coding conventions specific to this project. E.g.,)*
*   **State Management:** RxJS and Angular Signals.
*   **API Design:** RESTful principles.
<!-- *   **Error Handling:** Use custom `AppError` class for backend errors. -->
*   **Commit Messages:** Follow Conventional Commits format.

---

## Key Constraints

*   None
<!-- *(List any major limitations or non-negotiable requirements. E.g.,)*
*   Must support IE11 (if applicable).
*   Deployment target is AWS Lambda.
*   Strict adherence to budget/performance targets. -->
