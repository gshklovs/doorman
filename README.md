# Doorman

Your phone stays face-down. Doorman reads every incoming notification and decides:

- **Break through**: truly urgent (family calling twice, a 2FA code you asked for, a gate change).
- **Hold**: batched into a calm digest you open when *you* choose.
- **Drop**: marketing and engagement bait.

You pick up your phone a few times a day instead of ~96.

**Live demo:** https://doorman-dnd.vercel.app (open it on your phone)

How it works: on-device rules and a small classifier handle the obvious cases, and an LLM handles the ambiguous ones with a one-line reason for every verdict.

Built at the Do Not Disturb Hackathon x Phone Use, SF, 2026-11-13.
