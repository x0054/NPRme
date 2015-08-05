# NPRme

## Why NPRme

I created this for personal use, for those times when I would love to listen to NPR Morning Edition in my car when I am out of data or radio range. It happens a lot, living in the High Desert of California and all.

## How to Use
1. Download [NPRme script](https://github.com/x0054/NPRme/raw/master/nprme) and place it in an empty directory on your web server.
2. Change the ``server`` variable in the script to the **HTTP URL** of the folder where the script lives.
3. Add the script to your cron tasks or run manually as necessary.
4. Make sure that the user running the script has write privileges to the directory housing the scrip.

### Optional Setup:

* Change the ``nprurl`` variable in the script to another program, like [All Things Considered](http://www.npr.org/programs/all-things-considered/), to download that program.
* Ddd ``logo.jpg`` file to the same directory with dimensions 300x300px and it will appear as the thumbnail for the podcast.

## Legal Stuff
NPR permits you to download MP3s for personal use. This software downloads the MP3s to your computer, and than transfers them to your Podcast playing device, which isn't much different from you doing the same work manually. So this should not be a violation of their terms of service or fair use rules. However, do __NOT__ distribute the link to the feed or rebroadcast the programs without NPRs permission. All NPR programs are Copyrighted by NPR.