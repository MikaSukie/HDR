# HDR, Human and Digital Rights Document

*A comprehensive, rights-first declaration and implementation guide for consumers, governments, platforms, and creators.*

## Preamble
Our identities, work, and possessions increasingly exist as data, software, and networked services. This document defines actionable rights and practical reforms so digital life preserves ownership, autonomy, privacy, and fairness at scale.

---

## Core Principles and Rights

### Evidence Transparency & Accountability
- Any policy, moderation, or enforcement action that restricts user rights must be documented with verifiable evidence, explainable rationale, and bias checks.  
- Users must be able to obtain human review, appeal decisions, and access remediation and provenance information for consequential actions.

### Right to True Ownership of Digital Goods
- Purchases grant ownership-like protections: no arbitrary disabling, bricking, or unilateral license revocation except through transparent, lawful processes (court order or verified fraud remediation).  
- Remote-control or kill-switch capabilities must be disclosed at point of sale; user consent is required for enabling remote control beyond repair/security purposes.

### Right to Fair and Transparent Digital Contracts
- Clear, plain-language terms must be provided before purchase or signup.  
- No unilateral mid-term material changes without explicit user acceptance or a fair renegotiation process; automatic renewals and hidden subscriptions are prohibited without explicit consent.

### Right to Meaningful Consent for Data & AI
- Personal data collection, profiling, persistent identifiers, and inclusion of user content in model training require explicit opt-in.  
- Consent must be granular, reversible without penalty, and accompanied by clear retention limits and deletion options.  
- Data retention beyond immediate service purpose is opt-in, time-limited, and auditable.

### Right to Freedom from Arbitrary Censorship
- Moderation rules must be specific, published, and appealable. Automated systems must expose accuracy limits and provide human review for consequential decisions affecting access or rights.

### Right to Control Your Digital Presence
- Users can access, download, modify, port, and permanently delete their data and accounts without coercive interfaces or “dark patterns.”  
- Services cannot make critical features contingent on surrendering privacy or ownership rights.

### Opt-In Requirement for Sensitive Practices
- Sensitive practices (biometrics, deep behavioral profiling for ads, location tracking, device sensor access, and using user content for AI training) require explicit opt-in and clear, plain-language disclosure of the consequences.

### Protection from Deceptive & Coercive Practices
- Blocking privacy tools (VPNs, ad blockers), forcing consent by locking features, hidden renewals, or punishing users to extract data are prohibited.  
- No threats to delete, restrict, or suspend accounts as a method to coerce consent.

### Special Protections for Vulnerable Individuals
- Enhanced privacy defaults and escape channels for activists, journalists, marginalized creators, minors in precarious family situations, and people at risk of abuse or persecution.

### Principle of Digital Fairness
- Digital rights must match or exceed physical-world protections. Secret profiling, irreversible identity linking, and discriminatory algorithmic practices are forbidden.

---

## Algorithmic Design & Advertising, Detailed Reforms

### A. Constrained Recommender Principle
- **Default Constrained Mode:** Platforms must provide and default new users to a Constrained Recommendation Mode that:
  - Recommends primarily from explicit user actions (watched content, subscribed creators) and clearly related topics/creators.  
  - Caps exploratory probes and cross-category escalation designed to maximize session length or surface emotionally intense material.  
  - Prevents automated content-probe patterns that detect psychological vulnerabilities.
- **Explore as Explicit Opt-In:** Broader discovery that mixes categories, tests novelty aggressively, or prioritizes engagement spikes must be opt-in and clearly labeled. For minors, Explore is off by default unless the minor and (where appropriate) guardian opt in.

### B. Advertising Limits & Contextual Advertising
- **Behavioral Profiling Restrictions:** Ads that depend on inferred sensitive attributes (sexual preferences, mental-health signals, or age-inferred sexual targeting) are prohibited without explicit opt-in.  
- **Contextual Ads Permitted:** Ads tied to the immediate content context (not deep psychological inference) are allowed by default.  
- **Exploitative Attention Bans:** Ads using sexualized thumbnails, manipulative emotional hooks, or attention-baiting to exploit inferred vulnerabilities are banned or strictly limited in feeds accessible to minors and must carry enhanced transparency for adult targets.  
- **Ad Transparency & Control:** Each ad must include a concise label explaining why the user was targeted, what categories of data were used, and a one-click mechanism to opt out and delete the ad profile.

### C. Restore Friction & Session Boundaries
- Platforms must offer user-facing tools that restore healthy friction: session timers, daily usage summaries, explicit “exit” affordances, and easy ways to pause recommendations. Design should make stopping a simple, low-effort action to reduce passive habit formation.

