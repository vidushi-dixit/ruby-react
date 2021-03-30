# README
In Satellite:
* git checkout tags/<tag> -b <branch> (point to the version which your app is using)
* yarn build
* cd packages/<package-name> (eg. cd packages/satellite-auth)
* yarn link

Now, in your app eg. IBD, Providers etc(whichever is using satellite):
* yarn link @medlypharmacy/<library-name> (eg. yarn link @medlypharmacy/satellite-auth)
