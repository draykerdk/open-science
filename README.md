# Open science & health

> Research people can examine, with care centred on the person.

Open Science explores how Dk could support research and health through traceable methods, authorised data use and findings that others can examine.

The proposed path connects consent, data provenance, analysis and review, keeping research claims distinguishable from validated applications.

The aim is broadly accessible scientific progress and human flourishing. Each application must establish its own evidence, safeguards and practical limits.

**Autonomous Health** is the health system this work is meant to build: an artificial intelligence health system integrated with each person’s [UID](https://uid.drayker.org), [personal Dk](https://personal.drayker.org), personal Dknowledge and devices, with clinics run with artificial intelligence. Patterns that may be connected to a condition with sufficient probability are investigated, so besides saving lives it improves the multifactor detection of every kind of condition. A diagnostic intelligence learns from every examination, a treatment intelligence draws on the whole body of studies and learns from outcomes, and the person’s Dk follows their health over time, for prevention and for personalised, accessible treatment. Clinics and doctors take part through their own registered identities. The data belongs to the person, and consent stays specific and revocable. For every active member, Autonomous Health is the form the common floor takes in health ([Distributed Support](https://support.drayker.org)). None of this operates today.

## A practical example

A study could publish its method and limitations while protecting participant data and recording which uses each participant authorised. This is an illustration of the proposed design.

## The problem it addresses

Research depends on reliable evidence and responsible access to data. Health applications also require consent and careful evaluation of their effect on people.

## Where this stands

The current synthesis of [Autonomous Health](https://dknowledge.drayker.org/papers/main-projects/ecosystem/autonomous-health) and the [order in which it can be built](https://dknowledge.drayker.org/roadmap/main-projects/ecosystem/autonomous-health-roadmap) are published, each stage with an exit condition. What is still open is which part of open science comes first and how DFM review relates to peer review; anyone who works in either field is better placed to write that than we are.

The internal assessment is deliberately severe, and it belongs in public: this is conceptual and high-risk work. There is no clinical protocol, no validation, no dataset, no device, no regulatory approval and no safety evidence — not held back, simply absent. Treat every description here as a research direction, and nothing as a capability.

This repository develops the proposal through public documentation and review. The capabilities described here still require specifications, worked examples and implementation.

## Scope

- Applications on the Dk kernel
- Identity through UID, and consent as the entry condition
- Professional review alongside AI diagnosis and monitoring
- DFM review alongside peer review
- Data that belongs to the person
- Data, processing and records distributed across the network rather than held by one operator, with provenance kept in [Dknowledge](https://dknowledge.drayker.org)

## Not in scope

- A medical service, a diagnosis, a treatment recommendation or advice of any kind today.
- Eugenic optimization, genetic caste stratification, or biological discrimination of any kind.
- A claim that any research or health application is running.
- Any handling of real patient data.

## Commitments

Research and care on Dk follow three commitments: care continues after an intervention; those who live with a condition take part in the process; and results stay recorded, even when they contradict the initial promise. The same capacity is meant to sustain research on neglected diseases, the ones the market leaves aside, and to widen access to treatment.

A study may keep an unvalidated technique unpublished, but its purpose, the resources it commits, the conditions of data use and its criterion for stopping are open from the first day to those who oversee it. A request beyond the authorised scope (a finer location than the one participants agreed to, for instance) is refused at once, with the reason recorded and visible to oversight; widening it takes a new authorisation from the participants.

## How it fits the whole

The first domain Dk is meant to serve — the reason the infrastructure exists, and the test of whether it can be trusted with a life.

Open science is an application on [Dk](https://dk.drayker.org): AI diagnosis and monitoring run on the intelligence, with professional review. Identity through [UID](https://uid.drayker.org) and consent are the entry condition — the data belongs to the person, not to the institution holding the record. Evidence and papers stay traceable in [Dknowledge](https://dknowledge.drayker.org), reviewed alongside [DFM](https://dfmp.drayker.org). The clinics and laboratories of the [stations](https://stations.drayker.org) are where the same work meets the physical world. It sits at the end of the chain that starts with a delivered function. Without a domain it visibly serves, the rest would be engineering for its own sake.

**Relations.** An application on Dk · identity through UID · review alongside DFM.

**Depends on.** `dk` · `uid` · `dfmp`

## First functions

These are concrete and unclaimed. Any of them can be opened as an issue and delivered
by one person.

1. A small first function that one person can deliver today: pick one non-clinical
   research question and demonstrate only search, explanation or organization of
   evidence, on synthetic data, with specialist review. The order of the larger stages,
   starting with a first AI-run clinic, is in the
   [roadmap](https://dknowledge.drayker.org/roadmap/main-projects/ecosystem/autonomous-health-roadmap).
2. Write what open science on Dk would have to guarantee.
3. Write where the professional review sits, and what it may override.
4. Compare DFM review with peer review honestly.

## How to contribute

Read [CONTRIBUTING.md](https://github.com/draykerdk/.github/blob/master/CONTRIBUTING.md)
and [GOVERNANCE.md](https://github.com/draykerdk/.github/blob/master/GOVERNANCE.md) in
`draykerdk/.github`. In short: open or find an issue, say in the thread that you are taking
it, branch as `fn/<issue-number>-<short-name>`, and open a pull request against
`master`. There is no separate review branch.

Participation is voluntary and implies no compensation, employment or future claim.

## Sources of truth

- This repository, for what Open science & health is and is not.
- [`.drayker/component.yml`](https://github.com/draykerdk/open-science/blob/master/.drayker/component.yml) — the machine-readable contract,
  validated on every pull request.
- [drayker.org/project/openscience/](https://drayker.org/project/openscience/) — the same record
  inside the portal, with the live board.
- [drayker.com/project/openscience/](https://drayker.com/project/openscience/) — the case for it,
  in plain terms.

---

Part of [Drayker](https://drayker.org) · content under CC BY 4.0
