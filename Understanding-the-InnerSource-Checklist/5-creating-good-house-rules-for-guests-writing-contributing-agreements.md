# Creating Good House Rules for Guests: Writing Contributing Agreements

TL;DR
=====

* Trusted Committers (TCs) are responsible for writing contributing agreements to explain house rules to contributors (e.g., code conventions and dependencies). Contributing agreements are living documents.
* Contributors need to be good houseguests and read the agreements (and any other findable documentation) before contributing. The better they groom their contribution to match the contributing agreement, the greater the velocity of acceptance.
* Management needs to support the TCs on these agreements.
* Be careful when standardizing agreements because this leads to less ownership by the TCs. Complex agreements can prevent contributions and should be reserved for high-risk projects.
  
TCs cannot be forced to accept and take ownership of broken code, code without proper tests, undocumented code, or even code that doesn’t meet their style standards. Contributing agreements are a way to formalize the responsibilities of the developers on the originating side of the code.

What Is a Contributing Agreement?
=================================

The TCs write and own their _contributing agreements_. A contributing agreement is a device that specifies the house rules to let contributors know what is required in order for the TC to accept a code contribution. Contributing agreements are viewable by everyone in development. They must have the TCs’ names, contact information, and schedule. After that, the content is up to the TC. It will likely include some of the following:

* The authoring TC’s specialties
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
* Definition of done
* Dependencies
* Build-process schedule
* Sprint schedule
* Road map

It is very important for the TCs to be able to invoke these agreements for protection. If another team’s code contribution does not meet the receiving TC’s specifications, the TC needs to be able to point to the contributing agreement to explain exactly why the code is being rejected. This helps immensely to minimize corporate politics and escalation issues.

Mi Casa Es Su Casa
==================

The contributing agreements are also crucial in managing a contributor’s expectations. The metaphor we use is that of house rules for guests. Everything goes more smoothly if hosts communicate their expectations to their guests, instead of assuming that everyone has the same standards. Someone with a nice house with many breakable things and a very organized kitchen will have different house rules from a person who lives in a comfortable mess with cat-scratched furniture.

And hosts should warn guests about quirks in their house, like a circuit breaker that trips if someone tries to run the microwave and the dishwasher at the same time. The contributing agreement is the perfect place to list the house rules and pitfalls of your codebase. And, like clearly explained house rules, it can prevent damage, misunderstandings, and hurt feelings.

The metaphor extends to contributor behavior. Good guests follow the house rules, of course, but they also tidy up; that is, they help fix bugs or refactor code. And a _great_ guest brings a bottle of wine! A great codebase guest might contribute a feature or fix that everyone likes and wants.

Win/Win
=======

Most contributors quickly realize that the more closely their submissions adhere to the contributing agreements, the faster those submissions are accepted and committed. Also, contributors know that when they see a more permissive agreement, there is less risk in submitting changes.

One Size Fits All?
==================

In the open source world, different groups have different rules for contributions. Most of the differences are risk related. The Linux kernel has very strict submittal guidelines and processes that go far beyond a simple contributing agreement. On the other hand, agreements for Node.js modules are very permissive; they mostly ask that people do a search to ensure that they aren’t duplicating someone else’s effort.

This diversity is very similar to the variety of projects in an enterprise. We all have certain core projects that could topple the business if they fail, and these projects require strict contributing agreements. But we also have tools that we would like to standardize, and this is a much lower-risk activity. The toolset teams should have the flexibility to have simpler contributing agreements to lure people into collaborating. Often, these less-risky codebases can be safe places for contributors to learn how to participate in InnerSource projects.

Creating the contributing agreements is a balance between safety and participation. A short, easy agreement indicates that you welcome contributions and are willing to mentor people through the process of contributing. A longer, more complex agreement can convey difficulty, risk, and the fact that contributors need to pass several goals before their code will be accepted.

Some groups have tried to standardize one contributing agreement across the entire company. This is a pretty natural reflex for large enterprises. But we have fought against this because a company-wide agreement takes ownership away from the TCs, costing the company their buy-in, and eliminates the flexibility just outlined. Instead, we create templates as a starting place for TCs (such as the list in [“What Is a Contributing Agreement?”](#what-is-a-contributing-agreement)), adjusted for various levels of risk and complexity. We also ask that TCs revisit and update their contributing agreements after a retrospective or when new TCs are assigned to the codebase. It is vital that contributing agreements remain living documents.
