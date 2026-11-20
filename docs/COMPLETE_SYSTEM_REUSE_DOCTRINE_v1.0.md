# Complete-System Deployment Doctrine — v1.0

**Canonical rule: REUSE THE SYSTEM, NOT THE COMPONENTS.**

| Field | Value |
| --- | --- |
| Doctrine ID | PPSAI-CSD-001 |
| Version | 1.0 |
| Status | CANONICAL / FROZEN |
| Ratified | 2026-11-19 |
| Governing authority | Pro Prime Series AI LLC, acting through its authorized system owner |
| Scope | Every host deployment of A.I.M.S. and/or the Vault Logic System |

## Article I — Authoritative Explanation

The following paragraph is the canonical deployment explanation and must be preserved verbatim when quoted as doctrine:

> **A.I.M.S. and the Vault Logic System are complete reusable systems. They are not shared services, frameworks, utilities, or collections of reusable components. When adopted by a host, they are deployed as whole systems whose architecture remains intact. The host may rename content, vaults, records, datasets, directories, and classifications to fit the deployment. The host may not redefine the architecture by extracting selected portions and presenting the result as the original system. Reuse occurs through complete-system adoption, not component-level reconstruction.**

**Memorable principle: Reuse the system, not the components.**

- **Vault Logic:** A complete logic-management system reused intact across products. The host changes its logic and naming, not its architecture.
- **A.I.M.S.:** A complete memory-management system reused intact across products. The host changes its knowledge and naming, not its architecture.
- **HARO:** Receives its own complete A.I.M.S. deployment and its own complete Vault Logic System deployment, rather than consuming a single shared instance serving unrelated products.

## Article II — What Complete-System Reuse Means

1. **Architecture is invariant.** All established architectural responsibilities, internal relationships, lifecycle behaviors, integrity mechanisms, and functional contracts are preserved.
2. **Deployment is per host.** Each adopting product receives its own complete deployment and data domain. A shared central A.I.M.S. or shared central Vault Logic instance serving all products is not the prescribed integration pattern.
3. **Content is host-specific.** Each deployment may have different rules, evidence, datasets, stored records, metadata, classifications, configuration values, operational context, and display labels.
4. **Host naming is adaptable.** Titles, host-owned storage directories, data filenames, database namespaces, vault names, collections, and record labels may reflect HARO, ORBOT, VIV, or another product.
5. **The complete system remains recognizable.** New host naming must not be used to conceal removal or reconstruction of required architectural components.
6. **Co-deployment does not imply absorption.** When a host adopts both systems, they are independent, complete sibling subsystems connected by explicit contracts. One is not reduced to a feature of the other.

A complete system may be packaged as a process, package, service, or deployable unit inside its particular host without making it a *single shared cross-product service*. Deployment topology is separate from the requirement for an independently owned full instance per host.

## Article III — Two Prohibited Misinterpretations

### A. Shared-service substitution is not the doctrine

**Incorrect:** Application A, B, and C all send their independent memory or logic to one centrally shared instance, with no complete host-owned deployments.

**Correct:** Each product owns its own complete A.I.M.S. and/or Vault Logic deployment and its corresponding data and configuration. Any later inter-product communication is a separately authorized integration, not a reason to collapse deployments.

### B. Component-level reconstruction is not the doctrine

**Incorrect:** Copy only an index, ledger, graph, memory cache, rule evaluator, or glyph file; modify selected pieces; call the result A.I.M.S. or the Vault Logic System.

**Correct:** Adopt the complete architecture. Reuse its existing implementation and interfaces. Customize the host-facing names, datasets, rules, vault contents, records, and configuration without removing or redesigning the system.

No host may describe a selectively extracted subset as a conformant deployment of the complete original system.

## Article IV — Vault Logic System Identity

The **Vault Logic System** is a reusable logic-management architecture. Its established design includes configuration, host-defined logic vaults and their rules, evaluation/resolution mechanisms, glyph tracing, its own memory matrix, telemetry, interfaces, tests, and supporting utilities.

- Logic vaults contain domain-specific rules, conditions, classifications, and supporting material.
- The evaluation engine applies the relevant logic and returns traceable results.
- Glyph traces provide observable markers for evaluation paths and decisions.
- The native memory matrix preserves its defined place in Vault Logic; it is not removed because A.I.M.S. is present.
- Telemetry reports operational behavior, events, and available diagnostic evidence.
- The host retains authority for external action or enforcement.

The host may rename the deployment **HARO Vault Logic System**, **VIV Vault Logic System**, **ORBOT Vault Logic System**, or another host-appropriate title. Its content may concern resource eligibility, relationships, communications, cognition, or other domains. **The underlying system design remains unchanged.**

The template repository may contain illustrative or placeholder code; this doctrine fixes design intent and deployment boundaries, not unverified claims of implementation readiness.

## Article V — A.I.M.S. Identity

**A.I.M.S. — Agnostic Immutable Memory System** is a reusable memory-management architecture. Its established design includes Short-Term Memory, append-only Long-Term Memory, an immutable evidence Vault, A Priori and A Posteriori knowledge, derived persistent indexes, Structured Knowledge Graphs, retrieval records, integrity mechanisms, and provenance.

