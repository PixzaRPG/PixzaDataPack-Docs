# PixzaRPG - Manifest Documentation

The `manifest.json` file is a required file that is placed in the root directory of all data packs.

```json
{
    "version": 1,   // Data pack parser version to use. Currently only version 1 exists.

    "info": {
        "name": "Name of the data pack",
        "description": "Description of this data pack",
        "author": "The author of this data pack",
        "uuid": "uuid of this data pack",
        "version": 1    // Version of the data pack
    },

    "dependencies": [   // Any other data packs that should be loaded before this data pack

        {
            "uuid": "uuid of the data pack this data pack depends on",
            "version": 1    // The required version of the data pack we depend on
        }
    
    ]
}
```