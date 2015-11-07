---
author: Stefan Kueng
layout: news
title: CryptSync
---

So I made another tool: CryptSync.

CryptSync is a small utility that synchronizes two folders
while encrypting the contents in one folder. That means one
of the two folders has all files unencrypted (the files
you work with) and the other folder has all the files
encrypted.

The synchronization works both ways: a change in one folder
gets synchronized to the other folder. If a file is added
or modified in the unencrypted folder, it gets encrypted.
If a file is added or modified in the encrypted folder, it
get decrypted to the other folder.

<p>
    <img class="defer" src="data:image/gif;base64,R0lGODlhAQABAAAAACH5BAEKAAEALAAAAAABAAEAAAICTAEAOw==" data-src="/assets/img/news/cryptsync_info.jpg" alt="CryptSync overview" width="500" height="250">
    <noscript><img src="/assets/img/news/cryptsync_info.jpg" width="500" height="250" alt="CryptSync overview"></noscript>
</p>

More information here about [CryptSync](http://stefanstools.sourceforge.net/CryptSync.html).

