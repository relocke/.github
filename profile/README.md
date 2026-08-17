# ReLocke

## Infrastructure for open economic systems shared by humans and machines

ReLocke is building an interoperability and development layer for fragmented
blockchain communities. It gives users, developers, applications, LLMs, and
autonomous agents a common way to understand, build, authorize, and interact
with smart-contract systems across WAX, XPR Network, Vaulta, and Telos.

Our aim is to create a nexus where developers, communities, machines,
investors, and traditional and onchain financial systems can test competing
ideas in public. Economic and governance structures should be visible,
executable, measurable, and forkable—so their benefits can be demonstrated,
their weaknesses exposed, and better systems developed.

It is a place to reimagine money, value, authority, and institutional design as
systems that can be built, deployed, observed, challenged, and improved—not
only debated in theory.

Capital can provide soft power by supporting useful infrastructure and ideas.
Communities retain the freedom to disagree, fork, and leave. ReLocke preserves
the interface between them.

> **Decentralization creates fragmentation. ReLocke makes fragmentation
> interoperable.**

```mermaid
flowchart LR
    H["Humans"] --> R["ReLocke nexus"]
    M["Machines and LLMs"] --> R
    D["Developers and communities"] --> R
    F["Traditional and onchain finance"] --> R

    R --> B["Build and document"]
    R --> T["Test and compare"]
    R --> G["Govern and fund"]
    R --> I["Interoperate and fork"]

    B --> N["WAX · XPR · Vaulta · Telos"]
    T --> N
    G --> N
    I --> N
```

## Technology built

| Technology | Purpose |
| --- | --- |
| **ReLocke web portal** | A common interface for accounts, permissions, contracts, tables, actions, documentation, signing, and deployment. |
| **ReLockeQL** | Reads live contract ABIs and generates GraphQL queries and mutations through a shared multi-chain API. |
| **Agentic ABI** | Extends the executable ABI with contract intent, permissions, risks, side effects, provenance, versions, and context that people and machines can understand. |
| **Ricardian contract interface** | Displays human-readable contractual terms beside the executable smart-contract interface. Legal effect depends on the relevant agreement and law. |
| **CDT compiler endpoint** | A Vercel backend that accepts C++ contract source and returns compiled WASM and ABI artifacts for browser review. |
| **Client-authorized deployment** | Deploys reviewed WASM and ABI artifacts using the permissions and signatures of the selected blockchain account. |
| **WebAuthn and K1 signing** | Supports Antelope WebAuthn/WA and secp256k1/K1 authorization paths. |
| **Multi-chain infrastructure** | Provides load-balanced access to WAX, XPR Network, Vaulta, and Telos while keeping each network's identity and governance explicit. |

## What comes next

ReLocke intends to connect multilingual LLM assistance to this existing stack.
A person or community could describe an application, treasury, financial
system, permission model, or governance structure in a familiar language. The
result would be translated into reviewable specifications, Ricardian terms,
contract source, permissions, tests, simulations, and deployable artifacts.

Natural language will remain an authoring interface—not runtime truth.
Generated systems must be reviewed, compiled, tested, simulated, and explicitly
authorized before they control real authority or assets.

## Explore

- [ReLocke](https://relocke.io)
- [ReLocke concept paper](../WHITEPAPER.md)
- [ReLockeQL](https://github.com/pur3miish/ReLockeQL)
- [Agentic ABI](https://github.com/relocke/agentic-abi)
- [ReLocke Wallet](https://github.com/relocke/relocke-wallet)
- [WASM secp256k1](https://github.com/relocke/wasm-secp256k1)

RLOC Capital is a separate proposed capital-allocation structure. It is not a
current investment offering. Its legal, securities, custody, tax, governance,
and accounting architecture must be established independently from ReLocke's
public technology documentation.
