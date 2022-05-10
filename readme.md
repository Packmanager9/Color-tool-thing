to run this, you gotta disable cors and drag the html file to the tab bar.


on linux, to disable cors for chrome:

google-chrome --disable-web-security


On mac to open chrome with disabled cors run this in terminal:
open -n -a /Applications/Google\ Chrome.app/Contents/MacOS/Google\ Chrome --args --user-data-dir="/tmp/chrome_dev_test" --disable-web-security

If you use windows, I don't know, you can probably look it up, sorry. 
