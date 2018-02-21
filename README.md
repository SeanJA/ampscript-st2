AMPScript
====

It is an exact target creation, you can find the docs here: https://developer.salesforce.com/docs/atlas.en-us.mc-programmatic-content.meta/mc-programmatic-content/index.htm

INSTALL
====

1.  Install [Sublime Package Control](http://wbond.net/sublime_packages/package_control)
1.  Open package control settings `ctrl-shift-p` then `Install Package`
1.  Search for `AmpScript Highlighter`
1.  Enojy :)

FEATURES
====
*  Highlights of all the functions in the wiki
*  Highlights all the personalization strings
*  To see what else works you can look in the `test.amp` file inside the `AmpScript Highlighter` package folder for samples from exact target
*  Some snippets for completing ampscript blocks `%%[ ]%%` is really annoying to type when you have bracket complete on

NOTES
====
*  Use one `%` or two `%%` signs to delimit your code blocks (more will technically work, but at somepoint it gets a little silly)
*  If you're working with pasted text that has html and ampscript, make sure you select the `HTML(AMPSCRIPT)` syntax
*  If you are only working with ampscript then you should be ok with the basic `AMPSCRIPT` syntax

TODO
====
1.  <del>Put in package control</del>
1.  Syntax hilighting in html attributes
1.  Auto completion of code/Snippets

Patches
====

Submit patches to the .JSON-tmLanguage files, not the xml files which are generated from them.

Build with AAAPackageDev and test against `test.amp`
