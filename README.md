[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-24ddc0f5d75046c5622901739e7c5dd533143b0c8e959d652212380cedb1ea36.svg)](https://classroom.github.com/a/-ucQIGTc)
[![Open in Visual Studio Code](https://classroom.github.com/assets/open-in-vscode-718a45dd9cf7e7f842a935f5ebbe5719a5e09af4491e668f4dbf3b35d5cca122.svg)](https://classroom.github.com/online_ide?assignment_repo_id=15228298&assignment_repo_type=AssignmentRepo)
# SE-Assignment-2
Assignment: Introduction to Software Engineering
Instructions:
Answer the following questions based on your understanding of software engineering concepts. Provide detailed explanations and examples where appropriate.

Questions:
Define Software Engineering:
Software engineering is a discipline that involves the application of engineering principles to the design, development, maintenance, testing, and evaluation of software systems


What is software engineering, and how does it differ from traditional programming?

Software engineering is the disciplined application of engineering principles to the design, development, maintenance, testing, and evaluation of software systems. It aims to produce high-quality, reliable, and efficient software that meets user requirements. This field integrates concepts from computer science, project management, and engineering to ensure software projects are completed on time, within budget, and to quality standards.


How Software Engineering Differs from Traditional Programming

Scope:
Traditional Programming: Focuses on writing code to solve specific tasks or problems.
Software Engineering: Encompasses the entire software development lifecycle (SDLC), including requirements analysis, design, implementation, testing, deployment, and maintenance.

Process and Methodology:
Traditional Programming: Often lacks a formal process, relying on the programmer's intuition and immediate needs.
Software Engineering: Follows structured methodologies (e.g., Agile, Waterfall, DevOps) to guide development activities systematically.

Team Collaboration:
Traditional Programming: Typically an individual or small-team effort with limited coordination.
Software Engineering: Involves large, cross-functional teams requiring effective communication and collaboration.

Quality Assurance:
Traditional Programming: Quality assurance is often informal and ad hoc.
Software Engineering: Employs rigorous quality assurance practices, including automated testing, code reviews, and continuous integration and deployment (CI/CD).

Documentation:
Traditional Programming: Documentation may be minimal or absent.
Software Engineering: Requires comprehensive documentation, covering requirements, design, testing, and maintenance.


Software Development Life Cycle (SDLC):

Explain the various phases of the Software Development Life Cycle. Provide a brief description of each phase.
Agile vs. Waterfall Models:


Planning:
Description: The initial phase where the project's scope, objectives, and feasibility are determined.
Activities: Define project goals, conduct feasibility studies, allocate resources, create a project timeline, and establish project plans.
Deliverables: Project plan, feasibility study report, resource allocation plan.

Requirements Analysis:
Description: Gathering and documenting the functional and non-functional requirements of the software.
Activities: Engage stakeholders to collect requirements, analyze requirements for completeness and consistency, document requirements in detail.
Deliverables: Requirements specification document, use case diagrams, user stories.

Design:
Description: Creating the architecture and detailed design of the software.
Activities: Develop system architecture, create detailed design for each component, design user interfaces and system interfaces, specify data structures and algorithms.
Deliverables: Design documents, architectural diagrams, database schemas, user interface designs.

Implementation (Coding):
Description: Writing the actual code according to the design specifications.
Activities: Develop software components, write and compile code, implement algorithms and data structures, perform initial debugging.
Deliverables: Source code, compiled code, software builds.

esting:
Description: Verifying that the software meets the specified requirements and identifying defects.
Activities: Conduct unit tests, integration tests, system tests, acceptance tests, log and fix defects.
Deliverables: Test plans, test cases, test scripts, test reports, defect logs.

Deployment:
Description: Installing the software in the production environment and making it available to users.
Activities: Prepare deployment environment, install software, perform final testing, provide user training, transition to live operation.
Deliverables: Deployment plan, installation guide, user manuals, training materials, deployed software.

Maintenance:
Description: Providing ongoing support to fix issues, improve performance, and add new features.
Activities: Monitor software performance, log and fix bugs, implement updates and patches, enhance functionality based on user feedback.
Deliverables: Maintenance reports, updated software, patch releases, enhancement documentation.


Compare and contrast the Agile and Waterfall models of software development. What are the key differences, and in what scenarios might each be preferred?
Requirements Engineering:

Waterfall Model
Overview:

The Waterfall model is a linear and sequential approach to software development.
Each phase must be completed before the next phase begins, with little overlap.
Phases:

Requirements: All requirements are gathered and documented upfront.
Design: The system and software design is prepared based on requirements.
Implementation: The actual coding and development of the software takes place.
Verification: Testing is done after the implementation phase to identify and fix defects.
Maintenance: Post-deployment maintenance and updates.
Characteristics:

Documentation: Heavy documentation at each phase.
Process: Rigid and structured process.
Flexibility: Low flexibility for changes once a phase is completed.
Risk Management: Risks are managed upfront, but late discovery of issues can be problematic.
Scenarios for Preference:

Well-Defined Requirements: Projects where requirements are clear, fixed, and unlikely to change.
Simple Projects: Projects with straightforward and well-understood processes.
Regulated Environments: Industries with strict regulations and documentation requirements, such as healthcare or aerospace.
Agile Model
Overview:

Agile is an iterative and incremental approach to software development.
Development is carried out in small, manageable units called sprints, typically lasting 2-4 weeks.
Phases:

Planning: High-level planning and prioritization of features.
Iterations (Sprints):
Design: Design for the current sprint.
Implementation: Develop the features planned for the sprint.
Testing: Continuous testing of the current sprint’s features.
Review: Review and feedback at the end of each sprint.
Release: Deployment of functional software at regular intervals.
Maintenance: Ongoing support and improvement based on user feedback.
Characteristics:

Documentation: Minimal documentation, focusing more on working software.
Process: Flexible and adaptive process.
Flexibility: High flexibility to incorporate changes even late in development.
Risk Management: Continuous risk management through iterative progress and frequent feedback.
Scenarios for Preference:
volving Requirements: Projects where requirements are expected to change or are not well-defined from the start.
Complex Projects: Projects that benefit from iterative progress and frequent reassessment.
Customer Involvement: Projects where continuous customer feedback and involvement are critical.
Innovation and Prototyping: Environments that encourage innovation and rapid prototyping.
Key Differences
Approach:

Waterfall: Linear and sequential.
Agile: Iterative and incremental.
Flexibility:

Waterfall: Low flexibility; changes are costly and difficult to implement after initial phases.
Agile: High flexibility; changes are welcomed even late in the development process.
Documentation:

Waterfall: Heavy upfront documentation.
Agile: Minimal documentation, focusing on working software.
Customer Involvement:

Waterfall: Limited to initial requirements and final delivery.
Agile: Continuous involvement throughout the development process.
Risk Management:

Waterfall: Risks are identified and managed early; late discovery of issues can be problematic.
Agile: Continuous risk management through frequent iterations and feedback.
Delivery:

Waterfall: Single final product delivery at the end of the project.
Agile: Frequent deliveries of functional software increments.
When to Use Each Model
Waterfall:

Suitable for projects with well-defined, stable requirements.
Ideal for projects where rigorous documentation is necessary.
Best for shorter projects with low complexity.
Agile:

Suitable for projects with evolving or unclear requirements.
Ideal for projects requiring rapid delivery and customer feedback.
Best for complex projects that benefit from iterative development and frequent reassessment.


What is requirements engineering? Describe the process and its importance in the software development lifecycle.
Software Design Principles:

Requirements engineering is the process of defining, documenting, and maintaining the requirements for a software system. It involves understanding what the stakeholders need from the software and ensuring that these needs are met throughout the development lifecycle. The process is crucial as it sets the foundation for all subsequent phases of the software development lifecycle (SDLC).

Process of Requirements Engineering
The requirements engineering process typically includes the following phases:

Requirements Elicitation:

Description: Gathering requirements from stakeholders, users, and other relevant sources.
Activities: Interviews, surveys, questionnaires, observations, workshops, and analysis of existing documents.
Importance: Ensures that all relevant needs and constraints are understood and documented.
Requirements Analysis:

Description: Analyzing and refining the gathered requirements to ensure clarity, feasibility, and consistency.
Activities: Conflict resolution, feasibility analysis, risk analysis, prioritization of requirements.
Importance: Helps identify potential issues early and ensures that requirements are realistic and achievable.
Requirements Specification:

Description: Documenting the requirements in a clear and precise manner.
Activities: Creating requirements specification documents, use case descriptions, and user stories.
Importance: Provides a reference point for developers, testers, and stakeholders, ensuring everyone has a common understanding.
Requirements Validation:

Description: Ensuring that the documented requirements accurately reflect the stakeholders' needs and are achievable.
Activities: Reviews, walkthroughs, inspections, prototyping, and validation meetings with stakeholders.
Importance: Ensures that requirements are correct, complete, and acceptable to all stakeholders.
Requirements Management:

Description: Managing changes to the requirements as the project progresses.
Activities: Tracking requirements status, maintaining traceability, handling requirement changes, and impact analysis.
Importance: Ensures that the project can adapt to changes in requirements without losing control over the development process.
Importance of Requirements Engineering in the SDLC
Foundation for Design and Development:

Requirements engineering provides a clear and detailed understanding of what needs to be built, serving as a blueprint for the design and development phases.
Stakeholder Alignment:

By involving stakeholders early and continuously, requirements engineering ensures that their needs and expectations are understood and met, reducing the risk of misunderstandings and dissatisfaction.
Risk Reduction:

Identifying and addressing potential issues during the requirements phase can prevent costly changes and rework later in the project, thereby reducing overall project risk.
Scope Management:

Clearly defined and managed requirements help in preventing scope creep, ensuring that the project remains focused and within budget and time constraints.
Quality Assurance:

Well-defined requirements provide the basis for creating test cases and validation criteria, helping to ensure that the final product meets the specified needs and quality standards.
Project Planning:

Accurate requirements are essential for realistic project planning, including resource allocation, time estimation, and cost forecasting.
Improved Communication:

Documented requirements facilitate better communication among team members, stakeholders, and other project participants, ensuring that everyone has a common understanding of the project goals and scope.


Explain the concept of modularity in software design. How does it improve maintainability and scalability of software systems?
Testing in Software Engineering:
Modularity in software design refers to the practice of dividing a software system into distinct, self-contained units or modules, each of which encapsulates a specific functionality or set of functionalities. These modules interact with each other through well-defined interfaces. The key idea is to create a system where each module can be developed, tested, and maintained independently of the others.
ow Modularity Improves Maintainability and Scalability
Maintainability:

Isolation of Changes: Because modules are self-contained, changes in one module can be made with minimal impact on other parts of the system. This isolation simplifies debugging and reduces the risk of introducing errors in unrelated areas of the code.
Simplified Testing: Individual modules can be tested independently (unit testing), making it easier to identify and fix defects. This modular testing approach leads to more reliable and robust software.
Clear Structure: Modularity provides a clear and organized structure to the codebase. Developers can easily understand and navigate through the code, making it simpler to add new features or update existing ones.
Reuse of Code: Modules can be reused across different parts of the application or even in different projects. Reusing well-tested modules enhances reliability and reduces development time.
Scalability:

Distributed Development: Different modules can be developed concurrently by different teams, speeding up the development process. This parallel development approach is crucial for scaling up large projects.
Incremental Growth: Modularity allows systems to grow incrementally. New modules can be added without significantly altering existing code, enabling the system to scale smoothly with increasing requirements.
Load Distribution: In distributed systems, modularity helps distribute the load across multiple servers or services. Each module can be deployed and scaled independently based on its performance and load requirements.
Independent Deployment: Modules can be deployed independently, allowing for more frequent and flexible deployment cycles. This capability is particularly useful in microservices architectures, where each service can be scaled and updated independently.
Key Practices for Achieving Modularity
Encapsulation: Each module should encapsulate its data and implementation details, exposing only what is necessary through a well-defined interface. This hides the internal workings and reduces dependencies between modules.

Cohesion: Modules should have high internal cohesion, meaning that the elements within a module should be closely related and focused on a single task or functionality.

Coupling: Aim for low coupling between modules. Modules should interact with each other through simple, well-defined interfaces. Low coupling reduces dependencies and makes the system more flexible and easier to maintain.

Separation of Concerns: Divide the system into modules based on distinct functionalities or concerns. Each module should address a specific aspect of the overall system, such as user interface, business logic, or data access.

Examples of Modularity
Object-Oriented Programming (OOP): In OOP, modularity is achieved through classes and objects. Each class represents a module that encapsulates data and behavior, and objects interact with each other through methods.

Microservices Architecture: In microservices architecture, the application is divided into small, independent services, each responsible for a specific functionality. These services communicate over a network using lightweight protocols like HTTP or messaging queues.

Component-Based Development: Software systems can be built using reusable components, such as libraries or frameworks. Each component provides a specific functionality and can be integrated into different parts of the application.


Describe the different levels of software testing (unit testing, integration testing, system testing, acceptance testing). Why is testing crucial in software development?
Version Control Systems:


Software testing is a critical component of the software development process, aimed at ensuring the quality, reliability, and performance of the software. Different levels of testing focus on various aspects and stages of the software. Here are the primary levels of software testing:

Unit Testing:

Description: Tests individual components or units of code, such as functions, methods, or classes, in isolation from the rest of the system.
Purpose: Verify that each unit functions correctly on its own.
Conducted By: Developers, typically using automated testing frameworks.
Examples: Testing a specific function in a library to ensure it returns the expected output for given inputs.
Integration Testing:

Description: Tests the interaction between integrated units or components to ensure they work together correctly.
Purpose: Detect issues in the interfaces and interactions between modules.
Conducted By: Developers or specialized testers, often using automated or manual tests.
Examples: Testing the interaction between a database and a web application to ensure data is correctly retrieved and displayed.
System Testing:

Description: Tests the complete and integrated software system as a whole to ensure it meets the specified requirements.
Purpose: Validate the overall behavior and functionality of the system.
Conducted By: Independent testing team, separate from the development team.
Examples: Testing the entire application, including all its modules and components, under various scenarios and conditions.
Acceptance Testing:

Description: Validates the software against user requirements and checks whether it is ready for delivery.
Purpose: Ensure the software meets the business needs and is acceptable to the end users or stakeholders.
Conducted By: End users, clients, or an independent testing team, often in a real-world or simulated production environment.
Examples: User acceptance testing (UAT), where users perform tasks to verify the software works as expected in their workflows.
Importance of Testing in Software Development
Quality Assurance:

Ensures the software functions as intended and meets the specified requirements, leading to a high-quality product.
Defect Detection:

Identifies bugs, errors, and defects early in the development process, reducing the cost and effort required to fix them later.
Reliability and Performance:

Validates that the software performs reliably under expected and stress conditions, ensuring it can handle real-world usage.
User Satisfaction:

Ensures that the software meets user expectations and requirements, leading to higher satisfaction and acceptance.
Risk Mitigation:

Reduces the risk of failures and issues in production, minimizing potential downtime and negative impact on users and business operations.
Compliance and Standards:

Ensures the software complies with industry standards, regulations, and best practices, which is critical in regulated industries.
Maintenance and Scalability

What are version control systems, and why are they important in software development? Give examples of popular version control systems and their features.
Software Project Management:


Version Control Systems (VCS) are tools that help manage changes to source code over time. They track and record every modification made to the codebase, allowing developers to collaborate more effectively, manage versions, and maintain a history of the project's development.

Importance of Version Control Systems in Software Development
Collaboration:

Allows multiple developers to work on the same codebase simultaneously without overwriting each other's changes. This enables efficient teamwork and parallel development.
History and Traceability:

Maintains a history of changes, including who made changes, when, and why. This traceability is crucial for debugging, auditing, and understanding the evolution of the project.
Backup and Recovery:

Acts as a backup system. If something goes wrong, developers can revert to previous versions of the codebase, ensuring no work is permanently lost.
Branching and Merging:

Facilitates branching, allowing developers to create separate branches for new features, bug fixes, or experiments without affecting the main codebase. These branches can later be merged back into the main code.
Release Management:

Helps manage and track different releases and versions of the software, ensuring a systematic and organized deployment process.
Code Review:

Supports code review processes by enabling developers to review, comment on, and approve changes before they are integrated into the main codebase.
Examples of Popular Version Control Systems and Their Features
Git:

Description: A distributed version control system widely used for its speed, flexibility, and strong support for branching and merging.
Features:
Distributed architecture: Each developer has a full copy of the repository.
Efficient branching and merging.
Staging area for preparing commits.
Support for various workflows (e.g., GitFlow, GitHub Flow).
Extensive ecosystem of tools and integrations (e.g., GitHub, GitLab, Bitbucket).
Subversion (SVN):

Description: A centralized version control system that maintains a single central repository.
Features:
Centralized architecture: All changes are committed to a central repository.
Directory versioning: Supports versioning of entire directory trees.
Atomic commits: Ensures complete and consistent commits.
Access control and permissions.
Strong support for binary files and large files.
Mercurial:

Description: A distributed version control system known for its simplicity and performance.
Features:
Distributed architecture: Similar to Git, each developer has a full copy of the repository.
Simple and intuitive command set.
Efficient handling of large projects.
Built-in web interface for browsing repository history.
Extensions for additional functionality.
Perforce (Helix Core):

Description: A centralized version control system designed for handling large codebases and binary files.
Features:
Centralized architecture with high performance and scalability.
Support for large binary files and complex dependency management.
Fine-grained access controls and permissions.
Visual tools for code review and collaboration (e.g., Helix Swarm).
Integrations with various IDEs and build tools.



Discuss the role of a software project manager. What are some key responsibilities and challenges faced in managing software projects?
Software Maintenance:


A software project manager plays a crucial role in overseeing the planning, execution, and delivery of software projects. They are responsible for coordinating resources, managing timelines, and ensuring that the project meets its objectives within budget and quality standards. Here are some key aspects of their role:

Planning and Coordination:

Develops project plans, defines project scope, objectives, and deliverables.
Creates schedules, allocates resources, and manages dependencies.
Coordinates activities among team members, stakeholders, and other project participants.
Communication and Stakeholder Management:

Acts as a liaison between the development team, stakeholders, and senior management.
Communicates project status, progress, risks, and issues to stakeholders.
Manages expectations and addresses concerns to ensure alignment with project goals.
Risk Management:

Identifies potential risks and develops mitigation strategies.
Monitors and evaluates risks throughout the project lifecycle.
Implements contingency plans to address unforeseen issues and minimize project disruptions.
Quality Assurance:

Ensures that the project adheres to quality standards and meets customer requirements.
Implements quality assurance processes, such as code reviews, testing, and validation.
Monitors and tracks defects, ensuring timely resolution and continuous improvement.
Resource Management:

Manages project resources, including personnel, budget, equipment, and software tools.
Allocates resources effectively to maximize productivity and minimize project costs.
Identifies and resolves resource constraints or bottlenecks to maintain project momentum.
Change Management:

Manages changes to project scope, requirements, and priorities.
Evaluates the impact of changes on project schedule, budget, and resources.
Communicates changes to stakeholders and implements change control processes to ensure proper documentation and approval.
Challenges Faced in Managing Software Projects
Scope Creep:

Managing changes in project scope and requirements without impacting project timelines and budgets.
Resource Constraints:

Balancing the availability and allocation of resources, including personnel, budget, and technology.
Technical Complexity:

Dealing with the inherent complexity of software development, including technical challenges, dependencies, and integration issues.
Schedule Pressures:

Meeting aggressive project deadlines while maintaining quality standards and managing risks.
Stakeholder Expectations:

Managing diverse stakeholder expectations, priorities, and communication preferences.
Team Dynamics:

Building and managing high-performing teams, fostering collaboration, and resolving conflicts or interpersonal issues.
Risk Management:

Identifying and mitigating project risks, such as technical challenges, resource constraints, or external dependencies.
Change Management:

Handling changes in project scope, requirements, or priorities while minimizing disruptions and maintaining project alignment.


Define software maintenance and explain the different types of maintenance activities. Why is maintenance an essential part of the software lifecycle?
Ethical Considerations in Software Engineering:


Software maintenance refers to the process of modifying and updating a software system after it has been delivered to address defects, enhance functionality, improve performance, adapt to changes in the operating environment, and meet evolving user needs. It involves making changes to the software to ensure its continued usefulness and effectiveness throughout its lifecycle.

Types of Maintenance Activities
Software maintenance activities can be broadly categorized into four main types:

Corrective Maintenance:

Description: Involves addressing and fixing defects or errors discovered in the software after deployment.
Activities: Identifying bugs, analyzing root causes, developing and implementing fixes, and testing the corrections to ensure they resolve the issues without introducing new problems.
Adaptive Maintenance:

Description: Involves modifying the software to accommodate changes in the operating environment, such as hardware or software upgrades, changes in regulations, or compatibility issues with other systems.
Activities: Assessing the impact of changes, modifying the software architecture or codebase as necessary, and testing the changes to ensure they function correctly in the new environment.
Perfective Maintenance:

Description: Involves enhancing or optimizing the software to improve its performance, reliability, usability, or maintainability based on user feedback or evolving requirements.
Activities: Identifying areas for improvement, implementing new features or enhancements, optimizing algorithms or code structures, and testing the changes to ensure they meet quality standards.
Preventive Maintenance:

Description: Involves proactively identifying and addressing potential issues or risks in the software to prevent future problems from occurring.
Activities: Conducting code reviews, performance monitoring, security assessments, and software audits to identify areas of weakness or vulnerability. Implementing measures such as refactoring, code cleanup, or security patches to mitigate risks and improve the overall health of the software.
Importance of Software Maintenance
Software maintenance is an essential part of the software lifecycle for several reasons:

Ensures Long-Term Viability:

Maintaining and updating software ensures its continued usefulness and relevance over time, allowing organizations to maximize their return on investment and meet evolving user needs.
Improves Quality and Reliability:

Addressing defects and making enhancements improves the quality, reliability, and performance of the software, enhancing user satisfaction and trust in the product.
Adapts to Changing Requirements:

Software maintenance enables organizations to adapt to changes in technology, business requirements, regulations, and user expectations, ensuring the software remains competitive and aligned with organizational goals.
Reduces Total Cost of Ownership (TCO):

Proactive maintenance helps prevent costly downtime, security breaches, and performance issues, ultimately reducing the overall cost of ownership and maximizing the value derived from the software.
Supports Continuous Improvement:

By collecting feedback, identifying areas for improvement, and making iterative enhancements, software maintenance supports a culture of continuous improvement and innovation within organizations.
Preserves Investment in Existing Systems:

Maintaining and extending existing software systems allows organizations to leverage their investment in technology and intellectual property, avoiding the need for costly and disruptive rewrites or replacements.


What are some ethical issues that software engineers might face? How can software engineers ensure they adhere to ethical standards in their work?
Submission Guidelines:

Privacy Concerns: Developing software that collects and stores personal data raises concerns about privacy infringement and data security breaches.

Bias and Fairness: Designing algorithms and AI systems that exhibit bias or discrimination based on race, gender, or other characteristics can perpetuate societal inequalities.

Intellectual Property: Ensuring proper attribution and respect for intellectual property rights when using open-source software, third-party libraries, or proprietary code.

Transparency and Accountability: Communicating honestly and transparently about the capabilities, limitations, and potential risks of software products and systems.

Safety and Reliability: Building software that meets safety standards and reliability requirements, particularly in critical domains like healthcare, transportation, and finance.

Environmental Impact: Considering the environmental impact of software development processes, such as energy consumption, carbon footprint, and electronic waste.

Accessibility: Ensuring that software products and services are accessible to users with disabilities and diverse needs.

To adhere to ethical standards in their work, software engineers can take several proactive measures:

Education and Awareness: Stay informed about ethical issues relevant to software engineering through continuous learning, training, and engagement with professional communities and resources.

Ethical Guidelines and Codes of Conduct: Familiarize themselves with ethical guidelines and codes of conduct established by professional organizations, such as the ACM Code of Ethics and Professional Conduct or the IEEE Code of Ethics.

Ethical Decision-Making Frameworks: Use ethical decision-making frameworks, such as the Ethical Decision-Making Framework developed by the Markkula Center for Applied Ethics, to evaluate ethical dilemmas and make principled decisions.

Collaboration and Consultation: Seek input and guidance from colleagues, mentors, and subject matter experts when facing ethical challenges, fostering a culture of collaboration and ethical reflection within the software engineering community.

Inclusive Design Practices: Embrace inclusive design practices that prioritize diversity, equity, and accessibility, ensuring that software products and systems serve the needs of all users.

Transparency and Accountability: Communicate openly and transparently about ethical considerations, potential risks, and decision-making processes throughout the software development lifecycle, fostering trust and accountability with stakeholders.

Continuous Reflection and Improvement: Reflect on ethical implications of software engineering practices, learn from past experiences, and strive for continuous improvement in ethical decision-making and behavior.

Your answers should be well-structured, concise, and to the point.
Provide real-world examples or case studies wherever possible.
Cite any references or sources you use in your answers.
Submit your completed assignment by [due date].
