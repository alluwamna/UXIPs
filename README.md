# UX Improvement Proposals (UXIPs)

This repository contains the official UX Improvement Proposals (UXIPs).

UXIPs define a structured, transparent process for proposing changes to the UX Protocol, documenting decisions, and building long term community consensus.

UXIPs are off chain governance documents. They describe what should change and why. Actual parameter changes or upgrades are executed separately through on chain governance proposals.

## Purpose

The UXIP process exists to:

- provide a clear and consistent proposal workflow
- document protocol changes in a durable, reviewable format
- ensure decisions align with the protocol’s core principles
- separate policy design (off chain) from execution (on chain)
- enable open community participation

## Repository Structure

/UXIPs  
uxip-0-process.md  
uxip-1-authoring-guidelines.md  
uxip-2-core-principles.md  
uxip-xxx-title.md  

/template  
uxip-template.md  

README.md

## Naming Convention

UXIP files use the format:

uxip-<number>-<short-slug>.md

Numbers are assigned by editors.  
Slugs are lowercase, hyphen separated, and descriptive.

## UXIP Lifecycle

1. Draft – Proposal is submitted as a pull request.  
2. Review – Community discussion and refinement.  
3. Final – Consensus reached, UXIP merged.  
4. Implemented – If needed, a separate on chain governance proposal executes the change.

UXIPs themselves do not modify the chain.

## Submitting a UXIP

1. Fork this repository.  
2. Copy the template from /template/uxip-template.md.  
3. Create a new file named uxip-xxx-title.md (editors assign the number).  
4. Submit a pull request.  
5. Participate in the discussion and refinement.

Anyone may propose a UXIP.

## Relationship to On Chain Governance

UXIPs define policy, rationale, and design. On chain proposals perform actual parameter changes.

Example:

A UXIP defines which pools should be wound down and why.  
A separate on chain proposal updates the pool parameters.

## Status

The initial priorities are:

UXIP‑0: Proposal process  
UXIP‑1: Authoring guidelines  
UXIP‑2: Core principles  

Once these are finalized, the community can begin submitting UXIPs for topics such as:

- liquid staking guidance (ETH, BTC, etc.)
- pool lifecycle and wind down criteria
- long term governance structure
