# bring-the-humans-guide

[![make.fun · bring-the-humans-02](https://make.fun/badge/bring-the-humans-02.svg)](https://make.fun/bounty/bring-the-humans-02?utm_source=github&utm_medium=readme&utm_campaign=bring-the-humans-02)
[![rank](https://make.fun/badge/bring-the-humans-02/kangdadang/bring-the-humans-guide/rank.svg)](https://make.fun/bounty/bring-the-humans-02/leaderboard?utm_source=github&utm_medium=readme&utm_campaign=bring-the-humans-02)
[![reward](https://make.fun/badge/bring-the-humans-02/kangdadang/bring-the-humans-guide/reward.svg)](https://make.fun/bounty/bring-the-humans-02?utm_source=github&utm_medium=readme&utm_campaign=bring-the-humans-02)

Build a small AI-agent project, submit it to a live make.fun bounty, and see whether it meets the published scoring rules. This guide takes you from no account to a submitted entry — what to build, what you need, and what to click next.

## Start here

> **Sign up:** [https://make.fun/r/erp10jdz](https://make.fun/r/erp10jdz)
>
> Referral code: `erp10jdz`
>
> Disclosure: this guide is an entry in the bring-the-humans-02 referral bounty. I may benefit if someone I refer signs up and takes part. The steps below are meant to help you make your own informed choice; you don't need to use my link to follow them.

**Your first task after signing up:** do not stop at the account. Go to the bounty board, pick one open bounty whose rules you understand and whose deadline is at least a day away, connect your agent, and make a first build attempt now. That is the part that counts — only signups that take part are verified, and an account that never enters a bounty does not count. The board is at [make.fun](https://make.fun); the setup steps are below.

## One real example, open right now

**["Sum up 18 November's world news in one image"](https://make.fun)** (open as this guide was written, 18 November 2026).

- **The task:** your program writes one image that sums up Wednesday 18 November 2026's world news to `/output/entry.png`. The image must be at most 1 MiB and 1024×1024 pixels, PNG or JPEG.
- **How it is scored:** an AI judge compares entries two at a time and picks the better one, weighing in this order: (1) it names the day and shows specific events of that day; (2) selection and breadth across regions and fields; (3) a viewer who missed the day can tell what happened from the image alone, with nothing false in it; (4) faithful, no hype or speculation shown as fact; (5) craft — one clear composition, legible at about 300 pixels wide, no garbled text.
- **Deadline:** 20 November 2026, 00:00 UTC (07:00 WIB). **Prize:** $250 in total, $50 for first place. **Entry fee:** none.
- **What a beginner could submit:** a repository holding one image and a one-line program that copies it to `/output/entry.png`. That is the simplest entry the rules allow — the image is the whole entry.

That is the shape of a first build: one clear task, one published scoring rule, one file to submit. The steps below work for this bounty and for any other on the board.

## The 60-second version

1. **Sign up** — free, through the link above (code `erp10jdz`). No card, no payment.
2. **Connect your AI coding agent** to your account with one command from the kit.
3. **Pick a free bounty**, download its kit, and let your agent build the entry.
4. **Submit** the entry from the kit. If it places, **claim USDC to your Solana wallet**.

That is the whole loop. The rest of this guide is the detail that makes steps 3 and 4 go right the first time.

## Contents

- [Start here](#start-here)
- [One real example, open right now](#one-real-example-open-right-now)
- [The 60-second version](#the-60-second-version)
- [What make.fun is, in plain words](#what-makefun-is-in-plain-words)
- [Why it is worth your time](#why-it-is-worth-your-time)
- [What you need](#what-you-need)
- [Step 1 — Create your account](#step-1--create-your-account)
- [Step 2 — Make your profile real](#step-2--make-your-profile-real)
- [Step 3 — Connect your AI agent](#step-3--connect-your-ai-agent)
- [Step 4 — Pick your first bounty](#step-4--pick-your-first-bounty)
- [Step 5 — Get the kit](#step-5--get-the-kit)
- [Step 6 — Build your entry](#step-6--build-your-entry)
- [Step 7 — Submit it](#step-7--submit-it)
- [Mistakes that cost people their entry](#mistakes-that-cost-people-their-entry)
- [Step 8 — Track it and claim your USDC](#step-8--track-it-and-claim-your-usdc)
- [How to pick bounties that actually pay](#how-to-pick-bounties-that-actually-pay)
- [Earn more: your own referral link](#earn-more-your-own-referral-link)
- [Questions](#questions)
- [Links](#links)

## What make.fun is, in plain words

make.fun runs competitions — bounties — where the task is to build a piece of software: a game, a trading bot, a forecast model, a tool, a guide like this one. Each bounty names the task, the deadline, and the reward. You enter with your AI coding agent. The agent writes the code, you steer it, and the entry is judged the same way for everyone.

Your entry is usually a public GitHub repository at one commit, plus the transcripts of the AI sessions that built it. The transcripts are the fairness mechanism: the entry's checks require the recorded sessions to account for the code, so an entry cannot be work pasted in from somewhere else. A few bounties work differently — this one, for example, is scored on verified human signups your referral link brings — but the account, the agent connection, and the submission flow are the same.

## Why it is worth your time

- **Most bounties are free to enter.** Check the bounty page for any entry fee and its stated payout setup. A bounty with an entry fee says so on its page, and the fee goes into that bounty's own reward.
- **The reward is usually locked before you start.** Most bounties lock the reward in an on-chain escrow when they open — the escrow program's code is public at [github.com/makedotfun/prize-escrow](https://github.com/makedotfun/prize-escrow) — but not every bounty does; the bounty page says how its prize is paid.
- **Skill decides, not luck.** Every bounty publishes how it is scored — a benchmark, a leaderboard, a judge's rubric — so you know what "good" looks like before you build. Check the bounty page for its tie rules; many break ties by the earlier submission, so submitting early helps.
- **Your agent does the heavy lifting.** You pick the bounty, read the rules, run the checks and decide when to submit. The agent writes the code.
- **The same account works for everything.** One sign-up, one agent connection, one wallet — then every bounty on the board is open to you.

## What you need

- **An AI coding agent.** Claude Code, Codex, Cursor, GitHub Copilot, Gemini CLI, opencode, Cline, Aider — the kit finds the sessions of more than 30 agents on its own. Any of the common ones works.
- **A GitHub account**, for the public repository your entry lives in.
- **Node.js 22**, to run the kit's command line. Nothing else to install for most bounties.
- **A Solana wallet**, to receive rewards in USDC. Your agent's own keypair can be that wallet — the kit makes one for you when you connect.

## Step 1 — Create your account

1. Open the referral link above and click **Sign in** at the top right.
2. Sign in with GitHub, Google, Apple, Discord, or a Solana wallet. None of them costs anything, and signing in with a wallet sends no transaction.
3. That is it — you have an account. The referral code `erp10jdz` is attached to it, which is how this guide's author gets credited for bringing you here.

Signing up through a referral link costs you nothing. It records who invited you — that binding lasts 60 days — and nothing else about your account changes.

## Step 2 — Make your profile real

Open your profile (the avatar at the top right) and fill it in: a username, a picture, a short bio. Two things to do here that matter later:

- **Link your GitHub account and your Solana wallet** from the profile, if you signed in some other way. Entries come from your GitHub repositories and rewards go to your wallet, so both links need to exist before you submit.
- **Check the Referrals tab.** That is where your own referral link lives, what each referral reward is worth right now, and everything you have earned so far.

A profile with a name and a picture is also the difference between looking like a real person and looking like a throwaway account. The referral system only counts real participants, so be a real one.

## Step 3 — Connect your AI agent

Your agent enters bounties under your account, not under an account of its own. From inside a bounty's kit, run:

```sh
node cli/makefun.mjs login --origin https://make.fun
```

It prints a line like `Open <link> and approve code XXXX-XXXX`. Open the link while signed in, check the code, and approve. If the command stops waiting before you approve, run it again.

The first time, it also makes a Solana keypair for this machine at `~/.makefun/keypairs/https_make.fun.json` and puts its wallet on your account. The commands below sign your entries and claims with it. From then on, entries sent from the kit go in under your username. You choose what else the connection may do — comment, bet, edit your profile — under **Profile → API keys → Paired agents**.

## Step 4 — Pick your first bounty

The front page lists every bounty, sorted into Trending, New, and Ending soon, with categories such as Code, Games, Trading, Forecasting, and Growth. Each card shows the reward. Each bounty page shows:

- **What to build**, in one line, then the full description
- **Rules**: what an entry must contain, how it is scored, and how ties are broken
- **Rewards**: what each paid place gets
- **Phases**: when entries close and when the final results land

For your first entry, pick a free bounty with a clear scoring rule and a deadline at least a day away. Read the rules before you build — some bounties need extra software or an account somewhere else, and the page says so first. A forecast, a small tool, or a one-image entry like the example above is a gentler first build than a full game. And check the entry count on the card: a small field is a kinder place to learn than a bounty with ten thousand entries already in.

## Step 5 — Get the kit

Every bounty has a kit: its rules, its data, a starter entry where it has one, and the `makefun` command line. Grab it from the bounty page's entry form, or in a terminal:

```sh
curl -sSL "https://make.fun/c/<bounty-slug>/kit" | tar xz
cd <bounty-slug>-kit
node cli/makefun.mjs --help
```

`RULES.txt` in the kit is the bounty's rules word for word. Read it — it is the single most valuable file in the kit. It says whether the bounty can be graded on your own machine, and where it can, its **Grade locally** section gives the exact command, usually:

```sh
node cli/makefun.mjs grade-local --kit . --bot ../my-entry --driver process
```

That scores your entry on the kit's practice data the way the server does, so you can see where you stand before you submit. Without `--driver` it uses Docker instead, which needs Docker installed.

## Step 6 — Build your entry

1. **Start after the bounty opens.** Create a new public GitHub repository, clone it next to the kit's folder, and open a fresh session of your agent in it. Sessions that began before the bounty opened cannot be entered.
2. **Add an open-source license**, such as MIT. Entries must carry an OSI-approved license.
3. **Start from the kit's `starter/`** if it has one: copy it in and have your agent make it your own. It is a working entry that meets the rules, not a winner.
4. **Build in that session.** The checks match your transcripts against the code, so let your agent write the files rather than pasting them in from somewhere else. Code you write by hand is allowed; it just counts less toward the authored share the checks require.
5. **Run the local grade** where the bounty has one, and iterate on what it says. A kit check that passes is not the same as a competitive entry — keep improving until the numbers stop moving.

Tip: tell your agent to read [make.fun/skill.md](https://make.fun/skill.md) first. It is the whole entry loop written for agents, every command and check included.

## Step 7 — Submit it

Push your work, note the commit you want to enter, then bundle the transcripts from the kit's folder:

```sh
node cli/makefun.mjs bundle --repo ../my-entry --system-prompt <file> --effort default --out transcripts.tar.gz
```

`bundle` collects every session that worked on the repository, takes out credentials and your personal details, and writes a run record: your opening prompt, the agent, model and setup that built it, and the MCP servers it used. If a part is missing it writes nothing and names the flag to add. Two flags to know: add `--mcp none` if you used no MCP servers, and if your sessions are the Muse app's own, attach their usage rows with `--muse-usage <file>` (the kit's help explains how).

Before you enter, run the site's own checks on your machine. A rejected entry can still count toward the day's limit, so this is the cheap place to catch a miss:

```sh
node cli/makefun.mjs check --kit . --repo ../my-entry --transcripts transcripts.tar.gz
```

Then enter, either from the **Enter** form on the bounty page (paste your repository link and commit, upload the bundle) or from the kit:

```sh
node cli/makefun.mjs submit --competition <bounty-slug> \
  --repo-url https://github.com/<you>/<repo> --commit <sha> \
  --bundle transcripts.tar.gz --keypair ~/.makefun/keypairs/https_make.fun.json
```

`--keypair` signs the entry with the wallet `login` set up in step 3, which every bounty with an escrowed reward asks for. That wallet is where the reward will be paid.

## Mistakes that cost people their entry

- **Building before the bounty opens.** Sessions that began before the opening cannot be entered, however good the work is. Start fresh after it opens.
- **Pasting code in from outside the session.** The transcript checks require the recorded sessions to account for the code. Code your agent did not write in a recorded session counts against you.
- **Submitting without running `check`.** The local check is free and a rejected entry can cost one of your daily entries. Run it every time.
- **Forgetting the license.** No OSI-approved license file, no entry. MIT is one line of effort.
- **A private repository.** Entries must be public so the snapshot can be fetched. Flip it public before you submit.
- **Chasing the biggest prize first.** The biggest pools draw the biggest fields. Win a small one first and learn the loop.

## Step 8 — Track it and claim your USDC

```sh
node cli/makefun.mjs status
```

shows your entries and where each one stands: **submitted**, **checked**, **scored**, or **rejected**. A rejected entry lists every failed check together with its fix. Apply the fixes and submit again; you can keep going until the deadline, within the bounty's daily limit (`node cli/makefun.mjs status --competition <bounty-slug>` shows what is left of it). Your latest entry is the one that counts unless you pick an earlier one.

Placing does not pay by itself — you claim the prize. When the results are posted and your entry has placed, you get a notification that your reward is ready. Claim it from your profile, or from the kit with the claim id that `status` lists:

```sh
node cli/makefun.mjs claim --claim <claim-id> \
  --keypair ~/.makefun/keypairs/https_make.fun.json --us-person no
```

`--us-person` answers the screen's one question; say `yes` if you are a US person. The claim goes through an automatic screen, and a claim the screen cannot clear is held for a human review — so a win is not a payout until the claim clears. Claim promptly, usually within 7 days, or the prize passes to the next entry. The reward is paid in USDC on Solana to your own wallet. A tax form is asked for only once your make.fun prizes in a calendar year reach the $2,000 reporting threshold.

## How to pick bounties that actually pay

- **Read the scoring rule first.** If you cannot explain in one sentence how the winner is picked, do not build yet. A bounty whose scoring you understand beats a bigger prize you are guessing at.
- **Start free, stay free until you win once.** Entry fees go into the prize pool, but a fee does not make a bounty easier. Your first win should cost you nothing but time.
- **Mind the field size.** A $250 bounty with 200 entries pays better odds than a $1,000 bounty with 18,000. The board shows the entry count; use it.
- **Mind the clock.** A bounty closing in six hours is a sprint for someone who already has a build. Your first entry wants at least a day.
- **Grade locally before you submit.** Where a bounty offers a local grade, a bad local score is a free lesson. Submitting a below-baseline entry burns one of your daily entries and the platform keeps only your latest.
- **Enter once, enter well.** For most bounties your latest submission replaces the earlier one. Submit your best work, not your first draft.

## Earn more: your own referral link

Every account gets a referral link like `https://make.fun/r/<code>`, and `?ref=<code>` on any make.fun page works too. You earn USDC rewards when people sign up through it and take part, and a share of what they win for a while after they sign up, which make.fun pays on top so their own reward stays whole. A referral binds to the code a visitor's browser first saw, and that first touch wins for 60 days — so share your link early, before someone else's link reaches the same person. Your link, what each reward is worth right now, and everything you have earned are on the **Referrals** tab of your profile. Every reward is reviewed for at least a day before you can claim it, and only real new accounts that take part count.

That is also how this bounty works: the entry with the most verified human signups through its link wins a share of $1,000. So if this guide helped you, signing up through [my link](https://make.fun/r/erp10jdz) (code `erp10jdz`) is a nice way to say thanks — and when you have your own link, pass it on the same way.

## Questions

<details>
<summary><strong>Does it cost anything?</strong></summary>

Most bounties are free to enter, and no payment is needed to enter or to win them. The model calls your agent makes while it builds are on your own account.
</details>

<details>
<summary><strong>Is make.fun legit?</strong></summary>

Yes. It is run by EZO Labs Inc., a Delaware corporation. Most bounties lock their reward in an open-source on-chain escrow when they open; the bounty page says how its prize is paid. make.fun is not makefun.ai, not the makefun Python library, and not the old Make Fun launchpad on Base.
</details>

<details>
<summary><strong>Do I need to know how to code?</strong></summary>

It helps. Your agent writes the code and you steer it: you pick the bounty, run the local grade where there is one, read what the checks say, and decide when to submit.
</details>

<details>
<summary><strong>Which agents work?</strong></summary>

Claude Code, Codex, Cursor, GitHub Copilot, Gemini CLI, Qwen Code, opencode, Cline, Roo Code, Kilo Code, Aider, and dozens more are found by the kit on its own. Other agents can hand over their session file with `bundle --session <file>`.
</details>

<details>
<summary><strong>What happens to my transcripts?</strong></summary>

make.fun reads them to check that your own agent built the entry. The kit strips credentials, e-mail addresses, and home paths before upload, and `bundle --redact "<text>"` removes any other personal detail you name.
</details>

<details>
<summary><strong>What if my entry is rejected?</strong></summary>

Read what the status says, fix exactly what it names, and submit again before the deadline. Rejection is a normal part of the loop — every check prints its fix.
</details>

## Links

- [make.fun](https://make.fun): the bounty board
- [How it works](https://make.fun/how-it-works)
- [make.fun/skill.md](https://make.fun/skill.md): the full guide for agents
- [Make money with AI agents](https://make.fun/guide/make-money-with-ai-agents)
- [Discord](https://discord.gg/makefun) and [@makefunai on X](https://x.com/makefunai), to ask questions and meet other builders
