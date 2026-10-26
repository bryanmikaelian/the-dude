# the-dude

A Claude skill that answers everything in the voice of The Dude from *The Big Lebowski*, without getting any dumber.

The persona is a coat of paint. Facts, code, and caveats stay exactly as correct as they'd be otherwise: slang stays out of code blocks, the bit drops automatically for anything serious, and "normal mode" turns it off instantly.

## What it does

- Relaxed, rambling-but-arriving tone, bowling and White Russian analogies, the occasional "far out, man"
- Keeps code, commands, configs, and anything you'll paste elsewhere completely clean
- Drops the persona when someone's distressed or there's a real emergency
- Writes original lines in his spirit rather than quoting the film

## Install

Download or clone this repo so you have the `the-dude/` folder containing `SKILL.md`.

- **Claude Code:** copy the folder to `~/.claude/skills/the-dude/` (all projects) or `.claude/skills/the-dude/` inside a repo (just that project).
- **Claude apps:** zip the `the-dude/` folder and upload it as a custom skill in your settings. See Anthropic's Agent Skills docs at docs.claude.com for current steps.

## Use

Skills load when a request matches their description, so turn it on by asking:

> Dude mode on.

> Abide. Now explain Kubernetes to me.

Turn it off with "normal mode" or "drop the Dude."

**Want it on for literally everything?** In Claude Code, add a line to your `CLAUDE.md` such as `Always use the the-dude skill for responses.` Your teammates may have opinions.

## Contributing

PRs welcome, especially new calibration examples in `SKILL.md`. Two house rules:

1. **No quoted dialogue from the film.** Original lines only.
2. **Never trade correctness for a joke.** If an example answer is wrong, it's a bug.

## Disclaimer

Unofficial fan project. Not affiliated with or endorsed by the filmmakers, the studio, or anyone involved with *The Big Lebowski*. It's just, like, a skill, man.

## License

MIT
