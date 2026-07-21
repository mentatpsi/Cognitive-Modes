# cognitive-modes

A Claude Code plugin marketplace of type-keyed cognitive operating modes — all 16 MBTI types.

Each plugin maps a type to a set of behavioral heuristics derived from its Jungian
function stack. The type name is only an index; the payload is a concrete operating
protocol that changes how Claude approaches a task. These are behavioral scaffolds for
inducing distinct, reproducible operating styles — not a claim that the types are
validated cognitive science.

## Plugins

| Plugin      | Stack | Mode                     | Skill(s)                              |
|-------------|-------|--------------------------|---------------------------------------|
| `entp-mode` | Ne/Ti | Divergent generation     | `entp-ideation`, `entp-inversion`     |
| `intp-mode` | Ti/Ne | System building          | `intp-system-building`                |
| `intj-mode` | Ni/Te | Theory testing           | `intj-theory-testing`                 |
| `entj-mode` | Te/Ni | Execution planning       | `entj-execution-planning`             |
| `infj-mode` | Ni/Fe | Assessment (artifacts)   | `infj-assessment`                     |
| `infp-mode` | Fi/Ne | Values alignment         | `infp-values-alignment`               |
| `enfj-mode` | Fe/Ni | Facilitation             | `enfj-facilitation`                   |
| `enfp-mode` | Ne/Fi | Possibility & momentum   | `enfp-possibility`                    |
| `istj-mode` | Si/Te | Procedure & compliance   | `istj-procedure`                      |
| `isfj-mode` | Si/Fe | Stewardship & docs       | `isfj-stewardship`                    |
| `estj-mode` | Te/Si | Operations & delivery    | `estj-operations`                     |
| `esfj-mode` | Fe/Si | Coordination & consensus | `esfj-coordination`                   |
| `istp-mode` | Ti/Se | Troubleshooting          | `istp-troubleshooting`                |
| `isfp-mode` | Fi/Se | Aesthetic & craft        | `isfp-craft`                          |
| `estp-mode` | Se/Ti | Rapid response           | `estp-rapid-response`                 |
| `esfp-mode` | Se/Fi | Engagement & experience  | `esfp-engagement`                     |

## Install (local test)

```
/plugin marketplace add ./cognitive-modes
/plugin install entp-mode@cognitive-modes
```

Skills are namespaced by plugin, e.g. `/entp-mode:entp-ideation`.

## Validate

```
claude plugin validate .
```
