# ApeLevel — Public Technical Advisories

**We build on blockchain. We also believe we have a responsibility to speak up when something deserves scrutiny.**

As trusted blockchain developers, ApeLevel’s responsibility extends beyond delivering code. When we identify confusing interfaces, questionable practices, or potential risks to users, we believe those concerns should be disclosed—even when our conclusions are unpopular or our opinions are dismissed.

This repository makes our technical advisories, investigations, and recommendations available for public review.

## Why We Publish

Users often make decisions through interfaces they cannot independently audit. A familiar logo, recognizable asset name, or polished application can create confidence without explaining the underlying risks.

Our work gives those concerns a public record, explains the evidence, and proposes practical improvements.

Respect for our opinion is optional. Our responsibility to communicate concerns is not.

## What You’ll Find Here

- Technical advisories about blockchain applications, wallets, assets, and infrastructure.
- Investigations into unexpected behaviour and potential user risks.
- Explanations of design choices, trust assumptions, and technical limitations.
- Recommendations for developers and service providers.
- Corrections and updates as further evidence becomes available.

## Our Approach

**Evidence before accusations.** We distinguish documented observations from interpretations, unresolved questions, and confirmed findings.

**Clear limits.** Screenshots, interface behaviour, and preliminary tests do not always establish a root cause. We identify what the available evidence can—and cannot—support.

**Practical recommendations.** Where possible, we explain how developers can address the concern.

**Public accountability.** Our findings are open to challenge. Credible technical evidence can change our conclusions, and material corrections should be recorded openly.

An advisory is not automatically a completed security audit. Each publication should be read according to its stated scope and evidence.

## Featured Advisory

### When ETH Isn’t What the Wallet Says It Is

This preliminary advisory examines conflicting asset information observed in a transaction workflow involving Base, including an “Ethereum” entry labelled “soETH,” a new-token warning, and an ERC-20-style explorer page associated with a native-ETH placeholder address.

It discusses:

- The differences between native ETH, canonical WETH, and third-party representations.
- Why asset names, symbols, and logos do not independently establish identity or redeemability.
- How clearer asset classification and network-aware search could reduce user confusion.

The observations do not establish theft, lost funds, or responsibility on the part of a particular provider. The cause of the conflicting label remains unconfirmed.

## Feedback and Corrections

Use this repository’s Issues tab to submit technical feedback, reproducible examples, or corrections. Identify the relevant publication and include supporting evidence wherever possible.

Do not publish private keys, seed phrases, credentials, or personal information. For an undisclosed vulnerability that could expose users to exploitation, arrange a private reporting channel before posting operational details publicly.

---

**ApeLevel — Blockchain Development & Technical Analysis**

Building responsibly includes speaking openly.
