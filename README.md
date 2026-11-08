# YouTube workspace

Workspace for planning and producing YouTube content with Claude Code, using the **youtube-agent** skill pack (MIT, from [Jakeschincariol/youtube-agent-skill](https://github.com/Jakeschincariol/youtube-agent-skill)) installed project-local.

## Skills (`.claude/skills/`)
| Skill | Use |
|---|---|
| `yt-plan` | Video ideas and plan |
| `yt-script` | Script writing |
| `yt-viral` | Hooks and viral angles |
| `yt-seo` | Title, description, tags |
| `yt-package` | Title + thumbnail packaging |
| `yt-chapters` | Chapter timestamps |
| `yt-shorts` | Shorts from long videos |
| `yt-retention` | Retention review |
| `yt-edit` | Editing notes |
| `yt-comment` | Comment replies |
| `yt-audit` | Channel audit |

## Notes
- Voice profile template: `templates/voice.md` (copy to `~/.claude/youtube/voice.md`).
- On Windows run the skill tools with `py` (e.g. `py hookscore.py --hook "..."`).
- Nothing is published automatically — the owner uploads videos.
- Kids content is marked "Made for Kids"; no copied characters, shows or songs.
