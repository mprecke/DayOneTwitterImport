## Import your Twitter Archive into Day One as Journal Entries. ##
The dotw.bash script allows you to add Twitter posts into your Day One journal on a Mac via a bash shell. This tool is designed to import the Date and Text of your post as well as your (first) post pic and tags

This is Fork from: https://github.com/kitykity/dotw

# What I changed #
I updated the script to work with a twitter archives in April 2020 to account for different folder structures and changes in naming conventions in the DayOne CLI. 

# Prerequisites #
Before you run the script, you will need to download your Twitter Archive:
- Log in to your Twitter account and access your Settings and Privacy to request your archive.
- Download the .zip file from Twitter, and unzip it into a folder called "dotw" in your home directory (i.e. /Users/me/dotw).
- rename the downloaded folder "twitter".
- Copy the dotw.bash from the repository into the directory called dotw and run following commands:

# Commands to use in Terminal #
$ cd /Users/me/dotw

$ chmod 700 dotw.bash

$ ./dotw.bash


That's it!
