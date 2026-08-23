<div align="center">

# ⚡ HEXNOVA

### Modern Capture The Flag Platform

**Build • Host • Compete • Learn**

[![Website](https://img.shields.io/badge/Website-hexnova.space-7C3AED?style=for-the-badge&logo=googlechrome&logoColor=white)](https://hexnova.space)
[![Play CTF](https://img.shields.io/badge/Play%20CTF-ctf.hexnova.space-06B6D4?style=for-the-badge&logo=hackthebox&logoColor=white)](https://ctf.hexnova.space)
[![Discord](https://img.shields.io/badge/Discord-Join%20Server-5865F2?style=for-the-badge&logo=discord&logoColor=white)](https://discord.gg/3VJzX7bTC)
[![Instagram](https://img.shields.io/badge/Instagram-%40hexnova.space-E4405F?style=for-the-badge&logo=instagram&logoColor=white)](https://www.instagram.com/hexnova.space)
[![GitHub](https://img.shields.io/badge/GitHub-hexnovactf-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/hexnovactf)

</div>

---

## About

HEXNOVA is a modern Capture The Flag platform built for people who want to run
competitions without fighting their tooling. It handles the parts that usually
eat an organiser's weekend — challenge deployment, flag validation, scoring,
and a live scoreboard — so you can focus on writing good challenges.

Two ways to use it:

- **Compete** at [ctf.hexnova.space](https://ctf.hexnova.space) — jump into a
  running event, solve challenges, climb the scoreboard.
- **Host** your own event — deploy the platform, load your challenge set, and
  open registration.

New to CTFs? Start with the beginner track and the writeups. Everything is
designed to be approachable without being watered down.

## Features

| | |
|---|---|
| 🚩 **Challenge hosting** | Web, pwn, reverse engineering, crypto, forensics, and OSINT categories with per-challenge hints and attachments |
| 📊 **Live scoreboard** | Real-time rankings with solve timelines and tie-breaking by first-blood |
| 👥 **Teams & solo play** | Invite-code team formation, configurable size limits, or straight solo mode |
| ⚖️ **Dynamic scoring** | Point values that decay as more players solve, keeping late-game challenges meaningful |
| 🐳 **Isolated instances** | Per-player containerised challenge instances so one competitor can't break another's box |
| 🔒 **Flag validation** | Static and regex flags, per-team flag salting to discourage sharing |
| 📝 **Writeups** | Post-event writeup submission and a browsable archive |
| 🛠️ **Admin dashboard** | Challenge CRUD, user management, submission logs, and event scheduling |

## Getting Started

> **Note**
> Fill in the commands below with the real ones for this repo before publishing.

### Prerequisites

- Docker and Docker Compose
- Git

### Run locally

```bash
git clone https://github.com/hexnovactf/hexnova.git
cd hexnova

# copy the example environment file and fill in your secrets
cp .env.example .env

docker compose up -d
```

The platform will be available at `http://localhost:8000`.

### Configuration

Key environment variables:

| Variable | Description |
|---|---|
| `SECRET_KEY` | Session signing key — generate a fresh random value |
| `DATABASE_URL` | Database connection string |
| `ADMIN_EMAIL` | Bootstrap admin account |
| `EVENT_START` / `EVENT_END` | Competition window (ISO 8601) |

## Tech Stack

<!-- TODO: replace with the actual stack -->

- **Frontend:** _add yours_
- **Backend:** _add yours_
- **Database:** _add yours_
- **Challenge sandboxing:** Docker
- **Hosting:** _add yours_

## Roadmap

- [ ] Public API for scoreboard embedding
- [ ] Per-challenge writeup gating until event close
- [ ] Team-vs-team practice rooms
- [ ] Achievement badges and player profiles
- [ ] CTFtime integration

## Community

| Where | Link |
|---|---|
| 🌐 Website | [hexnova.space](https://hexnova.space) |
| 🚩 CTF Platform | [ctf.hexnova.space](https://ctf.hexnova.space) |
| 💬 Discord | [discord.gg/3VJzX7bTC](https://discord.gg/3VJzX7bTC) |
| 📸 Instagram | [@hexnova.space](https://www.instagram.com/hexnova.space) |
| 🐙 GitHub | [github.com/hexnovactf](https://github.com/hexnovactf) |

Discord is the fastest way to reach us — challenge support, event
announcements, and general hangout all live there.

## Contributing

Contributions are welcome, whether that's a new challenge, a bug fix, or docs.

1. Fork the repo and create a branch: `git checkout -b feature/your-feature`
2. Make your changes and commit them
3. Push and open a pull request describing what changed and why

For new challenges, please include the challenge source, a Dockerfile, the
flag, and a working solution script so we can verify it.

## Security

Found a vulnerability in the platform itself — as opposed to a challenge?
Please **don't** open a public issue. Report it privately via Discord DM to a
maintainer or email `security@hexnova.space`, and give us a reasonable window
to patch before disclosing.

Attacking the platform infrastructure, other competitors, or anything outside
the designated challenge scope is out of bounds during events.

## License

Released under the MIT License. See [LICENSE](LICENSE) for details.

<!-- TODO: confirm this matches the LICENSE file in the repo -->

---

<div align="center">

**Built by the HEXNOVA team** ⚡

If this project is useful to you, a ⭐ goes a long way.

</div>
