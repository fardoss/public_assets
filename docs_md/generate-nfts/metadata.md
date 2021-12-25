# Metadata

Metadata is a JSON format that helps sites like Opensea understand your NFT attributes, the collection it belongs too and where on IPFS it is located. 

![NFT Generator Updating Metadata](https://s3.amazonaws.com/cdn.fardoss.com/docs_content/Updating%20Metadata.png)

#### Built-In Editor

After every generated collection, you can update the metadata for any NFT on the spot with our JSON editor. Without leaving Fardoss, all created NFT's are shown so you can swipe through and change what you need to change.

This give you the freedom to update traits, add new traits or fix mistakes you found within any metadata file without leaving Fardoss.

---

#### Ethereum Format

Sites like Opensea use this format. Here is an example of what an Ethereum JSON file would look like.

```json5
{
   "name": "Fardos",
   "image": "2.jpeg",
   "description": "Minimalism at it's finest",
   "external_url": "https://fardoss.com",
   "token_id": 2,
   "attributes": [
      {
         "value": "light grey",
         "rare": "Normal",
         "trait_type": "background"
      },
      {
         "value": "inazuma x",
         "rare": "Normal",
         "trait_type": "weapon"
      },
      {
         "value": "persian",
         "rare": "Normal",
         "trait_type": "dynasty"
      },
      {
         "value": "orange xray",
         "rare": "Normal",
         "trait_type": "eyes"
      },
      {
         "value": "cloth tank top black",
         "rare": "Normal",
         "trait_type": "clothes"
      },
      {
         "value": "chrome",
         "rare": "Normal",
         "trait_type": "chain"
      },
      {
         "value": "ghost left",
         "rare": "Rare",
         "trait_type": "cyborg arms"
      },
      {
         "value": "shaolin fro xl",
         "rare": "Normal",
         "trait_type": "head wear"
      },
      {
         "value": "sweet dreams",
         "rare": "Normal",
         "trait_type": "face mask"
      },
      {
         "value": "pink hud",
         "rare": "Legendary",
         "trait_type": "eye wear"
      },
      {
         "value": "viking peace rolex left",
         "rare": "Normal",
         "trait_type": "hands"
      },
      {
         "value": "peace purple left",
         "rare": "Normal",
         "trait_type": "sleeves"
      },
      {
         "display_type": "number",
         "trait_type": "Rarity",
         "value": 45
      }
   ]
}
```

Every NFT will be connected to a JSON file like this one. It includes all the attributes used within that NFT and allows you to understand the rarity of each NFT compared to your entire collection.

#### Solana Format

The additional fields that are added to the Ethereum JSON format are 

- Family Name

- Symbol

- Seller Fee

- Creator Address

- Creator Share

These settings can be found on the right side of your nav under the General Tab.

![NFT Generator Solana Settings](https://s3.amazonaws.com/cdn.fardoss.com/docs_content/Solana%20Settings%20Left%20Nav.png)

After you fill these settings out, the added fields in your ouputed JSON file will look something like this:

```json5
"symbol": "FD",
"seller_fee_basis_points": "10",
"collection": {
   "name": "Fardos",
   "family": "Fardoss"
},
"properties": {
   "category": "image",
   "files": [
      {
         "uri": "3.jpeg",
         "type": "image/jpeg"
      }
   ],
   "creators": [
      {
         "address": "0x64A4e3A0e96B",
         "share": "10"
      }
}
```
