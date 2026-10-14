# Hi, I'm Soham Khardikar

Integrated B.Tech–M.Tech Cybersecurity student at NFSU (grad 2028) · Independent bug bounty researcher · AppSec / VAPT

I find and responsibly report vulnerabilities in open-source and cloud tooling, mostly authorization bypass, SSRF and command injection, and I write the fix when maintainers want one.

## Public security credits

| Project | What I found | Outcome |
| --- | --- | --- |
| Verdaccio | SSRF in the 6.x registry: a publisher-controlled `dist.tarball` was fetched server-side after the local tarball was removed, and could send the uplink's auth header to an arbitrary host | I authored the patch; shipped in [v6.10.3](https://github.com/verdaccio/verdaccio/releases) ([PR #6218](https://github.com/verdaccio/verdaccio/pull/6218)), credited in the release notes |
| Civo CLI | Command injection in `kubernetes application remove` | Fixed in [v1.5.4](https://github.com/civo/cli/releases/tag/v1.5.4) |
| Civo Cloud Controller Manager | Missing ownership validation in load balancer lookup | Triaged valid and fixed, credited by Civo |
| Appwrite | Insecure shipped-default jobs HMAC secret | Fixed to fail closed and generate a unique secret ([PR #14116](https://github.com/appwrite/appwrite/pull/14116)) |

## Other coordinated disclosures

- Critical vulnerability in a cloud platform vendor's bug bounty program: **vendor-assessed CVSS 9.9**, fixed fleetwide. Details withheld under program terms.

## Projects

- **AuthGraph** – GitHub App that scans pull requests for authorization and SSRF vulnerabilities (link the repo if it's public, otherwise delete this section) (in progress)

## Focus

AppSec · Source code review · Authorization bypass · SSRF · Command injection · Burp Suite · Semgrep · Go · Node.js · Python · CI/CD security

## Reach me

[LinkedIn](https://www.linkedin.com/in/sohamkhardikar/) · [Email](mailto:snkhardikar@gmail.com) · TryHackMe: cOmrade404 (top 3%)

*All reports are submitted under each program's disclosure rules.*
