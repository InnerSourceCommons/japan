# Working Within the Enterprise: Understanding Planning

**TL;DR**

<!--
* Transparency needs to be a part of the planning process. Creating internal transparency has led in our experience to more than an order of magnitude gain in external code acceptance.  
* Create formal processes to work within the enterprise environment. Formalizing processes keeps everyone on the same page.
* Transparency in planning helps because if the employees do not understand why decisions are made, they cannot propose corrections to the implementation. Top-down management is a complex process that rarely works. Open collaboration scales better.
-->
  
<!-- The biggest difference between InnerSource and open source is the business structure and its constraints. Working within an enterprise means a constant pull of hierarchy and power structures that are often contrary to the basic ethos of transparency and individual agency that is key to open source. Yet, open source has much to offer the business world. So how do we adapt to the business environment without diluting the fundamental aspects of open source? -->

## Keep It Small and Simple, and Engage Your Staff

<!-- Our biggest successes have resulted from finding and using a key point of leverage within the existing structures in the enterprise. We review current processes and find places to modify them in small ways to move incrementally toward InnerSource. We work with the business environment’s desire to work with _how_ s and not _why_ s, and simply tell them explicitly how to modify processes to improve outcomes, without going into lectures about transparency and ownership. It is best to make the changes as simple as possible, both to encourage adaptability and to avoid triggering the resistance large organizations can have to change. -->

<!-- For example, our written process for creating contributor agreements is very small and simple with few requirements: the agreements are owned by the Trusted Committers (TCs), they are viewable by other teams, and they contain the TCs’ contact information and availability. Other than the contact information and schedule, we do not dictate the content of the agreements at all. Of course, we do encourage and expect them to contain much more information! And problems with a guest contributor become the ideal learning experience to trigger additions or changes to the contributing agreement. It’s kind of like when you stay at someone’s house, and the host has a rule of no loud music after 2 a.m.; you know that someone before you must have played loud music at 2 a.m. -->

<!-- A crucial part of the TC process is that the employee who will be most affected by the change is given more power (and more responsibility) to manage that change. -->

<!-- These simple requirements, plus the rule that TCs are completely in charge of accepting or rejecting code changes, are relatively small and unalarming changes to the InnerSource process. But look at the results: -->

<!--
* The TCs have a huge incentive to fully participate in the new process.
* Better communication and documentation begins as soon as the agreement goes beyond contact information.
* The explicit expectations laid out in the document lead to better collaboration.
* Code changes move more quickly, leading to a positive feedback loop.
* As more code changes come in, the TCs do more mentoring, which creates more documentation.
* The TCs become more deeply familiar with their codebase and its external impact.
-->
  
<!-- The minimal requirements allow the teams to adapt the process to their own needs—a major tenet of open source—and lead to the InnerSource goals of better collaboration, fewer bottlenecks, better integration, and, almost certainly, cleaner code. -->

## Planning and Product Specialists

<!-- After our success in improving integration with TCs and contributor agreements, we knew we had to create something similar to smooth the planning process. The product specialist role, which monitors all aspects of the product lifecycle, needs to work on breaking down silos between teams and products, and to see how these products can integrate with others in the company. -->

<!-- Product specialists need the ability and knowledge to properly negotiate and prioritize features across teams. But, we have found that even though people working on code or product integration _know_ they need to sit down and discuss things with the other teams involved, they don’t usually make time for the necessary meetings unless they’re pushed. Anything not on the schedule is easy to put off. This results in poor communication, delays, and misunderstandings. The fix is a formal process change to force the necessary meetings, with greater inclusion to ensure that the appropriate people are in the planning sessions, and greater transparency to break down the silo mentality. We are working with our product specialists now to improve public records of this process. -->

## Inclusion and Transparency

<!-- Full inclusion in the planning stage of the process is crucial; all of the teams must be at the table for the process to work smoothly. Representatives from each team need to be present for the story grooming process, not just the owners of the primary codebase. Different teams often have different or conflicting priorities. Getting planners from each team together in one room helps them negotiate among themselves to get all the work done. Inclusion leads to smoother collaboration. -->

