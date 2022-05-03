# ETKRes-CPC
Resources for Emuteca: TurboGrafx 16 / PC Engine

Icons, images, texts, videos, etc. for use with [Emuteca](https://github.com/Chixpy/Emuteca).

Download
--------

Use GIT to clone the repository or download it in zip:

https://github.com/Chixpy/ETKRes-TG16/archive/master.zip

## About Images

### Screenshot, Titles

Rule #1: No filters to screenshots.

All images in .png format at original resolution: 256x232

### Front, Back, Spine, Manual, Media, Maps, Reviews, Ads, Other

Generally:

  * Scanned .jpg images 
  * Maximum of 2048px in its largest side, if its smaller don't scale it up.
  * If it's larger than 2048px, it's best to crop (see below) before scaling it down to 2048. Keeping aspect ratio.
  * Trying not to resave it many times. There are some transformations that can be done without lossing quality...

For game's media (Front, Back, Spine, Manual and Media):

  * Box Front, Back and Spine in separated images and cropped without any border. 
  * Media: Whole cart, CD, etc. scanned and cropped without any border (if possible)

For Magazine texts:

  * Crop original page image to article text and game images, with a little border.

For Maps (or magazine game guides):

  * If it's a magazine game guide: Same as Magazine texts.
  * If it's a digital map (made with screenshots or similar): Better in .png format and keep as is (do not remove author, or other info; and if it's bigger than 2048px keep the size too).

### Icons, Logos

Rule #1: Only 1 image for group or game. No folders with multiple images.

Icons are mainly extracted from game screenshots at original resolution. Usually they are protagonist frames, lives icons or recognizable icon.

Logos are usually extracted from Title or Main Menu screens.

All images are .png format. Width and Height are variable, using it's original size without resizing to a fixed size or adding more border to make it square. Emuteca handle they automatically.

The only time that the image will be scaled is when all 'icon pixels' are 2x2, 3x3, etc. pixels.

After extracting the icon image with transparent background, a border is added: Middle grey, half transparency (128, 128, 128, 128). 

[Emuteca](https://github.com/chixpy/emuteca) has [ETKIconBorder](https://github.com/Chixpy/Emuteca/blob/master/bin/Tools/ETKIconBorder.exe) tool in its distribution. A simple image editor to cut, extract, make transparency in images and apply filters to original image.

Altenatively, there is a GIMP's script too, that can add the border automatically after transparent background is created. But it's slooooow.

## About Texts

Raw text .txt.

Better if:

  * Empty line between paragraphs.
  * No new line inside paragraphs (Textbox has wordwrap activated).
  