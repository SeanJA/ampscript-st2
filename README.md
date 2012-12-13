AMPScript
====

It is an exact target creation, you can find the docs here: http://wiki.memberlandingpages.com/AMPscript/AMPscript_Syntax_Guide

I have some of the syntax hilighting working (code blocks, inline code, "constants"...).

INSTALL
====

1.  Install [Sublime Package Control](http://wbond.net/sublime_packages/package_control)
1.  Open package control settings.
    *  Sublime Text 2 > Preferences > Package Control  
1.  Select _PackageControl: Add Repository_
    *  The prompt will appear at the bottom.
1.  Paste in `https://github.com/SeanJA/ampscript-st2`
    * You'll see a message in the status bar saying that it was installed correctly.
1.  Open package control settings again
1.  Select _PackageControl: Install Package_
1.  When the new popup appears start find ampscript-st2 and double-click it.
    * ampscript-st2 has the best features for HTML ampscript
    *  BEWARE, there's also AMPscript.  Don't install that one.  You can have both installed, but why bother?
1.  If you're working with pasted text, make sure you select the syntax
    *  View > Syntax > ampscript-st2 > HTML(AMPScript)
1. Enojy :)

TODO
====
1.  Syntax hilighting in quotes in html attributes
1.  Tag Based Syntax
1.  Auto completion of code
1.  Snippets

Patches
====

Submit patches to the .JSON-tmLanguage files, not the xml files which are generated from them.

Build with AAAPackageDev and test against `test.amp`
