# Validator Selection — NeuroSentinel MVP

## Purpose

This document defines how validators are selected to propose and confirm blocks in NeuroSentinel.

Validator selection is based on a hybrid score combining intelligence and trust.

---

## Validator Score

Each validator has a score:

Validator Score = Intelligence Score × Trust Score

This ensures validators are both capable and reliable.

---

## Selection Process

1. All active validators are ranked by Validator Score.
2. The validator with the highest score is selected to propose the next block.
3. A random subset of other validators is selected to verify the block.

---

## Tie-Breaking

If multiple validators have equal scores:

- Prefer the validator with higher trust score.
- If still tied, select randomly.

---

## Verification Committee

A small group of validators is randomly selected to verify:

- block validity
- task correctness
- score updates

Majority agreement finalizes the block.

---

## Score Updates After Validation

After each block:

- Correct validators gain trust and intelligence.
- Incorrect validators lose trust and intelligence.
- Non-participating validators may lose trust.

---

## Security Considerations

- Random committee selection prevents collusion.
- Trust penalties discourage dishonest behavior.
- Reputation decay prevents long-term inactivity abuse.

---

## Future Enhancements

- Weighted random selection
- Byzantine Fault Tolerance (BFT) finality
- Reputation-based committee sizing
