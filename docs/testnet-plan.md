# NeuroSentinel Minimal Testnet Plan

## Purpose

This document outlines the design of the first NeuroSentinel test network (testnet) to validate the hybrid consensus model.

The testnet will demonstrate:

- Proof of Intelligence (PoI)
- Proof of Trust (PoT)
- Validator selection
- Trust and intelligence scoring

---

## Testnet Goals

- Validate consensus logic
- Simulate AI agent participation
- Test trust and intelligence scoring
- Identify edge cases and attack scenarios

---

## Network Size (MVP)

Initial testnet will run with:

- 3–5 validator nodes
- Simulated AI agents
- Local network environment

---

## Node Roles

### Validators
- Perform PoI tasks
- Verify peer results
- Propose and validate blocks

### AI Agents (Simulated)
- Submit task results
- Build trust and intelligence scores

---

## Testnet Workflow

1. Network starts with equal trust and intelligence scores.
2. PoI tasks are assigned to validators.
3. Validators submit results.
4. Peers verify correctness.
5. Trust and intelligence scores are updated.
6. Validator selection algorithm determines next proposer.
7. Blocks are finalized.

---

## Example Scenario

- Node A receives classification task.
- Node A submits correct result.
- Nodes B and C verify correctness.
- Node A trust + intelligence increase.
- Node A becomes next validator.

---

## Failure Scenarios to Test

- Incorrect task submission
- Validator inactivity
- Conflicting verification results
- Trust score decay over time

---

## Metrics to Observe

- Block finalization time
- Score distribution fairness
- Resistance to dishonest nodes
- Validator rotation patterns

---

## Future Testnet Phases

- Larger validator sets
- Real AI task integration
- Network latency simulation
- Adversarial testing
