# YouTube agent skills — @merchants_official

The eleven skills from
[Jakeschincariol/youtube-agent-skill](https://github.com/Jakeschincariol/youtube-agent-skill)
(MIT, see `LICENSE-youtube-agent-skill`), installed project-locally for the channel
[@merchants_official](https://www.youtube.com/@merchants_official).

Open this repo in Claude Code and the commands are available:

| command | what it does |
| --- | --- |
| `/yt-script` | One idea into a script, with five scored hooks |
| `/yt-package` | Title + thumbnail as one pairing, linted |
| `/yt-edit` | Transcript → edit decision list |
| `/yt-comment` | Comment triage and replies in your voice |
| `/yt-plan` | A weekly plan that fits your hours |
| `/yt-viral` | What's working in your niche, by outlier multiple |
| `/yt-retention` | Read your retention CSV export |
| `/yt-shorts` | Shorts hidden inside a long video |
| `/yt-seo` | Description, tags, target queries |
| `/yt-chapters` | Valid chapters from a transcript |
| `/yt-audit` | Whole-channel audit, ending in one fix |

## First step

Fill in [`.claude/youtube/voice.md`](.claude/youtube/voice.md). Every skill reads it (project file
first, then `~/.claude/youtube/voice.md`). Easiest: paste three of your video transcripts and say
"write my voice.md from these". Then run `/yt-audit` with your last ten titles.

Nothing here uploads or publishes. The skills write; you publish.
