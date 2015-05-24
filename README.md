# NPRme

## Why NPRme

I created this for personal use, for those times when I would love to listen to NPR Morning Edition in my car when I am out of data or radio range. It happens a lot, living in the High Desert of California and all.

## Why BASH

This would have been a lot easier to do in Python, or PHP, or any number of other scripting languages. But I wanted to learn more BASH at the time I wrote this, so here it is. My BASH isn't very good, so there are a bunch of temp files created and deleted at runtime. If you can improve it, please fork and send pull requests.

## How to Use
To use, just place this script in an empty directory on your web server and add it as a cron task. Change the __server__ variable to the http path of the folder where the script lives, and change the __nprurl__ variable if you would like to grab a different program.

## Legal Stuff
NPR permits you to download MP3s for personal use. This software downloads the MP3s to your computer, and than transfers them to your Podcast playing device, which isn't much different from you doing the same work manually. So this should not be a violation of their terms of service or fair use rules. However, do __NOT__ distribute the link to the feed or rebroadcast the programs without NPRs permission. All NPR programs are Copyrighted by NPR.

The author of this software does not encourage anyone to do anything that would infringe on NPRs legal rights, and will not be responsible for any violations resulting from use or miss use of this software.