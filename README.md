# VDB: Valerie's Database Program for VSH and ZSH
VDB is a comprehensive and powerful program for viewing, creating, modifying and deleting database entries from within your shell.
> Installation Instructions are on the bottom of this file.

## Usage
- ``vdb -add entry_name``: Add a new entry with the name entry_name.

- ``vdb -mod entry_name``: Modify the entry with the name entry_name.

- ``vdb -list``: Show a list in tree format of all the entries in the database.

- ``vdb entry_name``: Show the entry for name entry_name.

- ``vdb``: Shows these instructions within VDB


### Choosing an Entry Name
Entry names are to follow the following naming convention:
language/topic

So, for example, the entry on JUnit for Java would be named: ``java/junit``.


### Formatting Entries
  - Entries must begin with the ``Valerie's Database`` title, immediately followed by a summary of the entry. For example, if the entry name is ``ffmpeg``, this summary would describe the function of FFMPEG.
  - Titles, Headings and Subheadings must be formatted with a line (``-----``) underneath it.
  - The end of the entry must be marked with ``-- END OF ENTRY --``
  - Entries should have the date of last modification shown under the END OF ENTRY line. 
> Note: This formatting is just a suggestion, intended to match the default formatting of the preprovided entries. You are free to format (or re-format) your entries however you wish.

## Installation
Here's how to install VDB on your Mac.

### Method 1: Install VSH
VDB is bundled with VSH, which has a dedicated install script which simplifies the installation process substantially. You can install VSH by [visiting it's repo](https://github.com/thequeenofclubs/vsh) and following the instructions there.


### Method 2: Manual Installation
If you don't want to install VSH, you can run VDB from within BASH or ZSH by installing it manually.
**Steps:**
1. Download the VDB executable from the releases page.
2. Create a folder in your home folder called ~/Scripts
3. Add the scripts folder to the path by typing ``export PATH=$PATH:~/Scripts``.
4. Move the VDB executable into the Scripts folder you just created.
5. Create a folder within scripts called ``vdblib`` (Case Sensitive)
6. Restart your shell for the changes to take effect.
