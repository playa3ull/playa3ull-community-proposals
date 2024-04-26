<div align="center" style="padding-top: 128px">
  <img src="LOGO.png">
</div>

## What is a PLAYA3ULL Community Proposal (PCP)?

A PLAYA3ULL Community Proposal is a concise document that introduces a change or best practice for adoption on the [PLAYA3ULL GAMES Ecosystem](https://playa3ull.games).
PCPs should provide clear technical specifications of any proposals and a compelling rationale for their adoption.

PCPs are an open framework for proposing improvements and gathering consensus around changes to the PLAYA3ULL GAMES Ecosystem.
PCPs can be proposed by anyone and will be merged into this repository as long as they are well-formatted and coherent.

PLAYA3ULL GAMES may, from time to time, recommend specific PCPs that it believes benefit the PLAYA3ULL GAMES Ecosystem/Community.
PLAYA3ULL GAMES recommendation is not binding and is made without representations, warranties or guarantees of any kind.

## PCP Tracks
There are three kinds of PCP

### `Standards Track`
PCP describes a change, addition or removal to the design or function of the PLAYA3ULL GAMES Ecosystem

<details>
    <summary>Example</summary>
    Changes to the PLAYA3ULL GAMES Avalanche Subnet, Subnet architecture, Decentralized network or any change/addition that affects the interoperability within the PLAYA3ULL GAMES Ecosystem.
</details>

### `Best Practices Track`
PCP describes a design pattern or common interface that should be used across the PLAYA3ULL GAMES Ecosystem to make it easier to integrate with PLAYA3ULL GAMES Ecosystem.

<details>
    <summary>Example</summary>
    Proposing a smart contract interface, SDKs, APIs, not proposing a change to how smart contracts are executed.
</details>

### `Meta Track`
PCP describes a change to the PCP process or suggests a new way for the PLAYA3ULL GAMES Community to collaborate.

<details>
    <summary>Example</summary>
    Changes to the PCP process, PCP repository, or PCP workflow.
</details>

## PCP Statuses
There are four statuses of a PCP:

### `Proposed`
PCP has been merged into the main branch of the PCP repository. It is actively being discussed by the PLAYA3ULL GAMES Community and may be modified based on feedback.

### `Implementable`
PCP is considered "ready for implementation" by the author(s) and will no longer change meaningfully from its current form (which would require a new PCP).

### `Active`
PCP has been activated within the PLAYA3ULL GAMES Ecosystem. Once a PCP is Activated, it is locked.

### `Stale`
PCP has been abandoned by its author(s) because it is not supported by the PLAYA3ULL GAMES, or the PLAYA3ULL GAMES Community or has been replaced with another PCP.

## PCP Workflow

0. Think of a Novel Improvement to PLAYA3ULL GAMES
    <details>
      <summary>Details</summary>
      The PCP process begins with a new idea for PLAYA3ULL GAMES. Each potential PCP must have an author(s): someone who writes the PCP using the style and format described below, shepherds the associated GitHub Discussion, and attempts to build consensus around the idea. Note that ideas and any resulting PCP is public. Authors should not post any ideas or anything in a PCP that the Author wants to keep confidential or to keep ownership rights in (such as intellectual property rights).
    </details>
1. Post Your Idea to [GitHub Discussions](https://github.com/playa3ull/playa3ull-community-proposals/discussions/categories/ideas)
    <details>
      <summary>Details</summary>
      The author(s) should first attempt to ascertain whether there is support for their idea by posting in the "Ideas" category of GitHub Discussions.
      Vetting an idea publicly before going as far as writing a PCP is meant to save both the potential author(s) and the wider PLAYA3ULL GAMES Community time.
      Asking the PLAYA3ULL GAMES Community first if an idea is original helps prevent too much time being spent on something that is guaranteed to be rejected based on prior discussions (searching the Internet does not always do the trick).
      It also helps to make sure the idea is applicable to the entire community and not just the author(s).
      
      Small enhancements or patches often don't need standardization between multiple projects; these don't need a PCP and should be injected into the relevant development workflow.
    </details>
2. Propose a PCP via [Pull Request](https://github.com/playa3ull/playa3ull-community-proposals/pulls)
    <details>
      <summary>Details</summary>
      Once the author(s) feels confident that an idea has a decent chance of acceptance, a PCP should be drafted and submitted as a pull request (PR).
      This draft must be written in PCP style as described below. It is highly recommended that a single PCP contain a single key proposal or new idea.
      The more focused the PCP, the more successful it tends to be. If in doubt, split your PCP into several well-focused ones.
      The PR number of the PCP will become its assigned number.
    </details>

3. Build Consensus on [GitHub Discussions](https://github.com/playa3ull/playa3ull-community-proposals/discussions/categories/discussion) and Provide an Implementation (if Applicable)
    <details>
      <summary>Details</summary>
      PCPs will be merged by PCP maintainers if the proposal is generally well-formatted and coherent.
      PCP editors will attempt to merge anything worthy of discussion, regardless of feasibility or complexity, that is not a duplicate or incomplete.
      After a PCP is merged, an official GitHub Discussion will be opened for the PCP and linked to the proposal for community discussion.
      It is recommended for author(s) or supportive PLAYA3ULL GAMES Community members to post an accompanying non-technical overview of their PCP for general consumption in this GitHub Discussion.
      The PCP should be reviewed and broadly supported before a reference implementation is started, again to avoid wasting the author(s) and the PLAYA3ULL GAMES Community's time, unless a reference implementation will aid people in studying the PCP.
    </details>
4. Mark PCP as `Implementable` via [Pull Request](https://github.com/playa3ull/playa3ull-community-proposals/pulls)
    <details>
      <summary>Details</summary>
      Once a PCP is considered complete by the author(s), it should be marked as `Implementable`.
      At this point, all open questions should be addressed and an associated reference implementation should be provided (if applicable).
      As mentioned earlier, the PLAYA3ULL GAMES meets periodically to recommend the ratification of specific PCPs but it is ultimately up to members of the PLAYA3ULL GAMES/PLAYA3ULL GAMES Community to adopt PCPs.
    </details>

5. [Optional] Mark PCP as `Stale` via [Pull Request](https://github.com/playa3ull/playa3ull-community-proposals/pulls)
    <details>
      <summary>Details</summary>
      A PCP can be superseded by a different PCP, rendering the original obsolete.
      If this occurs, the original PCP will be marked as `Stale`. PCPs may also be marked as `Stale` if the author(s) abandon work on it for a prolonged period of time (12+ months).
      PCPs may be reopened and moved back to `Proposed` if the author(s) restart work.
    </details>


## What belongs in a successful PCP?

Use the format in [TEMPLATE.md](./PCPs/TEMPLATE.md)

### Auxiliary Files

PCPs may include auxiliary files such as diagrams. Image files should be included in a subdirectory for that PCP.
Auxiliary files must be named `PCP-XXXX-Y.ext`, where "XXXX" is the PCP number, "Y" is a serial number (starting at 1), and "ext" is replaced by the actual file extension (e.g. "png").

### Waived Copyright

PCP authors **must** waive any copyright claims before a PCP will be merged into the repository.
This can be done by including the following text in a PCP:

```text
## Copyright

Copyright and related rights waived via [CC0](https://creativecommons.org/publicdomain/zero/1.0/).
```

## Proposals

_You can view the status of each PCP on the [PCP Tracker](https://github.com/orgs/playa3ull/projects/3)._

| Number | Title | Author(s) | Type |
| :----- | :---- | :-------- | :--- |

## Contributing

Before contributing to PCPs, please read the [PCP Terms of Contribution](./CONTRIBUTING.md).

## Credit
[Avalanche Foundation - ACPs](https://github.com/avalanche-foundation/ACPs)
