# PhotoMD CHANGELOG

_**NOTES:**_
 1. Versions containing "alpha", "a", "beta", "b", or "rc" are pre-releases, and
subject to change.
 2. Pre-release versions are not available on the App Store.

## V2.8.1 Feb 1, 2021

### FIXED
 - Fixed crash if loading an invalid video
 - Help file and third-party licenses viewer now autoscale
 - Other internal fixes


## V2.8.0 Dec 22, 2020

### ADDED
 - Support for copy-paste of image data

### FIXED
 - Couple issues which may have caused crashing


## V2.7.1 Nov 1, 2020

### REMOVED
 - Removed support for opening video files (this was causing issues since PhotoMD would be the default video player)

## V2.7.0 Oct 5, 2020

### ADDED
 - Support for dragging mouse to scroll image when zoomed
 - Added option to animate zoom
 - Added option to hide scrollbars for image preview (default)
 - Added function to export selected images
 - Added support to change the preview background color in Preferences
 - Added debug output window when exporting images
 - Added custom images to Preferences window

### FIXED
 - Fixed issue when exporting a raw image
 - After deleting a image from the Image Table, show the image above it
 - When opening an image that already exists, select and hightlight it
 - Resets the image zoom after deleting all images
 - Fixed expand button image to change when pressed

### CHANGED
 - Changed menu item: Image -> Images
 - Only change the About window position when not visible

## V2.6.0 Sep 21, 2020

### CHANGED
 - About window will always be opened right in the middle of the main window
 - Improved Preferences window

### ADDED
 - Added support for BMP image formats
 - Added support for exporting images to other formats

### FIXED
 - Fixed image name label autofocus when expanding/un-expanding the view

## V2.5.0 Sep 7, 2020

### ADDED
 - Added support for expanding image previewer
 - Added button to reveal image(s) in Finder
 - Added basic support for video playback
 - Added ability to remove images from list
 - Added Tool Tips to some buttons
 - Added Report a bug/suggestion in menu (will link to web page)

### FIXED
 - Fixed issue when trying to open a non-standard image format
 - Fixed issue when selecting multiple images, then selecting one and staring it

### CHANGED
 - When selecting multiple images, the image-name label shows how many are selected
 - Better, and improved About window

## V2.4.0 Aug 27, 2020

### SUMMARY
 - Support for batch editing
 - New opening image and multi-selected image
 - Updated Preferences

### ADDED
 - Added support for batch metadata editing
 - Added "Reset user defaults" in preferences
 - Added alert before recompression all images
 - Added CameraOwnerName to editable data

### FIXED
 - Fixed constraints for Preferences window
 - Fixed issues in User interface in PhotoMD manual

### CHANGED
 - New opening image
 - Multi-selected images are now shown as overlayed images


## V2.3.0 - August 13, 2020

### SUMMARY
 - Better interface throught Menu items
 - Ability to edit _some_ metadata without recompression the image (only JPG)
 - Added support for more RAW image formats
 - Improvments to performance, and other bug fixes

### ADDED
 - Added function to Menu -> File -> Open recent
 - Added menu option (Menu -> File -> Recompress all images) to recompress all images to a specifyed compression
 - Added function to Menu -> File -> Open
 - Added ability to edit some image metadata without recompressing the JPG image (only some keys are supported)
 - Added alert if user closes window while sorting images (can be suppressed)
 - Added ARW, and DNG as a image format

### FIXED
 - Better handling when a metadata row is clicked/image changed
 - Fixed IsoSpeed -> ISOSpeed in combo-box
 - Better image data combo-box handling

### CHANGED
 - When opening image files, thumbnails will now be loaded in backround


## V2.2.0 - July 24, 2020

### SUMMARY
 - Cleaned and sorted menu items
 - Plays animated images
 - Better performance with large/raw images
 - Improved multi-image selection in image table
 - Improved, and added settings to Preferences

### ADDED
 - Added "Star all images" in "Image" menu
 - Added "Unstar all images" in "Image" menu
 - Added option in Preferences to "Show image thumbnail while loading image"
 - Added "Do not show me this message again" to delete all metadata popup
 - Added settings option to "Load low quality HEIC images first" in Preferences
 - Added option to "Show image thumbnail while loading image" in Preferences

### CHANGED
 - Animated images (GIFs) will preview as animated (instead of static images)
 - Changed menu item: PhotoMD Help -> PhotoMD Manual

