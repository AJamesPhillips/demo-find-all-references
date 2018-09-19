
In Visual Studio Code version 1.27.2 if file1.js is open but index.js is not, then using
"Find all references" whilst the cursor is on the `createRouter` returns only references
with in the file:

![alt text](https://github.com/AJamesPhillips/demo-find-all-references/raw/master/file1-open.png "file1.js open")

With index.js open, then this correctly shows all references:

![alt text](https://github.com/AJamesPhillips/demo-find-all-references/raw/master/both-files-open.png "file1.js and index.js open")
