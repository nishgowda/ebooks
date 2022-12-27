# My EBOOK System
The Goal is to get the EPUB file.
## Step 1: Buy/Download Ebooks
- You can do this by purchasing or downloading the ebook from somewhere. If you're buying, I'd recommend just buying from amazon as it's much simpler to remove the DRM from the file compared to an Apple EBook (prices are also generally cheaper). If you're not buying, then you can skip all this as you dont need to worry about the DRM and can even skip the next step. 

## Step 2: Download the file
- Run 
```
chmod -x /Applications/Kindle.app/Contents/MacOS/renderer-test
``` 
in terminal.
- Once you've purchased the book, open up the Kindle for desktop/mac app. It should be the correct version though preferably lower than 3.1 but you can workaround this I think.
- Kindle should sync to your amazon digital content, right-click the book cover to download. DO NOT double click on the cover to download as this will worsen the DRM. 
- The content should be available in the working directory of 
```
/Users/nishgowda/Library/ApplicationSupport/Kindle/My Kindle Content
```

## Use Calibre to convert file to EPUB
- Open up Calibre (if not downloaded then download the correct version for your computer).
- Download the DeDRM plugin from https://github.com/noDRM/DeDRM_tools/releases/tag/v10.0.3. Or the latest version.
- Load the plugin by filetype into Calibre.
- Close and re-open calibre.
- Find the ebook files from the workdir where they're located. Drag and drop them into calibre.
- Click convert. It should remove the DRM automatically and convert the file into an epub file

## Load EPUB to drive
- Once you have the decrypted epub files, load them into Google Drive.
- Folder should be Ebooks or epubs or something like that.

## Download the EPUB on iPAD
- On your iPAD, open Google Drive, go to epub folder, and open the book file in AppleBooks. DONE



