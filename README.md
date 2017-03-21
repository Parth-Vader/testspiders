# Testspiders
## Useful test spiders for Scrapy

A simple description of the spiders is as follows :-

* `brokenlink.py` : Checks which of the links are broken on the page.
* `dummy.py` : A dummy spider that just initiates and does nothing.
* `followall.py` : Crawls all the links on the page, and returns their `referer`, `size` , `title` and `url` and goes on recursively. 
* `justfollow.py` : Just crawls all the links of the page.
* `localinfo.py` : Crawls on the local system and returns 

     * `Scrapy` version 
     * `lxml` version
     * `libxml2` version
     * `Twisted` version
     * `Python` version
     * `pyOpenSSL` version 
     * `Platform` information.
* `loremipsum.py` : Shows how to create `DEBUG`, `INFO`, `WARNING` and `ERROR` messages for a spider.
* `mad.py` : This spider uses `followall` spider and returns `"something happened"` when a warning is to be given and `"something bad happened"` when an exception is raised.
* `noop.py` : Does nothing.
* `timed.py` : This spider uses `followall` spider with no domain restrictions.
* `timewaste.py` : This spider stops crawling for `600` seconds in between. It shows how scrapy could  be configured to delay in making requests.
