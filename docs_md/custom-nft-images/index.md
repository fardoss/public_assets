# Custom NFT Images

Sometimes you might want to add one of ones (images created by you that don't want us to generate)

Fardoss allows you to to quickly include them in your collection.

Located on the left side of your nav, click 'Upload' to include custom images.

![Upload custom NFT images](https://s3.amazonaws.com/cdn.fardoss.com/docs_content/Custom%20Images%20Box.png)

#### Folder structure

All your one of one images must be at the root of your custom images folder.

![NFT One of Ones Folder Structure](https://s3.amazonaws.com/cdn.fardoss.com/docs_content/Custom%20Folder%20Structure.png)

Custom images can have any trait values you want. However, we still need to connect your trait folders (ie: Background, Eyes, Ears) to these values.

The way we do this is with the file name.

Each custom image MUST include all the traits inside its file name.

---

Say we uploaded this assets structure:

![Fardoss Assets Structure](https://s3.amazonaws.com/cdn.fardoss.com/docs_content/Assets%20Layout.png)

We have 9 trait folders (ie: Background, Eyes, Clothes, Face). The file name for each custom image must include all 9 traits followed by an __

![Custom NFT Example](https://s3.amazonaws.com/cdn.fardoss.com/docs_content/custom_image_one.jpeg)

---

#### File Name Structure

Every custom image must have all the traits in the file name.

The trait values for this image are:

- **Background**: Blue Moon

- **Eyes**: Blue Glow

- **Clothes**: Grey and Blue Samurai Robe

- **Face**: NA

- **Mask**: Black and Blue Samurai

- **Arms**: NA

- **Sleeves**: NA

- **Hands**: Blue Orb

- **Eye Wear**: NA

All 9 traits have been defined because we have 9 trait folders in our assets folder.

You **MUST** include the traits that are **NOT** included.

---

#### Default Delimiter

The default delimiter is a double underscore __. This allows Fardoss to know when one trait begins and another ends.

[Learn more](https://fardoss.com/docs/custom-nft-images/delimiter) about custom delimiters.

---

#### Final Name

So the final file name for the custom NFT above will be

- blue moon__blue glow__grey and blue samurai robe__NA__Black and Blue Samurai__NA__NA__Blue Orb__NA.jpeg
