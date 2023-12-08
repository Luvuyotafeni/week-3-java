# week-3-java
What is SDLC?
SDLC Overview
Software Development Life Cycle (SDLC) is a process used by the software industry to design, develop and test high quality software. The SDLC aims to produce a high-quality software that meets or exceeds customer expectations, reaches completion within times and cost estimates.

SDLC is the acronym of Software Development Life Cycle.
It is also called as Software Development Process.
SDLC is a framework defining tasks performed at each step in the software development process.
ISO/IEC 12207 is an international standard for software life-cycle processes. It aims to be the standard that defines all the tasks required for developing and maintaining software.
History of the SDLC
The profession of “software developer” has existed since the first computers, and their operators, as far back as the days of ENIAC and vacuum tubes. Practices and methods for developing software have evolved over the decades since the invention of the computer. Those methods have adapted to the state of the art in computer hardware, development tools, and modern thinking about the organizational management of software development teams. With this progress, new methods of software development have grown out of private and public software development efforts around the world.
What is the SDLC?
Software is a complex product that is developed and delivered through a series of steps. That is the one thing all the various methods have in common: one way or another, software, like all products, starts as an idea. The idea then becomes a document, or perhaps a prototype, depending on the method in use. Whether a document, diagram, or working software, the artifact created in one step becomes the input to the next step. Eventually, the software is delivered to the customer

How does the SDLC work?
The process of software development is a never-ending cycle. The first release of a software application is rarely “finished.” There are almost always additional features and bug fixes waiting to be designed, developed, and deployed.

Reports from error monitoring software about usability and bugs feed back into the process of software development, and become new feature requests and improvements to existing features. This is why the Software Development Life Cycle is the most general term for software development methods. The steps of the process and their order vary by method. Regardless of method, they typically run in cycles, starting over with each iteration.

It’s very difficult to carry out a complex, team effort such as software development without some kind of plan. Each software development methodology (several will be detailed below) is a plan framework for how to develop software. There is much debate about which method is best overall, which is best suited to a particular type of software, and how to measure success in software development. One thing, however, is certain: any plan is better than no plan.

The seven important phases of SDLC
Planning/feasibility study:
This phase involves defining the project, setting goals, and establishing the project team. Key activities include defining project scope, objectives, timelines, and budget.

Requirements Analysis:
In this phase, the development team works closely with stakeholders to gather and document detailed requirements. The goal is to understand the needs and expectations of end-users.

Design:
The design phase involves creating a blueprint for the software based on the requirements. It includes high-level design, focusing on the overall system architecture, and low-level design, which involves detailed design specifications for individual components.

Implementation (Coding):
This is the phase where the actual code is written based on the design specifications. It involves transforming the design documents into executable code. Developers follow coding standards and best practices during this phase.

Testing:
The testing phase involves systematically evaluating the software to identify and fix defects. Testing may include unit testing (testing individual components), integration testing (testing the interaction between components), system testing (testing the entire system), and user acceptance testing (ensuring the software meets user expectations).

Deployment:
Once the software has successfully passed all testing phases and meets acceptance criteria, it is deployed to the production environment. Deployment involves making the software available to end-users.

Maintenance and Support:
The maintenance phase involves ongoing support and updates to address issues, fix bugs, and make enhancements. This phase ensures the software continues to meet user needs and remains compatible with evolving technologies.

SDLC Models
The V-Model, also known as the Verification and Validation model, is an extension of the traditional waterfall model. It emphasizes a systematic and sequential approach to software development and testing. The V-Model is called so because of its V-shaped representation, which illustrates the relationships between development phases and corresponding testing phases.

Business Requirement Analysis

The initial stage in the development cycle is Business Requirement Analysis, during which the product requirements are comprehended from the customer's standpoint. This phase entails extensive communication with the customer to grasp their expectations and precise needs. It is a crucial activity that requires effective management, given that many customers may not be entirely certain about their requirements. Additionally, acceptance test design planning occurs in this stage, utilizing business requirements as an input for acceptance testing.

System Design
System Design comes into play when you have well-defined and detailed product requirements. At this stage, the focus is on designing the entire system, including a comprehensive outline of the hardware and communication configuration for the ongoing product development. The system test plan is crafted based on this system design. Addressing this aspect early on allows ample time for the subsequent execution of actual testing.

Architectural Design
During the Architectural Design phase, the focus is on comprehending and creating specifications for the system's architecture. Typically, multiple technical approaches are suggested, and the ultimate decision is made based on considerations of technical feasibility and financial viability. This phase involves breaking down the system design into modules, each responsible for different functionalities—commonly referred to as High-Level Design (HLD).
In this stage, a clear understanding of data transfer and communication between internal modules and external entities (other systems) is established. This information is crucial for designing and documenting integration tests during this phase.

