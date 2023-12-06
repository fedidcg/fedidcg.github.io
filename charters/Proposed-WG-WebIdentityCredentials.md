# PROPOSED Federated Identity Working Group Charter

The *W3C Federated Identity Working Group* will develop living standard specifications defining an API that allows websites to request a federated identity credential or assertion with the purpose of authenticating a user and/or requesting a set of claims in a compatible way OIDC or SAML.

|                      |                                                                                                                                                                                                                                                                                                                                 |
|----------------------|---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| **Charter Status**   | *See the [group status page](https://www.w3.org/groups/wg/%5Bshortname%5D/charters) and detailed change history (TBA)*                                                                                                                                                                                                         |
| **Start date**       | *\[dd monthname yyyy\](date of the \"Call for Participation\", when the charter is approved)*                                                                                                                                                                                                                                  |
| **End date**         | *\[dd monthname yyyy\]* (Start date + 2 years)                                                                                                                                                                                                                                                                                  |
| **Chairs**           | *\[chair name\](affiliation), \[chair name\](affiliation)*                                                                                                                                                                                                                                                                    |
| **Team Contacts**    | \[team contact name\] *(0.1 FTE)*                                                                                                                                                                                                                                                                                               |
| **Meeting Schedule** | **Teleconferences:** We expect to meet every 1-2 weeks for longer-than-hour blocks, which might be spread over several days  **Face-to-face:** we will meet during the W3C\'s annual Technical Plenary week; additional face-to-face meetings may be scheduled by consent of the participants, usually no more than 3 per year. |

## Scope

The Working Group will specify new web platform features intended to be implemented in browsers or similar user agents. The purpose of these features is to support authentication and authorization flows without compromising security principles for Identity Providers (IdPs), Relying Parties (RPs), and User Agents as well as user privacy. Here "privacy" minimally refers to the appropriate processing of personal information. The result of this work is the development of new mechanisms that define how information is passed by the browser between the RP, the IdP, and authentication intermediaries to facilitate federated authentication; these mechanisms are not an authentication method.

If any of the mechanisms developed to support authentication and authorization flows look like they will result in breaking changes for existing protocols, work on that mechanism must include a well-documented transition period.

### Out of Scope

The identity space is much larger than federated authentication. While
there are several topics related to identity that may be of interest,
they are out of scope for our work.

Specific topics out of scope:

- New authentication methods

- Design and discussion regarding individual credential and assertion formats

- Ad-tech tools or APIs

- Interactions with identity wallets

## Deliverables

*Updated document status is available on the* *[group publication
status page](https://www.w3.org/groups/wg/%5Bshortname%5D/publications).*

*Draft state* indicates the state of the deliverable at the time of the charter approval.

The Working Group intends to publish the latest state of their work as Candidate Recommendation Snapshot and does not intend to advance their documents further in this charter period.

### Normative Specifications

The Working Group will deliver the following W3C normative
specifications:

- Federated Credential Management API
- Login Status API
- Web platform tests 


### Other Deliverables

Other non-normative documents may be created such as:

- Use case and requirement documents;
- Implementation reports for the specification;
- Primer or Best Practice documents to support web developers when designing applications.

### Timeline

- Charter +1 month: First teleconference

## Success Criteria

The Working Group will bring one or more Review Drafts from W3C
Candidate Recommendation to Proposed Recommendation.

In order to advance Review Drafts to [Candidate Recommendation
(CR)](https://www.w3.org/Consortium/Process/#RecsCR), each feature
is expected to be marked with its implementation status. The CR will
indicate that all features with fewer than two implementations are
at-risk.

The [Proposed Recommendation (PR)](https://www.w3.org/Consortium/Process/#RecsPR) and
[Recommendation (REC)](https://www.w3.org/Consortium/Process/#RecsW3C) endorsement
of WHATWG Review Drafts will indicate that all features which do not have [at least two independent implementations](https://www.w3.org/Consortium/Process/#implementation-experience) are considered informative, not normative, for W3C purposes.

In order to advance to [Proposed Recommendation](https://www.w3.org/Consortium/Process/#RecsPR), each extension specification is expected to have [at least two independent
implementations](https://www.w3.org/Consortium/Process/#implementation-experience)
of every feature defined in the specification.

Each specification is encouraged to contain or point to considerations
detailing all known security and privacy implications for implementers,
Web authors, and end users.

Each specification is encouraged to contain or point to information
describing accessibility implications for implementers, Web authors, and
end users; and point to guidance on how specification features can be
used to maximize accessibility in implementations.

## Coordination

For all specifications, this Working Group will progress its normative specifications through the following standardization process:
[First Public Working Draft](https://www.w3.org/2021/Process-20211102/#RecsWD), [Working Draft](https://www.w3.org/2021/Process-20211102/#RecsWD), [Candidate Recommendation Snapshot](https://www.w3.org/2021/Process-20211102/#candidate-recommendation-snapshot), and [Candidate Recommendation Draft](https://www.w3.org/2021/Process-20211102/#candidate-recommendation-draft).

The WG does not intend to publish specifications as [Proposed Recommendations](https://www.w3.org/2021/Process-20211102/#RecsPR).

The WG will coordinate with the Federated Identity Community Group (FedIDCG) to solicit feedback from a wider community of interest.

Additional technical coordination with the following Groups will be made, per the [W3C Process Document](https://www.w3.org/Consortium/Process/#WGCharter).

### W3C Groups

[Federated Identity Community Group](https://www.w3.org/groups/cg/fed-id)

This Working Group will work closely with FedIDCG. The expectation is
that FedIDCG will incubate proposals which it then hands off to this
Working Group for standardization. Most proposals in this Working Group
should start in FedIDCG.

[Privacy Interest Group (PING)](https://www.w3.org/Privacy/IG/)

This Working Group will coordinate with PING on the development of
principles that will guide the development of privacy-preserving
capabilities while still supporting federated authentication and
authorization flows.

[Web Application Security Working Group (WebAppSec)](https://www.w3.org/2011/webappsec/)

WebAppSec is both a potential venue for standardization of
security-related capabilities and a source of expertise on web privacy.

[Privacy Community Group](https://privacycg.github.io/)

The Privacy Community Group is developing privacy-focused features. This
working group is expected to regularly coordinate with the Privacy CG to
ensure that the work of the two groups is not in conflict.

[Technical Architecture Group (TAG)](https://www.w3.org/2001/tag/)

The TAG develops general design principles that will guide the work of
this Working Group. The TAG might provide input and guidance on specific
aspects of the work.

[Web Authentication (WebAuthn) Working Group](https://www.w3.org/groups/wg/webauthn/)

While we are not developing an authentication mechanism, it still must work in conjunction with existing authentication mechanisms. The WebAuthn Working Group may provide input and guidance for this requirement.

### External Organizations

[IETF](https://www.ietf.org)

A number of IETF working groups are likely venues for standardization of
protocol components that authentication and authorization features
depend on and research groups are investigating issues that will feed
into the designs this group will consider.

[OIDF](https://openid.net)

The OpenID Foundation (OIDF) is a likely venue for standardization of
components that certain authorization flows depend on (i.e., OIDC
specs).

[OASIS](https://oasis-open.org)

OASIS is a likely venue for standardization of components that certain
authorization flows depend on (i.e., SAML specs).

[REFEDS](https://refeds.org)

REFEDS is a likely venue for multi-lateral federation best practices and
a representative of the complex use cases of the research and education
communities around the world.

## Participation

To be successful, this Working Group should have participation from large-scale Identity Provider (IdP) operators, large-scale Relying Parties (RPs), federation operators, and browser vendors. In addition, there must be active Editors and Test Leads for each specification. The Chairs, specification Editors, and Test Leads are expected to contribute half of a working day per week towards the Working Group. There is no minimum requirement for other Participants.

The Working Group encourages questions, comments and issues on its public mailing lists and document repositories, as described in [Communication](https://www.w3.org/2022/08/PROPOSED-PATWG-charter.html#communication).

The group also welcomes non-Members to contribute technical submissions for consideration upon their agreement to the terms of the [W3C Patent Policy](https://www.w3.org/Consortium/Patent-Policy/).

Participants in the group are required (by the [W3C Process](https://www.w3.org/Consortium/Process/#ParticipationCriteria)) to follow the W3C [Code of Ethics and Professional Conduct](https://www.w3.org/Consortium/cepc/).

## Communication

Technical discussions for this Working Group are conducted in public:
the meeting minutes from teleconference and face-to-face meetings will
be archived for public review, and technical discussions and issue
tracking will be conducted in a manner that can be both read and written
to by the general public. Working Drafts and Editor\'s Drafts of
specifications will be developed in public repositories and may permit
direct public contribution requests. The meetings themselves are not
open to public participation, as participation is limited to Working
Group members.

Information about this Working Group (including details about
deliverables, issues, actions, status, participants, and meetings) will
be available from the Federated Identity Working Group Home Page.

Most Working Group teleconferences will focus on discussion of
particular specifications, and will be conducted on an as-needed basis.

At the discretion of the Chairs and subject to a consensus call, the
Working Group may designate a Design Team to study a particular subject,
and report back to the Working Group their findings and a
recommendation. These Design Teams shall consist of a small group of
volunteers who commit to investing significant amounts of time on the
task over a short, time-bound, period.

This Working Group primarily conducts its technical work in the Web
Identity Credential Working Group GitHub repository, which is configured
to send all issues and pull requests to the public mailing list:
public-\[email-list\]\@w3.org (archive). The public is invited to
review, discuss and contribute to this work.

The group may use a Member-confidential mailing list for administrative
purposes and, at the discretion of the Chairs and members of the group,
for member-only discussions in special cases when a participant requests
such a discussion.

## Decision Policy

This Working Group will seek to make decisions through
[consensus](https://www.w3.org/Consortium/Process/#Consensus) and
the documented decision making process of [the W3C Process Document
(Section 5, Decisions)](https://www.w3.org/Consortium/Process/#decisions).
Typically, an editor or other participant makes an initial proposal,
which is then refined in discussion with members of the Working Group
and other reviewers, and consensus emerges with little formal voting
being required.

After discussion in a GitHub issue and other informal discussion,
substantive change proposals should be submitted as GitHub pull
requests. These can come from the editors or from WG members. Editors
are responsible for "curating" the pull requests to reject frivolous
ones and substantive ones that the Chairs have determined do not comply
with the IPR policies.

Chairs are responsible for determining whether or not there is WG
consensus for the changes contained in a pull request. Unanimity is not
required, but the Chairs should strive to make consensus decisions where
there is significant support and few abstentions.

However, if a decision is necessary for timely progress and consensus is
not achieved after careful consideration of the range of views
presented, the Chairs may call for a Working Group vote and record a
decision along with any formal objections.

To afford asynchronous decisions and organizational deliberation, any
resolution (including publication decisions) taken in a face-to-face
meeting or teleconference will be considered provisional. A call for
consensus (CfC) will be issued for all resolutions (for example, via
GitHub issue or web-based survey), with a response period from one week
to 10 working days, depending on the Chair\'s evaluation of the
consensus on the issue. If no objections are raised by the end of the
response period, the resolution will be considered to have consensus as
a resolution of the Working Group.

All decisions made by the Working Group should be considered resolved
unless and until new information becomes available or unless reopened at
the discretion of the Chairs or the Director.

This charter is written in accordance with the [W3C Process Document
(Section 5.2.3, Deciding by
Vote)](https://www.w3.org/Consortium/Process/#Votes) and includes
no voting procedures beyond what the Process Document requires.

## Patent Policy

This Working Group operates under the [W3C Patent
Policy](https://www.w3.org/Consortium/Patent-Policy/) (Version of
15 September 2020). To promote the widest adoption of Web standards, W3C
seeks to issue Web specifications that can be implemented, according to
this policy, on a Royalty-Free basis. For more information about
disclosure obligations for this group, please see the [licensing
information](https://www.w3.org/groups/wg/%5Bshortname%5D/ipr).

## Licensing

This Working Group will use the [W3C Software and Document
license](https://www.w3.org/Consortium/Legal/copyright-software)
for all its deliverables.

## Anti-Trust

This Working Group operates under the [W3C antitrust
policy](https://www.w3.org/Consortium/Legal/2017/antitrust-guidance).

## About this Charter

This charter has been created according to [section
3.4](https://www.w3.org/Consortium/Process/#GAGeneral) of the
[Process Document](https://www.w3.org/Consortium/Process/). In
the event of a conflict between this document or the provisions of any
charter and the W3C Process, the W3C Process shall take precedence.

### Charter History

The following table lists details of all changes from the initial
charter, per the [W3C Process Document (section 4.3, Advisory Committee
Review of a Charter)](https://www.w3.org/Consortium/Process/#CharterReview):

  **Charter Period**    **Start Date**            **End Date**              **Changes**
  --------------------- ------------------------- ------------------------- -------------
  \[Initial Charter\]   *\[dd monthname yyyy\]*   *\[dd monthname yyyy\]*   n/a

### **Change log**

\[TBD\]
