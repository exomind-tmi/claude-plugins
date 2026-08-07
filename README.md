# exomind claude-plugins

The [Exomind Tmi](https://github.com/exomind-tmi) plugin catalog for [Claude Code](https://claude.com/claude-code).

Add the marketplace once per machine:

```
claude plugin marketplace add exomind-tmi/claude-plugins
```

Then install any plugin from the catalog:

```
claude plugin install adhd-bro@exomind
```

New plugins land here as a single line in `marketplace.json` — no new marketplaces to add, ever. Refresh with `claude plugin marketplace update exomind`.

## Plugins

| Plugin | What it does |
|--------|--------------|
| [adhd-bro](https://github.com/exomind-tmi/adhd-bro) | ADHD-friendly list handling: shared board, full relevant list at every decision point, visible progress, default recommendations |
