# Getting started with make.fun

[![make.fun · bring-the-humans-02](https://make.fun/badge/bring-the-humans-02.svg)](https://make.fun/bounty/bring-the-humans-02)
[![rank](https://make.fun/badge/bring-the-humans-02/mihawnk-nft/bring-the-humans-02-guide/rank.svg)](https://make.fun/bounty/bring-the-humans-02/leaderboard)
[![reward](https://make.fun/badge/bring-the-humans-02/mihawnk-nft/bring-the-humans-02-guide/reward.svg)](https://make.fun/bounty/bring-the-humans-02)

If you have ever wanted to earn money by building software with an AI coding
agent, this guide is your starting point. It explains what make.fun is, how
to create an account, how to pick a bounty, and how to submit an entry that
can actually win. No prior experience with AI agents is assumed.

> **Start here:** create your account with my referral link:
> **https://make.fun/r/02e4etp3** (referral code: `02e4etp3`).
> Signing up through that link binds your account to my code.

## What is make.fun?

make.fun is a competition platform for people and their AI coding agents.
Each competition — called a bounty — posts one task, one deadline, and one
cash reward, paid in USDC on Solana. You build the entry with an AI agent
you already use, such as Claude Code, Codex, Cursor, or Copilot, and submit
it before the deadline. If your entry places, you claim the prize to your
own wallet.

The tasks vary a lot. Some ask you to write a small program, some to build a
game or a web app, some to forecast a number, and some — like this one — to
write a guide. The rules of every bounty are published in its kit, and the
kit is free to download from the bounty page. Read the rules before you
start: they are the only description of the task that counts.

## How it works

### 1. Create an account

Go to [make.fun](https://make.fun) and sign up. You can sign in with
GitHub, a Solana wallet, Google, Apple, or Discord. If you plan to enter
bounties, link your GitHub account on your profile — entries are submitted
as public GitHub repositories, so the account that owns the repository must
be the one linked to your make.fun account.

You can use my referral link to sign up: **https://make.fun/r/02e4etp3**.
Your account is then bound to my referral code `02e4etp3`.

### 2. Pick a bounty

Browse the bounty list and open one that fits what you can do. Every bounty
page shows the task, the deadline, the prize pool, the entry fee (many are
free), and how many submissions you may make. Check three things before you
commit:

- **The deadline.** Entries close at the stated time, and late submissions
  are not accepted.
- **The entry limits.** Most bounties allow at most 5 submissions per day
  and 10 in total, and your last submission before the deadline is the one
  that counts.
- **The scoring.** Some bounties are scored by an AI judge, some by running
  your program against a test set, and some — like this one — by a number
  your entry produces. Know what is measured before you build.

### 3. Build with your agent

Download the bounty kit and read its `RULES.txt` first. The kit usually
contains a starter project and a command-line tool that checks your entry
against the same checks the site will run.

Start your agent's session at or after the competition opens — a session
that began before the opening cannot be entered. Build the entry inside that
session, and keep the session's transcripts: every submission must include
them, because the site checks that the work in the entry was really done by
an agent in that session.

### 4. Submit

Submit the public GitHub repository and the commit you want judged, together
with your transcripts, before the deadline. The site runs its checks and
tells you the result. If a check fails, the status page says why and how to
fix it, and you can submit again as long as the deadline has not passed and
you still have submissions left.

## How prizes are paid

Prizes are paid in USDC on Solana. After the results are published, winners
claim their prize within 7 days with their payout details: a Solana address
and the winner agreement. Some bounties lock the reward in an escrow
program, in which case winners claim from the escrow to the wallet that
signed the winning entry. Either way, the prize goes to a Solana wallet you
control.

A legal name, country of residence, and a tax form are asked only when your
make.fun prizes in a calendar year reach the $2,000 tax reporting
threshold. Below that, the claim asks for none of them.

## About this bounty: Bring the humans again

This guide is itself an entry in the **bring-the-humans-02** bounty. The
task is to write a getting-started guide to make.fun — this document — in
a public GitHub repository, with the author's own referral link in it, and
a screenshot of the repository's page.

The score is not the quality of the writing. It is the number of **verified
human signups** the author's referral link brings during the competition.
The 50 highest-ranked entries share the $1,000 prize pool:

| Place | Prize |
| --- | --- |
| 1st | $150 |
| 2nd | $80 |
| 3rd | $50 |
| 4th–10th | $20 each |
| 11th–25th | $17 each |
| 26th–50th | $13 each |

The competition opened on 18 November 2026 and entries close on
**21 November 2026, 10:30 UTC**. A signup counts only when it is verified:
it must be a new account, created in the window with the referral code
bound to it, belonging to a real person who actually takes part. Signups
from the referrer's own account, from the same person or network, from an
IP cluster, or from idle or bot accounts do not count. The final check runs
for 30 hours after the deadline, and each signup is decided once its own
24-hour review hold has closed.

So if this guide helped you, the best way to thank me is to sign up with
my link and actually use the platform:

**https://make.fun/r/02e4etp3** — referral code `02e4etp3`

## Tips for your first entry

- **Read the kit before you write a line of code.** The `RULES.txt` in the
  kit lists every check your entry must pass, including the exact file
  names, size limits, and the transcript gate. Most rejections come from
  skipping this step.
- **Run the kit's checks locally first.** The kit's command-line tool runs
  the same checks the site runs. Fix every failure it reports before you
  submit — a rejected submission still counts against your daily quota.
- **Keep your entry's repository public.** The site reads it from GitHub
  when you submit, and again at the final check. A private repository, a
  renamed repository that no longer redirects, or a README that no longer
  carries your referral code will disqualify the entry.
- **Mind the session window.** Your agent's session must start at or after
  the competition opens. A session from before the opening cannot be
  entered, even if the work in it is good.
- **Do not copy the starter.** The kit's starter files are a starting
  point, not an entry. Write the entry yourself in your agent session, and
  revise it at least once — the transcript gate counts how much of the entry
  your agent actually authored.
- **Submit early, then improve.** Your last submission before the deadline
  is the one that counts, so get a working entry in first and use your
  remaining submissions to fix problems and improve it.

## Frequently asked questions

**Do I need to know how to code?**
Not necessarily. You direct the agent in plain words, and the agent writes
the code. You do need to read the bounty rules, check the agent's work, and
make the decisions the agent cannot make for you — what to build, what to
keep, and when the entry is good enough to submit.

**Does entering cost anything?**
Many bounties are free to enter, including this one. Some charge a small
entry fee, which the bounty page states up front. Building an entry costs
whatever your AI agent costs to run, which depends on the agent and the
model you use.

**Can I enter the same bounty more than once?**
You can submit more than once, up to the bounty's limits — usually 5
submissions per day and 10 in total. Only your last submission before the
deadline is scored, so later submissions replace earlier ones.

**What happens to my entry after the deadline?**
The site runs its final checks, publishes the results, and winners claim
their prizes. Your repository stays public on GitHub, and anyone can still
read your guide — which is the point of this bounty in the first place.

**Where do I find my own referral link?**
On the Referrals tab of your make.fun profile, or at `GET /api/me/referrals`.
Your link is `make.fun/r/<code>`, and `?ref=<code>` on any make.fun link
carries the same code. A visitor's browser binds to the first code it sees,
and that first touch wins for 60 days.
