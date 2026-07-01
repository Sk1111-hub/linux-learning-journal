# Configs

Sanitized dotfiles and system configs (e.g. `.bashrc`, `sshd_config`
hardening changes, `iptables` rules) with comments explaining each
non-default choice.

**Before committing anything here:**
- [ ] Remove real IP addresses, hostnames, usernames
- [ ] Remove API keys, tokens, passwords, private keys
- [ ] Replace anything sensitive with placeholders like `<YOUR_IP>`

A `.gitignore` in the repo root helps prevent accidental commits of
sensitive files (see root `.gitignore`).
