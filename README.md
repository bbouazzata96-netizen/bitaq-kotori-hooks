# bitaq-kotori-hooks

Game hooks (obfuscated class, field and method names) for **[Bitaq] Kotori Utils**, a RuneLite plugin.
The plugin downloads `hooks.json` from this repo on startup:

    https://raw.githubusercontent.com/bbouazzata96-netizen/bitaq-kotori-hooks/main/hooks.json

- `hooks.json`: the current hooks. `"revision"` is the game revision they are for; the plugin warns when it
  doesn't match the running client.
- `hooks-<revision>.json`: a copy for every published revision.

Updated after each game update with `tools/find-hooks.sh` and `tools/publish-hooks.sh`.
