> [!WARNING]
> **Work in progress.** ReLocke is an evolving Open Source Finance research and development project. Its governance models, fiscal structures, code, and documentation are experimental and should be independently reviewed and stress-tested before real-world use.

<div align="center">

<img src="https://avatars.githubusercontent.com/u/46915607?s=240&v=4" alt="ReLocke icon" width="120" height="120">

# ReLocke

### Open Source Finance for interoperable governance.

A shared platform for people and machines to design, model, challenge, and improve the fiscal systems that shape our world.

[Website](https://relocke.io) · [Manifesto](https://relocke.io/manifesto) · [Agentic ABI](https://github.com/relocke/agentic-abi)

</div>

---

ReLocke is building a central point for individuals, communities, developers, and autonomous systems to devise governance structures that can interoperate with traditional finance and decentralized networks.

We call this **Open Source Finance (OSF)**: financial and fiscal systems whose rules, incentives, assumptions, interfaces, and consequences can be inspected, discussed, tested, and improved in public. OSF combines open-source software with transparent governance and blockchain infrastructure so communities can coordinate resources without hiding the structures of power that shape their choices.

## Why ReLocke exists

Financial systems do more than move money. They define who can participate, what behavior is rewarded, where resources flow, which risks are ignored, and who has the power to change the rules.

ReLocke exists to make those structures explicit and testable. The platform is intended to help people:

- design governance and fiscal structures for communities, protocols, public goods, and sectors of the economy;
- connect traditional and decentralized financial systems without erasing the important differences between them;
- create incentive structures that align participation, contribution, risk, and long-term outcomes;
- model how governance decisions allocate capital, labor, attention, infrastructure, and other scarce resources;
- expose assumptions, concentrations of power, failure modes, and unintended behavioral incentives; and
- publish systems in forms that both people and machines can inspect and reason about.

## A platform for adversarial testing

Governance and financial structures should be challenged before their failures become embedded in production.

ReLocke aims to give users and machines a coherent environment for defining threat models and attack vectors against modeled systems. Participants should be able to stress-test governance capture, incentive manipulation, coordination failures, liquidity shocks, permission boundaries, resource-allocation assumptions, and other risks that conventional financial design often leaves implicit.

This work is about controlled, transparent, and ethical testing. The goal is to reveal weaknesses, document trade-offs, and improve resilience—not to exploit live financial systems or their participants.

## What belongs in ReLocke

| Area | What it explores |
| --- | --- |
| **Governance structures** | Decision rights, representation, delegation, voting, accountability, dispute resolution, and the ability to change rules. |
| **Fiscal systems** | Revenue, expenditure, treasury policy, public-goods funding, taxation, subsidies, issuance, and resource allocation. |
| **Incentive design** | How rewards, costs, access, reputation, ownership, and risk shape individual and collective behavior. |
| **Financial interoperability** | Interfaces between traditional finance, decentralized finance, institutions, communities, and chain-native assets. |
| **Adversarial models** | Threat models, attack vectors, simulations, stress tests, failure scenarios, and governance-capture analysis. |
| **Machine-readable institutions** | Open interfaces that let software agents inspect rules, explain consequences, and test proposals within explicit trust boundaries. |

## What this organization will contain

The ReLocke organization will collect and develop:

- governance and fiscal design ideas;
- open specifications and research notes;
- code examples, smart contracts, interfaces, and reference implementations;
- reusable incentive and resource-allocation structures;
- models connecting traditional and decentralized financial systems;
- adversarial scenarios and stress-testing methodologies;
- tools for explaining institutional rules and their side effects; and
- experiments that communities and developers can adapt to their own economic context.

The intention is not to prescribe one universal financial system. It is to make governance power, behavioral incentives, and fiscal consequences visible enough to be debated, compared, forked, and improved.

## Supported blockchains

ReLocke currently supports **WAX, Vaulta, XPR Network, XRP Ledger, and Jungle testnet**.

Each blockchain is handled through a ReLocke chain profile that respects its native account, contract, token, permission, and transaction model. Support for a chain does not imply that every chain implements governance or programmable assets in the same way.

## ReLockeQL

[**ReLockeQL**](https://github.com/pur3miish/ReLockeQL) is ReLocke's programmable data and transaction layer: an open-source GraphQL client and server library for querying accounts, contracts, tables, and chain history through one typed interface.

ReLockeQL helps developers and software agents work across configured ReLocke chain profiles while keeping endpoint selection, permissions, signing, and execution explicit. It can power applications, institutional interfaces, governance tools, simulations, and machine-readable financial workflows without hiding the chain-specific rules underneath them.

[Source](https://github.com/pur3miish/ReLockeQL) · [npm](https://www.npmjs.com/package/relockeql) · [Live GraphQL playground](https://relocke.io/api/playground)

## ReLocke Manifesto

The deeper philosophy, principles, and direction of Open Source Finance live in the [**ReLocke Manifesto**](https://relocke.io/manifesto).


---

<div align="center">
<sub>Financial systems should be open enough to inspect, coherent enough to test, and adaptable enough to serve the people who live with their consequences.</sub>
</div>
