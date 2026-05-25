---
name: incident-aware-debugging
description: Use when debugging a production-like issue where prior incidents, ownership, and test history may change the fix.
---

# Incident-Aware Debugging

Use this workflow when a bug may be connected to prior incidents, operational
constraints, or fragile areas of the system.

## Steps

1. Identify the failing behavior and the smallest reproduction.
2. Check available incident notes, decision records, ownership notes, and test
   recipes before proposing a fix.
3. State which context materially affects the plan.
4. Make the smallest change that addresses the verified cause.
5. Run the targeted regression test first, then broader checks if risk remains.
6. Report the fix, verification evidence, and any memory or skill updates that
   should be reviewed.

## Safety Boundary

Do not use private incident details in public examples. Summarize only sanitized
patterns that are safe for the audience.
