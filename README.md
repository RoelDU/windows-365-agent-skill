# Windows 365 Agent Skill

[![skills.sh](https://skills.sh/b/YOUR-GITHUB-USER/windows-365-agent-skill)](https://skills.sh/YOUR-GITHUB-USER/windows-365-agent-skill)

A community Agent Skill for Windows 365 Cloud PC guidance.

This skill helps agents answer and operationalize Windows 365 scenarios across Enterprise, Business, Flex, provisioning, security, Conditional Access, RBAC, RDP redirection, resize, restore, monitoring, troubleshooting, and Graph/API automation.

## Install

After publishing this repo publicly on GitHub, install with:

```bash
npx skills add https://github.com/YOUR-GITHUB-USER/windows-365-agent-skill --skill windows-365
```

Replace `YOUR-GITHUB-USER` with the GitHub account or organization that owns the repo.

## Skill

The skill lives at:

```text
skills/windows-365/SKILL.md
```

## Example prompts

```text
/windows-365 Give me a security baseline for Windows 365 Cloud PCs covering MFA, RBAC, redirection, screen capture protection, watermarking, and Conditional Access.
```

```text
/windows-365 Troubleshoot a Cloud PC stuck in Not provisioned status.
```

```text
/windows-365 Compare Windows 365 Enterprise, Business, Flex, and Azure Virtual Desktop for a 500-user contact center.
```

```text
/windows-365 Build a deployment checklist for Windows 365 Enterprise with Microsoft hosted network and Entra join.
```

## Source basis

The skill is original guidance based on curated Microsoft Learn sources, including:

- Windows 365 overview
- Windows 365 Business and Enterprise comparison
- Windows 365 Enterprise requirements
- Windows 365 Flex documentation
- Provisioning policy documentation
- Security guidelines and security baselines
- Conditional Access, SSO, and RBAC documentation
- RDP redirection, screen capture protection, and watermarking documentation
- Resize, restore, reprovision, monitoring, reporting, troubleshooting, and Microsoft Graph API documentation

The skill intentionally links to Microsoft Learn rather than copying large documentation passages.

## Publishing checklist

1. Create a public GitHub repository named `windows-365-agent-skill`.
2. Upload this folder contents to the repository root.
3. Replace `YOUR-GITHUB-USER` in this README with the GitHub account or organization name.
4. Add repository topics such as `agent-skill`, `windows-365`, `cloud-pc`, `microsoft-intune`, and `microsoft-learn`.
5. Share the GitHub repository URL. People can install it with the `npx skills add` command above.

## License

MIT License. Reuse and contributions are encouraged.
