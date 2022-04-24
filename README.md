# SYSTEMMODAL
#include &lt;MsgBoxConstants.au3> Local $Part = 1;The "part" number of the status bar to read - the default is 1. 1 is the first possible part and usually the one that contains the useful messages like "Ready" "Loading...", etc. Local $sText = StatusbarGetText("title of window here",'',$Part) MsgBox($MB_SYSTEMMODAL, "", "status bar says: " &amp; $sText
