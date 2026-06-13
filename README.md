# Side Quest Studios — Open Source

Public open-source projects from [Side Quest Studios](https://sidequeststudios.xyz). We build infrastructure tooling, developer utilities, and self-hosted software — and share what we can in the open.

---

## Projects

### [mail-in-a-docker](https://github.com/rasrobo/mail-in-a-docker)

Run [Mail-in-a-Box](https://github.com/mail-in-a-box/mailinabox) inside a Docker container — portable, reproducible, and isolated from the host OS.

- One-command email server deployment with Postfix, Dovecot, Roundcube, DKIM, DMARC, and SPF
- Docker-based setup that coexists with other services on the same host
- SNIProxy for shared HTTP/HTTPS port usage
- Full DNS stack (NSD + BIND9) runs inside the container
- Ideal for homelab operators, VPS users, and agencies standardising mail deployments

### [terminal-king-terminal](https://github.com/rasrobo/terminal-king-terminal)

A terminal-focused open-source project — tooling and utilities for command-line workflows.

- Terminal user interface experimentation and tooling
- Utilities aimed at improving developer terminal experiences
- Open-source reference implementations for CLI patterns

### [sqs.chat](https://github.com/rasrobo/sqs.chat)

A self-hosted open-source dictation app that turns speech into text using local inference — no data leaves your server.

- Built on OpenAI Whisper for CPU-optimised speech-to-text transcription
- Docker Compose stack: FastAPI web app, Caddy reverse proxy, Whisper inference service
- Optional GitHub OAuth with daily usage quotas
- Designed for private, self-hosted dictation workflows on your own infrastructure

---

### [zonedrop](https://github.com/rasrobo/zonedrop)

Idempotent Namecheap DNS zone sync with safety guards — a CLI tool and Docker image for managing DNS zones without accidentally blowing away infrastructure records.

- Read, merge, guard, backup, write, verify pipeline
- Infrastructure record protection (aborts if required records would be removed)
- Full zone backup to disk before every write
- Post-write verification with retry
- Credentials via CLI args, env vars, or encrypted vault file (`zonedrop vault encrypt`)
- Docker image ready for CI/CD or Ansible integration

### [sqs-vibe-check](https://github.com/rasrobo/sqs-vibe-check)

A Dockerised malware scanner for Git repositories and source trees — powered by ClamAV.



- Scans AI-generated and vibe-coded repos for malware before shipping

- Standalone CLI, CI/CD integration, or marketplace deployment

- Uses the ClamAV engine maintained by Cisco Talos

- Open-source, Dockerized, ready to run

## Why this repo exists

This repository is the public index for Side Quest Studios open-source work. It exists so that visitors, contributors, and potential collaborators can find our projects in one place without digging through profiles or search results.

Each project linked here is maintained independently. This page is updated as projects are added, archived, or matured.

---

## Contributing

Contributions, issues, and feature requests are welcome on individual project repositories. Each project follows its own contribution guidelines.

For general questions or discussions, open an issue on this repository.

---

## Follow

Star or watch individual repositories to stay updated on specific projects. You can also follow the organisation or repository for broader announcements.

---

Built by [Side Quest Studios](https://sidequeststudios.xyz)

If you find any of these projects useful, consider [supporting development on Ko-fi](https://ko-fi.com/sidequeststudios).

**Keywords:** DNS management, Namecheap API, self-hosted email, Mail-in-a-Box Docker, CLI tools, malware scanner, speech-to-text, open-source infrastructure, devops utilities*