Module Design
During the Module Design phase, the intricate internal design for all system modules is precisely specified, known as Low-Level Design (LLD). It is crucial to ensure that the design is harmonious with other modules in the system architecture as well as external systems. This phase emphasizes the importance of unit tests, which play a critical role in identifying and rectifying faults and errors at an early stage of the development process. Unit tests can be crafted based on the detailed internal designs of the modules during this stage.

Spiral Model
Identification
This phase starts with gathering the business requirements in the baseline spiral. In the subsequent spirals as the product matures, identification of system requirements, subsystem requirements and unit requirements are all done in this phase. This phase also includes understanding the system requirements by continuous communication between the customer and the system analyst. 
Design
The Design phase starts with the conceptual design in the baseline spiral and involves architectural design, logical design of modules, physical product design and the final design in the subsequent spirals.
Construct or Build
The Construct phase refers to production of the actual software product at every spiral. In the baseline spiral, when the product is just thought of and the design is being developed a POC (Proof of Concept) is developed in this phase to get customer feedback. Then in the subsequent spirals with higher clarity on requirements and design details a working model of the software called build is produced with a version number.
Evaluation and Risk Analysis
Risk Analysis includes identifying, estimating and monitoring the technical feasibility and management risks, such as schedule slippage and cost overrun. After testing the build, at the end of first iteration, the customer evaluates the software and provides feedback.

Big bang model
Big bang model is focusing on all types of resources in software development and coding, with no or very little planning. The requirements are understood and implemented when they come. This model works best for small projects with smaller size development team which are working together.
Big Bang Model - Pros and Cons
The advantages of the Big Bang Model are as follows:
This is a very simple model
Little or no planning required
Easy to manage
Very few resources required
Gives flexibility to developers
It is a good learning aid for new comers or students.
The disadvantages of the Big Bang Model are as follows:
Very High risk and uncertainty.
Not a good model for complex and object-oriented projects.
Poor model for long and ongoing projects.
Can turn out to be very expensive if requirements are misunderstood.

Waterfall model
The waterfall is a widely accepted SDLC model. In this approach, the whole process of the software development is divided into various phases. In this SDLC model, the outcome of one phase acts as the input for the next phase.
with the following steps: requirement analysis, design, implementation, verification and maintenance.

Waterfall Model - Advantages
The advantages of waterfall development are that it allows for departmentalization and control. A schedule can be set with deadlines for each stage of development and a product can proceed through the development process model phases one by one.
Development moves from concept, through design, implementation, testing, installation, troubleshooting, and ends up at operation and maintenance. Each phase of development proceeds in strict order.
Some of the major advantages of the Waterfall Model are as follows −
Simple and easy to understand and use
Easy to manage due to the rigidity of the model. Each phase has specific deliverables and a review process.
Phases are processed and completed one at a time.
Works well for smaller projects where requirements are very well understood.
Clearly defined stages.
Well understood milestones.
Easy to arrange tasks.
Process and results are well documented.

Agile model
The Agile Software Development Life Cycle (SDLC) is an iterative and incremental approach to software development that emphasizes flexibility, collaboration, and customer satisfaction. It contrasts with traditional SDLC models, such as the Waterfall model, which follow a linear and sequential process. The Agile SDLC is well-suited for projects where requirements are expected to change or evolve over time.

Here are the key principles and phases of the Agile SDLC:

Iterative and Incremental:

Agile breaks down the development process into small increments with minimal planning.
Each increment represents a portion of the system's functionality.
Iterations are short, typically lasting 1 to 4 weeks.
Collaborative Approach:

Emphasizes close collaboration between cross-functional teams, including developers, testers, and business stakeholders.
Frequent communication and face-to-face interactions are encouraged.
Customer Involvement:

Customer feedback is crucial throughout the development process.
Requirements are not fixed; they can be modified and reprioritized based on customer feedback.
Adaptive Planning:

Plans are not rigidly fixed at the beginning; instead, they evolve as the project progresses.
Planning is done at different levels, and adjustments are made based on feedback and changing priorities.
Continuous Integration and Testing:

Continuous integration involves integrating code changes into a shared repository multiple times a day.
Automated testing is crucial to ensure that each increment meets quality standards.
Flexible Response to Change:

Agile embraces changes in requirements, even late in the development process.
Changes are viewed as opportunities to enhance the product rather than obstacles.
Sprint Planning:

Work is organized into time-boxed iterations called sprints.
Sprint planning involves selecting and prioritizing items from the product backlog to be developed in the upcoming sprint.
Daily Stand-ups:

