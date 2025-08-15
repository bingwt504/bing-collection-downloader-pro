# Bing Image Creator Collection Downloader pro (Chrome Extension wannabe)
Based on a pre-existing Chrome Extension by rugia813:
(https://github.com/rugia813/bing-collection-downloader/tree/master)

Original version features:
 - adds a button to the collection page which downloads all images you saved as a single zip file.
 - if the image is deleted, will try to download the thumbnail version instead.

This version (in addition):
 - downloads the prompts as .txt files with the same number as the image file.

# How to use
1) Download the files of this repository in a folder in your PC.
2) Open Google Chrome and go to chrome://extensions/.
3) At the top right, turn on Developer mode.
4) Click Load unpacked.
5) Select the folder where you downloaded the files.
6) Go to your Bing Collections Page, you should find a big "Download All Images" button on the left, and a small button next to any custom collection.

For further information on loading custom extensions see https://support.google.com/chrome/a/answer/2714278?hl=en

# (optional) Using with AI Images Gallery Generator

For easier management and visualization of your downloaded collections, you can use the **AI Images Gallery Generator** (see https://github.com/bingwt504/ai_images_gallery_generator).  

- This tool allows you to generate a **self-contained, searchable HTML gallery** of all your downloaded images and prompts.  
- You can organize images from **multiple downloaded ZIP files** into a **unique** gallery.  
- This makes it easier to browse, search, favorite, and manage your AI-generated images offline.  

**Recommended workflow:**  
1. Use this tool (Downloader) to get images from Bing Collections.  
2. Unzip them in separaed subfolders into the `images/` folder of the Gallery Generator.  
3. Run the Gallery Generator to create a single HTML gallery combining multiple collections.  

# Important
Please be aware that the HTML file is NOT PORTABLE!! Then it will break if you move it to another folder. So I'd suggest you to **keep the original zip files**, since they will always work.
