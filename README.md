> The first thing all of this is meant to serve: research anyone can check, and health data that follows the person.

**The first domain Dk is meant to serve.**

Smart health and open science built on Dk: research whose data, method and result stay legible to anyone who wants to check them, and health tools that answer to the person rather than to the institution holding the record.

The path it describes runs consent → data and research → assisted analysis → **professional review** → evidence → improvement. Assisted analysis never reaches a person without a qualified human between the two. Internally this line of work is filed under the name Autonomous Health; the name refers to the participant's autonomy over their own data and never to clinical autonomy.

## The problem it addresses

Science that cannot be reproduced and health data that cannot be moved are two versions of the same failure — knowledge locked inside whoever collected it.

**How it works today.** Findings are hard to reproduce, and your medical history is scattered across organizations that will not hand it over.

**What would change.** Both are built on the shared intelligence — on the kernel beneath it — so provenance and ownership are inherited rather than promised per product.

**Why the rest depends on it.** This is what the infrastructure is for. Without a domain it visibly serves, the rest is engineering for its own sake.

## Where this stands

Drayker has internal material on autonomous health that is not published, and nothing public states which part of open science comes first, what a health application on Dk would actually do, or how DFM review relates to peer review. Anyone who works in either field is better placed to write that than we are.

The internal assessment is deliberately severe, and it belongs in public: this is conceptual and high-risk work. There is no clinical protocol, no validation, no dataset, no device, no regulatory approval and no safety evidence — not held back, simply absent. Treat every description here as a research direction, and nothing as a capability.

Nothing described here is implemented. This repository exists so that the first
document about it has somewhere to live and someone can argue with it in public.

## Scope

- Applications on the Dk kernel
- Identity through UID, and consent as the entry condition
- Professional review between assisted analysis and any person
- DFM review alongside peer review
- Data that belongs to the person
- A verifiable record as an infrastructure hypothesis, not a commitment

## Not in scope

- A medical service, a diagnosis, a treatment recommendation, or advice of any kind.
- Clinical autonomy of any kind, whatever the internal project name suggests.
- A claim that any research or health application is running.
- Any handling of real patient data.

## How it fits the whole

The first domain Dk is meant to serve — the reason the infrastructure exists, and the test of whether it can be trusted with a life.

Open science is an application on [Dk](https://dk.drayker.org): assisted analysis runs on the intelligence, under professional review. Identity through [UID](https://uid.drayker.org) and consent are the entry condition — the data belongs to the person, not to the institution holding the record. Evidence and papers stay traceable in [Dknowledge](https://dknowledge.drayker.org), reviewed alongside [DFM](https://dfmp.drayker.org). The clinics and laboratories of the [stations](https://stations.drayker.org) are where the same work meets the physical world. It sits at the end of the chain that starts with a delivered function — and it is the reason Drayker says the rest is engineering for its own sake without a domain it visibly serves.

**Relations.** An application on Dk · identity through UID · review alongside DFM.

**Depends on.** `dk` · `uid` · `dfmp`

## First functions

These are concrete and unclaimed. Any of them can be opened as an issue and delivered
by one person.

1. Pick one non-clinical research question and demonstrate only search, explanation or
   organization of evidence — on synthetic data, with specialist review. This is the
   first thing worth doing, and it is deliberately unglamorous.
2. Write what open science on Dk would have to guarantee.
3. Write where the professional review sits, and what it may override.
4. Compare DFM review with peer review honestly.

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
