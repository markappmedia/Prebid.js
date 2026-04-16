# Security Policy

## Supported Versions

This repository is a fork of [Prebid.js](https://github.com/prebid/Prebid.js) maintained by MarkApp for integration with Pantheon (SSP) and Harion (DSP) bid adapter development.

| Version | Supported |
|---------|-----------|
| master  | ✅ Yes    |

## Reporting a Vulnerability

**Do not open a public GitHub issue for security vulnerabilities.**

Please report security vulnerabilities privately via GitHub's [Private Vulnerability Reporting](https://github.com/markappmedia/Prebid.js/security/advisories/new) feature.

### What to include

- Description of the vulnerability and potential impact
- Steps to reproduce
- Affected bid adapters, modules, or core components
- Any suggested remediation

### Response timeline

- **Acknowledgement:** within 48 hours
- **Initial assessment:** within 5 business days
- **Patch or mitigation:** within 30 days for critical issues

## Security practices

- All dependencies are monitored via Dependabot with automatic security updates enabled
- Secret scanning is active on this repository
- Private vulnerability reporting is enabled
- Fork is regularly synced with upstream [prebid/Prebid.js](https://github.com/prebid/Prebid.js)
- Bid adapter code is reviewed for data leakage and unauthorized tracking

## Scope

Security issues we care about:
- Bid adapter data leakage (user data sent to unauthorized endpoints)
- Supply chain attacks via npm dependencies
- XSS vulnerabilities in ad rendering
- Privacy regulation violations (GDPR, CCPA) in adapter implementations

## Contact

For urgent security matters, contact: security@markapp.io