<!-- Transparency during the planning process is also important. We feel that it helps to reduce conflict. When a conversation is public and intended to be archived, we find that participants often become better at considering the entire company when working out priorities. It helps to break down the silo mentality. -->

<!-- Transparency in planning increased as a side effect of adding more people to the planning meetings. More people are present for the trade-offs and negotiations. Just as important is the small process change we had already implemented, requiring that all relevant conversations be a part of the passive documentation. This means that everyone can review discussions in the future, and alters people’s conversational strategies. Also, by creating passive documentation, you can avoid information overload as people search more and spam less. -->

<!-- Prioritization of projects and resources is usually done opaquely at companies. The reasoning is rarely made public and is done behind closed doors. This leaves employees to come up with their own narratives to explain priorities. Again, we see that when a company gives the _how_ but not the _why_, employees cannot make adjustments on the fly. It cripples their decision-making, and is a key element of bad escalation processes. -->

<!-- Bringing transparency to the process gives employees the ability to make corrections as necessary, because they understand the end goal and will not blindly continue down a designated path that they know will lead to the wrong outcome. In addition, making prioritization and resource allocation more transparent reduces hierarchically based fears of kingdom building, or the appearance of it. -->

## Planners Can Have an Impact on Processes

<!-- We began with simple rules. For high-risk and high-demand codebases, we found it necessary to formalize planning. The product specialists worked with the TCs to add rules to the contributing agreements requiring external contributors to file an issue request before submitting a significant code change. “Significant” meant using more than three story points in Rally. This requirement was the first step in creating a solidified process that requires the product specialists on both teams to meet and collaborate with one another as well as the TC and contributor prior to a significant code change. -->

<!-- Such structured meetings were not necessary for other codebases. Instead, their contributing agreements generally ask potential contributors to contact the TC and product specialist in advance on the listed discussion channels. Again, adaptability is key! -->

## Results

<!-- Greater inclusion in the planning stages does create a resource problem initially: scheduling meetings with large groups is difficult, the meetings can run longer than anticipated, and every person pulled into a meeting necessarily is putting off other tasks. But we saw benefits almost immediately. The teams understood the prioritization process better, which improved our Agile process. And the change velocity in the core team’s ability to accept external code was so large that it more than made up for the time lost in planning, by a factor of 10. And we were able to clear stories from contributor’s teams that had been on the backlog for years. -->

<!-- Opening up the process by including more people and making it more transparent also has an amazing effect on the teams’ ability to cross-collaborate. This leads to more effective decision-making both internally and across teams. We also found that by improving communication through passive documentation, eventually the meetings became smaller as teams used clearer communication. -->

<!-- We did find that the increased communication required some external facilitation in the beginning. A key element was teaching the product specialists to negotiate more effectively by always looking at the win/win solution for the company. This stage was relatively short; after things were ironed out between teams, collaboration increased dramatically and little external help was needed. -->

## Crossing the Gap from Planning to Developers

<!-- To our great satisfaction, the teams at PayPal really began to work well together, doing some horse trading and some very complex bargaining. One team’s product specialist even came up with a new, simple process change that we have added to the InnerSource checklist: product specialists must create and own a file called _HELPWANTED.md_. This file is where product specialists can transparently post their backlog. Developers who are looking for a project to work on will search the code repositories, but don’t usually think to look into project management tools, even if they have access. So, the _HELPWANTED.md_ file is placed in the code repository. Again, findability is important! -->

<!-- Some well-done _HELPWANTED.md_ documents have been generated from the project management tools, complete with notes and levels of prioritization. This really helps inform guest contributors about other teams’ needs. Often, potential contributors can tell which stories are similar to their own projects, so they choose which ones they can help with the most. The _HELPWANTED.md_ file is a great addition to the win/win mentality. Contributors can and do trade with other teams, fixing an item in the backlog in exchange for moving their feature-sized code changes up the review list. -->
