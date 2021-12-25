# Uploading to Pinata

[Pinata](https://pinata.cloud/) is a pinning service to [IPFS](https://ipfs.io/). IPFS hosts your NFT's online but you still need a pinning service to keep those images online.

Fardoss offers a quick to upload your generated NFT's and metadata.



#### Process

After generating you NFT collection, the "Upload collection to Pinata" on the right side nav under the General Tab will pop up.

![NFT Upload to Pinata](https://s3.amazonaws.com/cdn.fardoss.com/docs_content/Upload%20to%20Pinata.png)



Enter your API Key and Secret API Key found in your Pinata Dashboard

- If you don't have a special gateway, we will use the default "https://api.pinata.cloud".



The location of the generated files will be in your output location. So for example, if you set your Desktop as the output location, the path for the collection would be:

- Desktop/asset_generator/



#### Uploading Process

![Pinata Uploading Process](https://s3.amazonaws.com/cdn.fardoss.com/docs_content/Upload%20to%20Pinata%20Process.png)

1. We first upload the images folder in your output collection. 

2. We then switch your metadata files with the correct online url
   
   - ie: "https://gateway.pinata.cloud/ipfs/IPFS_HASH_KEY/1.jpeg"



#### Upload Complete

![Pinata Upload Complete](https://s3.amazonaws.com/cdn.fardoss.com/docs_content/Upload%20to%20Pinata%20Process%20Complete.png)

After the upload is complete, you can instantly view your assets online.






