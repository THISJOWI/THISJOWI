<p align="center">
  <img src="https://pub-9030d6e053cc40b380e0f63662daf8ed.r2.dev/THISJOWI.png" alt="THISJOWI" width="150" />
</p>

<h1 align="center">THISJOWI</h1>

<p align="center">
  <strong>Open Source Notes & Password Manager</strong>
</p>

<p align="center">
  Secure, cross-platform, and self-hostable solution for managing your notes and passwords.
</p>

<p align="center">
  <a href="https://github.com/THISJowi/THISJOWI/releases">
    <img src="https://img.shields.io/github/v/release/THISJowi/THISJOWI?style=flat-square" alt="Release" />
  </a>
  <a href="https://github.com/THISJowi/THISJOWI/blob/main/LICENSE">
    <img src="https://img.shields.io/badge/license-MIT-blue.svg?style=flat-square" alt="License" />
  </a>
  <a href="https://github.com/THISJowi/THISJOWI/actions">
    <img src="https://img.shields.io/github/actions/workflow/status/THISJowi/THISJOWI/security-scan.yml?style=flat-square&label=security" alt="Security" />
  </a>
</p>

<p align="center">
  <a href="#features">Features</a> •
  <a href="#get-started">Get Started</a> •
  <a href="#download">Download</a> •
  <a href="#documentation">Documentation</a> •
  <a href="#contributing">Contributing</a>
</p>

---

## About THISJOWI

THISJOWI is a secure notes and password management platform that puts you in control of your data. Built with security-first principles, it allows you to store, organize, and access your sensitive information across all your devices.

Whether you're an individual looking to secure your digital life or an organization needing a self-hosted solution with LDAP integration, THISJOWI provides the tools you need.

---

## Features

### 🔐 Security First
- **End-to-end encryption** — Your data is encrypted before it leaves your device
- **Zero-knowledge architecture** — We can't read your data, even if we wanted to
- **Biometric authentication** — Unlock with Face ID, Touch ID, or fingerprint
- **OAuth2 & JWT** — Industry-standard authentication protocols

### 📝 Notes Management
- Create and organize encrypted notes
- Rich text editing
- Tags and categories
- Full-text search

### 🔑 Password Manager
- Secure password storage
- Password strength analyzer
- Auto-fill support
- Website launcher integration
- Organized by categories

### 🌐 Cross-Platform
- **Mobile:** Android, iOS
- **Desktop:** Windows, macOS, Linux
- **Web:** All modern browsers

### 🏢 Enterprise Ready
- LDAP/Active Directory integration
- Self-hosted deployment
- SSO support
- Audit logs

### 📴 Offline Mode
- Full offline access to your data
- Automatic sync when back online
- Local encrypted database

---

## Get Started

### Quick Start (Self-Hosted)

```bash
# Clone the repository
git clone https://github.com/THISJowi/THISJOWI.git

# Start the server
cd thisjowi-server
docker-compose up -d

# Or run the client
cd thisjowi-client
flutter run
```

### Use Our Cloud Service

Visit [thisjowi.uk](https://thisjowi.uk) to create a free account and start using THISJOWI immediately.

---

## Download

### Mobile

| Platform | Download |
|----------|----------|
| Android | [Google Play](https://play.google.com/store/apps/details?id=uk.thisjowi.app) • [APK](https://github.com/THISJowi/THISJOWI/releases) |
| iOS | [App Store](https://apps.apple.com/app/thisjowi) |

### Desktop

| Platform | Download |
|----------|----------|
| Windows | [Download .exe](https://github.com/THISJowi/THISJOWI/releases) |
| macOS | [Download .dmg](https://github.com/THISJowi/THISJOWI/releases) |
| Linux | [Download .deb](https://github.com/THISJowi/THISJOWI/releases) |

### Web

Access THISJOWI directly from your browser at [app.thisjowi.uk](https://app.thisjowi.uk)

---

## Architecture

```
thisjowi/
├── thisjowi-client/     # Flutter cross-platform application
└── thisjowi-server/     # Backend microservices
    ├── auth-service     # Authentication & authorization
    ├── notes-service    # Notes management
    ├── password-service # Password management
    └── gateway          # API Gateway
```

### Tech Stack

| Component | Technology |
|-----------|------------|
| Client | Flutter, Dart |
| Backend | Microservices Architecture |
| Database | PostgreSQL, SQLite (local) |
| Security | AES-256, RSA, bcrypt |
| Auth | OAuth2, JWT, LDAP |

---

## Documentation

- 📖 [User Guide](https://docs.thisjowi.uk/user-guide)
- 🔧 [Self-Hosting Guide](https://docs.thisjowi.uk/self-hosting)
- 🔌 [API Reference](https://docs.thisjowi.uk/api)
- 🛡️ [Security Whitepaper](https://docs.thisjowi.uk/security)

---

## Security

Security is our top priority. If you discover a security vulnerability, please report it responsibly.

- 📧 **Email:** security@thisjowi.uk
- 🔐 **Security Policy:** [SECURITY.md](./SECURITY.md)
- 🐛 **Bug Bounty:** Coming soon

See our [Security Documentation](https://docs.thisjowi.uk/security) for detailed information about our security practices.

---

## Contributing

We welcome contributions from the community! Whether it's fixing bugs, adding features, or improving documentation.

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/amazing-feature`)
3. Commit your changes (`git commit -m 'feat: add amazing feature'`)
4. Push to the branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request

Please read our [Contributing Guide](./CONTRIBUTING.md) for more details.

---

## Community

- 💬 [GitHub Discussions](https://github.com/THISJowi/THISJOWI/discussions)
- 🐛 [Issue Tracker](https://github.com/THISJowi/THISJOWI/issues)
- 📧 [Contact Us](mailto:support@thisjowi.uk)

---

## License

THISJOWI is released under the [MIT License](./LICENSE).

---

<p align="center">
  <sub>Built with ❤️ by <a href="https://github.com/THISJowi">THISJowi</a></sub>
</p>
