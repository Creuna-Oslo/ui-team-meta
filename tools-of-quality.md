# 🛠 Tools of Quality

Our working environment should help us do high quality work because of it, rather than in spite of it.

This document attempts to be an overview of what we need and want in such an environment, without prescribing concrete products. Preferences will be noted.

## 👀 Transparency

To ensure a wholesome and productive environment, we _must and will_ be fully transparent with the team.

The customer is a part of the team. Therefore, if you "can't" say something to the customer, it does not exist for the team. We will not be forced to keep secrets from our own team members.

In the same spirit, we will not do any double bookkeeping of issues, statuses, time etc. If this is "needed", we will have no part in it and the work will fall to whoever feels that this is "needed".

## 💬 Language

We strive to be as clear and concise as possible.

For the sake of clarity we forgo the use of abbreviations unless these are widely understood (we will, for example, use `URL` instead of `Uniform Resource Locator`).

We will write code, documentation, issues etc. in US English, as this is the language of the code we write, and makes it possible to include those not proficient in Norwegian as members of a team.

If the customer demands that some of these things be done in Norwegian, an explicit choice must be made to satisfy that demand.

Certain circumstances exist where mixing of languages is preferred, such as when a domain is only easily expressed in a given language.

Regardless of language, we will strive to write and speak in a gramatically correct manner in order to avoid misunderstandings.

There will be instances in which technical language, that is only understood by a person with sufficient proficiency, must be used.

## 👩‍👩‍👦‍👦 Explicit Roles and Mandates

We must know who is responsible for what. Therefore:

- Mandates must be defined.
- Roles must be defined.
- Roles must have one or more mandates.
- Members must be defined.
- Members must have one or more roles.

There must also exist a role with the mandate to define roles and mandates so that eventual missing or inconsistent roles and mandates can be (re)defined.

Creuna has this already, including several defined roles and mandates, but the defined roles and mandates might not (but should) be sufficient for most projects.

It's perfectly cromulent to not define extra roles or mandates, and also grow the team, mandates, and roles organically as development progresses.

## 📝 Issue Tracking

A way to track issues must exist.

The issues must be visible to, at least, the project members.

The status of an issue must be visible on the issue itself, and reflect the actual status of the issue in the real world.

This means that the overall state of the system is visible and knowable. E-mail, calls and other private messages are therefore not an acceptable form of issue tracking.

If an issue does not exist on the issue tracker, it does not (for the purposes of the project or system) exist.

Work is derived from issues on the issue tracker by members suited to perform the work, not prescribed to specific members.

We make no demands with regards to the exact type of issue tracker, but it must be compatible with the overall project workflow. [GitHub](https://github.com), [Jira](https://www.atlassian.com/software/jira), [Trello](https://trello.com), a [whiteboard](https://en.wikipedia.org/wiki/Whiteboard), [Post-it Notes](https://www.post-it.com/) are all fine in different circumstances.

## 💾 Source Control

All source code must live in an accessible repository. Source code that does not, does not (for the purposes of the system) exist and must not be required for an application to work.

We strongly prefer [Git](https://www.git-scm.com) hosted on an accessible to us customer owned system.

## 📚 Documentation

A project must be documented. This includes the location of the code repository, and the location of required content (for example databases).

We strongly prefer that this is done in an accessible to us customer owned system.

## 👩‍🏫 Onboarding

Onboarding a developer must be as easy as:

1. Being given access to required sources (documentation, repository etc.)
2. Pulling, aquiring dependencies, building, running the application(s)

Point two must be documented in the repository itself (usually in `README.md`).

We strongly urge system maintainers to [AUTOMATE ALL THE THINGS](https://knowyourmeme.com/memes/all-the-things) so that these steps can be executed as fast and error free as possible.

## 👩‍💻 Development

A project must have a defined strategy for change management. Scrum, Kanban etc. are well defined strategies. Others exist. We do not prescribe any one strategy, but lean heavily towards more agile strategies (f.ex. Kanban over Scrum).

A strategy for branching, approving, merging code etc. must be in place.

Popular strategies include [trunk based development](https://trunkbaseddevelopment.com), [pair programming](https://en.wikipedia.org/wiki/Pair_programming), [GitFlow](https://nvie.com/posts/a-successful-git-branching-model/).

A requirement for quality _of any sort_ is that at least two people must have the opportunity to discuss and review work.

Popular strategies for this include [dev designs](https://hackernoon.com/development-driven-development-75c01b2afca1), [code reviews](https://en.wikipedia.org/wiki/Code_review).

## 🏗 Continuous Integration

We must be able to continously integrate changes. This is "easy" given a defined process for change and a strategy for managing code changes.

## 📦 Continuous Delivery

We must be able to continously deliver the system. This delivery does not necessarily have to automatically be deployed to production, but this capability must exist.

## ⏱ Time Tracking

If time tracking is required, there must exist a working way to do this.

Members of a project that have no specific issues to work on, but still have time allocated to the project, must be able to perform work that is of value for the project. If required, time tracking of these activities must be possible.

Ideally, members should not be required to track their own time as this is a concern that can be solved in a higher level relationship (for example between representatives form Creuna and the customer).