- Short-Term Memory handles transient working context under its defined retention rules.
- Long-Term Memory and the evidence Vault preserve the history of committed observations, claims, changes, and relationships.
- A Priori and A Posteriori distinguish the origins and roles of knowledge.
- Derived indexes and graphs make evidence searchable and support current interpretation without rewriting history.
- The Retrieval Ledger preserves evidence of what was retrieved and returned.
- Integrity mechanisms protect the consistency and provenance of retained records.

The host may label its deployment **HARO A.I.M.S.**, **VIV A.I.M.S.**, **ORBOT A.I.M.S.**, or another host-appropriate title. Its stored knowledge and operational history can be entirely different between products. **A.I.M.S.' architecture remains unchanged.**

A.I.M.S.' **immutable evidence Vault** is not the same construct as the Vault Logic System's **logic vaults**. A.I.M.S.' integrity **Glyphs** are not interchangeable with Vault Logic's visual evaluation-trace **glyphs**.

The A.I.M.S. repository's published release-status and hardening contracts remain authoritative for implementation maturity. This doctrine does not elevate prototype capabilities to production claims.

## Article VI — Storage, Filesystem, and Database Naming

The allowed adaptation surface is the host-specific *identity and content of what is stored*. Examples include:

- Product-specific root data directories and display titles.
- Database names and tenant/host namespaces.
- Host-domain vault names, classifications, record types, collections, datasets, matrix identifiers, and data filenames.
- Rule content, knowledge content, telemetry content, policies supplied by the host, and configuration values supported by the installed version.

This rule does **not** authorize arbitrary renaming of internal source-code modules, import paths, canonical schema fields, integrity keys, historical identifiers, ledger event structures, or implementation dependencies.

When a filesystem or database rename affects references, schemas, hashes, manifests, imports, or persisted records, it requires an explicit compatibility-preserving migration with verification. **Host identity changes; architecture and evidence integrity do not.**

## Article VII — Host Examples

```text
HARO/
├── HARO-AIMS/                 # complete host-owned A.I.M.S. deployment
├── HARO-Vault-Logic-System/   # complete host-owned logic deployment
├── Scheduler/
├── Resolver/
├── Adapters/
└── Control-Center/

VIV/
├── VIV-AIMS/                  # complete host-owned A.I.M.S. deployment
├── VIV-Vault-Logic-System/    # complete host-owned logic deployment
├── Dossiers/
├── Relationships/
└── Communications/

ORBOT/
├── ORBOT-AIMS/                # complete host-owned A.I.M.S. deployment
├── ORBOT-Vault-Logic-System/  # complete host-owned logic deployment
├── CALI/
├── Cognition/
└── Governance/
```

**These trees illustrate the deployment doctrine and naming scheme, not verified current repository directory layouts or instructions to rename existing production paths.**

In HARO, host-specific A.I.M.S. content may include workload history, measured resource use, capacity profiles, admission decisions, scheduler outcomes, and recovery evidence. Its host-specific Vault Logic content may include capability constraints, scheduling rules, residency conditions, and recovery logic. Neither example changes the complete-system requirement.

## Article VIII — Authority, Evidence, and Isolation

- A.I.M.S. remembers and retrieves evidence. Remembered success is not current authorization.
- Vault Logic evaluates host-defined logic. An evaluation is not itself permission to perform arbitrary external actions.
- Each deployment maintains independent data ownership and appropriate host/tenant isolation.
- Any cross-product sharing, aggregation, synchronization, or communication requires an explicit authorization and data-flow contract. It must not silently convert complete host-owned deployments into a single shared service.
- History informs host decisions, but current applicable permissions, policies, and measured operational state retain their authority.
- The host may use both systems together, but neither absorbs or replaces the other.

## Article IX — Deployment Acceptance and Conformance

A complete-system adoption is conformant only when review demonstrates:

1. The complete architectural responsibilities are preserved; no selected subset is masquerading as the whole system.
2. Each host has its own independently identified deployment, lifecycle, and storage domain.
3. Host-specific naming and content changes are documented and do not silently change internal semantics.
4. Existing API, memory, evaluation, integrity, retrieval, and telemetry contracts remain compatible with their source architecture.
5. Persisted data and all applicable integrity references survive supported migrations and restarts.
6. Integration between A.I.M.S., Vault Logic, and the host occurs through explicit boundaries and does not collapse their responsibilities.
7. Tests demonstrate the actual supported behavior. Documentation or a directory tree alone is insufficient to prove runtime completeness.
8. Any deviation from this doctrine is recorded as a proposed architectural amendment, **not** introduced as an undocumented convenience refactor.

## Article X — Freeze, Integrity, and Amendment Procedure

**Version 1.0 is a frozen design-intent baseline.**

- The exact UTF-8 bytes of this document are hashed using SHA-256.
- The expected SHA-256 digest is stored **outside this document** in its adjacent `COMPLETE_SYSTEM_REUSE_DOCTRINE_v1.0.sha256` file and repeated in each host README. The checksum is external to avoid a self-referential hash.
- Both reference repositories carry **identical canonical text** and must have the same digest.
- The v1.0 file must not be silently rewritten after ratification. Changes require a new explicitly identified version (for example, v1.1), a dated amendment rationale, owner approval, impact review, and a new checksum.
- Older versions and their recorded hashes remain available for verification and historical reconstruction.
- A hash detects content changes; **a hash alone does not prevent someone with repository write access from replacing both file and hash**. Enforced immutability requires independent protected references, signed attestations, or equivalent access controls.

**Canonical closing rule: Reuse the system, not the components. Same architecture; host-specific names, content, and deployment.**
