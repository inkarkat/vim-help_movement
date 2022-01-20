HELP_MOVEMENT
===============================================================================
_by Ingo Karkat_

DESCRIPTION
------------------------------------------------------------------------------

This filetype plugin provides movement commands for Vim help sections.

USAGE
------------------------------------------------------------------------------

                            Move around Vim help sections (starting with a =====
                            line).
    ]]                      Go to [count] next start of a help section.
    ][                      Go to [count] next end of a help section.
    [[                      Go to [count] previous start of a help section.
    []                      Go to [count] previous end of a help section.

INSTALLATION
------------------------------------------------------------------------------

The code is hosted in a Git repo at
    https://github.com/inkarkat/vim-help_movement
You can use your favorite plugin manager, or "git clone" into a directory used
for Vim packages. Releases are on the "stable" branch, the latest unstable
development snapshot on "master".

This script is also packaged as a vimball. If you have the "gunzip"
decompressor in your PATH, simply edit the \*.vmb.gz package in Vim; otherwise,
decompress the archive first, e.g. using WinZip. Inside Vim, install by
sourcing the vimball or via the :UseVimball command.

    vim help_movement*.vmb.gz
    :so %

To uninstall, use the :RmVimball command.

### DEPENDENCIES

- Requires Vim 7.0 or higher.
- Requires the CountJump plugin ([vimscript #3130](http://www.vim.org/scripts/script.php?script_id=3130)).

CONTRIBUTING
------------------------------------------------------------------------------

Report any bugs, send patches, or suggest features via the issue tracker at
https://github.com/inkarkat/vim-help_movement/issues or email (address below).

HISTORY
------------------------------------------------------------------------------

##### 1.00    03-Oct-2010
- First published version.

------------------------------------------------------------------------------
Copyright: (C) 2010-2022 Ingo Karkat -
The [VIM LICENSE](http://vimdoc.sourceforge.net/htmldoc/uganda.html#license) applies to this plugin.

Maintainer:     Ingo Karkat &lt;ingo@karkat.de&gt;
