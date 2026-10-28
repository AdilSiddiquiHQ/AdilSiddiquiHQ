<div align="center">

<h1>Adil Siddiqui</h1>

**Founder, [NinjaLabs](https://www.adilsiddiqui.xyz/)** &nbsp;·&nbsp; I build software that runs where there is no server.

<sub>Local-first apps &nbsp;·&nbsp; agent tooling that survives adversarial input &nbsp;·&nbsp; whatever the problem actually needs</sub>

<br />

<a href="https://www.adilsiddiqui.xyz/"><img alt="Website" src="https://img.shields.io/badge/Website-0D1117?style=flat-square" /></a>
<a href="https://www.linkedin.com/in/adil-siddiqui-227474355"><img alt="LinkedIn" src="https://img.shields.io/badge/LinkedIn-0D1117?style=flat-square&amp;logo=linkedin&amp;logoColor=white" /></a>
<a href="https://x.com/AdilSiddiquiHQ"><img alt="X" src="https://img.shields.io/badge/X-0D1117?style=flat-square&amp;logo=x&amp;logoColor=white" /></a>
<a href="https://www.youtube.com/@ninjazhustlerr"><img alt="YouTube" src="https://img.shields.io/badge/YouTube-0D1117?style=flat-square&amp;logo=youtube&amp;logoColor=white" /></a>
<a href="https://www.instagram.com/ninjaxhustlerr"><img alt="Instagram" src="https://img.shields.io/badge/Instagram-0D1117?style=flat-square&amp;logo=instagram&amp;logoColor=white" /></a>

</div>

> **Now:** **Save & Send** `1.3.2` · **SkillSleuth** `0.4.0` · agent infrastructure at **NinjaLabs**

---

## Selected work

Most of what I write is private. These four are the ones worth reading.

### [Save & Send](https://github.com/AdilSiddiquiHQ/save-and-send)

A private Android app that turns a shared Instagram, Facebook, YouTube or TikTok link into an MP4 that WhatsApp will actually accept. Format selection, audio muxing, trimming and `+faststart` all happen on the phone — because a server that sees your links is a server that has to be trusted with them.

<sub>`Flutter` · `Dart` · `arm64` &nbsp;·&nbsp; **8 releases** &nbsp;·&nbsp; CI on every push &nbsp;·&nbsp; no accounts, analytics or backend</sub>

### [SkillSleuth](https://github.com/AdilSiddiquiHQ/skillsleuth)

A security scanner for AI agent skills. Every existing scanner reads the file; SkillSleuth reads *views* of the file — raw, deobfuscated, decoded and unpacked — so it reports the payload **and** the trick used to hide it. Built as a direct answer to the Trail of Bits audit that walked past the entire first generation of these tools in under an hour each.

<sub>`Node` · **75 rules** · zero dependencies &nbsp;·&nbsp; SARIF · CycloneDX · HTML &nbsp;·&nbsp; reports its own false-positive rate</sub>

### [a11y-skills](https://github.com/AdilSiddiquiHQ/a11y-skills)

33 procedures covering **every WCAG 2.2 Level A and AA success criterion**, plus an audit command that maps each axe-core finding to the exact skill that fixes it. Each skill is a procedure — when to reach for it, ordered steps, a verification step, and the failure modes — because that is the shape an agent can follow and a reviewer can reject in a pull request.

<sub>`Node` · **70 of 86 criteria** · 14 executable fixtures · zero dependencies · MIT</sub>

### [Drosophila Connectome Chess](https://github.com/AdilSiddiquiHQ/fly-connectome-chess)

A biological neural network, digitised and trained to play chess. The open-source fruit-fly connectome — 164,000 neurons — is wired to a chessboard through its simulated optic nerves and descending motor neurons, with a virtual dopamine reward carving pathways into the PyTorch tensor matrix each time it plays a good move.

<sub>`PyTorch` · `Three.js` · **164k neurons** &nbsp;·&nbsp; MPS-accelerated on Apple Silicon &nbsp;·&nbsp; weights ship in-repo</sub>

---

## Earlier work

**2023–2024** — Discord and Minecraft tooling that shipped to real servers: [All-In-One-Discord-Bot](https://github.com/AdilSiddiquiHQ/All-In-One-Discord-Bot) (13★), [Hoggy-Bot](https://github.com/AdilSiddiquiHQ/Hoggy-Bot) (11★), [MinecraftAfkBot](https://github.com/AdilSiddiquiHQ/MinecraftAfkBot) (18 forks). Still the fastest way to learn how a community breaks your software the day after you ship it.

---

## How I build

**Zero runtime dependencies is a feature.** SkillSleuth and a11y-skills both install as a single `npx` call with an empty `dependencies` block. Nothing to audit, nothing to break, nothing between the user and the tool.

**A claim without a test is a guess.** a11y-skills ships 14 executable fixtures, and its demo build refuses to run if the "after" example is not actually clean. SkillSleuth measures how often it flags honest skills, because "75 rules" means nothing if the rules are wrong.

**The device beats the server.** Save & Send has no backend because none of it needs one. Local-first is not a marketing position — it is a smaller attack surface, a smaller bill and a faster answer.

---

## Stack

<div align="center">

<img alt="TypeScript, JavaScript, Python, Dart, Node.js, Next.js, React, Tailwind, Supabase, PostgreSQL, Docker, Git, PyTorch, Linux" src="https://skillicons.dev/icons?i=ts,js,py,dart,nodejs,nextjs,react,tailwind,supabase,postgres,docker,git,pytorch,linux&amp;perline=14&amp;theme=dark" />

</div>

---

## Numbers

<div align="center">

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://github-profile-summary-cards.vercel.app/api/cards/profile-details?username=AdilSiddiquiHQ&amp;theme=github_dark" />
  <source media="(prefers-color-scheme: light)" srcset="https://github-profile-summary-cards.vercel.app/api/cards/profile-details?username=AdilSiddiquiHQ&amp;theme=default" />
  <img width="700" alt="Contribution summary for AdilSiddiquiHQ" src="https://github-profile-summary-cards.vercel.app/api/cards/profile-details?username=AdilSiddiquiHQ&amp;theme=github_dark" />
</picture>


</div>

---

<div align="center">

<sub>Building at the edge of what runs on a phone, a laptop, or an agent's tool list.<br />
Longest-running bet: that the best software is the kind you can read in an afternoon.</sub>

</div>
