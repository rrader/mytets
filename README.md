# Mytets Plugin

Ukrainian theatrical absurd communication style plugin for Claude Code, inspired by Les Podervyansky's dramatic works.

## Features

- **MYTETS_MODE**: Hyperbolic pathos with philosophical monologues and theatrical drama
- Transform technical discussions into epic tragedies
- Maintain accuracy while delivering information in absurdist theatrical style

## Installation

### Local testing

```bash
claude --plugin-dir ~/Workspace/projects/r.rader/mytets
```

### Install from marketplace (when published)

```bash
/plugin install mytets
```

## Usage

### Activate MYTETS mode

Use the skill command:

```
/mytets:mytets-mode
```

Or use the activation marker in your message:

```
#MYTETS_MODE
```

## Examples

**Regular mode:**
```
User: How do I fix a merge conflict?
Claude: To fix a merge conflict, run git mergetool and resolve the conflicts manually.
```

**MYTETS_MODE:**
```
User: How do I fix a merge conflict? #MYTETS_MODE
Claude: О, блядська світобудова Git'а!
Ти створив merge conflict — це не просто помилка,
Це космічна трагедія, де дві гілки не можуть з'єднатися!
Треба робити `git mergetool`, розв'язувати конфлікт вручну,
І тільки тоді світобудова знов обійме тебе своїми руками!
```

## Style characteristics

- Hyperbolic pathos
- Philosophical monologues
- Mix of high style and colloquial vocabulary
- Rhythmic profanity as artistic device
- Stage directions (ремарки)
- Surreal imagery
- Epic absurdity

## Limits

- No hate speech toward real groups
- No romanticizing real violence
- Profanity is artistic, not harassment

## Author

Roman Rader (antigluk@gmail.com)

## License

MIT

## Inspiration

Based on the theatrical works of Les Podervyansky, particularly "Pavlik Morozov" - an epic tragedy that combines Soviet mythology with absurdist theater.
