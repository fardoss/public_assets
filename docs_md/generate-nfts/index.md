# Generating NFT's

Fardoss allows you to generate thousands of NFT's with a click of a button.

#### Adding your assets

Please note, You must [organize your assets ](https://fardoss.com/docs/setting-up) before you can use them. After you have organized them, click "Upload" on the left side nav. 

FYI, we do not upload your assets to any online cloud storage. To offer the best privacy, all generations are kept locally unless you want to Upload to Pinata.

#### Collection Details

On the right side nav, set the

- Name

- Description

- External URL,

- Size

- Threads

![NFT Generator General Right Size](https://s3.amazonaws.com/cdn.fardoss.com/docs_content/General%20section.png)

#### Collection Size

The collection size will tell us how many NFT's we need to generate. For example, if the collection size is 1,000, Fardoss will create 1,000 NFT's and 1,000 JSON files.

---

#### Threads

Threads tell us how many images we should generate at the same time. So if you set the threads to 10, 10 images (depending on your computer). will generate at the same time.

---

#### Output Location

This field tells us where we need to create the folder "asset_generator". For example, if you set the output location to your Desktop, we will automatically create or replace the folder "asset_generator" on your Desktop.

---

#### Generating

After you finished generating your NFT's, you should see a new folder called asset_generator. This is the output structure that we use. You will find that NFT's and their metadata are separate. We do however connect them using their file number.

![NFT Generator Output Location](https://s3.amazonaws.com/cdn.fardoss.com/docs_content/Output%20Folder%20Structure.png)

So the metadata in images/0.jpeg will be in json/0 and so on. The JSON data will look something like this.

```json5
{
   "name": "Fardoss",
   "image": "1.jpeg",
   "description": "Minimalism at it's finest",
   "external_url": "https://fardoss.com",
   "token_id": 1,
   "attributes":[{
         "value": "white",
         "rare": "Normal",
         "trait_type": "background"
    }]
}
```

Attributes are an array of different traits included in the image. Sometimes, some images may include more attributes than others, so the size of this array varies. 

Traits are found in your folder system (ie: 1. Background). 

[Learn more](https://fardoss.com/docs/setting-up/placements)

#### Quick Tips

Generated NFT's are always

- Less than 1 MB

- High Resolution and Quality

- JPEG's
