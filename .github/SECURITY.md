# Security Policy

## Reporting Security Vulnerabilities

We take the security of EthSharp seriously. If you discover a security vulnerability, please report it to us privately.

**Please do NOT report security vulnerabilities through public GitHub issues.**

### How to Report

Send security vulnerabilities to: **mudblockhq@gmail.com**

Please include:
- Clear description of the vulnerability
- Step-by-step reproduction instructions
- Minimal code example (if applicable)
- Impact assessment and severity level
- EthSharp version, .NET version, OS
- Your contact information
- Any suggested fixes (optional)

### Response Timeline

- **Acknowledgment**: Within 72 hours
- **Resolution**: Depends on severity and complexity

### Disclosure Policy

- We will work with you to understand and resolve the issue quickly
- We ask that you do not publicly disclose the vulnerability until we have released a fix

## Supported Versions

As EthSharp is in early development, we currently only support the latest version.

## Security Best Practices

When using EthSharp:

### Private Key Management
- **Never commit private keys** to version control
- Use secure key storage solutions (Azure Key Vault, AWS Secrets Manager, etc.)
- Use environment variables or secure configuration for development

### Network & Contract Security
- Use HTTPS endpoints for all RPC connections
- Always verify contract addresses before interactions
- Validate input parameters and implement proper error handling

## Questions?

For security-related questions (not vulnerabilities), please:
- Check our [documentation](docs/)
- Open a [GitHub Discussion](https://github.com/Mudblock/EthSharp/discussions)
- Contact us at mudblockhq@gmail.com
