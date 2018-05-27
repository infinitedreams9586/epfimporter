# epfimporter
fixed utf8mb4 issue

This is Apple's EPF Importer utility which was last updated in 2010, with added fix for extended character set (like emojis etc.)
Original EPF Importer utility uses UTF8 encoding for database, which can't hold emoji chars, 
so, database should be supported with UTF8MB4 encoding type.

Apple's original EPF Importer: https://affiliate.itunes.apple.com/resources/documentation/epfimporter/
