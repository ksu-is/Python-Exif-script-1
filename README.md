# Python-Exif-script
Disclaimer: Only for Educational Purpose only.

Note: Do not use unauthorizeed images for test.

Extracts Exif Data from photo. 
This Python Script Extract the photo Exif Data. Also it can extract the location of photo :: 
only if the location is tagged in photo while capturing the photo.

Convert Exif data to CSV table
Read EXIF data (incl. GPS) of photos in a folder and make a CSV table.

All photos must be in same folder and with a .jpg extension.

Data extracted and added to table:

File name

Date and time

Camera make

Camera model

Photo caption

Photographer's name if in caption. # It must be in format "(Name Name/Agency)". Script will take whatever is between the open parenthesis and the slash.

Latitude

Longitude

Please Note:
Location can be extracted if you embed the photo from social media sites, 
because when user upload the photo on Social Media then the location is been attached into the photo.

This program is for .JPG and .TIFF format files. The program could be extended to support .HEIC, .PNG and other formats.
Installation and usage instructions:
1. Install Pillow (Pillow will not work if you have PIL installed):

python3 -m pip install --upgrade pip

python3 -m pip install --upgrade Pillow



