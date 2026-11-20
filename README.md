⚡ HEXNOVA — Modern Capture The Flag Platform

<p align="center">
  <img src="https://img.shields.io/badge/HEXNOVA-Cybersecurity%20Platform-7C3AED?style=for-the-badge" alt="HEXNOVA Cybersecurity Platform"/>
  <img src="https://img.shields.io/badge/CTF-Learn%20%7C%20Compete%20%7C%20Host-06B6D4?style=for-the-badge" alt="Capture The Flag"/>
  <img src="https://img.shields.io/badge/Community-Open%20to%20All-22C55E?style=for-the-badge" alt="Community"/>
</p><h3 align="center">Build. Host. Compete. Learn. Secure.</h3><p align="center">
  A modern cybersecurity and Capture The Flag (CTF) platform designed to make security learning, challenge hosting, and competitive hacking accessible to everyone.
</p><p align="center">
  <a href="https://hexnova.space"><strong>Official Website</strong></a> •
  <a href="https://ctf.hexnova.space"><strong>Play CTF</strong></a> •
  <a href="https://discord.gg/3VJzX7bTC"><strong>Join Community</strong></a> •
  <a href="https://github.com/hexnovactf"><strong>GitHub</strong></a>
</p>---

🌐 Discover HEXNOVA

HEXNOVA is a modern Capture The Flag (CTF) platform built to bring cybersecurity enthusiasts, ethical hackers, developers, students, and security researchers together.

Our goal is to create an accessible environment where people can develop practical cybersecurity skills through hands-on challenges, competitive events, and collaborative learning.

Whether you're solving your first beginner challenge or hosting an advanced cybersecurity competition, HEXNOVA aims to provide the tools and environment to make it happen.

Explore the HEXNOVA ecosystem

Platform| Description
🌐 Official Website| https://hexnova.space
🚩 CTF Platform| https://ctf.hexnova.space
💻 GitHub| https://github.com/hexnovactf
💬 Discord| https://discord.gg/3VJzX7bTC
📸 Instagram| https://www.instagram.com/hexnova.space

---

🚀 Core Features

Feature| Description
🚩 CTF Challenge Management| Create, organize, and manage cybersecurity challenges
🌐 Web Exploitation| Practice web security and vulnerability analysis
🔐 Cryptography| Explore encryption, decryption, and cryptographic puzzles
🧩 Reverse Engineering| Analyze binaries, programs, and application behavior
💻 Binary Exploitation| Practice low-level security and memory exploitation
🔎 Digital Forensics| Investigate files, artifacts, and digital evidence
🕵️ OSINT| Develop open-source intelligence investigation skills
📊 Live Scoreboard| Track competition rankings and player progress
👥 Team & Solo Competition| Participate individually or collaborate with teams
🐳 Isolated Challenge Instances| Container-based environments for supported challenges
⚖️ Dynamic Scoring| Challenge scoring that adapts to solve activity
🔒 Flag Validation| Static and regex-based flag validation
📝 Writeups & Learning| Share solutions and learn from the community
🛠️ Admin Dashboard| Manage users, challenges, events, and submissions

Feature availability depends on the deployed platform configuration.

---

🎯 Who Is HEXNOVA For?

- Beginners: Start learning cybersecurity through practical challenges.
- CTF Players: Improve your problem-solving and exploitation skills.
- Ethical Hackers: Practice security techniques in designated environments.
- Students: Build hands-on knowledge alongside academic learning.
- Developers: Understand application security and secure development.
- CTF Organizers: Build and manage cybersecurity competitions.

---

🧠 CTF Categories

Explore different areas of cybersecurity through practical challenges.

Category| Skills
🌐 Web| SQL Injection, XSS, SSRF, Authentication
🔐 Crypto| Ciphers, Encoding, Encryption
💻 Pwn| Buffer Overflows, Memory Corruption
🧩 Reverse Engineering| Binary Analysis, Debugging
🔎 Forensics| File Analysis, Metadata, Memory
🕵️ OSINT| Reconnaissance, Intelligence Gathering
⚙️ Misc| Programming, Logic, Problem Solving

---

⚡ Getting Started

Play CTF Challenges

1. Visit https://ctf.hexnova.space
2. Create an account or sign in.
3. Explore available challenges.
4. Choose a category and difficulty.
5. Solve challenges and submit your flags.
6. Track your progress on the scoreboard.

Host Your Own CTF

HEXNOVA is designed to support cybersecurity event management and challenge hosting.

Organizers can configure challenges, competition settings, participants, and scoring through the platform's supported administration features.

---

🛠️ Self-Hosting & Installation

Requirements

- Git
- Docker
- Docker Compose
- A supported database
- Linux server or local development environment

Clone the repository

