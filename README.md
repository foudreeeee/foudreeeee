# foudreeeee

Security researcher, offensive-leaning. I break things, trace the bug to root cause, write it up. Mostly bug bounty and LLM/sandbox security right now.

### Recent work

- **Grok sandbox (xAI)** — took the "Computer" agent sandbox apart from the inside. Root container in a per-session VM; I mapped what holds (cross-user isolation) and what breaks (readable session secrets, an unauthenticated local tool server, the host kernel sitting in a known-vuln window). Reported to the vendor — the full writeup goes public once it's patched.
- **[SlopGuard](https://github.com/foudreeeee/SlopGuard)** — triage layer for maintainers drowning in AI-generated vuln reports. Static checks first (does the cited file, line, symbol even exist?), then a grounded LLM pass that can only downgrade a report, never invent one. The tool never closes anything on its own.
- **Bug bounty** — HackerOne, mostly authorization and business-logic bugs in real apps.
- **[writeups](https://github.com/foudreeeee/writeups)** — Hack The Box and CTF, full chains from recon to root.
- **[elastic-siem-mini-soc](https://github.com/foudreeeee/elastic-siem-mini-soc)** — stood up a small SOC on Elastic to see detection from the other side.

I can read a codebase to find where a bug actually lives, and follow it down into the container or kernel it runs on.

**Reach for:** Python, Burp, Linux.
