# Awesome Coolify Templates

A curated collection of Docker Compose templates for deploying applications on [Coolify](https://coolify.io/). These templates provide structured tutorials, documentation, and simplified configurations for complex deployments that lack official templates or proper documentation.

## 📚 Available Templates

Browse our collection of production-ready templates:

<table>
<tr>
<td width="50%">

### 🗨️ [LobeChat Database](./templates/lobechat-database/) **⚠️ DEPRECATED**

Deploy LobeChat with database support, decoupled authentication, and S3 storage.

> **⚠️ This template is deprecated.** LobeChat is no longer actively maintained. Please use **Lobe Hub** (the successor of LobeChat) for new deployments.

**Stack:** LobeChat + PostgreSQL (pgvector)  
**External:** Logto (auth) + MinIO (S3)  
**Complexity:** 🔴 Advanced

[📖 View Guide](./templates/lobechat-database/README.md) • [📦 Compose File](./templates/lobechat-database/docker-compose.yaml)

</td>
<td width="50%">

### ⬇️ [Aria2-UI](./templates/aria2-ui/)

Complete download manager with Aria2, AriaNg, File Browser, and Rclone integration.

**Stack:** Aria2 + AriaNg + File Browser + Rclone + Caddy  
**Complexity:** 🟡 Intermediate

[📖 View Guide](./templates/aria2-ui/README.md) • [📦 Compose File](./templates/aria2-ui/docker-compose.yaml)

</td>
</tr>
<tr>
<td width="50%">

### 💻 [Coder](./templates/coder/)

Self-hosted cloud development environments with Docker workspace provisioning.

**Stack:** Coder + PostgreSQL  
**Complexity:** 🟡 Intermediate

[📖 View Guide](./templates/coder/README.md) • [📦 Compose File](./templates/coder/docker-compose.yaml)

</td>
<td width="50%">

<!-- Placeholder for future template -->

</td>
</tr>
</table>

## 🎯 Why This Repository?

Many applications have complex deployment requirements that:
- Cannot be automated in a single compose file
- Lack official Coolify templates
- Have scattered, outdated, or incomplete documentation
- Require specific configuration for proper integration

This repository provides:
- ✅ **Structured tutorials** with step-by-step instructions
- ✅ **Working compose files** tested on Coolify
- ✅ **Clear documentation** with troubleshooting guides
- ✅ **Best practices** for production deployments

## 🚀 How to Use

1. Browse the [templates directory](./templates/)
2. Select a template that fits your needs
3. Read the template's README for specific instructions
4. Copy the `docker-compose.yaml` to Coolify
5. Configure environment variables as documented
6. Deploy!

## 🤝 Contributing

Have a complex deployment template that others might find useful? Contributions are welcome!

Please read our [Contributing Guide](./CONTRIBUTING.md) for:
- Template structure requirements
- Documentation standards
- Submission process
- Best practices

**Quick Start for Contributors:**
1. Fork this repository
2. Create your template in `templates/your-template-name/`
3. Follow the template structure (compose file + README)
4. Add icons/banners to respective directories
5. Update main README with your template listing
6. Submit a pull request

**✨ Need Help?** Use our custom GitHub agents:
- `@template-verifier` - Validates your template for Coolify compatibility
- `@repo-organizer` - Helps integrate your template into the repository

[Learn more about our agents](./.github/agents/README.md)

## 📁 Repository Structure

```
.
├── .github/
│   └── agents/        # Custom GitHub agents for automation
├── templates/         # All deployment templates
├── icons/             # Icons used in documentation
├── cover-pages/       # Cover images for templates
└── README.md          # This file
```

## 🤖 Automated Quality Checks

We use custom GitHub Copilot agents to maintain repository quality:

- **Template Verifier** - Validates templates against Coolify requirements
- **Repository Organizer** - Maintains consistent structure and documentation

These agents automatically review pull requests and help contributors ensure their templates meet quality standards. [Learn more about our agents](./.github/agents/README.md)

## 📝 License

This repository is provided as-is for the community. Individual applications deployed using these templates retain their respective licenses.
