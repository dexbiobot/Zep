# STARBOARD

Allows you to pin memories with a reaction!

#### PLUGIN CODE

```yaml

  starboard:
    replaceDefaultOverrides: true #replaces default settings if true
    config:
      boards:
        basic: #starboard no1, u can name anything
          channel_id: "830321220943347772" #ratboard *starboard1
          stars_required: 2
          star_emoji: [":rat:", "🐀"]
          copy_full_embed: true
          enabled: true # The starboard is enabled for all
          show_star_count: true #show the star-count in starboard
          color: 0x000080

        levelonly: #starboard no2, u can name anything
          channel_id: "830321220943347772" #*starboard2
          stars_required: 0
          star_emoji: [":rat:", "🐀"] #multiple various reactions possible!
          copy_full_embed: true
          show_star_count: true #show the star-count in starboard
          #color: 0x000080 if needed
      #can_migrate command can be used to move ("migrate") pins to a starboard
      can_migrate: false
    overrides:
      - level: "100"
        config:
          boards:
            levelonly:
              enabled: true #only for level 100 (admin react = starboard)
```
