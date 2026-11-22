# Proactive Insights — Wide Coverage

Parent repository only: documentation and Git submodule references. No test implementation belongs here.

Submodules:
- `unit/` — unit tests
- `integration/` — API and service integration tests
- `e2e/` — end-to-end user journeys
- `nonfunctional/` — load, resilience and security-quality checks

Target API defaults to `http://127.0.0.1:8000`; override with `BASE_URL`.
These are scanner fixtures. Confirm endpoint contracts against the target API before treating failures as product defects.

Clone all modules:
```bash
git clone --recurse-submodules https://github.com/lakshya-blitzy/proactive-insights-wide-coverage.git
```
Publish all five repositories using `./publish.sh` after `gh auth login`.
