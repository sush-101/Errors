1. npm ERR! Unexpected end of JSON input while parsing near '...es":{"node":">=6.9.0"'

npm ERR! A complete log of this run can be found in:
npm ERR!     C:\Users\pc\AppData\Roaming\npm-cache\_logs\2020-06-05T05_35_39_846Z-debug.log

link : https://stackoverflow.com/questions/47675478/npm-install-errorunexpected-end-of-json-input-while-parsing-near-nt-webpack

This happens when the npm cache file gets corrupted.
The npm cache is located at C:\Users\pc\AppData\Roaming\npm-cache

We have to clean this and reinstall angular :
-> open cmd as admin
-> npm cache clean --force
-> npm install -g @angular/cli
