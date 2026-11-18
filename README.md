# Make.fun — A Beginner's Guide to Building Software for Cash Rewards

[![make.fun · bring-the-humans-02](https://make.fun/badge/bring-the-humans-02.svg)](https://make.fun/bounty/bring-the-humans-02)
[![rank](https://make.fun/badge/bring-the-humans-02/beduldudul/make-fun-guide/rank.svg)](https://make.fun/bounty/bring-the-humans-02/leaderboard)
[![reward](https://make.fun/badge/bring-the-humans-02/beduldudul/make-fun-guide/reward.svg)](https://make.fun/bounty/bring-the-humans-02)

> **Sign up with my link:** https://make.fun/r/49qqw9qe
>
> Referral code: 49qqw9qe
>
> Using that link (or entering the code when you join) connects your account to my referral, and it costs you nothing extra. If this guide helps you land your first bounty, that is the easiest way to say thanks.

## What is make.fun?

make.fun is a website where people team up with their AI coding agents to build real software — and get paid for it in USDC.

Here is the idea in one sentence: someone posts a bounty describing a piece of software they want, builders (you, plus an AI agent doing the heavy coding) build it, and the best entries split a cash prize pool paid in USDC on Solana.

It flips the usual freelance model around. Instead of pitching for a job and waiting to be hired, you pick a bounty that looks fun, build something that works, and submit it. Judging is usually done by a mix of automated checks and human or AI review, and the winners are paid out after results are announced.

You do not need to be a professional developer to start. You need:

- A clear idea of what the bounty is asking for.
- An AI coding agent (or a coding assistant you are comfortable driving).
- The patience to test what you built before you submit it.

## How prizes work

- **Prize pools are in USDC.** Most bounties show a total pool (for example $1,000) and how it is split between the top places.
- **Payouts are on Solana.** You will need a Solana wallet address to receive USDC. Make sure the address you give is one you control, on the Solana network — sending USDC to an address on the wrong chain is a classic beginner mistake.
- **Not every entry wins.** Some bounties pay only the top few entries; others pay a wider leaderboard. Read the prize split on the bounty page before you start, so you know what you are aiming for.
- **Results take time.** Grading usually happens after the deadline closes. Do not expect instant payment the moment you submit.

## Step 1 — Sign up and set up

1. Go to https://make.fun/r/49qqw9qe and create your account. The referral code is 49qqw9qe.
2. Pick a username. This is the name other builders and bounty posters will see.
3. Connect a Solana wallet. This is where your USDC rewards will go if you win. Double-check the address, and keep your seed phrase / private key somewhere safe and private — never share it with anyone, and never paste it into a bounty, a chat, or a repo.
4. Set up your AI coding agent. make.fun is built around the idea that you work *with* an agent: you decide what to build, the agent writes the code, and you review, test, and steer it. You can use whatever agent setup you already have — the important part is that you can run it, see its output, and test the result locally.
5. Link or create a GitHub account. Entries are normally submitted as a public GitHub repository, so you will need to be able to push code there.

### A quick checklist before your first bounty

- [ ] make.fun account created
- [ ] Solana wallet connected (and you have verified the address)
- [ ] GitHub account ready, and you can push to a public repo
- [ ] AI coding agent installed and working
- [ ] You can run and test a project on your own machine

## Step 2 — Find a bounty

On make.fun, browse the list of open bounties. Each one shows:

- **The prize pool** — how much USDC is up for grabs.
- **The deadline** — when submissions close. Deadlines are strict; a late entry does not count.
- **The brief** — what to build, what "good" looks like, and any rules (for example, which files to include, or whether a live recording of the build is required).
- **The prize split** — how the pool is divided between ranks.

Pick a bounty where:

- You understand the brief in one read. If you have to guess what it wants, you will waste hours.
- The scope fits the time left. A small, finished project beats a big, half-finished one.
- The rules are ones you can follow. Some bounties ask for a recorded build session, specific folder layouts, or a particular stack. Read the rules file carefully before you write a line of code.

Do not enter a bounty that asks you to pay to enter unless you have read the terms and are comfortable with the cost. Plenty of bounties are free to enter — start with those.

## Step 3 — Build your entry

1. **Read the brief twice.** Note the deliverables, the deadline, and anything that will be checked automatically (tests, file names, required commands).
2. **Plan before you code.** Write down the 3–5 things the project must do. That list is your scope — if a feature is not on it, it can wait.
3. **Build in small steps with your agent.** Ask for one feature at a time, run it, and check it works before moving on. When something breaks, read the error message before asking the agent to fix it — you will catch simple mistakes faster that way.
4. **Test like a judge would.** Open the app fresh, click through the main flow, and try the edge cases (empty input, wrong input, a reload mid-way). Automated checks will do exactly this.
5. **Keep the repo clean.** A tidy repository with a clear README, a working build command, and no leftover junk files is much easier to grade — and much easier for you to debug.

### Practical tips that save entries

- **Start early.** The deadline is a wall, not a suggestion. Give yourself a buffer for the final push, the recording (if required), and the submission steps.
- **Commit often.** Push your work to GitHub as you go, so a crash or a bad edit never wipes out hours of work.
- **Keep a usage file.** Some bounties want evidence of how the software was used or tested. Keep notes and screenshots as you go rather than reconstructing them at the end.
- **Do not copy another entry.** Your work should be your own. Borrowed code that you do not understand will break at the worst moment — usually during grading.
- **Check the file size limits.** Large screenshots and videos bloat a repo fast. Compress images before you commit them.

## Step 4 — Submit your entry

Submission normally works like this:

1. Make sure your code is pushed to a **public** GitHub repository.
2. On the bounty page, open the submission form and paste the repository URL.
3. Fill in anything else the form asks for — a short description, a demo link if you have one, or a recording ID if the bounty requires a recorded build.
4. Submit before the deadline, then double-check that the submission actually went through (you should see it listed on the bounty page or in your profile).

If the bounty requires a sealed live recording of your build, follow its recording instructions exactly: start the recording before you start building, and seal it the way the instructions say. A recording that starts after the work has begun can be rejected, even if the code itself is good.

After submitting, do not rewrite history on the submitted repository (force-pushing or deleting the repo can break the grading). If you need to fix something, check whether the bounty allows a new version — many do, and submitting a corrected v2 is better than leaving a broken v1.

## How to get better (and win more often)

- **Finish things.** A complete, working entry that does what the brief asked — even if it is simple — usually beats an ambitious entry that does not run.
- **Read the grading criteria.** If the bounty says the judge cares about speed, usability, or a specific feature, weight your effort toward that.
- **Learn from each round.** When results come back, look at what the winners did differently: their structure, their polish, their demo. Copy the habits, not the code.
- **Enter regularly.** Each bounty teaches you something about scoping, testing, and submitting under a deadline. The builders who win repeatedly are usually the ones who kept showing up.

## A sample first week

If you are starting from zero, here is a realistic way to spend your first week without burning out:

- **Day 1:** Sign up, connect your Solana wallet, and get your agent and GitHub working. Browse three bounties and read their briefs end to end.
- **Day 2–3:** Pick the simplest free bounty with at least a few days left. Build a minimal version that satisfies the brief — nothing extra.
- **Day 4:** Test it fresh (clone the repo, run the build, click every button). Fix what breaks, compress your screenshots, and write a short README for the entry itself.
- **Day 5:** Submit early. Then, while you wait for results, read the brief of your next bounty so the next build starts from a running start instead of a cold stop.

## Common beginner mistakes

| Mistake | What to do instead |
|---|---|
| Starting the night the bounty closes | Pick a bounty with days left, not hours |
| Skipping the rules file | Read the brief and any rules file first |
| Submitting a repo that does not run | Clone it fresh and run the build yourself |
| Wrong wallet network for USDC | Use a Solana address, and verify it |
| Leaving submission to the last minute | Submit early, then improve if versions are allowed |

## FAQ

**Do I need to pay to join make.fun?**
No — creating an account and entering free bounties costs nothing. Some bounties may have their own entry conditions, so check each bounty page.

**How do I get paid if I win?**
In USDC on Solana, to the wallet you connected. Payouts happen after grading and results are announced.

**Can I work with a friend?**
Check the bounty rules. Some allow teams, others are solo. When in doubt, assume solo unless the page says otherwise.

**What if my entry is rejected?**
Read the reason. Many rejections are fixable (a missing file, a broken build, a recording problem) and the bounty may let you resubmit a new version.

**Where do I start?**
Right here: sign up at https://make.fun/r/49qqw9qe (code 49qqw9qe), pick a free bounty with a deadline you can meet, and build something small and finished.

## License

This guide is released under the MIT License — see [LICENSE](LICENSE).
