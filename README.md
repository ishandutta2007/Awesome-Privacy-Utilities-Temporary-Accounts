# Awesome-Privacy-Utilities-Temporary-Accounts

# Top Privacy Utilities & Temporary Accounts Ecosystem

**Curated List of SaaS Products & Open-Source GitHub Projects**  
*Focused on Disposable Email Services, Email Aliasing & Forwarding, Burner SMS/Numbers, Identity Masking & Anti-Tracking Utilities*  
**Last updated: November 2026**

This repository tracks notable **SaaS platforms** and **open-source projects** for **Privacy Utilities & Temporary Accounts**. These tools protect user identity during signups and online testing by generating disposable inboxes, cryptographic email aliases, virtual burner phone numbers, masked payment cards, and automated account-creation utilities.

**Examples** include 10MinuteMail, Temp Mail, Guerrilla Mail, Burner Mail, SimpleLogin, AnonAddy (addy.io), Firefox Relay, Mailinator, TrashMail, Apple Hide My Email, and `BraveOPotato/FckSignups` (the category leaders). 

**Open-source emphasis**: This section is heavily expanded with every major active project for self-hosted disposable email servers, email alias forwarding engines, local SMTP catch-all receivers, and privacy-preserving signup tools — ideal for privacy advocates, QA automation engineers, security researchers, and self-hosters.

Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.

