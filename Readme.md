# AISG — AI Security Scanner

AISG is a security scanner for the apps AI writes for you. It catches leaked keys, unsafe
patterns, and vulnerable dependencies **before your users do**.

- Website: https://aisg.web.id
- Free URL scan (no account): https://aisg.web.id/#free-scan
- How it works: https://aisg.web.id/how-it-works
- Blog (Indonesian): https://aisg.web.id/blog
- LinkedIn: https://www.linkedin.com/in/aisg-ai-security-1ba24842b/

## What it does

AISG orchestrates 26 security sensors and runs the core sensors **on your own machine** — your
full source code does not leave your computer. Results are scored and turned into a report a
human can act on.

Coverage includes static analysis (SAST), secret scanning, dependency and configuration checks,
HTTP surface checks (TLS, security headers, CORS, exposed paths), and LLM advisory for AI
features such as prompt injection and RAG data exposure.

## What it is not

- **Not a penetration test.** Findings are *indications* that require human review. AISG does
  not exploit targets and does not prove exploitability.
- **Not a guarantee of security.** A high score means the checked surface looks clean — not that
  the application is safe. Every report states its coverage gaps.
- **Not a replacement for secure design.** It catches the obvious, costly mistakes earlier.

## Plans

Community (free), Beginner, Expert, Enterprise — feature and sensor coverage per plan is listed
on the pricing section of the website. Plans and limits may change during early access; the
website is the source of truth.

## Attribution and licensing

AISG runs open-source security tools as sensors. Each sensor belongs to its upstream project and
keeps its own license; the AISG platform states every sensor and its upstream license on
https://aisg.web.id/legal (Open Source Notices). AISG does not fork, rename, or relicense those
projects. Attribution travels with every artifact AISG produces.

## Security

Please report vulnerabilities in AISG itself to support@aisg.web.id.
See https://aisg.web.id/.well-known/security.txt

## About this repository

This public repository holds documentation and product information only. The AISG platform
source code, infrastructure configuration, and credentials are kept private.

