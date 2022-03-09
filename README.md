# Welcome to My Adblocking Filter Repository
This repository is used to give myself a convenient way to store and access my custom filters for uBO and my Pihole setup.

# General Information
Since these filters were created for myself to use, I will not remove any filters that negatively impact anyone that use them unless I feel as though they aren't worth keeping. **Use these filters at your own risk**

The "Hosts" folder contains hosts-formatted files that work with Pihole, but it can also be used with browser-based adblockers. The "UBO Syntax" folder contains many more filter lists and work well with browser based adblockers.

# Lists and Their Purposes
## YouTube-Spam
This list serves the purpose of cleaning up the hemorrhage that is the YouTube comment section. Spam bots are spreading so much garbage that I made this list primarily out of very aggressive regular expressions. This filter list removes **ALL** comments that contain: links, emojis, content promotion comments, and **all** non-ASCII characters, which unfortunately means all non-English replies will be removed as well. However, YouTube won't fix spam so collateral damage like this is perfectly fine in this case. **THIS LIST IS PERFORMANCE INTENSIVE**

## Sketchy-Domains
This is my anti-spam and anti-malware list. It is comprised of any domain I have ever seen in a spam text, spam email, or in a scam video or post online. This list is far from comprehensive but should provide some protection. I am taking suggestions for more domains to add as well.

## YouTube-Filters
This list simply removes any of the UI features that I don't like from YouTube. That's it, that's the list.

## Atypical-TLD-List
This list blocks any sites with an atypical or uncommon TLD such as `.fun` or `.apple`.

## Country-TLD-List
This list blocks any sites with a country specific TLD such as `.ru` or `.es`.

## Anti-Facebook
This list blocks the most common Facebook and Facebook associated sites because Facebook is a horrible company.

## Unbreak
This list resolves some issues that I have encountered with other filter lists by whitelisting some cosmetic filters.
