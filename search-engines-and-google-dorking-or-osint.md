# Search Engines and Google Dorking | OSINT

### Google Dorks

Google hacking / Dorking utilizes Google's advanced search engine features, which allow you to pick out custom content. You can, for instance, pick out results from a certain domain name using the site: filter

| Filter         | Example                         | Description                                                                |
| -------------- | ------------------------------- | -------------------------------------------------------------------------- |
| site           | site:tryhackme.com              | returns results only from the specified website address                    |
| inurl          | inurl:admin                     | returns results that have the specified word in the URL                    |
| filetype       | filetype:pdf                    | returns results which are a particular file extension                      |
| intitle        | intitle:admin                   | returns results that contain the specified word in the title               |
|                | intitle:ethical.hacker          | dot represents the space                                                   |
| IP             | IP:10.10.10.10                  | **works on bing**. Use to check which websites are hosted on an IP address |
| linkfromdomain | linkfromdomain:cehpractical.com | **Works on Bing**. get all links from a domain                             |

[![Logo](https://osint.cavementech.com/~gitbook/image?url=https%3A%2F%2Fwww.exploit-db.com%2Ffavicon.ico\&width=20\&dpr=3\&quality=100\&sign=fd508aab62ebfd4a138026d5efa2831e\&sv=3)OffSec’s Exploit Database Archivewww.exploit-db.com](https://www.exploit-db.com/google-hacking-database)

_curated list of google dorks_

### Google Advanced Search

Google Advanced Search is a set of specialized search features and filters that allow users to refine their search queries to find more precise and specific results. It offers a range of tools beyond the basic search bar, enabling users to tailor their searches based on various criteria.

[![Logo](https://osint.cavementech.com/~gitbook/image?url=https%3A%2F%2Fwww.google.com%2Ffavicon.ico\&width=20\&dpr=3\&quality=100\&sign=2668c6c6dc30eeaa3a49b46222a235b6\&sv=3)Google Advanced Searchwww.google.com](https://www.google.com/advanced_search)

### Tips

**Using double quotes, restrict the results to exact search. (Works on Google,bing)**

![](<.gitbook/assets/image (3)>)

**You can use multiple conditional operators with google dorks**

![](<.gitbook/assets/image (4)>)

**Asterisk can be used as placeholder.**

![](<.gitbook/assets/image (5)>)

**Sometimes you can find cache content on bing if you do not find cache on google.**

### Web Search Engines

| Search Engine | URL                     | Remarks                                            |
| ------------- | ----------------------- | -------------------------------------------------- |
| Bing          | https://www.bing.com/   |                                                    |
| Yandex        | https://yandex.com/     | Russian. Has very good image recognition algorithm |
| Baidu         | https://www.baidu.com/  | Chinese                                            |
| DuckDuckGo    | https://duckduckgo.com/ | Privacy preserving search Engine                   |

[IntelTechniques Search Toolinteltechniques.com](https://inteltechniques.com/tools/Search.html)

_Combine Search Engine_

### S3 Bucket Search

[![Logo](<.gitbook/assets/image (6)>)Public Buckets by Grayhatwarfarebuckets.grayhatwarfare.com](https://buckets.grayhatwarfare.com/)

### Google Drive Search

[![Logo](https://osint.cavementech.com/~gitbook/image?url=https%3A%2F%2Fwww.dedigger.com%2Ffavicon.ico\&width=20\&dpr=3\&quality=100\&sign=a302d752499559acee14e44414367ab2\&sv=3)de-digger find public files in Google Drivededigger](https://www.dedigger.com/?s=Ecss#gsc.tab=0\&gsc.sort=\&gsc.q=CEH)

### AI google Dork Generator

[![Logo](<.gitbook/assets/image (7)>)DorkGPT - Generate Google Dorks with AIwww.dorkgpt.com](https://www.dorkgpt.com/)

### Best OSINT Course for Beginners

[![Logo](https://osint.cavementech.com/~gitbook/image?url=https%3A%2F%2Fwww.udemy.com%2Ffrontends-course-landing-page%2Ffavicon.ico\&width=20\&dpr=3\&quality=100\&sign=a456e6ab72ed4d0430b74f6f96aca94c\&sv=3)Practical OSINT: The Complete Course for BeginnersUdemy](https://www.udemy.com/course/practical-osint/?referralCode=0848C4EC66BBAC2534D6)
