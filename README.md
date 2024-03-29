# Alekfull NX (ES-DE Version)
This is port of the AlekFull NX theme by [fagnerpc](https://github.com/fagnerpc) for the version of EmulationStation used in [ES-DE](https://es-de.org/)

**All artwork and layouts were designed and created by fagnerpc.  I simply made changes to the XML to make the theme compatible with ES-DE. The original version of the theme can be found [here](https://github.com/fagnerpc/Alekfull-NX)**

## Changes Made

- Removed all Batocera specific elements to make the theme compatible with ES-DE
- Updated system image names to match the standard used by ES-DE
- Added a 16:10 Layout Variant
- Added navigation sound set for ES-DE
- Replaced some images with new versions created by ClassicxCola ([Thread](https://www.reddit.com/r/retroid/comments/1049daq/im_happy_to_announce_the_release_of_colafulldx_a/))

## **Preview**

| System View | Gamelist View |
| --- | --- |
| <img alt="Screenshot 2023-12-27 at 10 58 09 AM" src="https://github.com/anthonycaccese/alekfull-nx-es-de/assets/1454947/5ecda38b-4d3e-49e8-b6dd-840f9d74fd82"> | <img alt="Screenshot 2023-12-27 at 10 59 17 AM" src="https://github.com/anthonycaccese/alekfull-nx-es-de/assets/1454947/4474e635-fa36-4145-b323-506a1d328ccb">

## **Configuration Options**

- The theme has a simple set of options that can be changed directly from the UI Settings menu of ES-DE
- `Theme Aspect Ratio` - sets the aspect ratio the theme will render at. If needed, this can be changed to match the aspect ratio of your screen (though it should happen automatically).
   - 16:9 and 16:10 are supported
- `Theme Variant` - sets the layout used for the gamelist view when media & metadata are scraped for your games.  There are 4 variants to choose from:
   - `List: Metadata & Miximage` - A simple list that displays the miximage artwork and shows all game metadata
   - `List: Metadata & Boxart` - A simple list that displays cover artwork and shows all game metadata
   - `List: Miximage` - A simple list that removes all gamemetadata and displays miximage artwork
   - `List: Boxart` - A simple list that removes all gamemetadata and displays cover artwork
- `Theme Color Scheme` - sets the color scheme that is used for the overall theme on all views.  There are 7 built in color schems to choose from:
   - `Light`
   - `Dark`
- `Theme Font Size` - enables you to change the size of the fonts displayed in the theme
   - `Medium` - good for display on tvs and computer monitors
   - `Large` - good for display on large handheld screens at 6 inches or larger
   - `Extra Large` - good for display on small handheld screens at 6 inches or below

### Preview of Variants and Color Schemes

| Dark | Light |
| --- | --- |
| <img alt="Screenshot 2023-12-27 at 10 58 22 AM" src="https://github.com/anthonycaccese/alekfull-nx-es-de/assets/1454947/6cad71f7-1175-46cb-80a3-3a7acda8ddab"> | <img alt="Screenshot 2023-12-27 at 10 58 09 AM" src="https://github.com/anthonycaccese/alekfull-nx-es-de/assets/1454947/0ba4f91e-6e07-48de-b026-8e18f7d8599e"> |
| <img alt="Screenshot 2023-12-27 at 11 01 00 AM" src="https://github.com/anthonycaccese/alekfull-nx-es-de/assets/1454947/7db55fcf-e399-4820-b22c-a9e22f38b9dd"> | <img alt="Screenshot 2023-12-27 at 10 59 17 AM" src="https://github.com/anthonycaccese/alekfull-nx-es-de/assets/1454947/32884694-0668-4b71-b793-254ef85c0a5a"> |
| <img alt="Screenshot 2023-12-27 at 11 00 44 AM" src="https://github.com/anthonycaccese/alekfull-nx-es-de/assets/1454947/2eb94be5-bc3b-442e-b31c-4e8450546b55"> | <img alt="Screenshot 2023-12-27 at 10 59 40 AM" src="https://github.com/anthonycaccese/alekfull-nx-es-de/assets/1454947/f46bd0ce-1c2b-4c7e-9a92-6fbbce201424"> | 

### Preview of Font Sizes

| Medium | Large | Extra Large |
| --- | --- | --- |
| <img alt="Screenshot 2023-12-27 at 10 59 17 AM" src="https://github.com/anthonycaccese/alekfull-nx-es-de/assets/1454947/32884694-0668-4b71-b793-254ef85c0a5a"> | <img alt="Screenshot 2023-12-27 at 11 31 24 AM" src="https://github.com/anthonycaccese/alekfull-nx-es-de/assets/1454947/d3a22a1b-24eb-4a2e-8318-2694b758151a"> | <img alt="Screenshot 2023-12-27 at 11 31 34 AM" src="https://github.com/anthonycaccese/alekfull-nx-es-de/assets/1454947/648f2c21-998d-4e16-839a-7e7b6d41d504">

## **Theme Customizations**

The theme allows customizations to artwork without the need to edit the source XML.  This enables you to change the look of the theme and still retain any changes when the root theme is updated.

### Start Here 
- Make sure `Light (Custom Artwork)` or `Dark (Custom Artwork)` is selected from `Menu > UI Settings > Theme Variant`
- This setting changes the directories that the theme looks for artwork in and sets up the ability for you to add custom artwork.

### Backgrounds
- Create a folder called `custom-backgrounds` in ES-DE's theme directory at: `ES-DE/themes/alekfull-nx-es-de/_inc/systems`
- Upload your custom background images to that folder
- They can be named:
    - _default.jpg
    - ${system.theme}.jpg
- `_default.jpg` can be used for creating a single image that is used for all systems OR a fallback for systems that you did not create a custom image for.
- `${system.theme}.jpg` should be named for the system you are looking to override.  For example if you wanted to override the artwork for `snes` you would create an image called `snes.jpg` in the backgrounds folder.
- If a given ${system.theme}.jpg image is not found it will use _default.jpg image so make sure to at least create that image.

### Carousel Icons
- Create a folder called `custom-carousel-icons` in ES-DE's theme directory at: `ES-DE/themes/alekfull-nx-es-de/_inc/systems`
- Upload your custom carousel icons to that folder
- They can be named:
    - ${system.theme}.jpg
- `${system.theme}.jpg` should be named for the system you are looking to override.  For example if you wanted to override the artwork for `snes` you would create an image called `snes.jpg` in the backgrounds folder.

## **Additional Notes**

### Versions for other ES forks:
* If you use Batocera... then check out the original version by fagnerpc [here](https://github.com/fagnerpc/Alekfull-NX).

## **Acknowledgments**
- All original artwork and layouts were designed and created by [fagnerpc](https://github.com/fagnerpc)
- Some artwork created by ClassicxCola ([Thread](https://www.reddit.com/r/retroid/comments/1049daq/im_happy_to_announce_the_release_of_colafulldx_a/))

## **License**
Creative Commons CC-BY-NC-SA - https://creativecommons.org/licenses/by-nc-sa/2.0/
You are free to share and adapt this theme as long as you provide attribution back to me (and the above credits) as well share any updates you make under the same licence terms.
