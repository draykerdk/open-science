# Open science & health

> The first thing all of this is meant to serve: research anyone can check, and health data that follows the person.

**The first domain the kernel is meant to serve.**

Smart health and open science built on Dk: research whose data, method and result stay legible to anyone who wants to check them, and health tools that answer to the person rather than to the institution holding the record.

## The problem it addresses

Science that cannot be reproduced and health data that cannot be moved are two versions of the same failure — knowledge locked inside whoever collected it.

**How it works today.** Findings are hard to reproduce, and your medical history is scattered across organizations that will not hand it over.

**What would change.** Both are built on the shared kernel, so provenance and ownership are inherited rather than promised per product.

**Why the rest depends on it.** This is what the infrastructure is for. Without a domain it visibly serves, the rest is engineering for its own sake.

## Where this stands

Drayker has internal material on autonomous health that is not published, and nothing public states which part of open science comes first, what a health application on Dk would actually do, or how DFM review relates to peer review. Anyone who works in either field is better placed to write that than we are.

Nothing described here is implemented. This repository exists so that the first
document about it has somewhere to live and someone can argue with it in public.

## Scope

- Applications on the Dk kernel
- Identity through UID
- DFM review alongside peer review
- Data that belongs to the person

## Not in scope

- A medical service, a diagnosis, or advice of any kind.
- A claim that any research or health application is running.

## Role in the system

The first domain the kernel is meant to serve.

**Relations.** An application on Dk · identity through UID · review alongside DFM.

**Depends on.** `dk` · `uid` · `dfmp`

## First functions

These are concrete and unclaimed. Any of them can be opened as an issue and delivered
by one person.

1. Write what open science on Dk would have to guarantee.
2. Describe one health application worth building first.
3. Compare DFM review with peer review honestly.

## How to contribute

Read [CONTRIBUTING.md](https://github.com/draykerdk/.github/blob/master/CONTRIBUTING.md)
and [GOVERNANCE.md](https://github.com/draykerdk/.github/blob/master/GOVERNANCE.md) in
the organization. In short: open or find an issue, say in the thread that you are taking
it, branch as `fn/<issue-number>-<short-name>`, and open a pull request against
`master`. There is no separate review branch.

Participation is voluntary and implies no compensation, employment or future claim.

## Sources of truth

- This repository, for what Open science & health is and is not.
- [`.drayker/component.yml`](.drayker/component.yml) — the machine-readable contract,
  validated on every pull request.
- [drayker.org/project/openscience/](https://drayker.org/project/openscience/) — the same record
  inside the portal, with the live board.
- [drayker.com/project/openscience/](https://drayker.com/project/openscience/) — the case for it,
  in plain terms.

---

Part of [Drayker](https://drayker.org) · content under CC BY 4.0