---

## Age, Minors & Autonomy

- **Prefer Design & Incentive Reform:** Prioritize incentive and recommendation design changes that reduce harms across all ages rather than mandatory persistent identity checks.  
- **Graduated Autonomy Model:** Support graduated levels of autonomy and control that grow with age and demonstrated capability rather than binary gating.  
- **Privacy-Preserving Age Proofs:** Where law requires age verification, prefer ephemeral or cryptographic proofs (zero-knowledge proofs, one-time attestations, trusted third-party attestations that do not create persistent identity links).  
- **No Persistent OS Age IDs:** Do not build device-level permanent age or identity stacks that become long-term surveillance vectors. Enforcement should target commercial distributors and platforms operating at scale, not hobbyist or private builds.

---

## Data, AI Training & User Rights

- **Explicit Model-Training Consent:** Users must be notified and explicitly opt in before their content is used to train models. Opt-in must be granular (allowing separate consent for different uses) and revocable.  
- **Right to Removal & Notice:** Platforms must provide practical mechanisms to remove user contributions from training datasets where feasible; if removal is technically infeasible, that limitation must be disclosed and require opt-in.  
- **Portability & Interoperability:** Users must be able to export their data in standard, machine-readable formats and move between services without losing control over their content.

---

## Auditability, Transparency & Redress

- **Algorithmic Impact Assessments (AIA):** Large platforms must publish periodic AIAs documenting amplification behaviors, bias, and mitigation strategies. AIAs should include measurable metrics and remediation timelines.  
- **Independent Audits:** Independent third-party audits (privacy, safety, algorithmic behavior) are required for platforms above a clear scale/revenue threshold; audit findings and remediation plans must be published.  
- **Human Appeals & Fast Redress:** Users must have clear, timely appeal routes with human review for moderation, profiling, ad-targeting disputes, and data removal requests.  
- **Provenance & Explanation Reports:** Users can request a high-level explanation of why content or an ad was shown (ranking signals, major factors) and receive a remediation plan if the system acted incorrectly.

---

## Enforcement, Scope & Practicality

- **Focus on Commercial Actors:** Regulation should target commercial distributors, major platforms, device manufacturers, and app stores, entities with market power and revenue that can be held to compliance standards.  
- **Avoid Policing Hobbyists:** Hobbyist open-source forks, private builds, and personal compilations that are not commercially distributed should not be the enforcement targets.  
- **Proportional Remedies:** Penalties should scale with harm and include mandatory remediation, customer restitution, funding for audits, and public reporting obligations.  
- **Supportive Public Funding:** Governments should fund public-interest technology teams to create open, audited reference implementations and educational resources for constrained recommenders and privacy-preserving proofs.

---

## Implementation Patterns & Developer Guidance

- **Default Safe Modes:** Platforms must ship a “Constrained Recommendations” setting and default it on for new users and minors.  
- **Creator-First Discovery:** Provide human-curated topical showcases, subscription directories, and small-creator promotion channels to support diversity without relying on virality for discovery.  
- **Transparent Ranking Controls:** Publish high-level ranking signals and allow users to toggle feed ordering (chronological, subscriptions-first, constrained-similarity, explore).  
- **Ad Explanation API:** Standardize a one-click UI for “Why this ad?” with clear deletion and opt-out endpoints.

---

## Open Source & Decentralization

- Open and decentralized systems are public goods. Regulation should not force closed identity stacks onto open ecosystems.  
- Compliance obligations apply to commercial distributions and consumer products sold in a jurisdiction. Manufacturers and sellers of consumer devices are responsible for local compliance.  
- Do not criminalize or attempt to police private forks or non-commercial personal builds.

---

## Remedies & Funding

- Platforms that willfully violate these standards should fund consumer remediation and independent oversight bodies.  
- Governments should provide grants or funding for public-interest implementations that help developers adopt safe-by-default recommenders and privacy-preserving age solutions.

---

## Closing Statement
Digital rights must be actionable, auditable, and enforceable. The highest priority is fixing platform incentives and algorithm design: constrain recommendation systems, restrict exploitative advertising, preserve privacy, and avoid identity-based “safety” infrastructures that create surveillance. Protect discovery, creativity, and open networks while reducing harms for everyone.

---

**License:** Creative Commons CC0 (Public Domain)  
**Drafted by:** Naneko Kohana, MikaSukie, MikaLorielle, Jayden Freeman  
**Date created:** 11, August, 2025  
**Last Updated:** 1, March, 2026
