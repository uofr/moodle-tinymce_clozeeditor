# CHANGE HISTORY
## 14 January 2019. v3.5r7
* Started to fix errors reported by Moodle plugins database in JS files
* editor_plugin.js
* dialog1.js
lib\editor\tinymce\plugins\clozeeditor\tinymce\js\dialog1.js
    #136: ····//·-·1·Because·there·is·a·headline·.
    Inline comments must start with a capital letter, digit or 3-dots sequence

lib\editor\tinymce\plugins\clozeeditor\tinymce\js\encode.js
    #1: //·JavaScript·Document
    Inline comments must end in full-stops, exclamation marks, or question marks
    #3: //·Determine·whether·the·actual·test·is·of·type·"numerical",·or·any·other
    Inline comments must end in full-stops, exclamation marks, or question marks
    #14: //·Create·answers·array·where·all·answers·will·be·saved
    Inline comments must end in full-stops, exclamation marks, or question marks
    #18: //·Ultimate·encoding·function·which·does·all·the·calculations·upon·hitting·the·"encode"·button
    Inline comments must end in full-stops, exclamation marks, or question marks
    #20: ····//·Create·new·answers·object·in·the·array·for·all·filled·inputs
    Inline comments must end in full-stops, exclamation marks, or question marks
    #23: ········//·Fill·array,·and·use·getXxxElement·function·to·address·it
    Inline comments must end in full-stops, exclamation marks, or question marks
    #27: ············//·Add·':'·in·front·of·throttle·values·(Moodle's·Cloze·Quiz·Coding·Style)
    Inline comments must end in full-stops, exclamation marks, or question marks
    #37: ····//·document.Formular.output.value·=·"";
    Inline comments must end in full-stops, exclamation marks, or question marks
    #40: ····//·Create·output·for·all·filled·input·fields
    Inline comments must end in full-stops, exclamation marks, or question marks
    #43: ········//·var·add_correct·=·'';
    Inline comments must end in full-stops, exclamation marks, or question marks
    #45: ········//·Trim·all·texts·to·avoid·vacuous·white·spaces
    Inline comments must end in full-stops, exclamation marks, or question marks
    #51: ········//·If·it's·not·the·first·answer,·then·add·'~'·as·delimeter·between·answers
    Inline comments must end in full-stops, exclamation marks, or question marks
    #56: ········//·var·el·=·getPercentElement(i);
    Inline comments must start with a capital letter, digit or 3-dots sequence
    #57: ········//·Check·whether·a·percent·value·is·above·100%,·which·should·never·happen
    Inline comments must end in full-stops, exclamation marks, or question marks
    #68: ····················//·add_correct·+·····//·looks·like·this·was·vacuous
    Inline comments must start with a capital letter, digit or 3-dots sequence
    Inline comments must end in full-stops, exclamation marks, or question marks
    #75: ····//·Finally·build·the·complete·question
    Inline comments must end in full-stops, exclamation marks, or question marks

## 05 September 2018. v3.5r5

### possible important changes in 
* tinymce/editor_plugin.js - restored file from moodle.com
* dialog.css - restored file from moodle.com
* version.php - Version and release changed

## 05 September 2018. v3.5r4
### minor changes in:
* encode.js - Comments should start with Uppercase
* parse.js - space in line before var noStrings = "";
* parseAnswer.js - Comments should start with Uppercase
* parseFeedback.js - Comments should start with Uppercase
* parseHelper.js - Comments should start with Uppercase
* parsePercentaje.js - Comments should start with Uppercase
* popup.js - Comments should start with Uppercase
* changehistory.md - THIS FILE
* dialog.php  * @package    tinymce_colzeeditor  made * @package    tinymce_clozeeditor
* version.php - Version and release changed

### possible important changes in 
* tinymce/editor_plugin.js - spaces between key and : character
* dialog.css many spaces in many places and some : characters at end of line


## 09 June 2018. 1.0
* Add privacy plugin data
* Increased window width (was 490) to 620 pixels
* Fixed all errors reported by the Moodle code checker plugin: 
  replaced tabs with spaces, 
  removed extra spaces at end of line, 
  added some needed spaces for indentation,
  added some braces in order to fix inline control errors
* Changed version numbering to 3.5r1 to reflect that 
  now it is compatable with Moodle 3.5 branch and that this is minor version 1
 
* (Hopefully) Fixed some phpdocs problems detected in the code by local_moodlecheck
* (Hopefully) Fixed most CSS problems detected by stylelint
 
* Previous version had (212 errors/353 warnings)
  => phplint (0/0), phpcs (0/53), 
  js (187/299), 
  css (9/0), 
  phpdoc (15/0), savepoint (0/0), thirdparty (0/0), 
  grunt (1/1), shifter (0/0), mustache (0/0),

* PHPDocs style problems (15 errors, 0 warnings)
* This section shows the phpdocs problems detected in the code by local_moodlecheck [More info]

* lib/editor/tinymce/plugins/clozeeditor/classes/privacy/provider.php
(#23) File-level phpdocs block is not found
(#25) Class provider is not documented
(#34) Function provider::_get_reason is not documented
(#19) Invalid inline phpdocs tag @package found
(#20) Invalid inline phpdocs tag @copyright found
(#21) Invalid inline phpdocs tag @license found
(#32) Invalid inline phpdocs tag @return found
(#25) Package is not specified for class provider. It is also not specified in file-level phpdocs

* lib/editor/tinymce/plugins/clozeeditor/dialog.php
(#17) File-level phpdocs block is not found
* lib/editor/tinymce/plugins/clozeeditor/lang/en/tinymce_clozeeditor.php
(#16) No one-line description found in phpdocs for file
(#19) Package tiny_mce is not valid
* lib/editor/tinymce/plugins/clozeeditor/lib.php
(#17) File-level phpdocs block is not found
(#32) Function tinymce_clozeeditor::update_init_params is not documented
(#23) Package tiny_mce is not valid
* lib/editor/tinymce/plugins/clozeeditor/version.php
(#19) Package tiny_mce is not valid

* CSS problems (9 errors, 0 warnings)
* This section shows CSS problems detected by stylelint [More info]

* lib/editor/tinymce/plugins/clozeeditor/dialog.css
(#6) Expected single space before "{" (block-opening-brace-space-before)
(#11) Expected a trailing semicolon (declaration-block-trailing-semicolon)
(#2) Expected indentation of 4 spaces (indentation)
(#3) Expected indentation of 4 spaces (indentation)
(#7) Expected indentation of 4 spaces (indentation)
(#15) Expected indentation of 4 spaces (indentation)
(#19) Expected indentation of 4 spaces (indentation)
(#20) Expected indentation of 4 spaces (indentation)
(#19) Unexpected unit "pt" (unit-blacklist)
