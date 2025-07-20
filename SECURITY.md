# Security Policy

## Supported Versions

We release patches for security vulnerabilities. Which versions are eligible for receiving such patches depends on the CVSS v3.0 Rating:

| Version | Supported          |
| ------- | ------------------ |
| 1.0.x   | :white_check_mark: |

## Reporting a Vulnerability

If you discover a security vulnerability, please send an email to security@mindfuljournal.app. All security vulnerabilities will be promptly addressed.

Please include the following information in your report:

- Type of issue (e.g. buffer overflow, SQL injection, cross-site scripting, etc.)
- Full paths of source file(s) related to the manifestation of the issue
- The location of the affected source code (tag/branch/commit or direct URL)
- Any special configuration required to reproduce the issue
- Step-by-step instructions to reproduce the issue
- Proof-of-concept or exploit code (if possible)
- Impact of the issue, including how an attacker might exploit the issue

## Security Considerations

### Data Privacy
- All journal data is stored locally in the browser's localStorage
- No data is transmitted to external servers
- Users have full control over their data

### Client-Side Security
- Input sanitization for all user-generated content
- XSS protection through React's built-in escaping
- No eval() or dangerous innerHTML usage

### Dependencies
- Regular dependency updates to patch known vulnerabilities
- Minimal dependency footprint to reduce attack surface
- Automated security scanning through GitHub Dependabot

## Best Practices for Users

1. **Keep your browser updated** to ensure you have the latest security patches
2. **Use HTTPS** when accessing the application
3. **Regular backups** of your journal data (export feature coming soon)
4. **Be cautious** when using the app on shared computers

## Responsible Disclosure

We kindly ask that you:

1. Give us reasonable time to investigate and mitigate an issue before public exposure
2. Make a good faith effort to avoid privacy violations and disruptions to others
3. Contact us before engaging in any testing that could affect our users or infrastructure

Thank you for helping keep Mindful Journal and our users safe!