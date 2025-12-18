SkillSphere README

Module Information

Module Code: COM4113
Module Title: Tech Stack
Institution: Leeds Trinity University

Project Overview

SkillSphere is a website and socializing platform for users to promote community learning by sharing interests, skills and information. Guests browse the platform without having to register, and signing up also unlocks many features such as personal profiles and messaging.

SkillSphere is intended to demonstrate how one can create a scalable and manageable front-end that is built upon modern web development technologies. We concentrate on the UI (User Interface) & interaction logic with mock data, for example no backend at present. These features include obvious user flows, an efficient and responsive design, and conditional access to features based on authentication, with user-friendly navigation. In the future, backend services, authentication servers and databases will be planned.

The Choice of Tech Stack

React vs Other Frameworks

We chose React for its modularity, a close-knit community, and component-based structure - which lets us build reusable, maintainable components. Other frameworks considered:

Vue.js: Easy to use with low learning curve.
Svelte: Compiles to simple JavaScript which is small and fast.
Angular: General for large code bases; complex but effective.
SolidJS/Qwik: New frameworks for short-paced, high efficiency apps.

React balances between speed, maintainability and wide community support.

Vite vs Other Build Tools

For easy setup and quickness, Vite was chosen. Other tools considered:

Webpack: Powerful but slower to set up, run or configure.
Turbopack: It's new too, good when creating large applications, but less mature.
Parcel: Basic but lacking some plugin and community support.

Tailwind CSS vs Other CSS Frameworks

Tailwind CSS: Used to ensure uniform CSS styling with flexibility and adaptability. Other frameworks explored:

Bootstrap: Pre-compiled parts, much more restrictive.
Windi CSS: Similar to Tailwind; but quicker compile time with more flexibility.
Materialize CSS/Bulma: They are pre-packaged assets but are less portable for dynamic builds.

Routing is handled with the use of React Router and the user can switch between pages without reloading.

Server-Side Considerations

SkillSphere, which is being focused on the front-end, has now been recommended for a server-side design. A well-built backend is essential as there are user signups, data persistence and content moderation.

For example, MongoDB and a RESTful API could support dynamic content storage for user-generated documents, user personal profiles, messages and resources sharing. Key considerations include:

Safe way to manage the sensitive data (hashed passwords, personal info)

Data integrity in input validation and error handling

Optimized performance by caching commonly used resources and speedy database queries

Server-side logging and monitoring to proactively find and fix problems

Planning a secure, maintainable, and scalable backend for smooth future integration should be done early on.

Server-Side Framework

Node.js using Express: This is a lightweight, JavaScript-based framework that has built-in support for React front-end.
Django: Framework written in structured Python with automated authentication/admin (for larger projects).
Firebase: Orchestration of cloud backend with real time database, easier to manage but less custom modules.

Node.js/Express has been chosen as being flexible and powerful for the community.

Versioning and Development Standards

Version control was done using Git and GitHub. Feature additions and bug fixes were tracked for reliability. Rollback capability is ensured, and project delivery follows a regular schedule.

Repository link: https://github.com/Garycole12343/Assessment

Installation Instructions

Open your terminal and log into the project directory.
Install dependencies using npm install.
Start the dev server with npm run dev.
Check your terminal output and open your local address in a browser.

Common Issue: Non-compatible Node.js versions can cause errors. The issue can be resolved by installing the latest LTS version.

Project Plan and Timeline

Development was constructed as an incremental process over 9 weeks:

Phase 1: Requirement studies, tech review, user journey design.
Phase 2: Environment design with Vite and React, initial layout and navigation.
Phase 3: Feature design on mock data, conditional access for profiles and messaging.
Phase 4: Re-styling, usability, mobile adaptation, re-specification of documentation, and testing across devices.

Gantt style chart :(src/images/Gantt-style_timeline.png)

User Journey of Interaction

Guests will be able to quickly browse skills and resources without needing to sign up. A sign-up button in the top right enables users to log in or sign up to see more features like profiles and messaging. The platform is built for ease, but currently it restricts features to those who have yet to sign in.

Legal, Ethical and Risks Implications

GDPR and Data Protection: The development of GDPR compliance is planned for the future. All data collection from users will require:

Explicit consent
Clear privacy policies
Secure storage of the data

Ethical trade-offs: Open browsing expands access, but with no content moderation, which could cause:

Misuse of the platform (inappropriate or misleading content)
Decreased user trust

Reporting and moderation plans in future updates will aim to mitigate such risks.

Risk Assessment

Current risks include:

No persistent data storage
No server-side validation
Reliance on mock data

Backend integration with secure APIs, authentication, and database support will help mitigate the risk.

Good Software Attributes

Maintainability: React components are modular.
Readability: Same naming conventions across the board.
Usability: A straightforward, accessible interface.
Efficiency: Developed for the present state and future potential.

Real-World Applications

SkillSphere can be applied to:

Community education sites
Hobbyist networks
Peer learning environments
Casual professional skill-sharing networks

Areas for Future Scaling

Backend API and MongoDB for persistent data
Authentication and messaging
Resource management
Recommendations, ratings, saved resources, AI alerts

Post-MVP Enhancements

Messaging Functionality: The platform will allow logged-in users to simulate chats by sending/receiving messages using React state.
Rationale: Messaging encourages community engagement through dynamic state management and conditional rendering.
Future Considerations: Backend with persistent storage will allow real-time updates and multi-user communication.

Ratings and Reviews: Skills/Resources can be rated or evaluated by users. Ratings are stored in React state and displayed alongside each resource.
Rationale: Ratings improve discoverability and trust, demonstrating dynamic input handling, component updates, and state management.
Future Work: Backend storage will allow aggregation and calculation of average scores per resource.

Search and Filter: The app includes a search bar to filter Skills/Resources by keywords using React state and array filtering methods.
Justification: Search improves usability and navigation and shows how React can be used to interactively manipulate data and enhance the UI.
Future Work: Backend integration will allow scalable, optimized queries with advanced filters.

Site Map

Home
│
├─ Browse Skills/Resources
│
├─ Signup/Login ──> Profile (User)
│ │
│ ├─ Messaging
│ └─ Saved Resources / Ratings
│
└─ Search / Filter

Gantt-style chart placeholder: [Insert image of project timeline here]
Site map diagram placeholder: [Insert Figma or flowchart diagram here]

AI Usage Declaration

Using generative AI techniques, documentation and code were reviewed for clarity, structure, and error checking. All application code was written by the author. AI was only used to review and refine the documentation.