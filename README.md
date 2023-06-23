# naicah0.2//VBScript
<script language="VBScript"><!--
function getIE()
dim t,l,a,b
set a=document.all.img1
t=document.all.img1.offsetTop
l=document.all.img1.offsetLeft
while a.tagName<>"BODY"
set a = a.offsetParent
t=t+a.offsetTop
l=l+a.offsetLeft
wend
msgbox "top="&t&chr(13)&"left="&l,64,"得到控件的位置"
end function
--></script>
