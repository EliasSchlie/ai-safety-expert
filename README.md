# AI Safety Expert

A [Claude Code](https://docs.anthropic.com/en/docs/claude-code) plugin that turns Claude into a knowledgeable AI safety field guide. It gives Claude the context, taste, and structure to help you navigate the AI safety ecosystem -- whether you're just discovering the field or actively working in it.

## Who is this for?

### 🌱 Newcomers

You've heard about AI safety and want to understand the landscape. The plugin helps Claude point you to the right introductory resources -- courses, blog posts, key papers, people to follow -- matched to your background and interests, instead of generic "start here" lists.

### 🔄 Career transitioners

You're a software engineer, policy researcher, PhD student, or something else entirely, and you want to pivot into AI safety work. Claude can help you find opportunities that actually fit your level and profile: fellowships for early-career researchers, engineering roles at safety labs, grants for independent work, upskilling programs, and more.

### 🔬 Active practitioners

You already work in alignment or adjacent areas but the field moves fast. Claude becomes better at answering technical questions across subfields, suggesting relevant recent work, and connecting dots between research directions you might not be tracking.

## What does it do?

The plugin is a knowledge layer that improves how Claude reasons about AI safety. Concretely, it helps Claude:

- **Recommend resources** -- blog posts, papers, courses, podcasts, and books worth your time
- **Map the landscape** -- organizations, research agendas, subfields, and how they connect
- **Find opportunities** -- jobs, fellowships, grants, programs, and events relevant to your situation
- **Answer technical questions** -- with better calibration on what's established vs. speculative, and where the real disagreements are
- **Give career advice** -- specific and actionable, not "just learn ML and apply"

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
