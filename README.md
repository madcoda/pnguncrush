pnguncrush
==========

convert PNG files from iOS apps to normal PNG

I'm not a iOS developer, but I happens to need to extract some images from an exisiting iPhone App, this is a 
little shell scipt that may saved your life.

## Usage
    
    git clone https://github.com/madcoda/pnguncrush.git
    
    # move the tool to where you want
    cd ./pnguncrush
    mv ./convert /path/to/your/pngs/
    
    # make sure it's executable
    cd /path/to/your/pngs/
    chmod +x ./convert
    
    # convert all the pngs in the folder
    ./convert *.png
    
Now you can find the converted PNGs in the "converted" folder


## Requirements
- Install XCode from App Store

## How do I get this command
A lot of QAs on the internet points me to use a tools in /Developer/Platforms/iPhoneOS.platform/Developer/usr/bin/pngcrush 
which I don't have on my Mac. In this Apple's Q&A it uses a tools "xcrun" which works for me. The command is found in 
https://developer.apple.com/library/ios/qa/qa1681/_index.html. This script is only the "loop" version of it for ease of use.
