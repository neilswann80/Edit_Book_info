Here is a quick and simple way to [B]edit specific book info[/B] directly from a PocketBook, focusing on the PocketBook library categories of:
[B][LIST]Author Name[/LIST]
[LIST]Book Title[/LIST]
[LIST]Series Title[/LIST]
[LIST]Number in Series[/LIST]
[LIST]Genre[/LIST][/B]
[B]Installation[/B]
Simply place "setup.app" (available [URL="https://github.com/neilswann80/Edit_Book_info/releases/download/PocketBook/setup.zip"]HERE[/URL]) into the applications directory of your device (/mnt/ext1/applications) and run it.  This will add the prerequisite files the script needs to your device and initiate a restart.

[B]Use[/B]
Simply long-press a book from the Home Screen or Library and you will have the option to: 
[U][I]Open with > Edit Book info[/I][/U]
where you will be prompted to enter the new details for the attributes listed above.  Once complete you'll have the option to overwrite the existing epub file or create an epub file by entering a new filename.

[B]Book series[/B]
Whenever you modify the following three book attributes:
[I][U]Author Name
Series Title
Genre[/U][/I]
a series template text file is created (in "/mnt/ext1/Series Templates").  This allows you to select a template when editing books of the same series rather than retyping the same info every time.  The text files are saved with a .tif extension so they can be managed/deleted easily via the Gallery application.

Please leave a comment on whether the package works for you, and/or if you have any suggestions for changes/additions.  [You will likely need to be on firmware 6+.]

Thanks to:
[LIST]This script is based on [B]rkomar's [/B] "edit-epub" script and uses his sh_ivtool, zip and unzip binaries available from [URL="http://komary.net/"]HERE[/URL][/LIST]
[LIST]This script also uses a method of merging a TAR file into the script to unpack prerequisite files; functionality I borrowed from [B]ezdiy's[/B] jailbreak installer.[/LIST]

The installer can be found [URL="https://github.com/neilswann80/Edit_Book_info/releases/download/PocketBook/setup.zip"]HERE[/URL]
