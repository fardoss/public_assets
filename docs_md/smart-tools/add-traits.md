# Add Traits

Sometimes, you might want to add your own traits to your NFT collection meta data. You can do this using the Add Trait widget.

![Add Traits - NFT Metadata](https://s3.amazonaws.com/cdn.fardoss.com/docs_content/Add%20Traits%20Smart%20Tools%201.png)

You can add as many new traits you want.

![NFT Add Metadata Traits](https://s3.amazonaws.com/cdn.fardoss.com/docs_content/Add%20Traits%202.png)

#### Output Metadata

The output json will look something like this:

```json5
...
      {
         "value": "arms fingers",
         "rare": "incredibly rare",
         "trait_type": "cyborg arms"
      },
      {
         "value": "head wear round samurai hat with hood up",
         "rare": "incredibly rare",
         "trait_type": "head wear"
      },
      {
         "value": "face mask gold samurai smile",
         "rare": "incredibly rare",
         "trait_type": "face mask"
      },
      {
         "value": "n",
         "rare": "incredibly rare",
         "trait_type": "eye wear"
      },
      {
         "value": "a",
         "rare": "incredibly rare",
         "trait_type": "hands"
      },
      {
         "display_type": "number",
         "trait_type": "Rarity",
         "value": 1
      },
      {
         "value": "smoke red",
         "rare": "40",
         "trait_type": "Purple BG"
      },
      {
         "value": "true",
         "rare": "0",
         "trait_type": "Orange BG"
      }
   ]
}
```

The new traits will be added to the end of your attributes as new values.
