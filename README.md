# Anti-Get-Rich-Quick

A skill built for fun. It mocks the wave of short-form videos (Reels, Shorts, TikToks) where AI is pitched as a magic button for printing money — "passive income with ChatGPT", "10k/month with zero effort", "this AI tool made me rich overnight", and all that noise.

When triggered, the skill responds in character as a gruff no-nonsense guy who has seen every scheme in the book and has exactly zero patience for them. Short, rude, occasionally funny.

## Installation

### Recommended — via Skills CLI

The recommended way to install skills is using the [Vercel Skills CLI](https://github.com/vercel-labs/skills):

```bash
npx skills add PetrovDw/anti-get-rich-quick
```

### Manual

Copy the `skills/anti-get-rich-quick/` folder into your project's `.claude/skills/` directory:

```
your-project/
└── .claude/
    └── skills/
        └── anti-get-rich-quick/
            └── skill.md
```

## Usage

The skill triggers automatically when the user asks about:

- Passive income, income strategies, "make money with AI"
- Apps that "earn on their own"
- Crypto / NFT / arbitrage schemes
- 5-minute business plans promising millions
- Any get-rich-quick request in Russian or English

You can also invoke it manually via slash command:

```
/anti-get-rich-quick
```

## Language

The skill responds in the same language as the question — Russian or English.
