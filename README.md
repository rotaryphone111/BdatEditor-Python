# BdatEditor-Python
Bdat Editor Python Rewrite

This program currently only works for XC2. In theory it should work for XC1DE but no testing has been done for this.
As should be evident by the release numbers, this package is currently in alpha and should therefore be used at your own risk.


INSTALLATION:
Run either:

    python setup.py (OSX/Linux)
    py setup.py(Windows)

or 

    pip install . (OSX/Linux)
    python -m pip install . (Windows)


CAVEATS:

- New rows *must* be filled completely right now. If they are not the bdat writer will throw an error.


CHANGELOG:

07/12/2021: Due to cross platform issues, I have added a tick box to display control characters. Saving while this is active is somewhat finnicky. Generally use at your own risk right now. Backup your stuff.

06/10/2021: Fixed an oopsies inherited from old BdatEditors to do with flags

06/09/2021: Fixed issues with the executable

06/09/2021: Crash bugfix

06/07/2021: Finally added setup scripts

06/04/2021: Added full undo and redo features
