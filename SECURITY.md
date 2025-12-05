# Security Policy

## 🔒 Overview

The security of this requirements repository is important to us. While this repository primarily contains dependency specifications rather than executable code, we take the security of the packages we recommend seriously.

---

## 📦 Supported Package Versions

We maintain requirements files with pinned versions of packages that are:

- ✅ **Actively maintained** by their respective projects
- ✅ **Tested for compatibility** with Python 3.10+
- ✅ **Free from known critical vulnerabilities** at the time of release
- ✅ **Widely adopted** in the industry

### Requirements File Updates

| File Category | Update Frequency | Last Updated |
|---------------|------------------|--------------|
| Data Analytics | Monthly | December 2024 |
| Data Engineering | Monthly | December 2024 |
| Data Science | Monthly | December 2024 |
| Machine Learning | Monthly | December 2024 |
| Deep Learning | Monthly | December 2024 |
| AI/LLM | Bi-weekly | December 2024 |
| All ML Categories | Monthly | December 2024 |

---

## 🛡️ Security Best Practices

### For Users

When using our requirements files, we recommend:

1. **Always use virtual environments** to isolate dependencies
   ```bash
   python -m venv venv
   source venv/bin/activate
   ```

2. **Regularly audit your dependencies** for vulnerabilities
   ```bash
   pip install pip-audit
   pip-audit
   ```

3. **Use additional security tools**
   ```bash
   pip install safety
   safety check
   ```

4. **Keep Python updated** to the latest stable version (3.10+)

5. **Review dependencies** before installing in production environments

6. **Monitor security advisories** for packages you use:
   - [GitHub Security Advisories](https://github.com/advisories)
   - [PyPI Security](https://pypi.org/security/)
   - [Snyk Vulnerability Database](https://security.snyk.io/)

---

## 🚨 Reporting a Vulnerability

### Package Vulnerability

If you discover a security vulnerability in any package listed in our requirements files:

1. **Check if it's already known:**
   - Search [GitHub Security Advisories](https://github.com/advisories)
   - Check the package's issue tracker
   - Review [CVE Database](https://cve.mitre.org/)

2. **Report to the package maintainers first:**
   - Follow the package's security policy
   - Use responsible disclosure practices
   - Allow time for the maintainers to respond

3. **Notify us by:**
   - Creating a [Security Advisory](https://github.com/christianabusca/requirements/security/advisories/new) (preferred)
   - Emailing: [your-email@example.com]
   - Opening a private issue (if urgent)

**Please include:**
- Package name and version
- CVE identifier (if available)
- Description of the vulnerability
- Potential impact
- Suggested remediation (if known)
- Proof of concept (if applicable)

### Repository Issues

For issues with the repository itself (e.g., malicious file modifications):

1. **Do NOT open a public issue**
2. **Report via:**
   - [GitHub Security Advisory](https://github.com/christianabusca/requirements/security/advisories/new)
   - Direct email to maintainers
3. **Include:**
   - Detailed description of the issue
   - Steps to reproduce
   - Potential impact
   - Suggested fix (if available)

---

## ⏱️ Response Timeline

| Stage | Timeline | Description |
|-------|----------|-------------|
| **Initial Response** | 24-48 hours | Acknowledgment of report |
| **Assessment** | 3-5 days | Evaluation of severity and impact |
| **Fix Development** | 7-14 days | Update affected requirements files |
| **Public Disclosure** | 30 days | After fix is available and deployed |

**Note:** Timeline may vary based on severity and complexity of the issue.

---

## ✅ What to Expect

### If Vulnerability is Accepted

1. We will acknowledge your report within 48 hours
2. We will assess the severity and impact
3. We will update the affected requirements files
4. We will credit you in the security advisory (unless you prefer to remain anonymous)
5. We will notify users through:
   - GitHub Security Advisory
   - Repository README
   - Wiki updates
   - Release notes

### If Vulnerability is Declined

1. We will provide a detailed explanation
2. We may suggest alternative approaches
3. The decision may be reconsidered if new information emerges

---

## 🔍 Security Scanning

We regularly scan our requirements files using:

- **pip-audit** - Python package vulnerability scanner
- **safety** - Dependency security checker
- **Dependabot** - Automated dependency updates
- **Snyk** - Vulnerability scanning and monitoring

---

## 📝 Security Checklist for Contributors

Before submitting a pull request that adds or updates packages:

- [ ] Package is from a trusted source (PyPI)
- [ ] Package has no known critical vulnerabilities
- [ ] Package is actively maintained
- [ ] Package has a security policy
- [ ] Version is pinned to a specific release
- [ ] Dependencies have been audited
- [ ] Package has been tested in a clean environment

---

## 🔐 Cryptographic Signatures

For critical releases, we provide checksums:

```bash
# Verify file integrity
sha256sum requirements-ml.txt
md5sum requirements-ml.txt
```

Checksums are published in release notes.

---

## 📚 Additional Resources

- [Python Security Best Practices](https://python.readthedocs.io/en/stable/library/security_warnings.html)
- [OWASP Dependency Check](https://owasp.org/www-project-dependency-check/)
- [Supply Chain Security](https://slsa.dev/)
- [Secure Software Development](https://www.cisa.gov/secure-software-development)

---

## 🙏 Hall of Fame

We recognize and thank security researchers who responsibly disclose vulnerabilities:

<!-- Contributors will be listed here -->

*Be the first to help us improve security!*

---

## 📜 Policy Updates

This security policy may be updated periodically. Major changes will be announced through:
- Repository notifications
- Release notes
- Wiki updates

**Last updated:** December 6, 2024  
**Policy version:** 1.0

---

## 📧 Contact

For security concerns that don't fit the above categories:
- GitHub: [@christianabusca](https://github.com/christianabusca)
- Repository: [requirements](https://github.com/christianabusca/requirements)

---

<div align="center">

**🔒 Security is a shared responsibility. Thank you for helping keep our community safe! 🔒**

</div>
