# linkedin/

Working files for the linkedin-agent skills in `.claude/skills/`. Paths are
relative to the repository root.

| file | written by | read by |
| --- | --- | --- |
| `voice.md` | `/li-post` (first run, from three past posts) | every skill that drafts text |
| `log.md` | `/li-post` (on "yes"), `/li-comment` | `/li-audit`, `/li-plan`, `/li-comment` |
| `plan.md` | `/li-plan` | the other skills |

Cloud sessions run in a throwaway container, so a file written here is lost
when the session ends unless it is committed and pushed. After writing or
changing any file in this folder, commit it and push to the current branch.

`.claude/linkedin-agent/voice.md` is the blank template for `voice.md`.
