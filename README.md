# catchy
An offline web cache.

## Motivation

Years ago, when I only had access to internet at the university, I used [wwwoffle](http://www.gedanken.org.uk/software/wwwoffle/) to cache sites that I could rebrowse at home. Nowadays, I would like an offline cache again to disconnect from the inet while programming.

## Design

* Handle HTTP and HTTPS w/o MITM.
* Have a list of low priority sites that would be the first in the chopping block when space runs low. For instance, OSM tiles.
* Just like wwwoffle, handle requests while offline, and have a script to fetch all queued requests.

## Links

https://github.com/inaz2/proxy2/blob/master/proxy2.py#L93
https://parsiya.net/blog/2016-07-28-thick-client-proxying-part-6-how-https-proxies-work/
