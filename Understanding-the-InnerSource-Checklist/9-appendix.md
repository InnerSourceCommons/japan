Chapter 9. Appendix
===================

The Actual Checklist
====================

It’s easy to feel overwhelmed with the task of starting an InnerSource project, much less taking your organization through the transition to a true InnerSource or open source company. PayPal has drawn a checklist from its own experiences and the experiences of colleagues in other companies making the transition. We present it here to help organize and focus what you need to do. Certainly, following the checklist slavishly will not produce success. Every organization needs to undertake investigations, discussions, and cultural change in order to benefit from InnerSource. But keeping this checklist in front of you can help reassure you that you’re making progress.

This report was inspired by both the GNU Manifesto and Checklist Manifesto. We hope to inspire you to take at least a small step toward InnerSource and creating your own checklist and sharing it with us. The Apache Way was an important inspiration for the team, and you will spot similarities in this list.

* Readiness
  * Personal
    * Do you believe this is a viable strategy for your company, or are you just doing it out of ideological commitment and idealism?
    * Do you understand the changes required to be successful at InnerSource?
    * Are you skillful at presenting ideas to others, listening to their concerns, and finding common ground without bias?
  * Project
    * Does this project matter to the company? Is it likely to survive strategy changes?
    * Appropriateness
    * Is this project likely to be interesting to developers outside the original development team?
      * Is it currently or could it be used widely by other teams in the company who depend on it?
      * Will it benefit from being extended by outsiders in ways that the original team could not anticipate?
    * Could the project benefit from having other teams contribute bug fixes and refactoring work?
    * Could outside developers contribute useful code or suggestions?
    * Would outside developers respond to appeals to contribute?
    * Code maturity
    * Is the project modular enough to make changes easy and safe to make?
    * Is the code well documented?
    * Existing process
    * Can releases be made frequently?
    * Is continuous testing and integration in place?
    * Is all of the code stored in a version control repository such as GitHub that makes branches, pull requests, and integration easy?
  * Team
    * Are team members ready for the challenges of InnerSource?
    * Accepting code and changes to their code from outsiders
    * Being responsible for less-than-perfect code contributed by outsiders
    * Having outsiders see their less-than-perfect code
    * Having to conduct conversations that are sometimes difficult with outsiders about accepting and rejecting their contributions
    * Mentoring and/or learning to mentor contributors
    * Do team members understand the requirements of running an InnerSource project? (It helps if members have participated on open source projects.)
    * Creating and maintaining documentation for guest contributors
    * Willingness to participate in forums and answer questions patiently
    * Using forums, which provide a historical record everyone can see, instead of hallway conversations (optionally, using a scribe to make notes during live meetings, just as long as all of the decisions and explanations for those decisions are documented)
    * Willingness to do code reviews of outside submissions
    * Maintaining the bug tracker
    * Taking a turn in the role of TC
    * Have you chosen TCs?
    * Do they understand their responsibilities?
      * Write and maintain the _CONTRIBUTING.md_ file in GitHub
      * Review incoming code (pull requests)
      * Mentor guest contributors
      * Merge pull requests
      * Take the lead on refactoring and modularization
      * Participate and answer questions on discussion lists
      * Send announcements
      * Watch for and suggest opportunities for collaboration
    * Do they understand the potential rewards (intrinsic and job-related) of this position?
      * Develop deeper understanding of the codebase
      * Improve the quality of your team’s code
      * Improve the quality of code within the organization as a whole with better integrations
      * Learn and grow as a developer by seeing many incoming code examples
      * Understand how to better refactor and modularize code to encourage external contributions
      * Develop interpersonal and leadership skills through mentoring and negotiation with guest contributors
    * Have they been given leeway to do things not previously in their job descriptions?
    * Is time set aside in team members’ work schedules for these new responsibilities?
    * Are team members trained to handle these responsibilities?
    * Is there a mechanism for making announcements that anyone in the organization can follow and search? (Examples: Slack, email)
    * Is there a recorded mechanism for discussion so that all Guest Contributor questions and internal team decisions are searchable by incoming Guest Contributors? (Examples: Slack, online forum)
  * Company
    * CxO-level executives
    * Do the executives understand the purpose and value of running a project as InnerSource?
      * The value of spreading tribal knowledge across the organization
      * The value of having teams remove their own external blockers and bottlenecks
      * The value of a more interconnected organization
      * The value of having advanced team members that have a deeper understanding of many arms of the codebase
      * How InnerSource encourages basic good practice and helps develop and spread even better coding and development practices
      * How InnerSource increases the learning and development of individual developers
    * Are they willing to support flexible work requirements and time spent on cross-departmental contributions?
    * Can they accept experimentation, failure, and repositioning?
    * Are they willing to support a path for career advancement that does not require management?
    * Does the executive team support the initiative?
    * Are company goals and KPIs clearly stated and shared?
    * Are the company’s vision and mission relevant, up-to-date, clear, respected, and followed?
    * Human resources
    * Are there rewards and criteria for promotions based on InnerSource values?
      * Rewards for people who contribute to projects in other departments
      * Rewards for developers who handle contributions from other departments (TCs)
    * Need path for advancement that respects community role and does not require moving into management
    * Organizational setup
    * Central coordinating team
      * Is the team set up?
      * Is it ready to communicate with projects interested in going InnerSource? Can it apply the criteria in this checklist to ensure that the project and team are ready?
      * How do projects register as InnerSource?
    * Do staff members have time to contribute to outside projects?
    * Do staff members have resources to measure and demonstrate gains and losses of teams?
    * Can staff members choose what projects to work on based on their expertise and motivations?
    * Is there a meritocratic philosophy that can appreciate good contributions from all corners?
    * Developers
    * Do developers around the company understand that they can contribute to the InnerSource project?
    * Do they understand the value of contributing to other projects?
      * Removing external blockers
      * Building integrations with other tools themselves
      * Seeing how other teams structure code and learn from examples
    * Do they understand the process for making contributions to other projects?
      * Joining the discussion
      * Reading the contribution requirements
      * Exploring and/or contributing to the Help Wanted file
      * Signing up for announcements
    * Do they know how to use the tools?
      * Version control
      * Programming language
      * Test development
    * Do they know how to support their team’s role in InnerSource?
      * Can they participate productively on forums?
        * Answer contributor questions
        * Describe the reasons for choices that have been made in a way that is clear
        * Respond constructively to feedback
      * Can they participate in dialogs around reviews of their code?
    * Are they permitted to contribute to projects outside their departments?
      * Do they understand how to get support from their product owners and managers?
