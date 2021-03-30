# README
In Satellite:
1. git checkout tags/<tag> -b <branch> (point to the version which your app is using)
2. yarn build
3. cd packages/<package-name> (eg. cd packages/satellite-auth)
4. yarn link /
Now, in your app eg. IBD, Providers etc(whichever is using satellite):
5. yarn link @medlypharmacy/<library-name> (eg. yarn link @medlypharmacy/satellite-auth)
