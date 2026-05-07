# Dice Roller Skill

A small AI Edge Gallery skill that rolls one to six six-sided dice and shows the result as an animated visual webview.

The rolled values are displayed on the top faces of the dice, matching the way physical dice are read after a throw.

## Usage

Import this folder as a local skill in AI Edge Gallery:

```text
dice-roller
```

Then ask the model:

```text
roll a die
roll one die
roll a pair of dice
roll 3 dice
```

## Structure

```text
SKILL.md
scripts/index.html
assets/dice-view.html
```

- `SKILL.md` describes when the model should call the skill.
- `scripts/index.html` generates random dice results and returns a webview.
- `assets/dice-view.html` renders the animated dice result.

## License

MIT
