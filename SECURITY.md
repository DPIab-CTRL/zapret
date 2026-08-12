# Security Policy

## Supported versions

Security fixes are provided for the latest published release of DPI LAB.

| Version | Supported |
| --- | --- |
| Latest release | ✅ |
| Older releases | ❌ |

Users should reproduce a security issue on the latest release before reporting
it whenever possible.

## Reporting a vulnerability

Please **do not publish exploit details, credentials, private server
information, or other sensitive material in a public issue**.

Preferred reporting method:

1. Open the repository's **Security** tab.
2. Select **Report a vulnerability** / private vulnerability reporting, if it
   is enabled.
3. Include enough information for the issue to be reproduced.

A useful report should include:

- affected DPI LAB version;
- Windows version and architecture;
- affected file or component;
- clear reproduction steps;
- expected and actual behavior;
- security impact;
- logs or screenshots with secrets removed;
- a minimal proof of concept when appropriate.

If private vulnerability reporting is not enabled, create a public issue only
to request a private contact method. Do not place vulnerability details or
working exploit code in that public issue.

## Third-party components

DPI LAB includes or redistributes third-party components such as zapret,
WinDivert and related utilities.

If a vulnerability exists entirely in an upstream component and is not caused
by a DPI LAB modification, it should also be reported to the upstream project.

## Security notes for users

- Download releases only from the official DPI LAB repository.
- Verify release hashes when `SHA256SUMS.txt` is provided.
- Review scripts and configuration before running modified or unofficial builds.
- Do not disable Windows security protections solely to make the software run.
- Do not run builds from untrusted mirrors.
- Keep Windows and network drivers up to date.

## Disclosure

Please allow a reasonable period for investigation and remediation before
publicly disclosing an unresolved vulnerability.

After a fix is released, the project may publish a short advisory describing
the affected versions, impact and remediation.
