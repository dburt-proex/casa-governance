# CASA Governance

CASA (Controlled Autonomous Systems Architecture) is a governance control plane for AI systems.

Decisions enforced at runtime:
- ALLOW
- REVIEW
- HALT

CASA ensures deterministic control, auditability, and risk containment for agentic systems.

## Architecture

<img width="2577" height="526" alt="mermaid-diagram" src="https://github.com/user-attachments/assets/7265d1a1-5801-4942-a10d-a8a1f3fd5fb0" />
    

## Key Features

- Real-time decision gating
- Risk scoring engine

- Audit logging (traceable events)
- Enforcement proxy layer

## Why It Matters

AI systems without governance drift.

CASA prevents:
- uncontrolled execution
- silent failure modes
- policy violations

## Dependencies

All dependencies in `requirements.txt` are pinned to exact versions for reproducible, deterministic builds.

To install:

```bash
pip install -r requirements.txt
```

To update a pin after testing a new version:

1. Upgrade the package: `pip install --upgrade <package>`
2. Check the installed version: `pip show <package> | grep Version`
3. Update the corresponding line in `requirements.txt` with the exact new version
4. Run the full test suite to verify compatibility

