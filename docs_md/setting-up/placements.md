# Placements

To understand how to create your images, we need to understand the order that each trait must be added. 

#### For example:

If we have a Background, Face and Mask asset, we have to layer these correctly so the image is perfect. We can't have the Background being last because your NFT will be covered by your Background.

We use numbers within the trait folders to do this like so:

![Assets Folder Layout](https://s3.amazonaws.com/cdn.fardoss.com/docs_content/Assets%20Layout.png)

Because Background starts with 1.  , Fardoss will know that this image must be placed in the beginning. Then Eyes will be placed because it is #2 and so on.

The format that each trait folder should have is as follows.

- The number (ie: 1,2,3,4,5) - to determine trait order

- One period

- One space

- Then the name of the trait

Fardoss also allows you to manually configure the placement. On the right side, you will find a tab called Placement. Without adding numbers to your trait folders, you can set the order here as well.

![Fardoss Left Side Placement](https://s3.amazonaws.com/cdn.fardoss.com/docs_content/Placement%20section.png)

Once you upload your assets, we will first check to see if you set the order in your trait folders. If not, we automatically number them for you alphabetically.
