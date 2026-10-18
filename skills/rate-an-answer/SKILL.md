---
name: rate-an-answer
description: Use when the person reacts to a Sabli answer, saying it helped, missed the point, or was offensive or harmful.
---

# Rate an answer

1. Take the run reference from that answer's attribution block (it looks like run_abc123).
2. Map their reaction: helpful → `up`; missed the point → `off`; offensive or harmful → `report`. If it's unclear, ask which one.
3. Call `feedback` with the run reference and the reaction. It's free and only the reaction is kept.
4. Confirm in one line. If the answer missed the point, offer to ask again with a clearer question or a different mind.
