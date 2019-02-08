# asset-fullscreen-ui-extension
A Contentful UI Extension that provides a navbar for full size or full screen asset preview. 
Please visit https://www.contentful.com/r/knowledgebase/ui-extensions-guide/ to learn how to install in Contentful Web App.

# Usage
This UI extension is designed to be used with  [Contentful](http://www.contentful.com), you will need a space ID as well as a CMA access token. The UI extension reads an assetId from a field called "asset" and retrieves the asset URL and sets it as target for the preview asset field which allows you to view the asset in Full Screen mode or at Full Size in a new tab.

1. Install this UI Extension in your Contentful space!
2. Update the SPACE_ID and CMA_TOKEN in the extension source (html). Don't forget to save!
2. Create a field on your content type called "Asset", set type to Media (a.k.a. asset reference or link).
3. Create a anotehr field on the same content type called "Asset Preview" of type "Object" and configure the field appearance to use this UI Extension, called: "Asset Full Screen".
