> [!WARNING]
> **Work in progress.** ReLocke is an active research and development project. Its software, governance models, financial structures, and documentation should be independently reviewed and stress-tested before production use.

<div align="center">

# ReLocke

### Making decentralized fragmentation interoperable.

ReLocke is building a persistent cross-chain interface where people and machines can discover, design, deploy, test, and connect economic and coordination systems across independently governed blockchains.

**Currently supporting WAX, XPR Network, Vaulta, and Telos.**

[Website](https://relocke.io) · [Documentation](https://relocke.io/docs) · [White paper](../WHITEPAPER.md) · [Build with us](https://github.com/relocke/.github/blob/main/CONTRIBUTING.md)

</div>

---

<div align="center">

## Why ReLocke exists

Decentralization naturally creates fragmentation. Communities disagree, blockchains evolve under different rules, developers fork software, and economic systems diverge. That freedom is essential, but fragmentation should not mean isolation. People, applications, and machines should be able to move between sovereign systems without losing the ability to understand, compare, or interact with them.

This is why ReLocke exists: to become a malleable, adaptable structure that can conform to the changing shapes of governance and economic systems. ReLocke provides an interoperability layer flexible enough to follow those changes while keeping independent systems discoverable, comparable, and usable through a common interface.

Through this interface, investors, communities, and institutions can help shape the financial and governance systems they want to support. They can describe rules, incentives, ownership, risk, permissions, and governance in natural language; translate those ideas into understandable, inspectable, and deployable systems; and model or stress-test them before committing capital or authority. This lowers the technical barrier without removing the need for independent review, testing, audit, and explicit authorization.

ReLocke assembles open-source technologies into a shared environment for developers, users, investors, institutions, and autonomous agents. Its continuity does not depend on any single community, company, foundation, organization, or blockchain. Capital can help shape useful technology through transparent allocation, while communities retain the freedom to experiment, compete, fork, and exit.

This is **Open Source Finance**: the architecture governing money, value, resources, incentives, and power should be open enough to inspect, coherent enough to test, and adaptable enough to improve.

</div>

## Technology

### [ReLockeQL](https://relocke.io/docs/relockeql-api-infrastructure)

ReLockeQL reads the published ABI of compatible smart contracts and exposes accounts, permissions, actions, tables, state, and transaction history through one typed GraphQL model. It gives developers, applications, LLMs, and users a consistent interface across WAX, XPR Network, Vaulta, and Telos while keeping the selected chain explicit.

The API can prepare typed mutations and compose ordered actions into one atomic transaction. The ReLocke GUI uses the same infrastructure so people can discover contracts, read ABI-derived documentation, query cross-chain state, and prepare actions without writing GraphQL by hand.

[Read the guide](https://relocke.io/docs/relockeql-api-infrastructure) · [Open the GraphQL playground](https://relocke.io/api/playground) · [API endpoint](https://relocke.io/api) · [Source](https://github.com/pur3miish/ReLockeQL)

### [Antelope WebAuthn](https://github.com/pur3miish/antelope-webauthn)

Antelope WebAuthn connects passkeys and platform authenticators to Antelope-compatible signatures. Private-key operations remain protected by the user's authenticator and local approval surface—such as biometrics, a device PIN, a TPM, secure enclave, or hardware security key—while public keys can be attached to on-chain account permissions.

WebAuthn is a W3C standard implemented across major browser and operating-system ecosystems, including Apple, Google, and Microsoft platforms. Some authenticators are device-bound; some passkeys may be securely synchronized by the user's platform provider. ReLocke preserves that distinction instead of claiming every credential is permanently tied to one physical device.

This creates a common approval experience across supported chains: ReLocke prepares an inspectable action, the user or investor reviews it, the authenticator approves it locally, and the selected network enforces its own on-chain permissions.

[How device-secured access works](https://relocke.io/docs/device-secured-digital-assets) · [Source](https://github.com/pur3miish/antelope-webauthn)

### [ReLocke Contract Console](https://relocke.io/docs/contract-console)

The Contract Console turns deployed smart contracts into a discoverable cross-chain workspace. Users can browse native, linked, or tracked contracts; inspect ABI and Agentic ABI documentation; query tables; assemble multi-contract action workflows; and review the chain, accounts, parameters, and permissions before signing.

It solves a basic accessibility problem: smart contracts should not be usable only by developers or machines that know a chain's RPC conventions. The same live contract surface can be explored through the GUI or consumed through ReLockeQL by applications and autonomous systems.

[Read the guide](https://relocke.io/docs/contract-console) · [Open the console](https://relocke.io/smart-contracts)

### [Agentic ABI](https://github.com/relocke/agentic-abi)

Agentic ABI enriches the executable ABI with structured contract identity, intent, permissions, risks, side effects, provenance, versions, icons, Ricardian terms, and human-readable context. People and machines can inspect the same model without confusing documentation with executable authority.

[Read the guide](https://relocke.io/docs/agentic-abi) · [Specification and tooling](https://github.com/relocke/agentic-abi)

### [Browser contract development](https://relocke.io/docs/native-antelope-smart-contracts)

ReLocke provides natural-language-assisted contract authoring and a serverless CDT compilation service. C++ source can be compiled in isolated disposable environments into reviewable WASM and ABI artifacts, then deployed client-side with the selected account's explicit authorization.

[Native contract guide](https://relocke.io/docs/native-antelope-smart-contracts)

---

<div align="center">

**WAX · XPR Network · Vaulta · Telos**

One interface for people and machines. Independent blockchains remain independent.

</div>
