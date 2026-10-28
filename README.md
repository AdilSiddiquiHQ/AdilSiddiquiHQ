<div align="center">

<h1>Adil Siddiqui</h1>

**Founder, [NinjaLabs](https://www.adilsiddiqui.xyz/)** &nbsp;·&nbsp; I build software that runs where there is no server.

<sub>Local-first apps &nbsp;·&nbsp; agent tooling that survives adversarial input &nbsp;·&nbsp; whatever the problem actually needs</sub>

<br />

<a href="https://www.adilsiddiqui.xyz/"><img alt="Website" src="https://img.shields.io/badge/Website-0D1117?style=flat-square" /></a>
<a href="https://www.linkedin.com/in/adilsiddiquihq"><img alt="LinkedIn" src="https://img.shields.io/badge/LinkedIn-0D1117?style=flat-square&amp;logo=linkedin&amp;logoColor=white" /></a>
<a href="https://x.com/AdilSiddiquiHQ"><img alt="X" src="https://img.shields.io/badge/-0D1117?style=flat-square&amp;logo=x&amp;logoColor=white" /></a>
<a href="https://www.youtube.com/@ninjaxhustlerr"><img alt="YouTube" src="https://img.shields.io/badge/YouTube-0D1117?style=flat-square&amp;logo=youtube&amp;logoColor=white" /></a>
<a href="https://www.instagram.com/ninjaxhustlerr"><img alt="Instagram" src="https://img.shields.io/badge/Instagram-0D1117?style=flat-square&amp;logo=instagram&amp;logoColor=white" /></a>

</div>

> **Now:** **Save & Send** `1.3.2` · **SkillSleuth** `0.4.0` · agent infrastructure at **NinjaLabs**

---

## Selected work

### [Save & Send](https://github.com/AdilSiddiquiHQ/save-and-send)

<p>
  <img alt="v1.3.2" src="https://img.shields.io/github/v/release/AdilSiddiquiHQ/save-and-send?style=flat-square&amp;labelColor=0D1117&amp;color=161B22" />
  <img alt="Flutter" src="https://img.shields.io/badge/Flutter-161B22?style=flat-square&amp;logo=flutter&amp;logoColor=white" />
  <img alt="Android 7.0+" src="https://img.shields.io/badge/Android%207.0%2B-161B22?style=flat-square&amp;logo=android&amp;logoColor=white" />
  <img alt="arm64-v8a" src="https://img.shields.io/badge/arm64--v8a-161B22?style=flat-square" />
  <img alt="No backend" src="https://img.shields.io/badge/no%20backend-161B22?style=flat-square" />
</p>

A private Android app that turns a shared Instagram, Facebook, YouTube or TikTok link into an MP4 that WhatsApp will actually accept. Format selection, audio muxing, trimming and `+faststart` all happen on the phone — no accounts, no analytics, no server that has to be trusted with your links.

<sub>8 releases · CI on every push · translations in Arabic and Urdu</sub>

### [SkillSleuth](https://github.com/AdilSiddiquiHQ/skillsleuth)

<p>
  <img alt="v0.4.0" src="https://img.shields.io/github/v/release/AdilSiddiquiHQ/skillsleuth?style=flat-square&amp;labelColor=0D1117&amp;color=161B22" />
  <img alt="Node 18+" src="https://img.shields.io/badge/Node%20%E2%89%A518-161B22?style=flat-square&amp;logo=nodedotjs&amp;logoColor=white" />
  <img alt="Zero runtime dependencies" src="https://img.shields.io/badge/0%20runtime%20deps-161B22?style=flat-square" />
  <img alt="75 rules" src="https://img.shields.io/badge/75%20rules-161B22?style=flat-square" />
  <img alt="SARIF + CycloneDX" src="https://img.shields.io/badge/SARIF%20%C2%B7%20CycloneDX-161B22?style=flat-square" />
</p>

A security scanner for AI agent skills. Every other scanner reads the file; SkillSleuth reads *views* of the file — raw, deobfuscated, decoded and unpacked — so it reports the payload **and** the trick used to hide it. Built as a direct answer to the Trail of Bits audit that walked past the entire first generation of these tools in under an hour each.

<sub>Reports its own false-positive rate instead of asserting precision</sub>

### [a11y-skills](https://github.com/AdilSiddiquiHQ/a11y-skills)

<p>
  <img alt="v0.4.0" src="https://img.shields.io/github/v/release/AdilSiddiquiHQ/a11y-skills?style=flat-square&amp;labelColor=0D1117&amp;color=161B22" />
  <img alt="WCAG 2.2" src="https://img.shields.io/badge/WCAG%202.2-161B22?style=flat-square" />
  <img alt="70 of 86 criteria" src="https://img.shields.io/badge/70%20of%2086%20criteria-161B22?style=flat-square" />
  <img alt="14 executable fixtures" src="https://img.shields.io/badge/14%20fixtures-161B22?style=flat-square" />
  <img alt="MIT" src="https://img.shields.io/badge/MIT-161B22?style=flat-square" />
</p>

33 procedures covering **every WCAG 2.2 Level A and AA success criterion**, plus an audit command that maps each axe-core finding to the exact skill that fixes it. Each skill is a procedure — when to reach for it, ordered steps, a verification step, and the failure modes — because that is the shape an agent can follow and a reviewer can reject in a pull request.

<sub>Zero runtime dependencies · installs with a single <code>npx</code> call</sub>

### [Chess vs. a Fruit Fly](https://github.com/AdilSiddiquiHQ/fly-connectome-chess)

<p>
  <img alt="5,065,217 parameters" src="https://img.shields.io/badge/5M%20params-161B22?style=flat-square" />
  <img alt="9,353 self-play games" src="https://img.shields.io/badge/9%2C353%20self--play%20games-161B22?style=flat-square" />
  <img alt="PyTorch" src="https://img.shields.io/badge/PyTorch-161B22?style=flat-square&amp;logo=pytorch&amp;logoColor=white" />
  <img alt="Three.js" src="https://img.shields.io/badge/Three.js-161B22?style=flat-square&amp;logo=threedotjs&amp;logoColor=white" />
  <img alt="Runs offline" src="https://img.shields.io/badge/runs%20offline-161B22?style=flat-square" />
</p>

A 3D chess opponent that physically picks up your pieces and flies them across the board. Every legal move is scored by a five-million-parameter network trained on 9,353 self-play games — no search tree, no engine. The telemetry sidebar is half real and half theatre, and the README says exactly which half is which.

<sub>Named after the FlyWire dataset. Honest about not using it yet.</sub>

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

## How this started

2023. I was thirteen, writing Discord bots and Minecraft AFK scripts for servers I did not own, with no tests, no CI and no idea what I was doing. Those repos are still public — I keep them because the curiosity in them is the same engine as everything above, just with worse naming.

Everything since has been one long attempt to keep that curiosity and add the discipline.

---

<div align="center">

<sub>Most of my work is private. The four above are the ones worth reading.</sub>

</div>
