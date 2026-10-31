# Security Policy

## Supported Products & Scope

Security updates are applied actively to current main branches across Snexon infrastructure repositories:

| Project | In Scope | Reporting Channel |
| :--- | :--- | :--- |
| **Payonic** (Lite & Pro) | Transaction validation, webhook integrity, signature verification | `security@sabbir.gg` |
| **Curdeck** | Identity namespace isolation, DNS routing, session authentication | `security@sabbir.gg` |
| **VectorFlix** | License verification, asset hash matching, delivery endpoints | `security@sabbir.gg` |
| **Shared Core Libraries** | Cryptographic primitives, storage managers, networking components | `security@sabbir.gg` |

---

## Reporting a Vulnerability

If you discover a potential vulnerability within any Snexon system, do not disclose it publicly or open a public issue.

1. **Email Details**: Send technical reproduction steps, curl requests, or proof-of-concept scripts to [security@sabbir.gg](mailto:security@sabbir.gg).
2. **Include Technical Evidence**:
   - Affected repository and commit hash / release tag
   - Direct impact assessment (privilege escalation, data exposure, transaction tampering)
   - Minimal reproduction script or HTTP trace
3. **Response Timeline**:
   - Acknowledgment within 48 hours.
   - Status triage and patch timeline provided following reproduction.
   - Coordinated disclosure upon deployment of the security patch.
