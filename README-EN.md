![仙尊 pixiv 下载器 英文截图](https://wx4.sinaimg.cn/large/640defebgy1fspktkplcxj20zs0xbq84.jpg)

# Introduction:

This is a Pixiv image downloader written in JavaScript, which is essentially a UserScript. It must be installed using User Script Manager.

Some auxiliary functions have also been added, such as removing ads, quick collections, and viewing pictures.

**This tool now has a Chrome extension:**

[Chrome webstore page](https://chrome.google.com/webstore/detail/hfgoikdmppghehigkckknikdgdcjbfpl)

### Recommended Use:

Browser: **Chrome** [(download Chrome browser)](http://www.google.com/chrome/browser/desktop/)

User Script Manager: **Tampermonkey** [(view in Chrome webstore)](https://chrome.google.com/webstore/detail/tampermonkey/dhdgffkkebhmkfjojejmpbldmpobfkfo)

- Please turn off "Ask where to save each file before downloading" in browser settings.

- I don't guarantee that this tool will work well in other configurations. If you use other browser, memory usage may be too large, or your browser can not save the file.

# Install:

You can install it at greasyfork.org:

[https://greasyfork.org/zh-CN/scripts/24252](https://greasyfork.org/zh-CN/scripts/24252)

The downloaded file will be saved in your browser's download directory.

# Supported languages:

Simplified Chinese (also used under Traditional Chinese settings)

English (machine translation, also used under Korean settings)

日本語 (machine translation)

You can also optimize the translation, thank you very much :)

# Tips:

- Chrome's resource limits

When you download picture, this page uses more memory and cpu resources. If you switch to another page and the download page is not activated, Chrome will limit the resource usage of the download page, resulting in slow download.

How to solve: Pull out the downloaded tabs individually and become a separate window. This page is the only one in the new window and it is always active. Downloads are not affected, we can use other pages too.

- How to view the animation ( ugoira image ):

The animated picture is suffixed with ugoira. Please install HoneyView software. Open the ugoira file with HoneyView to see the animation effect.

Now you can download the gif image directly for a single animation.

# Available pages and test URL:

- [Index page](https://www.pixiv.net/)

- [ALL works page](https://www.pixiv.net/member_illust.php?mode=medium&illust_id=62751951)

- [ALL works list page](https://www.pixiv.net/member_illust.php?id=544479)

- [ALL tag list page](https://www.pixiv.net/member_illust.php?id=544479&tag=%E6%9D%B1%E6%96%B9)

- [ALL bookmarks page](https://www.pixiv.net/bookmark.php?id=544479)

- [ALL tag search page](https://www.pixiv.net/search.php?s_mode=s_tag&word=saber)

- [Ranking page](https://www.pixiv.net/ranking.php)

- [Area ranking page](https://www.pixiv.net/ranking_area.php?type=state&no=0)

- [Similar works page](https://www.pixiv.net/bookmark_add.php?id=63148723)

- [Discovery page](https://www.pixiv.net/discovery)

- [New work: everyone](https://www.pixiv.net/new_illust.php)

- [New work: following](https://www.pixiv.net/bookmark_new_illust.php)

- [Illustration on Showcase](https://www.pixiv.net/showcase/a/3190/)

- [Illustration, comics, cosplay page on pixivision](https://www.pixivision.net/zh/a/3190)

- [Image response](https://www.pixiv.net/response.php?mode=all&id=194231)

## Library used：

[Viewer.js](https://github.com/fengyuanchen/viewerjs)

[zip.js](https://github.com/gildas-lormeau/zip.js)

[gif.js](https://github.com/jnordberg/gif.js)