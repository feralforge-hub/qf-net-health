# QF Net Health

Public, sanitized repository for Quantum Forge network-health work.

## Purpose

This repository is intended to hold shareable network-health notes, scripts, examples, or documentation for the Quantum Forge lab without exposing private infrastructure details.

Because this repository is public, it should only contain sanitized material.

## Safety Rules

Do not commit:
- real IP addresses, hostnames, or internal network maps
- passwords, tokens, API keys, private keys, or certificates
- real `.env` files
- VPN configuration files
- router, firewall, or DNS exports that contain private values
- screenshots that reveal private infrastructure details
- customer, work, or personally sensitive information

Use examples or placeholders instead, such as:
- `192.0.2.10`
- `example.local`
- `REDACTED_TOKEN`
- `YOUR_HOSTNAME_HERE`

## Recommended Repository Contents

Good candidates for this public repo:
- sanitized network-health scripts
- example configuration templates
- documentation for repeatable health checks
- notes about monitoring concepts
- non-sensitive troubleshooting writeups
- diagrams that use placeholder addresses and labels

Keep private operational files in a private repository instead.

## Relationship to Quantum Forge

Quantum Forge is the broader homelab project. This repository is the public/sanitized network-health side of that work.

Private infrastructure details should stay in private repositories or local notes.

## Current Status

This repository is public and should be treated as sanitized-by-default.

Before adding files, review them for secrets, private network details, and metadata that could reveal internal infrastructure.