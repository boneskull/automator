# Automator Workflows by [boneskull](https://github.com/boneskull)

This is a collection of random workflows made with [Automator.app](http://en.wikipedia.org/wiki/Automator_(software)).

## Contents

### Send to iBooks

A [service](https://developer.apple.com/library/mac/documentation/Cocoa/Conceptual/SysServices/introduction.html) which downloads the current webpage in Safari to a temp directory, then attempts to open it in [iBooks](http://en.wikipedia.org/wiki/IBooks).  The temporary file is then moved to the Trash.  

Supports `.pdf`, `.epub`, and [`.iba`](http://en.wikipedia.org/wiki/IBooks_Author) files.

#### TODO

1. For non-supported formats, it'd be cool to write some AppleScript to:
	1. Attempt to open in Safari's "Reader View"
	2. Print to `.pdf`
	3. Open resulting `.pdf` in iBooks
2. Support contents of clipboard, selected URLs (text) and "web content" (whatever that is) in any application.

## Author 

Christopher M. Hiller

## License

MIT
