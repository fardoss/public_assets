# Change Trait Values

If your collection is very rare and you want people to know it, you might want to add something to the beginning or end of your trait values.

![Change Metadata Trait Value](https://s3.amazonaws.com/cdn.fardoss.com/docs_content/Change%20Trait%20Values%201.png)

#### For example:

If you want to generate only 186 NFT's and publish those first from your collection, then you might want to add a 186 to the beginning of the Weapon value without changing your trait folder structure.

When we change the trait type for Weapon to start with 186, the attributes in your metadata will look something like this:

```json5
...
      {
         "value": "186weapon samurai swords",
         "rare": "incredibly rare",
         "trait_type": "weapon"
      },
      {
         "value": "body asian",
         "rare": "incredibly rare",
         "trait_type": "dynasty"
      },
      {
         "value": "blue eues",
         "rare": "incredibly rare",
         "trait_type": "eyes"
      },
      {
         "value": "vest",
         "rare": "incredibly rare",
         "trait_type": "clothes"
      },
      {
         "value": "clothes cyborg arm with black bushido hoodie",
         "rare": "incredibly rare",
         "trait_type": "chain"
      },
      {
         "value": "orange rockets",
         "rare": "incredibly rare",
         "trait_type": "cyborg arms"
      },
...
```

#### Quick tips:

- Feel free to use spaces within your values. We will include those as well.
  
  - So the above weapon value with a space would be "186 weapon samurai swords"
