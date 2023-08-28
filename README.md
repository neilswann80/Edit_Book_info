Here is a quick and simple way to edit specific book info directly from a PocketBook, focusing on the PocketBook library categories of:
Author Name
Book Title
Series Title
Number in Series
Genre

Installation
Simply place "setup.app" and run it. This will add the prerequisite files the script needs to your device and initiate a restart.

Use
Simply long-press a book from the Home Screen or Library and you will have the option to:
Open with > Edit Book info
where you will be prompted to enter the new details for the attributes listed above. Once complete you'll have the option to overwrite the existing epub file or create an epub file by entering a new filename.

Book series
Whenever you modify the following three book attributes:
Author Name
Series Title
Genre
a series template text file is created (in "/mnt/ext1/Series Templates"). This allows you to select a template when editing books of the same series rather than retyping the same info every time. The text files are saved with a .tif extension so they can be managed/deleted easily via the Gallery application.

Please leave a comment on whether the package works for you, and/or if you have any suggestions for changes/additions. [You will likely need to be on firmware 6+.]

Thanks to:
This script is based on rkomar's "edit-epub" script and uses his sh_ivtool, zip and unzip binaries.
This script also uses a method of merging a TAR file into the script to unpack prerequisite files; functionality I borrowed from ezdiy's jailbreak installer.
