# v2.0.1
* Moved env variable to system space. Added a USER_LICENSE_KEY to the MSI properties to install the license key as a user env variable
* Added `[TOTAL_FILESNUMBER]` to the possible prefixes
* Updated German translation

# v2.0.0
* Added Delete pages task
* Added Convert to grayscale task
* Added Extract text task
* Added Repair task
* New application look
* Rotate task can now be used on multiple input PDF files
* Upgraded PDF engine
* Upgraded PDF rendering engine
* Localization completely reviewed and updated
* Diminished the overall size of the application
* Added button to open the generated PDF file using the native PDF reader
* Improved user interface for the Extract pages task
* Added a `Discard bookmarks` option to Extract pages, Split by size, Split by bookmarks, Split by text
* Improved user interface for the Rotate task
* Added merge option to consider the first file as a cover when generating a ToC
* Improved user interface for the Crop pages task
* Added `Ends with` field to split by text
* Improved user interface for the Split task
* Added manual proxy configuration to the settings panel
* Language combo to properly show the default language
* Encrypted passwords for PDF file when saving  tasks parameters to output file
* Added a number of keyboard shortcuts
* Fixed split by text selection when moving among pages with `Next` and `Prev` buttons
* Fixed enabling and disabling (first page, last page) of `Next` and `Prev` buttons in split by text
* Added a Log Viewer window to show application errors
* Added MSI properties `LOCALE`, `ACCEPT_EULA` and  `BUGS_AUTOREPORT`
* MSI now installs env variables in user space and removes them on uninstall
* Added a .zip portable bundle

# v1.1.8
* Fixes bug in Encrypt task

# v1.1.7
* Updates PDF engine.
* Fixed a permission issue on Linux.

# v1.1.6
* Updates PDF engine.
* Updates EULA.

# v1.1.5
* Adds support for porxy configuration.
* Updates underlying PDF library.

# v1.1.4
* Adds Italian translation.
* Adds Spanish translation.
* Adds German translation.

# v1.1.3
* Moves config location on Windows from %USERPROFILE% to %APPDATA%.
* Updates Encrypt task adding more permissions.
* Updates underlying PDF library, includes many minor bug fixes.
* Fixes bug related to handling different files with the same name.
* Adds Portuguese translation.
* Remembers customised result filenames.

# v1.1.2
* Fixes bug related to activating the product

# v1.1.1
* Natural sorting of filenames (1.pdf, 2.pdf, 10.pdf, 11.pdf) for merge and combine & reorder tasks.
* Larger magnifier zoom (8x).
* Batch (multiple files) support for the Split by pages task
* Smaller bugfixes and improvements.

# v1.1.0
* Visual page composer for combining and reordering PDF pages
* Select file or folder output location, for each task
* After trial ends PDFsam Visual is free to use within daily limits. Upgrade for premium features and unlimited use.
* Various bug fixes and improvements

# v1.0.9
* Improves French translation

# v1.0.8
* Adds French language support

# v1.0.7
*  Minor fixes and improvements, updates credits section.

# v1.0.6
*  Fixes a critical bug that can lead to missing data.
*  Upgrades the PDF engine with various bug fixes and enhancements 

# v1.0.5
* Includes bugfix for pre-activated silent installs in enterprise environments

# v1.0.4
* 14-day trial
* Includes various bugfixes for existing tasks

# v1.0.2
* Includes various bugfixes for existing tasks.
* Adds support for pre-activated silent installs in enterprise environments.
* Added context menu to easily select, unselect, invert selection

# v1.0.1
* Improved size of smaller monitors
* Fixed permissions related failures.
* Improved combine and reorder task with multiple page drag and drop, simpler page delete.
* Filename patterns are now remembered.
* Fixed bug related to filenames with accented characters on Windows, other Windows related stability improvements.
* Better handling of large files, increased available memory pool to 1Gb.
* Upgraded sejda-console

# v1.0.0
* Added Split by text task
* Upgraded PDFjs with corrected cmaps folder
* Upgraded sejda-console
* Upgraded icons
* Fixed the encrypt task failing with AES256
* Hide purchase menu item for PRO users

# v0.9.2
* Added Crop
* Added rotation to the Combine and Reorder task
* Added a scroll to top tag
