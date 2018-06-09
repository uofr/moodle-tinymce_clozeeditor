# CHANGE HISTORY

### 09 June 2018. 1.0
* Add privacy plugin data
* Increased window width (was 490) to 620 pixels
* Fixed all errors reported by the Moodle code checker plugin: 
  replaced tabs with spaces, 
  removed extra spaces at end of line, 
  added some needed spaces for indentation,
  added some braces in order to fix inline control errors
* Changed version numbering to 3.5r1 to reflect that 
  now it is compatable with Moodle 3.5 branch and that this is minor version 1
  
* Previous version had (212 errors/353 warnings)
  => phplint (0/0), phpcs (0/53), 
  js (187/299), 
  css (9/0), 
  phpdoc (15/0), savepoint (0/0), thirdparty (0/0), 
  grunt (1/1), shifter (0/0), mustache (0/0),

* (Hopefully) Fixed some phpdocs problems detected in the code by local_moodlecheck
* (Hopefully) Fixed most CSS problems detected by stylelint

