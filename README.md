# syno-ds-magnetdl-dlm
Synology Download Station MagnetDL updated DLM search file

Recently Synology's Download Station stopped showing results. You just get "No results"

Synoboost's list is outdated and either doesn't work, or works poorly. The newer 1337xxx seems to show too many results, as if it searches each word in your query separately instead of the whole query itself. For example, searching for "myMovie x265 1080p" would get you all results for "1080p", and all results for "x265" along with all results of "myMovie", instead of searching for a specific "myMovie x265 1080p", which made it less than useful.

Anyway, TLDR, I modified the older MagnetDL.dlm from Synoboost. It should work now. For those interested in developing this more, you can use the API here: https://global.synologydownload.com/download/Document/Software/DeveloperGuide/Package/DownloadStation/All/enu/DLM_Guide.pdf

Rename the .dlm to .tgz, extract and edit the search.php file.

NOTE: I still got a lot of search results from 1337xxx even though I disabled it from download station's settings. If so, delete it, stop DS and start it again.

HTH.
