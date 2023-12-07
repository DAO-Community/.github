📄 File under 🏗 construction.

## New Members

A dedicated repository is made for new members/employees. Quickstart your DAO Community journey [here]().

## Governance Structure

This document describes the formal governance structure of the DAO Community. For the purpose of this document, “DAO-Community” includes all repositories in the [DAO Community GitHub organization](https://github.com/DAO-Community).


## Entities of the Community

This section outlines the different entities that exist within the DAO Community project, their basic role, and how membership of each entity is determined.

### For-Community

- Corporate Maintainer: MDI Novare
- BDFL [@bdfl](https://github.com/orgs/DAO-Community/teams/bdfl) [🔗](#bdfl-benevolent-dictator-for-life)
- Steering Committee [@steering-committee](https://github.com/orgs/DAO-Community/teams/steering-committee) [🔗](#steering-committee)
- Advisory Council [@advisory_council](https://github.com/orgs/DAO-Community/teams/advisory_council) [🔗](#advisory-council)
- Moderators [@moderators](https://github.com/orgs/DAO-Community/teams/moderators) [🔗](#moderators)
- Volunteers [@volunteers](https://github.com/orgs/DAO-Community/teams/volunteers) [🔗](#volunteers)
- Security Team [@security](https://github.com/orgs/DAO-Community/teams/security) [🔗](#security-team)

### Pillars

- Data Admin [@data-admin](https://github.com/orgs/DAO-Community/teams/data-admin) [🔗](#data-admin)
- Data Engineering [@data-engineering](https://github.com/orgs/DAO-Community/teams/data-engineering) [🔗](#data-engineering)
- Data Science [@data-science](https://github.com/orgs/DAO-Community/teams/data-science) [🔗](#data-science)

### Project Codebases
- Technical Committees [🔗](#technical-committee)
  - Git Hosting Platform Team [@git-hosting-platform-team](https://github.com/orgs/DAO-Community/teams/git-hosting-platform-team)
    - Maintainers/Leads for each SIG

---
---

# Responsiblities

## BDFL (Benevolent Dictator For Life)
[@bdfl](https://github.com/orgs/DAO-Community/teams/bdfl)

This organization follows a BDFL Governance Structure.

> Under this structure, one person (usually the initial author of the project) has final say on all major project decisions. [Python](https://github.com/python) is a classic example. Smaller projects are probably BDFL by default, because there are only one or two maintainers. A project that originated at a company might also fall into the BDFL category.
> &mdash; <cite>[Open Source Guides on BDFL][1]</cite>

[1]: https://opensource.guide/leadership-and-governance/#what-are-some-of-the-common-governance-structures-for-open-source-projects

See [Benevolent Dictator Governance Model](http://oss-watch.ac.uk/resources/benevolentdictatorgovernancemodel) for more information.

This role has the ability to veto against the Steering Committee.

---

## Steering Committee
[@steering-committee](https://github.com/orgs/DAO-Community/teams/steering-committee)

The Steering Committee supports the initiative by representing the DAO Community in all administrative and legal capacities.

The members of this committee must always be at counts `3`, `5`, `7`, and `9` **only**.

### Decision Making Process

The members of this committee are given 2 powers: lobby and vote.
- Members may lobby amongst the committee members their vote.
- Members may vote amongst the committee members their vote.

Decisions are made either unanimously or by rule of majority.

A rule of majority is recognized by a vote percentage of at least **70%** of the total committee members.

In case the committee is reduced to an even count, a priority by residence takes precedence,
and the member with the least residence shall be withdrawn the power to vote but not the power to lobby.

[//]: # "This section may be split into Financial and Non-Financial"

### Project Formation

The Steering Committee assigns the resources (maintainers, individual contributors, teams) to work on a For-Community project.

The committee may also assign resources on SIG projects but are not necessary.

[//]: # "TODO: Add instruction for RFC on project formation"

### Chairman

The Chairman of this committee must lead the delegation between the committee members.

The Chairman must:
- call and collect the votes of the committee members.
- represent the committee to the community.
- hold a tenure of 3 months (90 days) before a new Chairman is appointed.

The role of Chairman is nominated and voted amongst the committee members.

### Resignation

A member of the Steering Committee may leave the committee by doing the requirements below:
- notify the Steering Committee.
- submit a Pull Request adding their name to the [Former Steering Committee Members](https://github.dev/DAO-Community/.github/blob/main/CODE_OF_CONDUCT.md#former-steering-committee-members) and [Steering Committee Candidates Queue](https://github.dev/DAO-Community/.github/blob/main/CODE_OF_CONDUCT.md#steering-committee-candidates-queue) (ignore if the member is leaving the company).

If the resigning member is leaving the company, the other committee members must submit the PR.

### Candidates

The candidates for membership in the Steering Committee are considered either:
- by invitation from the Steering Committee or
- a RFC of nomination from the community or the potential candidates themselves.

The considered candidates are then queued in a list in the [Contributors](https://github.com/DAO-Community/.github/blob/master/Contributors.md) file.

First on the queue gets to take the open slot.

Candidates who are no longer an employee of the company will be removed from the list.

#### RFC for Nomination

A RFC for nomination will only be considered when 10% of the community upvotes within 30 days from posting.

A RFC for nomination will be closed with a comment of `Candidate invited, closing RFC.` if an invitation from the Steering Committee has been made.

If the RFC passed the criteria, then the RFC will be closed with a comment of `Nomination: passed, closing RFC.`. Otherwise, the RFC will be closed with a comment of `Nomination failed, closing RFC.`.

### Onboarding

Members must read and learn from the sites below:
- [Open Source Guides](https://opensource.guide)
- [GitHub Community](https://github.com/community)
- [The Linux Foundation: Open Source Guides](https://www.linuxfoundation.org/resources/open-source-guides)
- [OSS Watch](http://oss-watch.ac.uk/)
- [GitHub Docs](https://docs.github.com/en)
- [GitHub Skills](https://skills.github.com/)

## Advisory Council
[@advisory_council](https://github.com/orgs/DAO-Community/teams/advisory_council)

An advisory council provides advice and recommendations to the Steering Committee.

This council does not have direct decision-making authority.

Advisory councils are expected to provide valuable insights and advice, also offering diverse perspectives.

## Moderators
[@moderators](https://github.com/orgs/DAO-Community/teams/moderators)

This team is responsible for any moderation activity needed on the For-Community projects.

### Onboarding

Members must read and learn from the sites below:
- [Open Source Guides](https://opensource.guide)
- [GitHub Docs](https://docs.github.com/en)
- [GitHub Skills](https://skills.github.com/)

## Volunteers
[@volunteers](https://github.com/orgs/DAO-Community/teams/volunteers)

This team is responsible for any non-security sensitive activity needed on the For-Community projects.

## Security Team
[@security](https://github.com/orgs/DAO-Community/teams/security)

This team is responsible for any security activity needed on the For-Community projects.

`📝 NOTE`: Do not hold nominations for positions in this team.
The Steering Committee will reach out to potential members.

Members of this team is expected to hold their positions known only to the Steering Committee and BDFL.

Violations to cause for punishment and removal from the `Project: DAO Community` projects are:
- Disclosure of any security-related information kept by this team.
- Disclosure of one or more Security Team members

### Onboarding

Members must read and learn from the sites below:
- [GitHub Docs](https://docs.github.com/en)

## Data Admin
[@data-admin](https://github.com/orgs/DAO-Community/teams/data-admin)

Members of the Data Admin pillar.

This GitHub team only serves for tagging.

`📝 NOTE`: Do not create threads with this team.

## Data Engineering
[@data-engineering](https://github.com/orgs/DAO-Community/teams/data-engineering)

Members of the Data Engineering pillar.

This GitHub team only serves for tagging.

`📝 NOTE`: Do not create threads with this team.

## Data Science
[@data-science](https://github.com/orgs/DAO-Community/teams/data-science)

Members of the Data Science pillar.

This GitHub team only serves for tagging.

`📝 NOTE`: Do not create threads with this team.

## Git Hosting Platform Team
[@git-hosting-platform-team](https://github.com/orgs/DAO-Community/teams/git-hosting-platform-team)

The team for anything Git and Git hosting platforms related (Git-SCM, GitHub, GitLab).

The team that is also responsible for the technical requirements of this GitHub Organization in relation to the service of GitHub itself.

### Onboarding

Members must read and learn from the sites below:
- [Open Source Guides](https://opensource.guide)
- [GitHub Community](https://github.com/community)
- [GitHub Docs](https://docs.github.com/en)
- [GitHub Skills](https://skills.github.com/)

## Technical Committees

For each For-Community project repo, the Git Team focuses on all Git and GitHub related activities and processes. Including code review processes, technical standards and quality, release and versioning management.

For each By-Community project repo, the Maintainers and Lead(s) of a SIG are responsible.

## SIG Maintainers (WIP)

Project Maintainers/Leads are responsible for the technical development of their respective SIG' projects.

A new maintainer may be added by consensus of the current Project Maintainers and notification to the Steering Committee.

Before becoming a maintainer, it is expected that the community member will have been an active participant in the development and maintenance of at least one (1) of their SIG repository for a sustained period of time. This includes triaging issues, proposing and reviewing pull requests, and updating any binary dependencies as needed.

### Onboarding

Maintainers must read and learn from the sites below:
- [GitHub Docs](https://docs.github.com/en)
- [GitHub Skills](https://skills.github.com/)

## SIG Contributors (WIP)

### Onboarding

Contributors must read and learn from the sites below:
- [GitHub Docs](https://docs.github.com/en)
- [GitHub Skills](https://skills.github.com/)

## Users (WIP)

### Onboarding

---
---

### Notifications

Configured to be enabled only on specific/atomized teams to avoid causing an accidental email thread bomb.

Thus the following are implemented:
- Teams with at most 10 members are only allowed to have Notifications enabled.
- Parent Teams' Notifications must always be disabled.

See [1 PR, 400k+ devs, 60M+ emails](https://github.com/EpicGames/Signup/pull/24) for reference.

Articles:
* [Gigazine: Programmer accidentally sends GitHub notifications to about 400,000 people](https://gigazine.net/gsc_news/en/20220607-github-user-notification-400k-users/)
* [Segmentfault: A "reply-all event" triggered by an "@": Turning GitHub into a "botnet" sending harassing emails! Nearly 400,000 developers affected](https://segmentfault.com/a/1190000041959460/en)

| Teams | Receive<br>Notifications |
| -- | :--: |
| BDFL | ✅ |
| Steering Committee | ✅ |
| Advisory Council | ☑️ |
| Moderators | ✅ |
| Volunteers | ☑️ |
| Security Team | ✅ |
| Git Hosting Platform Team | ✅ |
| Data Admin | ☑️ |
| Data Engineering | ☑️ |
| Data Science | ☑️ |

[//]: # "Add Section: Conflict of Interest"

## Community Involvement (WIP)

The DAO Community project highly values the contributions made by members of the community. As an open-source project, DAO Community is both made for the community, and by the community.

There are five main channels that DAO Community uses to engage with the community.

### Community Forums (WIP)

The DAO Community Project Maintainers operate a [Matrix Network](https://groups.google.com/g/DAO Community) and host [GitHub Discussions](https://github.com/DAO-Community/Discussions/discussions) within the DAO Community repository. These forums serve two purposes. First, they provide a space for users to seek advice on how to use DAO Community (or convex optimization more broadly) in their intended application. Second, they provide a space for discussion on possible improvements to DAO Community or its dependencies.

### Matrix Server (WIP)

Discussions focused on the DAO Community’s development are conducted on a [Matrix Network](https://matrix.dao/xyz). The server is public but requires email verification.

The server consists of several channels with different permissions based on the concept of Matrix roles. The named roles are “Moderators”, “L1”, "L2", "L3".

The "L3" have write access to all channels and also have a private channel.

Those with the “L2” role have write access to the “developers” channel, which is otherwise read-only.

Individuals who have contributed significantly to the development of the DAO Community, for example by proposing and merging at least one substantial pull request, may be invited to the Matrix server as Contributors. L3 may grant the L2 role within Matrix at their discretion, and may create additional channels for specific long-term projects in the DAO Community’s development.

### Workplace Group (WIP)

The DAO Community Channel is open for anyone to post any topic.

[//]: # "Should this be regulated as well?"

### Developer Calls (WIP)

The Steering Committee hosts semiannual developer calls to discuss the DAO Community-related business. 

The precise time of a given call is determined one month ahead of time by discussions on the “developer-calls” channel of the DAO Community Matrix Network.

## Documentation

About the DAO Community documentation philosophy:

As the home to the MDI Novare's community of developers, we want to make sure that our documentation is accurate, valuable, inclusive, and easy to use. Our documentation philosophy leads us toward these goals.

We advocate for our users. This can occur at any point in the documentation process, from planning to writing to publishing. We respond to feedback and proactively work to create the best user experience possible on the GitHub site.
We collaborate with teams across MDI Novare to create high-quality content.
We continually learn and improve to curate the best experience for the community.

[//]: # "EOF"