### FIXED
 - Fixed issue when selecting more then one image (did not highlight the rows)
 - Fixed error alert when pushing "Stop" to delete all data popup
 - Fixed GitHub links to point to: https://github.com/west-technology/PhotoMD-public
 - Wont change the aspect ratio of the image thumbnail


## V2.1.1 - July 16, 2020

### SUMMARY
 - This update fixes the "Zoom in" issue
 - Minor updates to UI
 - Fixed issue when "Open with PhotoMD" for an image

### FIXED
 - Fixed issue when zooming in, with a fresh app install
 - Fixed word-correction in alert
 - Fixed menu item: "Star image" when not allowed to star images
 - Fixed issue when "Open with PhotoMD" for an image


## V2.1.0 - July 15, 2020

### SUMMARY
 - This update fixes several bugs, which effect the UI.
 - Added PhotoMD Preferences in menu.

### ADDED
 - Added button to cancel the "loading thumbnail..." prossess
 - Added PhotoMD Preferences
 - Added ability to "load low quality images over 20Mb"

### FIXED
 - Fixed issue when staring a large amount of images, when deleteing all but stared
 - Fixed alert when opening a lot of non-images
 - Fixed some typos in alerts


## V2.0.1 - July 12, 2020

### SUMMARY
 - This update fixes several bugs and crashes, and improves reliability. Specifically when removing an image during, or after processing the thumbnails.
 - Now uses a custom windows to display the help file PDFs (since Preview could edit the PDFs in the app).
 - Detect if the selected file(s) is an image before loading it, and don't load non-images.
 - Improved PhotoMD help PDF, and updated screenshots in App Store.

### ADDED
 - Added file check and alert for opening a file thats not an image
 - Added larger "?" (unknown image) for a missing image

### FIXED
 - Fixed crash when loading a folder, then deleting that folder while processing the image thumbnails
 - Fixed crash when "Deleting all except stared" when loading bar is almost complete

### CHANGED
 - If selecting more then one image, switching next/previous image will cancel multi-select
 - Changed from using Preview to show help file, and third-party licenses PDF, to using custom window. Since a user could edit the PDFs through Preview
 - Updated screenshots in App Store
 - Updated PhotoMD help to explain how to delete all image metadata
 - Disable zoom when selecting more then one file
 - Reset zoom when selecting more the one file


## V2.0.0 - July 10, 2020

### ADDED
 - Added support for dragNdrop (only for input images)
 - Added support for directories (can select whole directories with images)
 - Added tableView for related images, with thumbnails and names
 - Added support for zooming/magnifying an image
 - Added support for editing the image name
 - Added PhotoMD help PDF (can be accessed with Main Menu->Help->PhotoMD Help
 - Added ability to "star" an image
 - Added ability to "delete all exect stared" images (images deleted this way are moved to the users trash bin)

### CHANGED
 - New user inerface

### REMOVED
 - Removed support for undo/redo (may add this later)
 - Removed "Save as..." menu item (may be added back later)


## V1.2.0 - Jun 11, 2020

### ADDED
 - Support for undo and redo
 - Added "Revert all changes" menu item
 - Added menu checkbox to sort image metadata
 - Added new key "ImageDescription"
 - Added support for "Save as..."
 - Added warning if trying to open more then one file
 - Added new bug logo to some alert messages

### CHANGED
 - Select image will no longer be edited as data changes (will need to "Save..." before selected image gets updated)
 - If image is edited, closing the app will automaticly save the image
 - Updated app icon to use a bigger handle
 - Print the image res in X Y order


## V1.1.0 - Jun 4, 2020

### ADDED
 - Available to edit image metadata
 - Added delete selected row, to delete a selected row of data
 - Always will recompress image when editing data
 - Added image resolution label
 - Added "Delete all data" button to delete all image metadata
 - Added warning if trying to edit a unsupported image, eg. RAW images
 - Added warning if trying to add a tag on a image that does not support it
 - Added alert prompt to confirm that the user wants to edit the image (when editing data) (only popups one every app bootup)
 - Added alert prompt if the user wants to delete all image data
 - Reloads the "Image size label" after editing the image data
 - Added combo-box to select a data key to add
 - Added text-field to add a data value
 - Key, and value text fields are automaticly updated as the user selects rows of data from the table view
 - Added always-on checkbox to enable re-compressing image when editing data

### CHANGED
 - Fixed type: `Select a image` -> `Select an image`
 - Main window can no longer be resized

### REMOVED
 - Removed "PhotoMD help" from help menu (will add a help window soon)


## V1.0.0 - May 27, 2020

Init release.