* Repository
  * Are ancillary resources set up, such as the following?
    * Documentation
    * Discussion forum
    * Bug tracker
    * Wiki
  * Are the following files in place?
    * _README.md_
    * Project name
    * Any earlier names and codenames for this project
    * Project description
    * Team lead and PM/PMO contact information
    * Keywords for search purposes
      * So that people can find this particular project by name
      * So that people can find this project by what it does
    * How to sign up for the announcement list
    * Location of discussion forum
    * Location of other repositories (Examples: JIRA, Rally, Confluence)
    * _CONTRIBUTING.md_
    * Required
      * Table of contents
      * Names and contact information for TCs
      * TC availability schedule
    * Optional
      * Community guidelines
      * Code conventions
      * Testing conventions
      * Branching conventions
      * Commit-message conventions
      * Steps for creating good pull requests
      * How to submit feature requests
      * How to submit bug reports
      * How to submit security issue reports
      * How to write documentation
      * Dependencies
      * Build process schedule
      * Sprint schedule
      * Road map
      * Helpful links, information, and documentation
      * When the repositories will be closed to contributions
    * _HELPWANTED.md_
    * Can be initially empty
    * Can link to a forum where requests and offers are posted
    * Can contain a list of requests and offers
    * _GETTINGSTARTED.md_
    * Whatever a contributor might need to get the app up and running to begin coding
    * Can be filled in by an intern, or after some contributors get started, based on feedback about what would have been helpful to them to get started
  * Who reviews the documents in the repository?
* Tools
  * Version control
  * Continuous integration
  * Testing
* Logistics
  * Sprints
  * Codeathons, especially for tools
  * Education
  * Testing
  * Gamification
  * Reporting
    * Pull requests during recent period
    * Number
    * Size (in lines of code)
    * Type
    * Name of pull request submitter
    * Baseline metrics
    * Ongoing tracking
    * Resources
      * Costs
    * Time
    * Who sees measurements? Display to the community?
  * Bug fixing
* Product owners
