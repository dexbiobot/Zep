
**PLUGIN CODE**

```yaml
  auto_reactions:
    replaceDefaultOverrides: true #replaces default settings
    overrides:
      - level: '>=100'
        config:
          can_manage: true
          #only managable by level 100
          #!auto_reactions 629990160477585428 👍 👎
          #to apply auto reactions to a channel

          #!auto_reactions disable 629990160477585428
          #to disable auto reactions from a channel
```
