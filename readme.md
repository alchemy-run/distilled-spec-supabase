# distilled-spec-supabase

A git mirror of the Supabase [Management API spec](https://api.supabase.com/api/v1-json). The spec is fetched and committed as a JSON file so the repo serves as a versioned snapshot.

The mirror is updated every 24 hours and is designed to be used as a stable git submodule.

## Usage as a submodule

```sh
git submodule add https://github.com/alchemy-run/distilled-spec-supabase.git
```

## Updating specs

From `.meta/`:

```sh
bun install
bun run fetch-specs
```
