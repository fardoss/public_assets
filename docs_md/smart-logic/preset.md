# Presets

Presets are basically like requirements. 

Let's say that we have a trait called "Hands". We also have another trait called "Sleeves". We cannot have sleeves without hands. 

![Smart Logic Preset Generator](https://s3.amazonaws.com/cdn.fardoss.com/docs_content/Preset%20Smart%20Logic.png)

Using Presets, we can specify the requirements for the folder hands.

You can add multiple OR rows within your preset.

#### For example:

If we have another trait called "Eyes", that has the same requirements, then it would look something like this.

![Fardoss NFT Generator Preset](https://s3.amazonaws.com/cdn.fardoss.com/docs_content/Preset%20Final%20Result.png)

#### End Result

When the generator finishes, if the preset "Hands" is in the image, then we leave it is left alone. If the preset "Hands" is NOT included in the image and sleeves is, then we remove the sleeves trait from the image because Sleeves requires Hands.