Short daily meetings (stand-ups) are held to discuss progress, obstacles, and plans for the day.
Helps keep the team synchronized and identify and address issues quickly.
Retrospectives:

At the end of each iteration, the team conducts a retrospective to reflect on what went well, what could be improved, and how to adjust in the next iteration.
Popular Agile frameworks and methodologies include Scrum, Kanban, and Extreme Programming (XP). These frameworks provide specific practices and roles that teams can adopt to implement Agile principles effectively. Agile has gained widespread adoption in the software development industry due to its ability to deliver value quickly, respond to changing requirements, and foster collaboration within teams.

Software Prototyping
Software prototyping is a software development methodology in which a prototype (an early approximation of a final system or product) is built, tested, and then reworked until an acceptable prototype is achieved. This approach helps to gather feedback from stakeholders and end-users early in the development process, facilitating better communication and understanding of requirements. Prototyping is particularly useful in situations where the requirements are not well understood or are likely to change.

Here are key aspects of software prototyping:

Prototype Development:

A prototype is a working model of the proposed system or product.
It may be a simplified version of the final system, focusing on critical features and functionalities.
Types of Prototypes:

Throwaway or Rapid Prototyping: A quick and disposable prototype is built to explore design ideas. Once the design is validated, the prototype is discarded, and the actual system is developed.
Evolutionary Prototyping: The initial prototype is developed with the idea of evolving it into the final product. Changes and refinements are made based on user feedback.
Benefits of Prototyping:

Early User Feedback: Stakeholders can interact with the prototype early in the development process, providing valuable feedback and reducing the risk of misunderstandings.
Improved Communication: Prototypes help bridge the gap between users and developers, facilitating clearer communication about requirements and expectations.
Reduced Development Time: Prototyping can lead to faster development as it allows for early identification and correction of design flaws and misunderstandings.
Iterative Development:

Prototyping is an iterative process. Multiple iterations may be created, refined, and adjusted based on user feedback until the final product meets the desired specifications.
Use Cases of Prototyping:

User Interface Design: Prototyping is often used to design and refine the user interface, ensuring it aligns with user expectations.
Requirement Exploration: Prototypes help in exploring and validating system requirements, especially when they are not well-defined initially.
Risk Reduction: Prototyping can help identify and mitigate risks early in the development process.
Challenges of Prototyping:

Scope Creep: There is a risk of adding too many features during the prototyping phase, leading to scope creep.
Resource Intensive: Developing prototypes may require additional resources, and there's a possibility of investing time in features that might not be included in the final product.
Prototyping Tools:

Various prototyping tools are available to facilitate the creation of interactive prototypes. These tools allow designers and developers to create and test prototypes quickly.
It's important to note that while prototyping is a valuable approach in certain situations, it may not be suitable for all projects. The choice between prototyping and other development methodologies depends on factors such as project complexity, stability of requirements, and the level of understanding of the problem domain.

Advantages of the Prototyping Model

Here, are important pros/benefits of using Prototyping models:

Users are actively involved in development. Therefore, errors can be detected in the initial stage of the software development process.
Missing functionality can be identified, which helps to reduce the risk of failure as Prototyping is also considered as a risk reduction activity.
Helps team member to communicate effectively
Customer satisfaction exists because the customer can feel the product at a very early stage.
There will be hardly any chance of software rejection.
Quicker user feedback helps you to achieve better software development solutions.
Allows the client to compare if the software code matches the software specification.
It helps you to find out the missing functionality in the system.
It also identifies the complex or difficult functions.
Encourages innovation and flexible designing.
It is a straightforward model, so it is easy to understand.
No need for specialized experts to build the model
The prototype serves as a basis for deriving a system specification.
The prototype helps to gain a better understanding of the customer's needs.
Prototypes can be changed and even discarded.
A prototype also serves as the basis for operational specifications.
Prototypes may offer early training for future users of the software system.
Disadvantages of the Prototyping Model

Here, are important cons/drawbacks of prototyping model:
Prototyping is a slow and time taking process.
The cost of developing a prototype is a total waste as the prototype is ultimately thrown away.
Prototyping may encourage excessive change requests.
Sometimes customers may not be willing to participate in the iteration cycle for the longer time duration.
There may be far too many variations in software requirements when each time the prototype is evaluated by the customer.
Poor documentation because the requirements of the customers are changing.
It is very difficult for software developers to accommodate all the changes demanded by the clients.
After seeing an early prototype model, the customers may think that the actual product will be delivered to him soon.
The client may lose interest in the final product when he or she is not happy with the initial prototype.
Developers who want to build prototypes quickly may end up building sub-standard development solutions.
