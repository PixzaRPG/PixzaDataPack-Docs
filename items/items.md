# PixzaRPG - Items Documentation

Any files within the `/items` directory of your data pack will be parsed as a item.
A item is a minecraft item that has special properties that add to the RPG-like world experience.

```json
{
  "uuid": "uuid of the item",
  "item": "minecraft item name",    // e.g. STICK

  "components": [   // Properties of the item
    {
      "type": "component_type_name",
      "data": {
        // components can ask for specific configurable data here
      }
    }

  ]
}
```

## Item Components

Item components are special properties assigned to an item to give it special abilities/logic.

### `lore`

The `lore` item component allows items to be spawned with specific lore.
```json
{
    "type": "lore",
    "data": {
        "lines": [
            "This is line 1 of the lore",
            "This is line 2 of the lore"
            // ... more lines can be added
        ]
    }
}
```