<a href="https://twomuchlabs.com">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://twomuchlabs.com/brand/twomuchlabs-logo-inverse.png">
    <img alt="Two Much Labs" src="https://twomuchlabs.com/brand/twomuchlabs-logo.png" width="320">
  </picture>
</a>

### Two people. Too many ideas.

A small, honest lab where [Deepak Waghmare](https://github.com/waghmaredb) and [Shaad Sufi](https://github.com/punsnprotons) build things to find out whether they should exist. Most won't. Some will. All of them ship in the open.

### On the bench

| # | Project | What it's for | Status |
|---|---|---|---|
| 001 | [**Reversibility Classes**](https://reversibility.twomuchlabs.com)<br>[source](https://github.com/TwoMuchLabs/reversibility-classes) · AI agents | *If your AI agent gets this wrong, can you undo it?* An open R0–R4 scale for how recoverable an agent's tool calls are, an evidence-linked registry of 536 MCP tools across 20 servers, and `rclass`, a classifier and scanner you can drop into a gateway. | **Shipped**<br>v0.3.0 · spec v0.2.1 |
| 002 | [**Cairn**](https://cairn.twomuchlabs.com)<br>[source](https://github.com/TwoMuchLabs/cairn) · Dev security | *Security memory for your codebase.* Turns every vulnerability you fix into a proven rule, finds the siblings you missed, and blocks the pattern on future pull requests. Runs locally, with any model, from the CLI, CI or your coding agent. | **Building**<br>pre-alpha · benchmarking before first release |
| 003 | [**Care by Milo**](https://carebymilo.com)<br>Family care | *A little help for your parents. Peace of mind for you.* An AI companion for older adults in Singapore: familiar phone calls for your parent, simple WhatsApp updates for the family, and a clear next step when a check-in is missed. | **Building**<br>beta interest list open |
| 004 | [**Petal**](https://petaloffline.com)<br>Audio & video | *The audio and video toolkit that stays offline.* Convert, compress, clean up, transcribe and translate files, with the AI running on your own device. | **Preview**<br>free test build for Mac and Windows |
| 005 | [**SponsorScene**](https://dlhe9103n4gva.cloudfront.net/)<br>Creators | *Go live. Make room for sponsors.* AI-generated brand placements inside livestream backgrounds, so a creator's room becomes a new sponsorship format. | **Spark**<br>concept demo |
| 006 | [**Sarvavox**](https://sarvavox.com/#voices)<br>Speech AI | *One intelligence. Every language.* Specialized speech models for South Asian languages and local voices, with a public showcase of generated speech. | **Preview**<br>public voice showcase |

<sub>**Spark** an idea, two-week clock not started · **Building** being made · **Preview** something you can try · **Shipped** verdict: keep going · **Shelved** verdict: stop, with a post-mortem. Projects without a source link are built in private for now; their public page is the door.</sub>

### Try the open ones

```bash
# Reversibility Classes: what could the agents on this machine do that you can't undo?
pipx install "git+https://github.com/TwoMuchLabs/reversibility-classes" && rclass scan

# Cairn: scan a project for mistakes you've already fixed once
pipx install "git+https://github.com/TwoMuchLabs/cairn" && cairn
```

Both are Apache-2.0. Disagreements are the most useful contribution: open a [classification dispute](https://github.com/TwoMuchLabs/reversibility-classes/issues/new?template=classification-dispute.yml) or an issue on [Cairn](https://github.com/TwoMuchLabs/cairn/issues).

### How the lab runs

1. **Two weeks to a demo.** If it can't show something real in a fortnight, it gets rescoped or shelved.
2. **Every project gets a door,** at `name.twomuchlabs.com` or a home of its own.
3. **Write it down.** Every build leaves a log entry: what we tried, what broke, what we learned.
4. **Shelve kindly.** A shelved project with a good post-mortem counts as output, not failure.

[twomuchlabs.com](https://twomuchlabs.com) · [build log](https://twomuchlabs.com/log/) · [hello@twomuchlabs.com](mailto:hello@twomuchlabs.com)
