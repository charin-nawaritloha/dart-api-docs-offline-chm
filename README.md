# dart-api-docs-offline-chm
Offline version of Dart API Documents in Microsoft® HTML Help format (chm)

## About
- Original offline document from [Archive | Dart](https://dart.dev/get-dart/archive)
- Use Microsoft® HTML Help Workshop to compile
- The chm version support
  - Table of contents.
  - Search by index (class name, method, operator and etc.).
  - Full text search. (results are not impressive but it's better than nothing)
  - Bookmark (favorite tab)
- All HTML and CSS files of the Dart API documentation have been heavily modified to be properly viewed in the CHM Viewer (old Internet Explorer browser engine).
  - Remove all &lt;script&gt; tag
  - Remove external source from all &lt;link&gt; tag
  - Remove button that change Light/Dark theme
  - Insert HTML content in right-sidebar file to main file directly.
  - Hide left-sidebar.
  - Use local fonts Verdana and Consolas instead of Google fonts.

## Tools
- Download Microsoft® HTML Help Workshop from [MSDN archives](https://web.archive.org/web/20160201063255/http://download.microsoft.com/download/0/A/9/0A939EF6-E31C-430F-A3DF-DFAE7960D564/htmlhelp.exe)
- Download HelpDocs.zip from [MSDN archives](http://web.archive.org/web/20160314043751/http://download.microsoft.com/download/0/A/9/0A939EF6-E31C-430F-A3DF-DFAE7960D564/helpdocs.zip)
