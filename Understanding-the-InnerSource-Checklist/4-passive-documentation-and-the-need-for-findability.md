Chapter 4. Passive Documentation and the Need for Findability
=============================================================

TL;DR
=====

* Passive documentation is crucial for mentoring and capturing tribal knowledge. The team takes a communication hit at the beginning, but the increase in velocity more than makes up for it.
  
* You can accelerate passive documentation by rewarding both the writers and consumers of the document.
  
* Passive documentation must be findable to be useable. Sometimes, this means that you will need to manually cross-tag between siloed datasets.
  
Passive documentation is the record of the documentation we create every day while communicating openly. It is a great way to get tribal knowledge out of silos and into a format that is archival and findable. As an added bonus, it is typically kept with the project or the code that it documents, thus it is in an easy-to-find, context-relevant location.

Creating Passive Documentation
==============================

Passive documentation consists of written information that was produced not specifically to document for the future, but to explain something in the present, as it is needed. For example, it often includes the following:

* Conversations that the Trusted Committers (TCs) have while mentoring a contributor who is learning how to integrate with her codebase
* Conversations the product owners have when they are explaining their priorities to one another, or arranging them
* The connection between a piece of the code and the project stories about the code, and the live conversations about both

At first, the most difficult part is persuading people to have these conversations more openly. They tend to start out wary of creating a lasting reference document on the fly. We found that when people realize that they are not writing formal documents, but are simply capturing mentoring conversations, the resistance dissipates. And the benefits of the rapid increase in documentation are quickly obvious to all.

To be captured in passive documentation, conversations need to happen in a written format. Common written formats include comments in a pull request, a tagged conversation in a public Slack channel, a comments page in a wiki, and a tagged email in a discussion group. In the open source world, we often say that conversations that don’t happen publicly on the email list or wiki aren’t “real.” We are working to change the culture internally to be the same. If there is an important discussion in person, at the end of it one person always commits to creating a written record of it. They do this by writing the discussion up in an email that all parties can approve, and then posting the write-up to the larger community.

“Did You Read the FINE Manual?”
===============================

We found that after the TCs had answered a few easy questions publicly on pull requests, the velocity of the next contributor’s pull request immediately increased.

Diligent contributors search the documentation before asking for help, or even writing their pull requests. In our case, we store this in GitHub, and because everything is in GitHub, there is little ambiguity about where to look. We encourage the TCs to refer contributors back to previous conversations when they do not incorporate previous advice in their pull requests.

We are working on ways to reward these public conversations internally. We are creating dashboards that highlight when someone has written especially relevant documentation. And we allow TCs to reward contributors who do their research first. Trust me, the TCs will quickly learn who follows directions and will prioritize their pull requests first!

Findability
===========

In the open source world, when you want to find out how to do something, you simply Google it. In the corporate world, finding information is much more difficult. Most information is locked away in different software and datastores that might or might not be searchable. Often the information in these applications is locked down by default, because that seems safer. But in the long run it is very damaging to a company. Locking information away makes onboarding a new employee a difficult process, and it makes integrating a new acquisition almost impossible. Moreover, it invites, or even encourages, an atmosphere of tribal knowledge.

Sometimes, those difficulties are created by the tools themselves when they have a bad or nonexistent search function. Sometimes, there are just so many tools being used that aggregation becomes an issue. Too often, problems are aggravated by pricing issues that force the company to shell out additional fees to enable access for all users.

But documentation is only useful if people can find it, so this is a really important problem to solve. Many of our teams have begun requiring cross-tagging spanning application silos in order to enable manual searching. For example, we have had several teams decide in their contributing agreement that they will not even consider a pull request that does not have a searchable tag of some sort, for example, a JIRA number for a bug fix, or a Rally story number for a feature-level pull request in GitHub. This is a huge help when someone needs to manually search across multiple locked-up datastores, but it isn’t ideal, and it requires developers to be quite diligent.

We have begun creating tools to assist in finding and sharing information. We created (and open sourced!) [RallySlack](https://github.com/paypal/rallyslack). When someone is on Slack, RallySlack automatically pulls up all of that individual’s Rally stories to make it easier to find and tag a Slack conversation. With RallySlack, users don’t need to look up or memorize Rally story numbers. We are developing a similar tool for GitHub to help with tagging Rally story numbers in pull requests and issues. Eventually we hope to open source this tool, as well.
