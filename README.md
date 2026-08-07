# Zero Downtime Migrations

**Languages:** [English](README.md) · [Українська](README.uk.md)

> Practical reference by [Boryslav Deputat](https://github.com/boryslavdeputat) - Cloud / SRE / Platform.
> Sites: [Portfolio](https://boryslavdeputat.com/) · [ClawDBot / KLAV (UA AI)](https://clawdbot.llc/) · [Walk ATX Pet](https://walkatxpet.com/) · [DepuTater](https://deputater.com/)

Playbooks for **zero / low downtime** data migrations: dual-write, expand-contract, CDC, blue-green cutover.

## Patterns

| Pattern | Use when |
|---------|----------|
| Expand-contract | Schema changes with dual code paths |
| Dual-write | Short migration of writes to new store |
| CDC replay | Large datasets, async converge |
| Blue-green | Stateless services / versioned APIs |
| Shadow reads | Validate new path before cutover |

Docs in `docs/`, checklist in `templates/cutover-checklist.md`.

## Disclaimer

Educational and practical reference. Validate against your compliance, cost, and SLO requirements before production use.

## Contact

- Portfolio: https://boryslavdeputat.com/
- ClawDBot / KLAV (UA AI): https://clawdbot.llc/
- Email: info@boryslavdeputat.com

## License

MIT - see [LICENSE](LICENSE).

---

## Discoverability

- Author: [Boryslav Deputat](https://github.com/boryslavdeputat) · [https://boryslavdeputat.com/](https://boryslavdeputat.com/)
- AI context: [https://boryslavdeputat.github.io/llms.txt](https://boryslavdeputat.github.io/llms.txt)
- This repo: [llms.txt](llms.txt)

