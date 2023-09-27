# Governance

## Discussion/Purpose of this Document

This document is designed to document and clarify the governance of the Pulsar (Pulsar-Edit) organization, and the team structure within it, in an open and transparent way.
The intent is not for this to be a rigid set of rules, but to allow us to have some written reference as to how things are handled within the organization when it comes to team organization and roles.

Contributors do not necessarily work with a strict set of responsibilities nor a strict governance model. The organization mostly resemble a [Do-ocracy](https://communitywiki.org/wiki/DoOcracy) , without too much in the way of formal or elaborate governance and policies, but we do of course have some guidelines and agreed conventions, in order to have a better-working organization.

## Team Membership/Adopting Roles

Contributors may belong to zero formal teams or roles, or to one or more teams or roles.

Team membership or role adoption is optional -– most forms of contribution can be done more or less the same with or without membership in a team or adoption of a role.

Team membership and role adoption are done on a basis blended somewhere between “by invitation” and “by volunteering” –- that is, for those contributors who are willing and interested in joining a team or adopting a role, and who accept the responsibility that comes with access/permissions, and given that these permissions might enable them to contribute with less friction, they may request such permissions, and on consideration of existing formal team/organization members, the request may be accepted/granted. Likewise, existing formal team/organization members may notice a frequent or recurring contributor and ask them if they would like formal team/role membership. This may or may not be put to final poll before being enacted –- we have tended to put team membership/role changes to a poll in the past, but it remains ultimately at the discretion of the formal team/organization members how to undertake this process.

Likewise, a similar process may be undertaken to remove/reduce team membership, or to reverse role adoption, either at the request of the person wishing to leave a given team or role (in which case this is granted, no consensus needed), or at the decision of the rest of the formal team/organization members, on at least a loose consensus basis.

## Organizational Structure

This section defines the teams and roles of the Pulsar-Edit organization.

### GitHub

Our primary (and currently only) official organization on any [“code forge”]( https://en.wikipedia.org/wiki/Forge_(software)) site is the [Pulsar-Edit organization](https://github.com/pulsar-edit) on GitHub.
To run this effectively, we have a number of sub-teams to perform various duties across our various repositories and other areas contained on the site.

#### Admin team (Including “Owners”) **_\[editor's note - Any reason to mention Owners specifically? Any info we should highlight about this role, if so? I don't think this would be  a separate permissions tier if GitHub didn't make it one. It has no special significance other than how sensitive the perms/access is for it?\]_**
Responsible for GitHub organization-wide duties such as:
- Team and role administration
- Repository configuration & administration
- Management of organization-wide permissions and settings

#### Sub-Teams (Members)

Able to actively maintain the repositories which are linked to their respective team(s).
- Reviewing and merging PRs
- Triaging issues
- Maintaining project boards
- Publishing branches, tags, and releases, managing feature rollouts
- Communicating with other members
- Coordinating work with/across other repositories/sub-projects of the organization, as need may be

Admin members may also implicitly share in all of the above responsibilities.

Organization members may be assigned to more than one team.

The current teams on GitHub are as follows:
- **Core** - works on the Main part of our editor
- **Backend** - API and server Development
- **Documentation** - Website and Documentation team
- **Packages** - Works on our core packages **_\[editor’s note – obsolete/not actively in-use?\]_**

### Discord

Our Discord server is one of two preferred communication methods for team conversations and decision-making, more or less on equal footing with the code forge site (GitHub).
We define a number of official roles on here (as well as community ones) to make sure that administration and moderation requirements are met. These roles on the Discord server do not necessarily overlap with or imply roles or permissions on the code forge (GitHub) organization.

#### Admins

Responsible for overall configuration and maintenance of the Discord server.
- Creating, editing, removing channels
- Administrating roles and members
- Maintaining bot and app integrations
- Kicking/Banning users that break our rules and guidelines and code of conduct.

#### Moderators

Responsible for the day to day moderation of the Discord server and community interactions.
- Ensuring civil discourse is taking place and taking action (warning users etc.)
- De-escalating any situations or heated conversations

#### Community roles

Community roles can be self-granted via the `#role-select` channel.
These members are people who are who are interested in or actively participate within the Pulsar community. Just as for anyone else on the Discord server, these members are expected to adhere to our code of conduct. Otherwise, there are no official or specific responsibilities associated with these roles, but anyone granting themselves these roles should be aware that they may be pinged (`@mentioned`) on the given topic that the role relates to.
These roles are designed to help people get updates and communicate within the specific areas of the project that they are interested in.
Formal Pulsar GitHub org members will also tend to be part of these groups, but their roles on the Discord server may not entirely correlate to the memberships and responsibilities granted in the GitHub sub-teams.

Thes roles on the Discord server are (at the time this document was writen/last updated):

##### Core teams
- Core - works on code bundled with the editor
  - (some overlap with backend, especially on the [ppm](https://github.com/pulsar-edit/ppm) repository)
- Backend - API and server Development
  - (some overlap with core where core code interacts with the backend, including but not limited to [ppm](https://github.com/pulsar-edit/ppm) repo.)
- Documentation - Website and Documentation team
- Packages - Works on our core packages **_\[editor’s note – defunct/disused role?\]_**
- Developer - Just fills in anywhere that they want

##### Operating Systems
- Linux
- MacOS
- Windows

Users with these roles use the respective operating system(s), and may be pinged (`@mentioned`) for input on topics affecting the respective operating system(s) from time to time.

##### Other roles
- Community Packages - join if you're into making packages for the editor
- Updates - Join this if you're interested in receiving updates as they come out

## Team member & role additions/removals

Team/role administration and membership decision making is mostly covered by our [Policies](https://github.com/pulsar-edit/.github/blob/main/POLICY.md) but this section details the criteria and justifications for adding or removing team members and/or roles.

### Adding members/roles

Adding team members is performed in much the same way as any other decision (see [Policies](https://github.com/pulsar-edit/.github/blob/main/POLICY.md)) by proposals being made to add somebody to a team or role and a vote then taking place on that proposal.
If the vote passes without any significant disagreements then the member can be added to the relevant team or role.
There is no strict set of criteria for addition but generally people who are active in the community and project for an extended period of time, have contributed and added value, and share in the organization's goals & vision can be considered.

### Removing members/roles

Team membership/role removal is not an action that the organization wants to perform in an ideal circumstances but this is something we do require some reference for so that people do not feel unfairly treated.
There are a number of circumstances where this might need to be performed and this section outlines (non-exhaustively) those reasons and justifications.**_\[editor’s note: The granting of permissions implies ability for them to be removed. Hopefully with no fuss or drama -- I feel it is a given that team members will try to be mature and act with respect, especially given our code(s) of conduct. This intro may add more drama than it helpfully addresses, IMO, so I would suggest removing it. Otherwise, please avoid a too apologetic or indirect tone and use a direct/firm, if still empathic or "considered" tone.\]_**

- **Removal requests**: If a member simply asks to be removed from a team or role for any reason, then this should be done as they wish, with no votes required.

- **Inactivity**: If a member of a team or role becomes inactive for an extended period of time (3+ months) without any justification or conversation then removal may be required. The member should be first contacted by a another team member and, depending on the outcome, it should then be brought up and voted on as with any other decision. If the vote passes then the member will be removed from these various roles and teams. This vote may be to remove a person entirely or it may be to move to a role with fewer privileges but remain within the organization. **_\[editor’s note: consensus on this? One last push to nail down an inactivity-removal policy? Or drop it from the document if we can’t all get behind any specific, real policy we will _actually_ follow.\]_**

-  **Misuse of privileges, negligence of duties or policy/code of conduct breaking**: If a member of a team or role is found to be misusing privileges granted to them or is found to have broken our policies, guidelines, rules or code of conduct then this may be grounds for removal of privileges or team/role membership. In serious cases it might be that we need to remove these privileges instantly in the case where it is believed that harm may come to the organization or project but these can be re-instated after discussion and voting if that is the outcome.

## Changes to this Document

This document may need to be updated from time to time, to reflect changes in the wishes of team members with regards to how best to run the organization/communications platform(s) it uses over time. **_\[editor’s note, regarding paragraph/section deleted in this commit: Too meta? Should be covered in POLICY.md already? IDK.\]_**

## Other roles and responsibilities

Not every single role or responsibility has been detailed in this document. Some responsibilities are handled as and when required and to the person or people most suited for it.
Such areas include access details and administration of various tools and services used by the organization, social media account access, fund/donation access and expenses approval and organization secrets access.
In order to preserve flexibility, these areas may be handled case-by-case, on at least a loose consensus basis among formal team/organization members, where possible. Improvisation may be necessary, and those entrusted with responsibility are asked to use it wisely, and indeed, “responsibly.” If such an arrangement needs to be modified, we will do our best to do so in an orderly manner that is agreeable to the most parties.

~~The above policies regarding adding or removing people to these specific privileges still apply.~~[**_\[editor’s note: If we have delegated something to someone with which we have only limited contact, such as with the Chocolatey or Flatpak packaging, can we really vote to remove them, when they are self-managing? Or more to the point, _would we_ vote on this? In the past we haven’t handled any of this with votes. We have liaised with these folks with a very loose and informal way, as suits their limited time/availability to coordinate, limited organization level/formality of their “commitment” as such, and working mostly outside our teams structure, other than implicitly there being a general established respectful working relationship, and, as much as anyone, abiding by our codes of conduct. Likewise, we haven’t really ever put perms management on these outside-coordinated responsibilities to a vote, at most we have discussed it in #team chat and formed as much of a loose “do-ocracy”, reasonable-amount-of-time-allowing consensus as could be marshalled.\]_**
