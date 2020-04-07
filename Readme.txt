- Winrar_Archiver_Preactived info

  Official Web: https://www.rarlab.com/

  Details       : wrar590.exe
  MD5           : 27853ff0ca183366477afb6c2e119d67
  SHA1          : 8148790d89ccf01a7c56766e4354927e7ccdf30e
  File type     : executable
  File size     : 3.82 MB
  File Version  : 5.90.0
  Copyright     : Copyright © Alexander Roshal 1993-2020
  Product       : WinRAR
  Description   : WinRAR archiver
  Original Name : WinRAR.exe
  CompanyName   : Alexander Roshal
  Virus Analysis: 28/72 (virus total)    https://www.virustotal.com/gui/file/c9524ab51f0d4b3cf632ed6a709e8441657b46d2a558cdf276762ad14db3e26b/details

  Details       : winrar-x64-590.exe
  MD5           : 3db8957da64527f49f810462a37da682
  SHA1          : 8bc5d9c8de499c918e231dd27b60e0352cf537ef
  File type     : executable
  File size     : 4.41 MB
  File Version  : 5.90.0
  Copyright     : Copyright © Alexander Roshal 1993-2020
  Product       : WinRAR
  Description   : WinRAR archiver
  Original Name : WinRAR.exe
  CompanyName   : Alexander Roshal
  Virus Analysis: 26/72 (virus total)  https://www.virustotal.com/gui/file/5638e870bae8092958631c5801e3fb8184f8391db9bc7327753261bc20675165/details

- Notes:
  1. it's false possitive and safe to install on your computer
  2. it's pre-activated and ready to use without activation
  3. use "wrar590.exe" to x32 bit operating system windows and use "winrar-x64-590.exe" to x64 bit operating system windows
 
- What's new in winrar version 5.90:
  1. RAR compression speed is improved for CPUs with 16 and more cores.

  2. "Fastest" method (-m1 command line equivalent) typically achieves
      a higher compression ratio for highly compressible data types
      when creating RAR5 archives.

  3. Maximum number of utilized threads is increased from 32 to 64.
      Command line -mt<threads> switch accepts values from 1 to 64.

  4. "Multithreading" parameter on "General" page of WinRAR settings
      is replaced with "Threads" input field, where you can specify
      the desired number of CPU threads. It can take values from 1 to
      maximum number of available logical CPU units.

  5. WinRAR displays packed and unpacked folder sizes when browsing
      archive contents.
   
  6. "Total folders" field is added to list of archive parameters
      displayed by WinRAR "Info" command. Same field is added to
      "Archive" page in archive properties in Windows Explorer.

  7. Window including a progress bar and "Cancel" button is displayed
      if reading archive contents takes noticeable time.
      It can be useful for archive formats with slower access to contents,
      such as large TAR based archives like .tar.gz and tar.bz2.

  8. Archiving and extraction progress windows, also as progress windows
      for some other commands, can be resized.
         
  9. "Repair" performance for RAR5 archives with recovery record
      and without data shifts is improved. It deteriorated in WinRAR 5.80
      and is now restored to original level.

 10. Password prompt is not issued when performing recovery record based
      repair for RAR5 archives with encrypted file names.
      This command can be performed without providing a password.

 11. If folder for converted archives in "Convert archives" command
      does not exist, WinRAR attempts to create it. Previous versions
      failed to create converted archives in non-existent destination folder.

 12. Added extraction support for GZIP archives with optional header
      checksum field.
   
 13. Bugs fixed:

     a) "Repair" command could erroneously display "Recovery record is
         corrupt" message when processing an archive with valid recovery
         record. This message did not prevent further repair operation;

     b) if quick open information option was set to "Do not add" in default
         compression profile and this profile was loaded by some command
         or dialog, WinRAR ignored quick open information when browsing
         contents of RAR archives. For example, it happened after opening
         archiving or password dialogs;

     c) Ctrl+C "Copy" shortcut key did not work in archive comment window;

     d) if "Put each file to separate archive" and "Archives in subfolders"
         options were set, WinRAR ignored the destination path specified
         in archive name field.
         
  - More Info: https://www.rarlab.com/rarnew.htm
