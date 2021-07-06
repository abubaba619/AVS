add KPU.js file in your HTML
use function name for popup $_kitotPopUp()
use class name for close button position P1 to P6
use class name for close button style C1 to C15 , use 'none' for hide button
use class name "KPUclose" to close popup .
check/use sample html file for practice.
example:
$_kitotPopUp({
"width":"300",
"height": "800",
"ID": "TP3",
"BG": "dark",
"html": "<img src='img file path here' class ='KPUclose' style='width:100%'/>", // or you can use/add custom HTMl here
"close":"C13 P4",
"CSS": "1",
});
