SkillSphere README. Module Information.

Module Code: COM4113.
Module Title: Tech Stack
Institution: Leeds Trinity University.
Project Overview. From web-based platforms that enable the user to share his hobbies, skills and learning resources with you, it also promotes community-based learning as one way of doing so. You as a guest can freely browse through the content, for all that can be attained. You can sign up now for your personal profile and messages. SkillSphere is designed to exhibit how to build a scalable, maintainable front-end built using the latest web development technologies. The primary purpose of this preliminary phase is to work on the UI/interaction logic and also mock data rather than developing a live backend. We need to consider clear user flows, responsive design, feature access that's driven by your authentication, and how to get around the features in an easy way. Backend services, authentication servers, and databases will not be added during this stage but will come much later when need be.

Choice of Tech Stack. React vs. Other Frameworks. I chose React due to its adaptability, robust community support, and component-oriented architecture (we merged components to facilitate the writing of reusable code and avoid dependencies), allowing for maintainable code to be built. We also tested other frameworks:

Vue.js: Easy to use and very little learning curve.
Svelte: A program to render code in simpler form with a neat, minimalist JavaScript libraries (from JavaScript with JavaScript stack compile time and simplicity, quick and lightweight development).
Angular: Great for a big codebase but typically has a higher codebase complexity for bigger applications.
SolidJS/Qwik: New and upcoming frameworks that are good at dynamic applications.
Finally, React seemed to balance performance and maintainability, but at the same time was well suited for community support, so it was a good choice for our projects.

Vite vs. Other Build Tools. Due to Vite's speed of setup and configuration, I selected Vite as our build tool since I believe it has a faster startup time and easy configuration. We have other options we considered:

Other choices that I attempted to work with:

Webpack: Good power but slow to setup and run.
Turbopack: Great for big, but new and better for big-data applications.
Parcel: Friendly, but relatively few plugins and less community support.
Tailwind CSS vs CSS Frameworks. Styling - Since we always want to keep the same style but still have an easy style with simplicity with the same structure, for styling, we used Tailwind CSS. The other frameworks we explored were:

Bootstrap: These are a few types of pre-defined components, but it can be too restrictive as there are many items it contains.
Windi CSS: Like Tailwind but much faster to compile
Materialize CSS/Bulma: Great for premade assets but if you wanted a fast but dynamic build it becomes difficult.
By using React Router for routing, we will go smoothly from page to page without reload to other pages without loads.

Things to consider from Server-side perspective. Whilst the server side strategy for SkillSphere right now focuses greatly on the frontend, I have also done some thinking about some of the server side design too. User authentication, data persistence and content moderation will demand a great server setup. Suppose, for example, that we were developing a RESTful API with MongoDB and supporting this dynamic storage for user-generated content, profiles, messages and shared resources, on our scaling platform. The core concepts include sensitive data handling (for example hashed passwords and personally identifiable information) and validation and error handling to make sure data is true. Performance considerations for instance, would involve caching resources most frequently used as well as enhancing the response time of the database queries to application load. And server-side logging and monitoring would help us in preventing any of these issues, in advance.

Optional Server-side Framework Comparison

We will discuss different server-side frameworks in future:

Node.js with Express: A lightweight, JavaScript-based design that fits well with React Front End.
Django: A more formal (Python based) framework with built-in authentication & admin features, but heavier for smaller projects.
Firebase: A run-on-cloud, managed backend service with a real-time database. Less need for server maintenance but not as many modules.
Node.js/Express is preferred for its flexibility and strong community support among the JavaScript ecosystem at these times. We use Git and GitHub for version control. All feature additions and bug fixes are included in the commit files of our app, which maintains good development practices that possess at least three attributes:

Traceability of changes.
Rollback capabilities.
Organized project delivery cycle.
GitHub Repository: (https://github.com/Garycole12343/Assessment). Open a terminal and go to the project directory. Run

Copy code
npm install to install the required dependencies. Run

Copy code
npm run dev; run its server in your browser; see what is installed. Main problem to be fixed:

Non-compatible Node.js versions are the main source of errors. I fixed this by ensuring that the most recent LTS version is installed.

Project Plan and Timeline
For implementation, I did something like a comprehensive, incremental process over nine weeks:

Phase 1: Necessitate analyses, review of tech, and design of user journey concept.
Phase 2: Building environmental setups with Vite and React, and initial layout / navigation.
Phase 3: Use of fake data to apply features that are allowed in profiles and messaging sections (or provide only conditional access).
Phase 4: Response styling, usability improvement, end-user testing, document refinement, testing from devices.
To provide a clear visual overview of this timeline, a detailed Gantt-style chart has been created and included in the project repository at

Copy code
src\images\Gantt-style_timeline.png. This chart breaks down tasks and milestones into time-bound phases, helping track progress and manage deliverables effectively throughout development.

User Journey of Interaction
Guests can pick up skills and resources right away without having to sign up. A large signup button in the top-right-hand corner serves as a prompt to signup for a personal online account that has many more features like profiles and messaging. It is an easy to use system but limited in functionality to the limited number of registered users. I plan to be GDPR-compliant but have not used it. This allows for rapid prototyping, but collecting user data would require:

Explicit consent.
Clear privacy policies.
Secure data storage.
But without such safeguards, scaling up the project might threaten privacy.

Ethical Trade-offs
The open browsing model broadens access to the platform but does not include content moderation, which can lead to negative repercussions, including:

Misuse of the platform (for example: inappropriate/misleading content).
Potential declining user trust.
Moving forward, the next updates emphasize that these risks will be minimized and mitigated through reporting and moderating capabilities.

Risk Assessment
Current risks include:

No persistent data storage.
No server side validation.
Reliance on mock data.
To avoid these problems, we will assist with our backend integration with secure APIs and support of authentication and database.

Good Software Attributes
This project exemplifies:

Maintainability: React Components as Modularity.
Readability: Same naming concepts.
Usability: Simple and easy to use.
Efficiency: Built for today and tomorrow.
Real-World Applications
SkillSphere has several functionalities as:

For community education.
Hobbyist networks.
Peer learning environments.
Casual professional skill-sharing networks.
Areas for Future Scaling
Things that could be considered in the future include:

API (backend) and MongoDB connection for backup, and persistence of data.
Authentication and messenger capabilities.
Resource management.
Recommendations, ratings, retained resources, AI alerts, etc.