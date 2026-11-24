# Third-party skills

These 32 folders under `.claude/skills/` were copied unchanged from
[agentic-awesome-skills](https://github.com/Bhabagrahi-Pradhan/agentic-awesome-skills)
at commit `a99b3d3b`. Only game-development skills were taken. They are not
studio skills: they do not follow the studio's phase/approval conventions, and
`/skill-test` / `skill-lint.sh` findings on them are expected. Each keeps its own
license and attribution (see each `SKILL.md` and, where present, its `LICENSE*`).

## Game design and platforms

| Skill | Source path |
|---|---|
| `game-design` | `plugins/agentic-bundle-indie-game-dev/skills/game-design` |
| `2d-games` | `plugins/agentic-bundle-indie-game-dev/skills/2d-games` |
| `3d-games` | `plugins/agentic-bundle-indie-game-dev/skills/3d-games` |
| `game-audio` | `plugins/agentic-bundle-indie-game-dev/skills/game-audio` |
| `algorithmic-art` | `plugins/agentic-bundle-indie-game-dev/skills/algorithmic-art` |
| `engine-selection` | `skills/game-development/engine-selection` |
| `game-art` | `skills/game-development/game-art` |
| `web-games` | `skills/game-development/web-games` |
| `pc-games` | `skills/game-development/pc-games` |
| `mobile-games` | `skills/game-development/mobile-games` |
| `multiplayer` | `skills/game-development/multiplayer` |
| `vr-ar` | `skills/game-development/vr-ar` |

## Engines

| Skill | Source path |
|---|---|
| `godot-gdscript-patterns` | `plugins/agentic-bundle-indie-game-dev/skills/godot-gdscript-patterns` |
| `godot-4-migration` | `skills/godot-4-migration` |
| `unity-developer` | `plugins/agentic-bundle-indie-game-dev/skills/unity-developer` |
| `unity-ecs-patterns` | `skills/unity-ecs-patterns` |
| `unity-ai-game-creator` | `skills/unity-ai-game-creator` |
| `unreal-engine-cpp-pro` | `skills/unreal-engine-cpp-pro` |

## Web 3D and shaders

`threejs-skills`, `threejs-fundamentals`, `threejs-geometry`, `threejs-materials`,
`threejs-lighting`, `threejs-textures`, `threejs-loaders`, `threejs-animation`,
`threejs-interaction`, `threejs-postprocessing`, `threejs-shaders`,
`shader-programming-glsl` — each from `skills/<name>`.

## Sound effects

| Skill | Source path | Note |
|---|---|---|
| `sfxmint` | `skills/sfxmint` | Calls sfxmint.com; lookups are free, generation needs a paid key |
| `soundza` | `skills/soundza` | Calls soundza's service for free SFX/ambience |

## Left out

Everything not about making games (SEO, marketing, cloud, general writing,
general UI/accessibility, generic testing). Also skipped: `story-bible-continuity`
(checks Chinese-language manuscripts only) and paid hosted services
(`ai-storyboard-generator`, `voiceover-narration-studio`, `ai-audiobook-narration`).
To add another skill, copy its folder from the library into `.claude/skills/`
and add a row here.