git clone https://github.com/hexnovactf/hexnova.git

cd hexnova

Configure environment variables

cp .env.example .env

Update the configuration with your own secure values.

Variable| Purpose
"SECRET_KEY"| Application session signing key
"DATABASE_URL"| Database connection
"ADMIN_EMAIL"| Initial administrator email
"EVENT_START"| Competition start time
"EVENT_END"| Competition end time

Start with Docker Compose

docker compose up -d

Check running containers:

docker compose ps

Check application logs:

docker compose logs -f

Note: Verify the repository's actual Docker configuration, environment variables, database requirements, and application port before using these instructions in production.

---

🧱 Technology Stack

Layer| Technology
Frontend| To be confirmed
Backend| To be confirmed
Database| To be confirmed
Containerization| Docker
Deployment| To be confirmed
Infrastructure| To be confirmed

---

🗺️ Roadmap

Our development roadmap focuses on improving the platform and expanding the cybersecurity learning experience.

- [ ] Public API for scoreboard integration
- [ ] Advanced challenge management
- [ ] Team-versus-team practice rooms
- [ ] Player profiles and achievement badges
- [ ] CTFtime integration
- [ ] Improved analytics and event reporting
- [ ] Enhanced documentation
- [ ] More beginner-friendly learning resources
- [ ] Additional challenge categories

---

📚 Documentation & Resources

Explore HEXNOVA and stay connected with the ecosystem.

Resource| Link
Official Website| https://hexnova.space
CTF Portal| https://ctf.hexnova.space
GitHub Organization| https://github.com/hexnovactf
Discord Community| https://discord.gg/3VJzX7bTC
Instagram| https://www.instagram.com/hexnova.space

For platform-specific installation and configuration instructions, refer to the repository documentation.

---

💬 Support & Contact

Need assistance, want to report a technical issue, or interested in collaborating with HEXNOVA?

We're happy to hear from you.

Department| Contact
General Enquiries| contact@hexnova.space
Technical Support| support@hexnova.space
Security Reports| security@hexnova.space
Community Support| https://discord.gg/3VJzX7bTC
Website| https://hexnova.space

Support guidelines:

- General enquiries: Contact us for questions about HEXNOVA.
- Technical support: Report installation issues, bugs, or platform problems.
- Security reports: Privately disclose vulnerabilities affecting the platform.
- Community: Join Discord for announcements, discussions, and assistance.

Email addresses should be configured and tested before publishing this README.

---

🔐 Security & Responsible Disclosure

The security of HEXNOVA and its community is important to us.

If you discover a vulnerability affecting the HEXNOVA platform or infrastructure, please report it privately.

Security contact: security@hexnova.space

Please include:

1. A clear vulnerability description.
2. Steps to reproduce the issue.
3. Potential security impact.
4. Supporting evidence or a proof of concept.

Please do not publicly disclose unpatched vulnerabilities.

All testing must remain within authorized environments and designated CTF challenge scopes. Attacks against other competitors or platform infrastructure are not permitted during competitions.

---

🤝 Contributing to HEXNOVA

We welcome contributions from cybersecurity researchers, developers, CTF players, and open-source enthusiasts.

You can contribute through:

- Bug fixes and improvements.
- New CTF challenges.
- Documentation updates.
- Feature suggestions.
- Security improvements.
- Community collaboration.

Contribution workflow

# Fork the repository first

git clone https://github.com/hexnovactf/hexnova.git

cd hexnova

git checkout -b feature/your-feature

# Make your changes

git add .

git commit -m "Add: your feature"

git push origin feature/your-feature

Then open a Pull Request on GitHub with a clear explanation of your changes.

For challenge contributions, include the challenge source, Dockerfile where applicable, flag configuration, and a working solution or validation procedure.

---

🌟 Join the HEXNOVA Community

Cybersecurity is best learned through practice, collaboration, and continuous exploration.

Be part of the community, participate in challenges, share knowledge, and help build the future of practical cybersecurity learning.

<p align="center">
  <a href="https://ctf.hexnova.space">🚩 PLAY CTF</a> •
  <a href="https://discord.gg/3VJzX7bTC">💬 JOIN DISCORD</a> •
  <a href="https://github.com/hexnovactf">⭐ EXPLORE GITHUB</a>
</p>---

📄 License

This project is intended to be released under the MIT License.

See the "LICENSE" (LICENSE) file for complete licensing terms.

Confirm that the repository's actual LICENSE file matches before publishing.

---

<p align="center">
  <strong>⚡ Built with passion by the HEXNOVA Team</strong>
  <br/>
  <sub>Build • Host • Compete • Learn</sub>
  <br/><br/>
  <a href="https://hexnova.space">hexnova.space</a>
</p>