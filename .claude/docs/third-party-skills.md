# Third-party skills

These folders under `.claude/skills/` were copied unchanged from
[agentic-awesome-skills](https://github.com/Bhabagrahi-Pradhan/agentic-awesome-skills)
at commit `a99b3d3b`. They are not studio skills: they do not follow the studio's
phase/approval conventions, and `/skill-test` / `skill-lint.sh` findings on them
are expected. Each keeps its own license and attribution (see each `SKILL.md`
and, where present, its `LICENSE.txt`).

| Skill | Source path | Why it is here |
|---|---|---|
| `game-design` | `plugins/agentic-bundle-indie-game-dev/skills/game-design` | Core loop, GDD and progression principles |
| `2d-games` | `plugins/agentic-bundle-indie-game-dev/skills/2d-games` | 2D scene, sprite and camera patterns |
| `3d-games` | `plugins/agentic-bundle-indie-game-dev/skills/3d-games` | 3D scene and rendering patterns |
| `game-audio` | `plugins/agentic-bundle-indie-game-dev/skills/game-audio` | Audio formats, mixing and adaptive music |
| `algorithmic-art` | `plugins/agentic-bundle-indie-game-dev/skills/algorithmic-art` | p5.js generative art (placeholder/ambient art) |
| `godot-gdscript-patterns` | `plugins/agentic-bundle-indie-game-dev/skills/godot-gdscript-patterns` | GDScript patterns, if the engine is Godot |
| `unity-developer` | `plugins/agentic-bundle-indie-game-dev/skills/unity-developer` | Unity 6 practices, if the engine is Unity |
| `web-games` | `skills/game-development/web-games` | Browser game tech choices (the default `/prototype` target) |
| `beautiful-prose` | `skills/beautiful-prose` | Clean, concrete prose for dialogue, clues and lore |
| `avoid-ai-writing` | `skills/avoid-ai-writing` | Audit player-facing text for formulaic wording |

The rest of the ~3,100-skill library was deliberately left out: loading all of
it would flood every session's skill list and most of it (SEO, marketing,
cloud ops) is unrelated to making a game. To add another skill, copy its folder
from the library into `.claude/skills/` and add a row here.
