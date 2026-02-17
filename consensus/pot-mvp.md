# Proof of Trust (PoT) — MVP Design  (Minimum Viable Protocol or Product)

## Purpose

Proof of Trust (PoT) measures the reliability and honesty of validators over time.

It ensures that only trustworthy nodes gain influence in block validation.

---

## MVP Goals

- Track validator reliability
- Penalize dishonest behavior
- Reward consistent correctness
- Prevent collusion

---

## Trust Score Overview

Each validator has a trust score that changes over time based on behavior.

Trust score increases when:
- results are verified as correct
- validator participates consistently
- peers confirm reliability

Trust score decreases when:
- incorrect results are submitted
- validator fails to respond
- malicious or suspicious behavior detected

---

## Trust Score Update Rules

### Increase Trust
- Correct task result verified by peers
- Timely participation in validation

### Decrease Trust
- Incorrect result submission
- Repeated non-participation
- Collusion signals (future detection)

---

## Trust Score Example

Validator A submits correct result → trust +2  
Validator A submits incorrect result → trust -5  
Validator A misses task → trust -1  

---

## Anti-Collusion Measures (MVP)

- Random validator assignment
- Independent verification groups
- Trust penalties for coordinated false results

---

## Role in Consensus

Validator selection depends on:

Validator Score = Intelligence Score × Trust Score

Low-trust validators lose influence even if intelligent.

---

## Security Considerations

- Trust decays slowly over inactivity
- Sudden trust spikes flagged for review
- Repeated dishonest behavior leads to exclusion

---

## Future Enhancements

- Graph-based trust analysis
- Reputation propagation
- AI-based anomaly detection
