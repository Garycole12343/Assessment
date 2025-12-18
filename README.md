SkillSphere README
Module Information

Module Code: COM4113
Module Title: Tech Stack
Assessment Title: Tech Stack Proposal
Institution: Leeds Trinity University

This repository contains the front-end implementation and supporting documentation for the SkillSphere project.

Project Overview

SkillSphere is a web-based platform designed to encourage community-driven learning by sharing hobbies, skills, and learning resources. Users can browse content freely as guests, removing barriers to entry, while creating an account unlocks additional features like personal profiles and messaging.

The main goal of this project is to demonstrate the design and implementation of a scalable and maintainable front-end using modern web development tools. This version focuses on the user interface and interaction logic, using mock data instead of a fully functional backend.

The project scope includes clear user flows, responsive design, conditional feature access based on authentication, and intuitive navigation. Backend services, authentication servers, and databases are intentionally excluded in this phase, with plans for future integration.

Choice of Tech Stack
React vs Other Frameworks

React was chosen for its flexibility, large community support, and component-based architecture, making it easy to build reusable and maintainable code. Other frameworks were considered:

Vue.js: Beginner-friendly with a gentle learning curve.

Svelte: Compiles to plain JavaScript, making apps fast and lightweight.

Angular: Powerful for large applications but heavier and more complex.

SolidJS / Qwik: Newer frameworks with strong performance for high-speed applications.

React was selected for its balance of performance, community support, and ease of building scalable UIs.

Vite vs Other Build Tools

Vite was chosen as the build tool because of its fast startup time and simplified configuration. Alternatives considered:

Webpack: Powerful but slower to configure and run.

Turbopack: Promising for large apps but still new.

Parcel: Simple to use but has fewer plugins and smaller community support.

Tailwind CSS vs Other CSS Frameworks

Tailwind CSS was used for its utility-first approach, which allows consistent styling while remaining flexible. Other options:

Bootstrap: Lots of pre-built components but can feel restrictive.

Windi CSS: Similar to Tailwind but faster compilation.

Materialize CSS / Bulma: Good for pre-built components but less customizable.

Routing is handled with React Router, enabling smooth navigation and page separation without full reloads.

Future Backend Plans: The platform will later integrate with a RESTful API using MongoDB, chosen for its flexibility with user-generated content and scalability for community platforms.

Version Control and Development Practices

The project used Git and GitHub for version control, with commits reflecting incremental feature development, refactoring, and bug fixes. This approach demonstrates good software engineering practices by enabling:

Traceability of changes

Rollback capability

Structured project progression

Repository link: https://github.com/Garycole12343/Assessment

Installation Instructions

Ensure Node.js is installed.

Open a terminal and navigate to the project directory.

Run npm install to install dependencies.

Start the development server with npm run dev.

Open the displayed local address in your browser.

Common Issue: Incompatible Node.js versions can cause errors. Installing the latest LTS version resolved this.

Project Plan and Timeline

Development followed a structured, iterative approach over nine weeks:

Phase 1: Requirement analysis, technology evaluation, and user journey design.

Phase 2: Environment setup with Vite and React, implementing core layout and navigation.

Phase 3: Feature implementation, including conditional access to profile and messaging sections using mock data.

Phase 4: Responsive styling, usability improvements, cross-device testing, and documentation refinement.

Minor adjustments were made to improve navigation clarity and simplify the interface based on usability feedback.

User Journey and Interaction Flow

Guests can immediately browse skills and resources without signing up.

A permanent sign-up button in the top-right corner encourages account creation.

Logged-in users can access additional features like profiles and messaging.

This design ensures accessibility while providing gated functionality for registered users.

Legal and Ethical Considerations
GDPR and Data Protection

At this stage, GDPR compliance is planned but not implemented. While this allows rapid prototyping, any real user data collection would require:

Explicit consent

Clear privacy policies

Secure data storage

Without these measures, scaling the project could create privacy risks.

Ethical Trade-offs

The open browsing model improves accessibility but prevents content moderation. Risks include:

Misuse of the platform (e.g., inappropriate or misleading posts)

Potential damage to user trust

Future implementation of reporting or moderation features will mitigate these risks.

Risk Assessment

Current risks include:

No persistent data storage

Lack of server-side validation

Reliance on mock content

These are acceptable for a front-end prototype. Planned backend integration will address these issues through secure APIs, authentication, and database validation.

Good Software Attributes

The project demonstrates:

Maintainability: Modular React components

Readability: Consistent naming conventions

Usability: Intuitive, responsive interface

Efficiency: Optimized for current scope and future feature expansion

Real-World Applications

SkillSphere could be applied to:

Community education platforms

Hobbyist networks

Peer learning environments

Informal professional skill-sharing communities

Future Considerations for Scaling

Future development plans include:

Integration with a backend API and MongoDB for persistent data

Authentication and messaging

Resource management

Additional features such as ratings, saved resources, and AI-assisted recommendations

In-Code Documentation

Key components and functions include inline comments explaining their purpose and behavior, supporting code readability, collaboration, and future maintenance.

AI Usage Declaration

During this project, I used generative AI tools to review the documentation and code for clarity, structure, and potential errors. All application code was written by me. AI tools were only used to check and refine the work, not to generate the core implementation.