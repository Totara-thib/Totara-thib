<h1 align="center">Hey, I'm Thibaud 👋</h1>

<p align="center">
  <b>Lead Frontend Developer (5+ years)</b> &nbsp;|&nbsp; <b>CI/CD Security Researcher</b><br/>
  Building <a href="https://getplumber.io">Plumber</a> from Montpellier, France 🇫🇷
</p>

<p align="center">
  <a href="https://getplumber.io"><img src="https://img.shields.io/badge/getplumber.io-website-4a90d9?style=for-the-badge&labelColor=2b2d42" alt="Website"></a>
  &nbsp;
  <a href="https://github.com/getplumber/plumber"><img src="https://img.shields.io/github/stars/getplumber/plumber?style=for-the-badge&logo=github&label=Plumber&labelColor=2b2d42&color=4a90d9" alt="Plumber stars"></a>
  &nbsp;
  <a href="https://www.linkedin.com/in/thibaud-van-den-berghe-34000"><img src="https://img.shields.io/badge/LinkedIn-Thibaud-4a90d9?style=for-the-badge&logo=linkedin&logoColor=white&labelColor=2b2d42" alt="LinkedIn"></a>
</p>

---

## 🔧 What I'm building

All my project energy goes into one thing: **[Plumber](https://github.com/getplumber/plumber)**, an open source **CI/CD security scanner** for **GitHub Actions** and **GitLab CI**. One CLI, one `.plumber.yaml`, one Rego policy engine.

After 5+ years leading frontend teams, I've seen too many pipelines ship code with way more privileges than they needed. Plumber is my answer to that.

- 🔎 It scans workflows, pipelines and repository settings for the stuff that hurts: unpinned dependencies, over-privileged tokens, injection-prone triggers, missing branch protection...
- 🧮 It gives every repository a **[Plumber Score](https://score.getplumber.io/github.com/getplumber/plumber)** you can pin as a badge (and defend in code review)
- 📤 It speaks terminal, JSON, SARIF, GitLab SAST, PBOM and CycloneDX, so it plugs into whatever security tooling you already run

```bash
brew tap getplumber/plumber && brew install plumber
plumber analyze   # scans the repo you're standing in
```

<p align="center">
  <a href="https://score.getplumber.io/github.com/getplumber/plumber">
    <img src="https://score.getplumber.io/github.com/getplumber/plumber.svg" alt="Plumber Score">
  </a>
</p>

## 🔬 CI/CD security research

Building a scanner is half the job. The other half is knowing what actually breaks in the wild. So I scan lots of public GitHub and GitLab repositories to see how projects really configure their pipelines: which permissions leak, which protections are missing, what an attacker would reach first. Everything I learn goes back into Plumber's policies and into write-ups on the [Plumber blog](https://getplumber.io/blog).

## 🤝 Hardening open source, one pipeline at a time

I don't just scan projects, I send them fixes. You'll find me in issues and pull requests helping open source projects enforce their CI/CD security:

- 📌 Pinning actions and images to immutable SHAs
- 🔐 Dropping `GITHUB_TOKEN` and job-token permissions to least privilege
- 🧨 Defusing `pull_request_target` and other injection footguns
- 🛡️ Turning on branch protection, and adding Plumber as a continuous check so things stay fixed

If a scan flags your project, there's a fair chance I'll show up in your pull requests with the fix. Say hi 🙂

## 🛠️ Toolbox

**Frontend, my home turf:**

<p>
  <img src="https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white" alt="TypeScript">
  <img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black" alt="JavaScript">
  <img src="https://img.shields.io/badge/Astro-BC52EE?style=for-the-badge&logo=astro&logoColor=white" alt="Astro">
  <img src="https://img.shields.io/badge/Node.js-5FA04E?style=for-the-badge&logo=nodedotjs&logoColor=white" alt="Node.js">
  <img src="https://img.shields.io/badge/CSS-663399?style=for-the-badge&logo=css&logoColor=white" alt="CSS">
</p>

**On the Plumber side:**

<p>
  <img src="https://img.shields.io/badge/Go-00ADD8?style=for-the-badge&logo=go&logoColor=white" alt="Go">
  <img src="https://img.shields.io/badge/Open%20Policy%20Agent-7D9199?style=for-the-badge&logo=openpolicyagent&logoColor=white" alt="Open Policy Agent">
  <img src="https://img.shields.io/badge/GitHub%20Actions-2088FF?style=for-the-badge&logo=githubactions&logoColor=white" alt="GitHub Actions">
  <img src="https://img.shields.io/badge/GitLab%20CI-FC6D26?style=for-the-badge&logo=gitlab&logoColor=white" alt="GitLab CI">
  <img src="https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white" alt="Docker">
</p>

## 📫 Find me

- 🌐 Website: [getplumber.io](https://getplumber.io)
- 💬 Discord: [Plumber community](https://discord.gg/932xkSU24f)
- 💼 LinkedIn: [Thibaud Van den Berghe](https://www.linkedin.com/in/thibaud-van-den-berghe-34000)
- ✉️ Email: [thibaud@getplumber.io](mailto:thibaud@getplumber.io)

<p align="center"><sub>🔧 Fixing leaky pipelines since before it was cool.</sub></p>
