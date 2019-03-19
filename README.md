**Fork using OS command to correctly list >2GB filesizes on x86 (Linux only)**

sql.safe_mode = Off in php.ini required for the function to use exec
since ls -lh is used former function function __formatSize is obsolete 


Evoluted Directory Listing Script
==================================


System Requirements
--------------------
- PHP Version 5.3 or greater (5.6 recommended)
- GD Image Library
- ZipArchive PHP Extention (optional)

Installation
-------------
1. Unzip the provided files
2. Modify the configuration options as needed at the top of the index.php file.
3. Upload the index.php file to your web-accessible directory
4. You're done! Browse to the directory to see the script in action!

Credits for ls call: http://www.devkb.org/php/113-get-file-size-in-php-for-files-larger-than-2-gb
