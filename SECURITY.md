# Security Policy

**Please do not disclose security vulnerabilities publicly.**

Security issues should not be reported through public GitHub issues, discussions, pull requests, or social media.

## Supported Versions

Meulah is currently under active development and has not yet reached a stable `1.0` release.

Security fixes are generally provided for the latest maintained release.

| Version | Supported |
| ------- | --------- |
| Latest release | ✅ |
| Older releases | ❌ |
| Development branches | Best effort |

Users are strongly encouraged to keep both the Meulah framework and application starter updated.

## Reporting a Vulnerability

To report a security vulnerability, use GitHub's private vulnerability reporting feature in the affected repository.

Relevant repositories:

- `Meulah/framework`
- `Meulah/meulah`

Please include as much of the following information as possible:

- A clear description of the vulnerability
- The affected Meulah package and version
- Steps required to reproduce the issue
- A minimal proof of concept
- The potential security impact
- Any known workarounds or suggested fixes
- Your preferred name or handle for acknowledgment

Please do not include real credentials, private user data, access tokens, or production secrets in the report.

## What Happens After Reporting

After receiving a report, the Meulah maintainers will:

1. Confirm receipt of the report.
2. Review and attempt to reproduce the issue.
3. Determine its severity and affected versions.
4. Develop and test a fix where appropriate.
5. Coordinate disclosure and release timing with the reporter.
6. Publish a security advisory when necessary.

Response times may vary while the project is maintained by a small team, but legitimate security reports will be treated seriously.

## Responsible Disclosure

Please allow the maintainers reasonable time to investigate and release a fix before publicly disclosing the vulnerability.

Do not:

- Exploit the vulnerability against systems you do not own
- Access, alter, or delete other users' data
- Perform denial-of-service testing
- Use social engineering
- Publicly disclose the issue before a fix or coordinated disclosure

Good-faith security research that follows this policy is welcome.

## Scope

Security reports may include vulnerabilities involving:

- HTTP request and response handling
- Routing and middleware
- File uploads
- Authentication or authorization components
- Session or cookie handling
- Database access
- Migrations and console commands
- Dependency injection
- Application bootstrap and configuration
- Sensitive data or exception leakage
- Path traversal
- Cross-site scripting
- Cross-site request forgery
- SQL injection
- Command injection
- Remote code execution
- Unsafe defaults in the framework or starter application

General feature requests, installation problems, and ordinary bugs should be reported through the normal GitHub issue tracker.

## Security Advisories

Confirmed vulnerabilities may be published through GitHub Security Advisories after an appropriate fix is available.

## Public PGP Key

Meulah does not currently publish a PGP key for vulnerability reports.

This section will be updated if encrypted email reporting is introduced.