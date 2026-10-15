# localLOOP Organization Profile

> [!IMPORTANT]
> **Archived 2026-10-14.** localLOOP is now developed in the open at **[MycelAI/LocalLOOP](https://github.com/MycelAI/LocalLOOP)**; this repository's history continues there in [`ops/org-profile`](https://github.com/MycelAI/LocalLOOP/tree/main/ops/org-profile). This repository is read-only.
> The lab demo now lives at **https://loop.urbnia.com** (API under `/api/`); `localloop.urbnia.com` and `loop-api.urbnia.com` redirect there.

This repository defines the GitHub organization profile for localLOOP.
See `profile/README.md` for the public landing page content.

> Early-stage, low-TRL concept. No public pilots or deployments. Lab demo only.

## What is here

- `profile/README.md`: org profile content (rendered at <https://github.com/local-loop-io>).
- `AGENTS.md`, `CLAUDE.md`: org context, domains, and runbooks for contributors and agents.
- `CODE_OF_CONDUCT.md`: organization-wide code of conduct.
- `scripts/check-policy.sh`, `scripts/check-security-pointer.sh`: content-policy checks run by `.github/workflows/policy-check.yml`.
- `CHANGELOG.md`: history of profile and policy changes.

## How to update

1. Edit `profile/README.md`.
2. Keep the early-stage, low-TRL, lab-demo-only posture and no-public-pilots-or-deployments wording.
3. Run `bash scripts/check-policy.sh` before opening a PR.

## Links

- Org profile: <https://github.com/local-loop-io>
- Docs hub: <https://localloop.urbnia.com>

## Live endpoints

- Public site: <https://localloop.urbnia.com>
- Backend API: <https://loop-api.urbnia.com>
- Canonical note: `api.local-loop.io` does not exist.

## How to cite

If you reference this repository, please cite:
Alphin C. Tom. "localLOOP Organization Profile." localLOOP (Mycel),
2025-2026. <https://github.com/local-loop-io/.github>

```bibtex
@misc{localloop_org_profile_2025,
  author = {Alphin C. Tom},
  organization = {Mycel},
  title = {localLOOP Organization Profile},
  year = {2026},
  howpublished = {GitHub repository},
  url = {https://github.com/local-loop-io/.github},
  note = {Repository maintained by the author}
}
```
