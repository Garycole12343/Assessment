SkillSphere README

Module Information

Module Code COM4113
Module Title Tech Stack
Assessment Title Tech Stack Proposal
Institution Leeds Trinity University

This repository contains the front end implementation and documentation for the Skillsphere project.

Project Overview

The SkillSphere is a web based platform designed to support community driven learning through the sharing of hobbies, skills, and learning resources. The platform allows users to browse content freely as a guest, reducing barriers to entry, while optional account creation unlocks enhanced features such as personal profiles and messaging.

The primary objective of this project is to demonstrate the design and implementation of a scalable and maintainable front end architecture using modern web development technologies. This version of the application focuses solely on the user interface and interaction logic, using mock data in place of persistent storage.

The scope of the project includes navigation, conditional feature access based on authentication state, responsive design, and clear user flows. Backend services, authentication servers, and databases are intentionally excluded at this stage and planned for future development.

Choice of Tech Stack and Justification

React vs Other Frameworks
React is pretty much the standard these days for web projects, and for good reason. It’s flexible, has a massive community, and makes it easy to build reusable components. But it’s not the only option. Vue.js is known for being beginner-friendly and has a gentler learning curve, which is great if you’re just starting out. Svelte is interesting because it compiles down to plain JavaScript, so your apps can feel faster and lighter. Angular is powerful for big projects, but it’s also heavier and a bit harder to get your head around. SolidJS and Qwik are newer and promise even better performance, especially if you’re building something that needs to be super fast.​

Vite vs Other Build Tools
Vite is the new kid on the block, and it’s really fast to set up and run. If you’ve ever waited ages for Webpack to start, you’ll appreciate how quick Vite is. Webpack is still popular for complex projects, but it’s slower and can be a pain to configure. Turbopack (used in Next.js) is great for big apps, but it’s still a bit new and not as well supported as Vite. Parcel is super simple to use, but it doesn’t have as many plugins or as big a community.​

Tailwind CSS vs Other CSS Frameworks
Tailwind’s utility-first approach makes it easy to keep your styles consistent and flexible, and its just-in-time compiler means you only load what you actually use. Bootstrap is more traditional, with lots of ready-made components, but it can feel a bit limiting if you want something unique. Windi CSS is like Tailwind but compiles even faster, so it’s good for bigger projects. Materialize CSS and Bulma are nice if you want pre-built components, but they’re not as easy to customise.

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

The diagram below illustrates the planned phases for the SkillSphere front‑end implementation across a nine‑week schedule.

![SkillSphere project Gantt chart](src/images/Gantt-style_timeline.png)


The initial phase focused on requirement analysis, technology evaluation, and user journey design.

The second phase involved environment setup using Vite and React, followed by implementation of the core layout and navigation system.

The third phase focused on feature implementation, including conditional access to profile and messaging sections based on authentication state, using mock data.

The final phase included responsive styling, usability improvements, testing across screen sizes, and documentation refinement.

Minor adjustments were made to the original plan to improve navigation clarity and reduce interface complexity following usability testing.

User Journey and Interaction Flow

Upon visiting the platform, users can immediately browse skills and resources as a guest. There is no forced login or sign up prompt, improving accessibility and user engagement.

A sign up option is permanently visible in the top right hand corner. Once a user signs up and is logged in, additional features such as the profile page and messaging functionality become accessible. This design balances openness with feature gated functionality.

Legal and Ethical Considerations

GDPR and Data Protection

At this MVP stage, GDPR compliance is only planned for the future, not actually implemented. This is a significant trade-off: while it lets us build a working prototype quickly, it means the project isn’t ready for real-world data protection standards. If the app were to launch and start collecting basic user information—like names or emails—it would need explicit consent, clear privacy policies, and secure data storage, none of which are in place yet. Just planning for GDPR isn’t enough; without real implementation, there’s a real risk of privacy breaches if the project is scaled up without proper safeguards.

Ethical Trade-offs
The platform’s openness—letting users browse as guests—is a positive feature, but it also means there’s no effective way to monitor or moderate content. Without a moderation or reporting system, there’s a risk of misuse, such as inappropriate or misleading posts. This simplicity works for now, but it could harm the platform’s reputation and user trust over time. Planning for features like user reporting or content moderation is important, but until these are actually built, the ethical risks remain.

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