# emacs-42-auto-header
tiny 'package' to configure emacs to automagically insert the 42 header into newly created .c and .h files
also updates time stamps as you go and replaces botched headers for you automagically
(those parts work 90% of the time 80% of the time)

'installation':
place this file as ~/.emacs.d/init.el, if you do not have an init.el already
if you have an existing init.el, just append the contents of emacs-42-auto-header.el to init.el
if you have split up your config into files, remember to add (provide '42-auto-header) at the end of the file,
and place it in whichever directory you have your other .el files in
