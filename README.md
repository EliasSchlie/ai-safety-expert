# AI Safety Expert

A [Claude Code](https://docs.anthropic.com/en/docs/claude-code) plugin that turns Claude into a knowledgeable AI safety field guide. It gives Claude the context, taste, and structure to help you navigate the AI safety ecosystem -- whether you're just discovering the field or actively working in it.

## Who is this for?

Anyone who regularly asks Claude questions about AI safety. The plugin uplevels every answer -- more knowledge, better calibration, stronger recommendations.

Whether you're exploring the field for the first time, looking for your next role, or deep in alignment research, it helps Claude:

- **Know more** -- the organizations, people, programs, subfields, and how they connect
- **Recommend better** -- high-signal blog posts, papers, courses, podcasts, books, and people to follow instead of generic lists
- **Find opportunities** -- jobs, fellowships, grants, events, and programs matched to your background and level
- **Answer technical questions** -- with better calibration on what's established vs. speculative, and where the real disagreements are
- **Give real career advice** -- specific and actionable, not "just learn ML and apply"

## Installation

Add the marketplace (one-time):
```
/plugin marketplace add EliasSchlie/claude-plugins
```

Install the plugin:
```
/plugin install ai-safety-expert@elias-tools
```

That's it. The skill activates automatically when you ask Claude about AI safety topics.

## Contributing

Know about a program, organization, or resource we're missing? Think the advice could be better calibrated? Open a PR or file an issue -- this is a community tool and contributions are welcome.

Areas where help is especially useful:
- **Coverage gaps** -- subfields, orgs, or programs the skill doesn't know about well enough
- **Outdated info** -- programs that shut down, orgs that pivoted, deadlines that changed
- **Better taste** -- which resources are actually high-signal for different audiences

## License

MIT
