# Contributing to EthSharp

Thank you for your interest in contributing to EthSharp! We welcome contributions from the community.

## Code of Conduct

Please read our [Code of Conduct](CODE_OF_CONDUCT.md) before participating.

## Prerequisites

- [.NET 8.0 SDK](https://dotnet.microsoft.com/download/dotnet/8.0) or later
- [Git](https://git-scm.com/)
- A code editor (Visual Studio, VS Code, or JetBrains Rider)

## Getting Started

1. **Fork and clone the repository:**
   ```bash
   git clone https://github.com/YOUR_USERNAME/EthSharp.git
   cd EthSharp
   ```

2. **Set up development:**
   ```bash
   dotnet restore
   dotnet build
   ```

## Development Workflow

1. **Create a branch:**
   ```bash
   git checkout -b feature/your-feature-name
   ```

2. **Make your changes:**
   - Follow our coding standards (.editorconfig)
   - Add tests for new functionality
   - Update documentation as needed

3. **Test and format:**
   ```bash
   dotnet test
   dotnet format
   ```

4. **Commit and push:**
   ```bash
   git commit -m "feat: describe your changes"
   git push origin your-branch-name
   ```

5. **Create a Pull Request** on GitHub

## Coding Standards

- Follow .NET naming conventions
- Use modern C# features and nullable reference types
- Write XML documentation for public APIs
- Keep code simple and readable

## Reporting Issues

When reporting bugs or requesting features, please provide:
- Clear description
- Steps to reproduce (for bugs)
- Environment details (.NET version, OS)

## Getting Help

- Check the [Issues](https://github.com/Mudblock/EthSharp/issues) page
- Use GitHub Discussions for questions

Thank you for contributing! 🚀
