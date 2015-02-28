# divi-subscribe-module-feedpress-addon
Addon for ElegantThemes Divi theme to provide Feedpress functionality to the Subscribe Module

Fetch this patch.

Download Divi from ElegantThemes.  Latest Version is **2.3.1**.

Unzip Divi, and place the patch in the same directory as Divi.

Patch Divi.

```
patch -p0 < divi-2.3.1-subscribe-module-feedpress-addon.patch
```
**NOTE: You will need to go into the functions.php file, and replace <INSERT-FEED-NAME> with your feedpress feed.**
```
window.open('https://feed.press/e/mailverify?feed_id=&lt;INSERT-FEED-NAME&gt
```

If you have issues with the patch failing, please let me know. 
