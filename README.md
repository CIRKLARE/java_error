# java_error
solve java error in Linux
---------------------------------

this is error

-----------------------------------------------------------------------------

Picked up _JAVA_OPTIONS: -Dawt.useSystemAAFontSettings=on -Dswing.aatext=true

------------------------------------------------------------------------------

to solve this issue
paste this in terminal before running your command

--------------------------------------

SILENT_JAVA_OPTIONS="$_JAVA_OPTIONS"
unset _JAVA_OPTIONS
alias='java "$_SILENT_JAVA_OPTIONS"'

-------------------------------------
