# gazoubbsfix
GazouBBS (画像BBS) fixed for PHP 7.

# Note:
This was not translated to english. Every string and comment is in japanese. I suggest using DeepL and Google translate both at the same time to read comments/strings for the most accurate results (there are often multiple interpretations).

# Setup:
1. Make sure that the img folder (create it first), gazou.php and imglog.log are in the same directory.
2. Set the permission of imglog.log to at least 606. (code says 666)
3. Set the permission of the img folder to at least 717 (755 should be fine, code says 777)

# Fixed:
- Removed functions (ereg(), ereg_replace(), split())
- Upload directory BS
- Security flaw regarding file types

# Changes:
- Different autolink, which now shortens the url
- Different anti-multiline

# Credits:
ToR - original GazouBBS from 2002
