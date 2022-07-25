Chapter 2. What InnerSource Is and Isn’t
========================================

TL;DR
=====

Too often, enterprise culture wants to change the definition of InnerSource to something more familiar. We must help enterprise stakeholders create clear practices and definitions in order to maintain the culture of open source as much as possible while still highlighting the benefits to the enterprise.

One of the major problems we have encountered when implementing InnerSource has been, at its root, a vocabulary problem. After we completed several successful InnerSource projects, we noticed that many people began using the word InnerSource in a simplistic, degenerate manner. Probably the most damaging misunderstanding was that InnerSource meant outsourcing work from a busy team to another that presumably had more capacity. In general, it’s easy to fall into the fallacy of thinking that effective processes are just about following certain procedures or using certain tools, without regard for the culture that makes success possible.

Discussing the problems caused by this vocabulary issue became a bonding moment for all of us at the InnerSource Commons. Many members of the Commons want to focus on the larger problems of culture change, and the distorted definitions of Innersource were emblematic of the problems they are fighting. InnerSource goes much farther than simple processes or tools, and sometimes that makes definitions more difficult to communicate in an enterprise environment.

The vocabulary issue might sound minor, but we’ve found again and again that it is vital, especially when introducing change, that terms are clearly and explicitly defined and agreed upon. It is also important that the definitions are easy to find. This includes terms like “InnerSource,” but also includes roles and responsibilities. Some of the first steps toward InnerSource are to clearly and publicly define standards, roles, and responsibilities.

We Have GitHub Enterprise, So We Must Be InnerSource!
=====================================================

TL;DR
=====

GitHub helps with code transparency, but doesn’t actually change the typical enterprise silo-based mentality. Without the processes we talk about in this book, GitHub instead creates serious collaboration and integration issues, which can turn into bottlenecks, especially on critical codebases needed by many teams.

The idea that GitHub is all that’s needed to be InnerSource is a concept we fight against daily. Most people do not realize that it takes much more than GitHub to find, create, and grow open source communities. The communities create the software, not the other way around, but more often than not, large companies lack a sense of holistic community.

InnerSource Is About Culture and Processes, Not Just Tools
----------------------------------------------------------

The first steps toward InnerSource must be to foster trust and increase clear communication. This makes it possible for a sense of community to grow and improves collaboration. But businesses often lead from the _how_, rather than the _why_. We can’t tell them to foster trust in their teams; that is too vague and can’t be expressed as an action item. We fight the constant battle of process and hierarchy versus agility and customer influence. So how do we work around that? How do we make better decisions and collaborate more, without spending more money? These are things that GitHub cannot answer but InnerSource can.

It is true that using a tool like GitHub to make version control easy, visible, and accessible is a step in the right direction. But we need to think beyond tools and their advantages and flaws, and consider people. Enterprises are made of people with their own fears, habits, established patterns, hierarchy, and motivations, and they respond to corporate politics as much as to technology. This is why each of the checklist items focuses on some aspect of the human piece of the puzzle.

A Parable: GitHub Without InnerSource
-------------------------------------

The first big problem we encountered when introducing InnerSource was an increase in escalation up the management chain. We like to call it the “Big Cheese Story” (see the following sidebar). At its core, it is a story of fear. We believe it is unique to the corporate environment and not the open source world. We found that this story resonated with many of our participants in the InnerSource Commons. The awesome part is that open source’s existing processes already had several pieces of the solution, though they had not been put together before.

##### The Big Cheese Story

Once upon a time, there was a company that decided to embrace InnerSource, so it dictated that all code was to be moved to GitHub Enterprise. Because there was no cohesive version control before, there was much rejoicing across the company. Now, the developers finally had visibility to one another’s code! No longer would the developers need to submit a change request to planning, and hope it was accepted and scheduled some time in the next year. Visions of seamless collaborations danced in developers’ heads!

An intrepid programmer decided to do a pull request on the big codebase, and told her manager that she could write the necessary change in a matter of weeks. Her Big Cheese was very pleased. So, the intrepid programmer wrote the change and submitted the pull requests and waited...and waited...and waited...until her Big Cheese became very unhappy and asked why the changes had not been added. The intrepid programmer replied that she had finished the work and submitted the pull request, but the changes hadn’t been accepted by the other codebase.

