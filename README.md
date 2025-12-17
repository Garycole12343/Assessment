Community Skill Swap Hub README

Module Information

Module Code COM4113
Module Title Tech Stack
Assessment Title Tech Stack Proposal
Institution Leeds Trinity University

This repository contains the front end implementation and documentation for the Community Skill Swap Hub project.

Project Overview

The Community Skill Swap Hub is a web based platform designed to support community driven learning through the sharing of hobbies, skills, and learning resources. The platform allows users to browse content freely as a guest, reducing barriers to entry, while optional account creation unlocks enhanced features such as personal profiles and messaging.

The primary objective of this project is to demonstrate the design and implementation of a scalable and maintainable front end architecture using modern web development technologies. This version of the application focuses solely on the user interface and interaction logic, using mock data in place of persistent storage.

The scope of the project includes navigation, conditional feature access based on authentication state, responsive design, and clear user flows. Backend services, authentication servers, and databases are intentionally excluded at this stage and planned for future development.

Choice of Tech Stack and Justification

React was selected as the front end framework due to its component based architecture, which supports separation of concerns, reusability, and long term maintainability. Compared to traditional multi page approaches, React enables efficient state management and smoother user interactions, making it suitable for a platform expected to scale in complexity.

Vite was chosen as the build tool and development environment because it offers faster development startup times and more efficient hot module reloading than older tooling such as Create React App. This improves development efficiency and reduces iteration time.

Tailwind CSS was selected for styling due to its utility first approach, which promotes consistency across the interface and simplifies responsive design. This choice reduces custom CSS complexity and supports rapid UI iteration.

Client side routing is handled using React Router, allowing logical separation of pages and seamless navigation without full page reloads.

Although no backend is implemented in this phase, future development plans include a RESTful API integrated with MongoDB. MongoDB has been identified as a suitable database due to its flexibility with user generated content and its scalability for community driven platforms.

Version Control and Development Practice

Git and GitHub were used consistently throughout the project to manage version control. The repository was accessed through GitHub Classroom and commits were made incrementally to reflect feature development, refactoring, and bug fixes.

This workflow demonstrates good software engineering practice by enabling traceability of changes, rollback capability, and structured project progression.

Repository link https://github.com/Garycole12343/Assessment

Installation Instructions

This project uses npm and is executed via Command Prompt.

Node.js must be installed before running the application.

Open Command Prompt and navigate to the project directory.
Run npm install to install project dependencies.
After installation, run npm run dev to start the development server.
Open a browser and navigate to the local development address displayed in the terminal.

The most common technical issue encountered was incompatible Node.js versions. This was resolved by installing the latest LTS version of Node.js and restarting the development environment.

Project Plan and Timeline

Development followed a structured and iterative plan.

The initial phase focused on requirement analysis, technology evaluation, and user journey design.

The second phase involved environment setup using Vite and React, followed by implementation of the core layout and navigation system.

The third phase focused on feature implementation, including conditional access to profile and messaging sections based on authentication state, using mock data.

The final phase included responsive styling, usability improvements, testing across screen sizes, and documentation refinement.

Minor adjustments were made to the original plan to improve navigation clarity and reduce interface complexity following usability testing.

User Journey and Interaction Flow

Upon visiting the platform, users can immediately browse skills and resources as a guest. There is no forced login or sign up prompt, improving accessibility and user engagement.

A sign up option is permanently visible in the top right hand corner. Once a user signs up and is logged in, additional features such as the profile page and messaging functionality become accessible. This design balances openness with feature gated functionality.

Legal and Ethical Considerations

The current implementation does not store sensitive personal data, reducing privacy and security risks at this stage. Ethical considerations include transparent feature access, respect for user autonomy, and responsible platform design.

Future backend implementation will comply with data protection legislation such as GDPR and will include secure authentication, data encryption, and clear user consent mechanisms.

Risk Assessment

Identified risks include lack of persistent data, absence of server side validation, and reliance on mock content. These risks are acceptable for a front end prototype and are documented transparently.

Planned backend integration will mitigate these risks through secure APIs, database validation, and authentication services.

Good Software Attributes

The project demonstrates maintainability through modular React components, readability through consistent naming conventions, and usability through responsive and intuitive interface design.

The application is efficient for its current scope and has been structured to support future feature expansion without major refactoring.

Real World Applications

The platform could be applied to real world scenarios such as community education platforms, hobbyist networks, peer learning environments, and informal professional skill sharing communities.

Future Considerations for Scaling

Future work will include integration with a backend API and MongoDB to enable persistent user data, authentication, messaging, and resource management. Additional features such as ratings, saved resources, and AI assisted recommendations can be layered on top of the existing architecture.

In Code Documentation

Key components and functions include inline comments that explain purpose, logic, and behaviour. This improves code readability and supports collaboration and future maintenance.

AI Usage Declaration

This assignment used generative AI to review the documentation and code for clarity, structure, and potential errors. All application code was written by the author. AI tools were used only as a checking and refinement aid and not to generate the core implementation.