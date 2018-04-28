# IconJarExtractor

This AppleScript droplet extracts icons from an IconJar archive and renames the icons using the tags set in IconJar.

## Usage

1. Download this script to your Mac computer and extract the ZIP file. 
2. Double-click the file named `JSON Helper.zip` and copy the extracted file to your `Applications` folder.
3. Drop 1 or more IconJar files onto the IconJarExtractor droplet.
4. The script will create a folder on your desktop named `iconjar-extractor`
5. The icons will be extracted from your IconJar file and renamed using the tags you have specified in IconJar. If no tags have been specified, the name of the icons will be used. If no name has been specified, the script will error out.
6. The renamed icons will be saved in a ZIP file in `~/Desktop/icon-extractor/{name}-{uuid}/out`

## What is this for?

Icon marketplaces like Iconfinder can accept ZIP uploads and will use the names of your icons to automatically tag the icons. This script allows you to extract the icons from your IconJar files, rename them, and quickly upload them to Iconfinder without having to spend time manually re-tagging the icons.

## Support

I am happy to provide limited support at no charge. I am also available for hire for custom scripts and more complex support issues.

## Change Log
2018-04-25 : Fixed a bug related to file names with spaces or commas (IconJar or icon file names) causing the script to break

2018-04-25 : Added a dialog when the script finishes indicating the file location as well as a button to open the folder where the ZIP file containging the extracted icons is located

2018-04-27 : Hardened the fix for file paths with file paths with spaces and/or commas

2018-04-27 : Added 'on run' as well as 'on open' handlers to work as a droplet and double-clickable applet

2018-04-27 : Added feature to allow users to save password in a text file instead of being prompted for the password every time a file is processed. NOTE: This is inherently risky. Use at your own risk. Securely delete the password file after use. This should only be used on a well-protected, private system.

## Reporting a Bug

Please report any issues to https://github.com/iconifyit/iconjar-exporter-appletscript/issues or via email at scott_at_atomic_lotus_dot_net.

When reporting a bug, please include as much detail as possible including:

- The year and model of your Mac computer
- The version of MacOS running on your computer
- The IconJar file you're trying to extract would also be very helpful

## Known Issues
- None at this time

## Acknowledgements
- Thanks to Hemmo de Jong a. k. a., [Dutch Icon](https://twitter.com/dutchicon) for help testing (and his patience)
- Thanks to [MouseDown.net](http://www.mousedown.net/mouseware/JSONHelper.html) for graciously providing a free copy of the JSON Helper app for AppleScript to this project. Please visit their page and donate.

## Donations

Donations help open source developers continue to create free resources. You can donate to this project via [my PayPal page](https://paypal.me/iconify).