So, her Big Cheese went to the Big Cheese that owned the other codebase, and asked him to force one of his groups to accept those changes. After all, there was now a big backlog waiting to go through! The Big Cheese of the codebase agreed and ordered some poor individual in his group to accept those changes. But that individual didn’t like how the intrepid programmer wrote the changes, because they were not “how things are done.” They were written in a different style, used a different test scheme, and maybe didn’t take advantage of an existing module. Thus, the second programmer rewrote the entire change before adding it to the codebase.

No one learned anything. No documentation was created. And now everyone hates InnerSource because it creates bottlenecks and makes programmers look difficult to the Big Cheeses. Plus, the product owners are frustrated because no one has included them in the process.

Breaking Down the Big Cheese Problem
------------------------------------

At first, we were surprised by the Big Cheese problem, because we knew that the more code that other teams can see into, the better they can understand the pieces they are integrating with and/or reusing. But we found that just having the code visible doesn’t automatically lead to collaboration, especially in an enterprise environment. The incentives are different from the open source environment.

First, most of the code had previously been developed in silos. This meant that teams had undocumented styles, structures, and practices that outsiders couldn’t know about until they submitted code that could not be accepted by the maintainers. Beyond that, there was a siloed culture that encouraged people to talk only to people in their own group and to use language that outsiders couldn’t understand. This often happens in complex structures. I’ll cover the organizational aspects later in this booklet.

If you do not understand the underlying architecture of the full stack, especially an older one with poor documentation, making silos is a normal response. It is easier to understand and take ownership of only your component. This is the piece you have the most control over. However, this method doesn’t lend itself to an atmosphere of collaboration, and can increase complexity and discourage reuse.

Because of this complexity, potential collaborators didn’t want to contribute until the pain from lack of integration was more painful than the fear of contributing. And the owners of the codebase were loath to accept responsibility for code that was not their priority and was written by someone not on their team. This resistance to collaboration resulted in a constant stream of escalations up the leadership chain. It turned GitHub into a bottleneck, especially for high-demand codebases, which tend to be high risk. Consequently, the code that the most people needed access to became the most difficult to contribute to.

We found that contributors were often inspired to write pull requests for the changes they needed in other codebases. But the codebase hosts were not accepting their pull requests, mainly because it meant extra work and responsibility for them. It became all risk and little gain.

We had to go back in the history of open source to find answers to these cultural problems. Then, we had to figure out how to make the solutions match enterprise structures. And we had to simplify the solutions so that they could be more universally adopted. I’ll explain our solution in [Chapter 3, _The Most Important Role, and the First Step: Trusted Committer_](/chapter-3#the_most_important_rolecomma_and_the_fir).

More Communication Pitfalls
---------------------------

Communication in a siloed culture presents problems that are very different from those in a traditional open source environment. In particular, planning is significantly different. Two weeks before the beginning of my employment at PayPal, several teams submitted their feature-level integration requests to one popular codebase as a part of their quarterly planning. The core team took those stories and rewrote them to fit the current construct of their codebase, with no involvement of the submitters, and then sent them back to the external teams. Near the end of the quarter, many team leads came to the InnerSource team with the rewritten stories, complaining that InnerSource was really just “conscripted code.” They felt like they were being conscripted to do another team’s work. They did not realize that the code they were being asked to produce was actually the changes needed to complete their own integration requests. Confused, we sent them back their original requests and showed how the new stories were actually derived from their original stories. This is when we learned that the external teams had not been involved at all in the rewrite. Clearly, this was a major communication failure! For the next (and all subsequent) rounds of planning, we made sure all teams were present for the negotiations and rewrites of stories. After this communication problem was solved, we made significant gains. An order of magnitude of code was accepted through pull requests, and external stories that had been on backlogs for years were cleared.

We also had an issue with teams creating significant pull requests against codebases with little to no warning to the codebase owners. Of course, in an enterprise environment, such a significant expenditure of resources without planning or communication too often became a battle of the Big Cheeses.

We needed to create a defined list of proven practices based on our experiences. We could see that better communication and well-defined expectations across teams was absolutely necessary. [Chapter 6, _Working Within the Enterprise: Understanding Planning_](/chapter-6#working_within_the_enterprise_understand) presents an explanation of the steps we’ve taken toward a solution.
