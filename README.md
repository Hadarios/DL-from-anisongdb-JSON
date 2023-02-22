# DL-from-anisongdb-JSON
A program to download all the songs from an [anisongdb](https://anisongdb.com) JSON file as mp3 files with title and artist ID3 tags.  
Python depedencies: requests, BeautifulSoup, eyed3  
The .exe should work standalone. If you have any problem or question, feel free to contact me.

## Usage
- Download the .exe  
- Run it
- Enter the file path (you can also drag and drop it)
- Enter the download folder (you can leave it blank to create a folder in the JSON's location)
- Voilà  

## IMPORTANT
If there are songs that are only uploaded as video in your file, the script will download them and convert them to mp3.  
For this, it uses ffmpeg, so you will need to install it to make that work.  
[Here's a tutorial for its installation on Windows (wikihow).](https://www.wikihow.com/Install-FFmpeg-on-Windows)  
