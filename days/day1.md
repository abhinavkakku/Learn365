# Day-1

# Google Dorks / Search Engine Dorking

Want to use google as a tool for Hacking ? or as an advanced search engine giving more accurate results ?
Google Dorks help us do the same, there are some keywords that help us refine the search results with some given criteria.

- `inurl` - search a keyword in urls , also see `allinurl`
- `intitle` - seach for terms in the title of website
- `intext` - search for terms in text (body) of website
- `site` - get results from a particular site only
- `cache` - get results from cached copy, can be used to see when website is down or old data
- `allintitle` - search websites for terms in title, more than one terms an be given
- `allinurl` - same as inurl but more than one terms allowed ( all be present in result)
- `allintext` - search for all words in text of a website
- `filetype` - looking for a particular file type ? mention extension
- `inanchor` - search for texts in anchors on page
- `*` - search for wildcards in words
- `|` - or operator
- `+` - one or more time
- `-` - remove results with -

## Examples

allintext:password filetype:log after:2019

allintext:username filetype:log

DB_USERNAME filetype:env

DB_USERNAME filetype:env

inurl:top.htm inurl:currenttime

intitle:"index of" inurl:ftp

intitle:"index of" inurl:http after:2018

intitle:"forum" inurl:http after:2018

cache:websitename.com

filetype:log username putty

filetype:xls inurl:"email.xls”

References :

[DorkSearch - Speed up your Dorking](https://dorksearch.com/)

[Google Dorking Examples](https://securitytrails.com/blog/google-hacking-techniques)

[Offensive Security's Exploit Database Archive](https://www.exploit-db.com/google-hacking-database)
