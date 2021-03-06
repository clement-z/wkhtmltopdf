v0.12.1 (unreleased)
--------------------
* **#1502**: fix spurious "exit with code 1 due to http error: 1xxx" errors
* **#1504**: **[qt]** fix rendering issues for JPEG with XMP metadata
* **#1507**: **[qt]** fix crash when CSS widows are specified
* **#1509**: fix TOC support which was broken after upgrade to latest QT
* produce selectable text when printing to PDF on Mac OSX
* generate API documentation for libwkhtmltox (on the website)
* display version in compiled binary properly under various scenarios
* minor improvements in the Windows/OS X build scripts

v0.12.0 (2014-02-06)
--------------------
* **#443**: add "sitepage" and "sitepages" support for headers
* **#175**: add ability to auto calculate header/footer heights
* **#1086**: don't return freed memory; instead use a string cache
* **#648**: delete infinite warnings into console about window status
* **#550**: enable tunneling to use a HTTP proxy for HTTPS
* **#1277**: avoid crash due to premature deletion of ResourceObject
* lots of fixes/enhancements for memory and error management
* add *--quiet* option to wkhtmltoimage
* add *--cache-dir* option for configuring web cache directory
* add *--load-media-error-handling* to handle errors for media files
* add *--viewport-size* to specify viewport size
* reserve heights when not using HTML header/footer
* lots of improvements in the build system
* lots of typos were fixed in various places
* **[qt]** rebase patch series on QT 4.8.5 (now hosted on github)
* **[qt]** fixes to get static builds working for MSVC 2010 (32/64 bit)
* **[qt]** prevent page breaks in table rows
* **[qt]** repeat THEAD/TFOOT when table contains page breaks
* **[qt]** improve font kerning as per Webkit bug 93263
* **[qt]** various table page-break improvements
* **[qt]** fix rendering due to incorrect page height computation
* **[qt]** implement "page-break-inside: avoid" for non-floating block elements
* **[qt]** enable WOFF file support
* **[qt]** add support for CSS widows and orphans for block elements
