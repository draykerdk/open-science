> Research people can examine, with care centred on the person.

Open Science explores how Dk could support research and health through traceable methods, authorised data use and findings that others can examine.

The proposed path connects consent, data provenance, analysis and review, keeping research claims distinguishable from validated applications.

The aim is broadly accessible scientific progress and human flourishing. Each application must establish its own evidence, safeguards and practical limits.

The internal name **Autonomous Health** refers to the person’s authority over bodily choices and data. Any future clinical use would require qualified professional review, with consent remaining specific and revocable.

## A practical example

A study could publish its method and limitations while protecting participant data and recording which uses each participant authorised. This is an illustration of the proposed design.

## The problem it addresses

Research depends on reliable evidence and responsible access to data. Health applications also require consent and careful evaluation of their effect on people.

## Where this stands

Drayker has internal material on autonomous health that is not published, and nothing public states which part of open science comes first, what a health application on Dk would actually do, or how DFM review relates to peer review. Anyone who works in either field is better placed to write that than we are.

The internal assessment is deliberately severe, and it belongs in public: this is conceptual and high-risk work. There is no clinical protocol, no validation, no dataset, no device, no regulatory approval and no safety evidence — not held back, simply absent. Treat every description here as a research direction, and nothing as a capability.

This repository develops the proposal through public documentation and review. The capabilities described here still require specifications, worked examples and implementation.

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
- Eugenic optimization, genetic caste stratification, or biological discrimination of any kind.
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
