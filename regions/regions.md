# PixzaRPG - Regions Documentation

Any files within the `/regions` directory of your data pack will be parsed as a region.
A region is an area of the world that you can apply special flags to make it unique from the rest of the world.

```json
{
    "uuid": "uuid of the region",

    "description": "Short description of what this region represents",

    "boundaries": [ // The coordinates of the two corners of this region
        { "x": 0, "y": 0, "z": 0 },
        { "x": 0, "y": 0, "z": 0 }
    ],

    "flags": [  // Modifiers for this region

        {
            "type": "flag type",

            "data": {}  // Associated data to configure this flag
        }
    
    ],

    "subregions": [ // regions within this region
        // region objects go within this array
    ]
}
```

## Region Flags

Region flags are components for a region in order to give it unique behaviour.

There are no region flags at the moment...