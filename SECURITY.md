# Security Policy

## Supported releases

While Zencode is in public beta, only the newest published beta release receives fixes and security updates. Older beta downloads may be retired when a replacement is published.

Install updates promptly and reproduce a suspected problem on the newest release when it is safe to do so.

## Report a vulnerability privately

Use [GitHub private vulnerability reporting](https://github.com/zencode-chat/zencode/security/advisories/new) for:

- suspected vulnerabilities in Zencode;
- compromised or unexpected release assets;
- invalid code signatures, notarization, or checksums;
- exposed Zencode-controlled credentials or signing material; and
- security issues that could put other users, projects, or systems at risk.

Do not disclose these issues in a public issue, discussion, pull request, social-media post, or shared screenshot before Zencode has had a reasonable opportunity to investigate and address them.

## What to include

Provide only the information needed to reproduce and assess the problem:

- the Zencode version and operating system;
- the affected feature and expected behavior;
- clear reproduction steps or a minimal proof of concept;
- the observed security impact;
- relevant logs with credentials, tokens, personal data, and private source code removed; and
- checksum, signature, filename, and download-source details for release-integrity reports.

Do not access, modify, retain, or disclose another person's data. Do not perform destructive testing, disrupt services, establish persistence, deploy malware, or use automated testing that creates excessive traffic.

## Third-party services

Issues confined to an AI provider, ACP agent, MCP server, Git host, package registry, operating system, or another third-party product should normally be reported to that provider under its security policy. If the issue is caused by Zencode's integration or affects Zencode users, report it privately here as well.

## Release verification

Official Zencode downloads are published on the [Releases](https://github.com/zencode-chat/zencode/releases) page. Each release includes `SHA256SUMS.txt`; macOS and Windows packages are also code signed. Do not install or redistribute a file whose origin, checksum, or signature cannot be verified.