## Table of Contents
- [SaaS/Hosted Platforms](#saashosted-platforms)
- [Open-Source GitHub Projects](#open-source-github-projects)
- [How to Contribute](#how-to-contribute)
- [Disclaimer](#disclaimer)

## SaaS/Hosted Platforms

- **[SimpleLogin (Proton)](https://simplelogin.io)**  
  Cloud email aliasing and reverse-alias reply service enabling users to shield their primary inbox with unlimited custom or generated addresses.

- **[addy.io (formerly AnonAddy)](https://addy.io)**  
  Privacy-focused email forwarding and aliasing service supporting custom domains, PGP encryption, and on-the-fly alias creation.

- **[Firefox Relay (Mozilla)](https://firefox.com)**  
  Mozilla's privacy masking service providing instant email aliases and virtual phone number forwarding integrated directly into Firefox.

- **[Apple Hide My Email (iCloud+)](https://apple.com)**  
  Built-in Apple ecosystem feature generating unique, random email addresses that forward directly to a user's personal inbox.

- **[10MinuteMail](https://10minutemail.com)**  
  Classic instant disposable email service generating self-destructing temporary inboxes to bypass forced website registration walls.

- **[Temp Mail](https://temp-mail.org)**  
  High-availability disposable temporary email platform offering web, mobile, and API-based throwaway addresses.

- **[Guerrilla Mail](https://guerrillamail.com)**  
  Veteran disposable temporary email provider offering scramble addresses, outgoing email composition, and custom domain support.

- **[Burner Mail](https://burnermail.io)**  
  Browser-extension-driven email privacy service creating isolated burner addresses per website with one-click deactivation.

- **[Mailinator](https://mailinator.com)**  
  Public and enterprise disposable email testing platform widely used by QA teams for automated signup, OTP, and workflow verification.

- **[TrashMail](https://trashmail.com)**  
  Disposable email address manager featuring configurable lifespan expirations, forward counts, and challenge-response spam filtering.


## Open-Source GitHub Projects

- **[BraveOPotato/FckSignups](https://github.com)**  
  Open-source privacy utility engineered to bypass tedious website signup walls and protect personal credentials using automated temporary accounts.

- **[SimpleLogin (Self-Hosted Open-Source Core)](https://github.com)**  
  Full-featured open-source email alias server written in Python and Postfix, allowing complete self-hosting of SimpleLogin's aliasing engine.

- **[addy.io / AnonAddy (Open-Source Core)](https://github.com)**  
  Open-source Laravel/PHP anonymous email forwarding platform enabling self-hosted wildcard aliases, GPG/OpenPGP encryption, and API management.

- **[Firefox Relay (Open-Source Backend)](https://github.com)**  
  Mozilla's open-source Django application powering Firefox Relay email and phone number masking infrastructure.

- **[Inbucket](https://github.com)**  
  Self-contained open-source disposable webmail server written in Go with built-in SMTP, POP3, REST API, and zero external database dependencies.

- **[MailHog](https://github.com)**  
  Popular open-source email and SMTP testing server with a clean web UI and JSON API for capturing temporary signup and OTP messages locally.

- **[Mailpit](https://github.com)**  
  Modern, ultra-fast open-source email testing tool and disposable SMTP catch-all server replacing MailHog with HTML checks and REST/WebSocket APIs.

- **[Forsaken Mail](https://github.com)**  
  Lightweight open-source Node.js self-hosted temporary email system receiving real-time incoming messages over WebSockets.

- **[MoeMail](https://github.com)**  
  Modern open-source temporary email service built with Next.js and Cloudflare Workers/Email Routing for serverless custom-domain throwaway inboxes.

- **[Cloudflare Temp Email](https://github.com)**  
  Serverless open-source disposable email platform powered by Cloudflare Workers, D1, and Email Routing for instant zero-cost self-hosting.

- **[Guerrilla Mail (Go-Guerrilla SMTP Daemon)](https://github.com)**  
  Minimalist, high-concurrency open-source SMTP server written in Go designed specifically for powering high-volume disposable email services.

- **[Haraka](https://github.com)**  
  High-performance, plugin-driven open-source Node.js SMTP server ideal for building custom catch-all email routers and alias forwarders.

- **[Spamgourmet](https://github.com)**  
  Pioneer open-source self-destructing email address proxy allowing users to set exact message count limits per disposable alias.

- **[33Mail (Open-Source Legacy / Wildcard Aliasing)](https://github.com)**  
  Open-source components and concepts for instant on-the-fly subdomain email aliasing (`anything@://domain.com`) without pre-creation.

- **[DuckDuckGo Email Protection (Duck Address Extension)](https://github.com)**  
  Open-source browser autofill integration supporting `@duck.com` private email addresses and tracker-stripping email forwarding.

- **[Maildrop (Heluna)](https://gitlab.com)**  
  Open-source stateless disposable email server built on Node.js with Redis storage and custom anti-spam filtering.

- **[Bitwarden Username & Email Alias Generator](https://github.com)**  
  Open-source password manager clients featuring built-in API integrations for generating unique SimpleLogin, addy.io, Firefox Relay, and DuckDuckGo aliases per login.

### Additional Strong Open-Source Options

- **[TempMail (Smail / Disposable-Email-Domains)](https://github.com)** for community-maintained blocklists and datasets of disposable email providers.
- **[Poster / Poste.io / Docker-Mailserver](https://github.com)** for full-stack self-hosted mail servers supporting regex/catch-all virtual aliases.
- **[LibreQoS / Pi-hole / AdGuard Home](https://github.com)** for blocking email tracking pixels and third-party analytics domains alongside masked accounts.
- **[Tor Browser](https://torproject.org)** and **[Mullvad Browser](https://github.com)** for fingerprint-resistant browsing when creating isolated temporary sessions.
- Many community **SMS-receive VoIP gateway bridges (`Asterisk` / `Gammu`)**, **playwright/puppeteer signup automation helpers**, and **CLI temp-mail clients (`tmpmail`)**.

**Frameworks for building custom systems**: Combine **Cloudflare Temp Email** or **Inbucket / Mailpit**, **SimpleLogin** or **addy.io**, **Bitwarden**, and **BraveOPotato/FckSignups** for a sovereign, privacy-first temporary account and email-aliasing setup.

## How to Contribute

1. Fork the repo.
2. Add/edit entries in `README.md` (follow existing format).
3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.
4. Submit PR with a short explanation.

Star the repo if you find it useful!

## Disclaimer

- This is a **community-curated** list — not exhaustive and not an endorsement.
- Public disposable inboxes (e.g., Mailinator, public 10MinuteMail instances) are unencrypted and publicly readable by anyone who guesses the address; never use public temporary inboxes for sensitive personal, financial, or password-reset communications.
- Always respect website Terms of Service and applicable anti-abuse laws when automating account creation or testing signup workflows.

---

**Made for privacy advocates, security researchers, QA automation engineers, and self-hosters.**  
Let's make online identity protection and temporary account management simpler, safer, and open.
