# renovate-config

We're using [Renovate](https://github.com/renovatebot/renovate) for automated dependency updates.

This repo has an extendable [config preset](https://docs.renovatebot.com/config-presets/#grouporganization-level-presets).

## Usage

```js
// renovate.json
{
  "$schema": "https://docs.renovatebot.com/renovate-schema.json",
  "extends": ["local>Arbeidstilsynet/renovate-config"]
}
```
