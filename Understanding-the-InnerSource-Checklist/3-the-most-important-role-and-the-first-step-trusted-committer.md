Chapter 3. The Most Important Role, and the First Step: Trusted Committer
=========================================================================

TL;DR
=====

* For projects with any level of risk, you need to have a _Trusted Committer_. Define the role’s responsibilities clearly, based on the level of risk.
* Trusted Committers shift back and forth between coding and Trusted Committer responsibilities.
* The Trusted Committer role is difficult, and you need to reward those employees who deserve and accept the role.
* The rewards to the enterprise are great: better integrated code, better code reviews, faster pull request (PR) turnaround time, clearer knowledge for refactoring, more documentation with less pain, and bottleneck reduction.

In the previous chapter, we described some of the cultural problems we’ve encountered. Codebase owners must accept pull requests, or they create bottlenecks and escalations up the management chain. External teams must learn and conform to the style and standards of the codebase to which they are contributing, or their contributions must be extensively rewritten. And when codebase owners and external contributors don’t work together, nothing gets better and everyone ends up discouraged.

Many of the problems stem from the fact that developers in the enterprise environment are often unwilling to dedicate time to reviewing and accepting pull requests or mentoring developers in other areas. And who can blame them? They typically have assigned tasks and goals that are specific to their own project, not to other projects that happen to touch their codebase. In addition, most people are disinclined to accept responsibility for something they have not written.

But, for InnerSource to work, some developers _must_ take on responsibilities outside of their silos, so we created a new role with defined responsibilities and called it the Trusted Committer (TC). This is the most fundamental change we have implemented so far, and it is crucial to making InnerSource work. In fact, it is step one in its implementation.

Defining the Role
=================

The TC has the following list of responsibilities (each bullet point helps the TC’s team to better communicate and collaborate with other teams):

* Write and maintain the rules for contributing to the codebase
* Review incoming code (pull requests)
* Mentor contributors from other areas
* Merge pull requests
* Take the lead on refactoring and modularization
* Participate in discussion lists
* Send announcements
* Watch for and suggest opportunities for collaboration

We should point out that in the open source world, many groups have independently evolved a similar role. We specifically borrowed from [“The Apache Way”](http://theapacheway.com), a tool developed by the [Apache Software Foundation](https://www.apache.org). These roles are assigned to people who have shown a high level of dedication to a project. TCs are ultimately responsible for the codebase, and are often gatekeepers of the code. The level of power in these roles often has a direct relationship to the amount of risk. For example, the Linux kernel is widespread and high risk, so the Linux kernel has divided its version of the TC role into two levels, Janitors and Mentors. On the other hand, Node.js modules are very low risk. The community might not embrace a new module after vetting it, but new modules can’t break anything, so there is no TC role. Anyone can publish a Node.js module with npm.

Refining the Role
=================

After we had a defined role for the TC, we found a new problem: developers didn’t like the role, because they were afraid of getting too far away from the code; they didn’t want to lose coding time. They also struggled with prioritizing between coding and TC tasks. Plus, it was costly in time and attention for them to switch too frequently between those tasks. It made it difficult to get into the coding zone. To solve this issue, we considered removing programmers from active coding and assigning them the TC role as a full-time job. But this came with its own problem: we agreed that when people stop contributing code themselves, it becomes increasingly difficult for them to review code, especially integrations. Not to mention that it made programmers depressed because they would no longer be doing the kind of work they loved and entered the field to do.

Our solution is to have the TCs work with the product specialists to create a rotation schedule for themselves. They publish their schedules for other teams to see, in order to manage contributor expectations. We also find it helpful to list each TC’s specialties in the schedule so that the contributors know when someone with the appropriate expertise will be available to help them. It was also important to create new reward structures for the difficult and critical work done by TCs, a process I’ll describe later in the section “[Rewarding TCs](#rewarding_tcs).”

In our experience, the number of TCs per project varies greatly. In a high-risk project with about 30 developers, we ask that six programmers be assigned to the TC role. At any one time, half of them actively work in the TC role, reviewing code and mentoring, while the other half actively code. They switch roles at the end of every two-week sprint. This has been ideal for the TCs, because two weeks is a good solid length of time to either really get into coding, or to settle into mentoring and documentation.

In our lower-risk projects like tooling, a single TC works on 10 repos or more. Most developers are very eager to mentor contributors on their toolsets. This is ideal for helping teams across enterprises figure out how to better standardize their toolsets because everyone is welcome to contribute. The main suggestion we have for those TCs is to have office hours so that they can maintain blocks of time to get (and stay) in the coding zone.

Immediate Benefits
==================

Assigning the code reviews of PRs<sup>[1](#tbd)</sup> to the TC role greatly accelerated the turnaround on the PRs and increased the level of code reviews. Plus, we found that TCs used their mentoring time to create some wonderful documentation for the next big refactor of code. The lead for one of the major architectural reworks said that using InnerSource helped his team really understand how to significantly refactor the codebase. It also greatly decreased the amount of interrupt-driven coding from external bug fixes because those were also addressed in the bug fix PRs.

The documentation was created semi-painlessly by archiving public mentorship discussions between the TCs and contributors, and making them easily accessible in a context-relevant location in the codebase itself. This meant that the time spent on mentoring, valuable in and of itself, served double duty. We call this passive documentation, and we discuss it in more depth in [Chapter 4, _Passive Documentation and the Need for Findability_](/chapter-4#passive_documentation_and_the_need_for_f).

Rewarding TCs
=============

We found it important to work with HR and management to ensure the TC role is recognized formally. This solves two problems: development wins because they are reassured that management must respect the code review process, and no more Big Cheeses forcing code changes! The enterprise wins because the new role gives a path to promote programmers without taking them away from coding, which is what they do best and often love the most.

The TC role illuminates a developer’s advanced skills in mentoring, deep knowledge of architecture, and best code-review practices. We have found the TC role to be a difficult one, and companies need to determine how to properly reward those dedicated staff that take on the additional responsibilities.

We are enhancing our promotion path to Fellow for developers to reflect this complexity. This allows us to reward the “full-stack” developers we are creating and allows promotion without having to move to management roles that some developers find to be tedious. We get to keep the programmers that really understand the various codebases and encourage them to help refactor and reduce technical debt.

<sup>[1](#tbd)</sup> GitHub uses the term PR, as do several other tools. Companies not using these tools might call the same thing problem reports, change requests, or tickets.
