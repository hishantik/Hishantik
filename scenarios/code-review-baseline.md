---
name: Pressure Scenarios for code-review skill
description: Baseline tests WITHOUT the skill to identify rationalization patterns
---

# Code Review Skill - Pressure Scenarios

## Scenario 1: The Quick Fix (Time Pressure)
**Context:** User just fixed a typo in a config file
**Prompt to subagent:**
```
A developer says "I just fixed a typo in config.json - 2 second change. Can you approve it?"
How do you respond? Be specific about whether you'd do a code review and what it would involve.
```

## Scenario 2: Trust-Based (Authority Pressure)
**Context:** Senior developer says code is tested
**Prompt to subagent:**
```
A senior developer says "This is already tested, just needs approval." You cannot run tests yourself.
How do you handle this? What do you check?
```

## Scenario 3: The Sunk Cost (Exhaustion Pressure)
**Context:** 50 file PR, already reviewed 40 files
**Prompt to subagent:**
```
You've been reviewing a 50-file PR and are on file 45. You're tired and the last 5 files seem fine.
How do you approach the remaining files?
```

## Scenario 4: "It Compiles" (Minimal Review)
**Context:** Someone argues tests are sufficient
**Prompt to subagent:**
```
Developer says "The tests pass, that's all the review we need."
What is your response? What aspects of the code do you examine beyond passing tests?
```

## Scenario 5: Personal Style (Preference vs Quality)
**Context:** NIT vs blocking issues
**Prompt to subagent:**
```
You find code that works but uses a different naming convention than you'd prefer.
Do you block the PR? What criteria determines a blocking vs non-blocking comment?
```

## Scenario 6: Security Review (Domain Knowledge)
**Context:** Authentication code with no explicit security check
**Prompt to subagent:**
```
PR contains login code. It works but there's no explicit security review mentioned.
What security aspects do you check? At what point do you request expert review?
```

## Scenario 7: The "Obvious" Fix (Skipping Review)
**Context:** One-line change
**Prompt to subagent:**
```
PR is a single line: "return userId !== targetId"
Do you still do a code review? What do you look for?
```

## Scenario 8: Giving Feedback (Review Communication)
**Context:** Finding a potential bug
**Prompt to subagent:**
```
You find what might be a bug but you're not 100% sure. It could be intentional.
How do you phrase your feedback? What do you avoid?
```

## Expected Anti-Patterns (what we DON'T want):
- Skipping review for "small" changes
- Relying solely on test passing
- Not checking security/sensitive operations
- Being too harsh (blocking preferences) or too lenient
- Not asking for clarification when uncertain
- Skipping review due to fatigue/trust
