<div align="center">

## Javascript\(s\) you better not miss\!\!\!


</div>

### Description

I have presented a few Javascript examples that I have found very useful while designing professional websites. This tutorial is aimed at those who have good knowledge of Javascript. So the examples are not explained in great detail. Only the important parts are highlighted.There are many ways to implement these examples here. The code presented here is neither the shortest nor the most efficient. But it does work satisfactorily.
 
### More Info
 


<span>             |<span>
---                |---
**Submitted On**   |
**By**             |[KP](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByAuthor/kp.md)
**Level**          |Intermediate
**User Rating**    |4.1 (41 globes from 10 users)
**Compatibility**  |
**Category**       |[Internet/ Browsers/ HTML](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByCategory/internet-browsers-html__2-68.md)
**World**          |[Java](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByWorld/java.md)
**Archive File**   |[](https://github.com/Planet-Source-Code/kp-javascript-s-you-better-not-miss__2-2694/archive/master.zip)





### Source Code


<font face="Verdana, Arial, Helvetica, sans-serif" size="-1"> <b><font size="+2">
</font></b></font>
<table width="98%" border="0" bgcolor="#AFAFAF" cellpadding="1" cellspacing="0" align="center">
 <tr>
  <td>
   <table width="100%" border="0" cellpadding="3" cellspacing="0">
    <tr bgcolor="#FFFFFF">
     <td>
      <div align="center"><font face="Verdana, Arial, Helvetica, sans-serif" size="-1"><b><font size="+2">9
       Javascript(s) you better not miss !!</font></b></font></div>
     </td>
    </tr>
   </table>
  </td>
 </tr>
</table>
<br>
<font face="Verdana, Arial, Helvetica, sans-serif" size="-1"><br>
This tutorial is aimed at those who have a working knowledge of Javascript. So
the examples are not explained in great detail. Only the important parts are highlighted.
I have presented 9 Javascript examples that I have found very useful while designing
professional websites. There are many ways to implement these examples here. The
code presented here is neither the shortest nor the most efficient. But it does
work satisfactorily.<br>
<br>
Please not that that wherever there is a mention of any .jpg , .gif or any other
.html files, see to it that you have a dummy .gif, .jpg or .html file in the same
directory as the script file so that the script finds these files. They can be
any files since the logic of the script doesn't depend on these files. Try to
understand the way the examples work, and you will be able to modify them and
make them more useful. Also note that the entire code for the html page is not
present here. Only the script and the relevant html is present.<br>
<br>
<br>
<b>Example 1 : A Single click for checking-unchecking multiple check boxes</b><br>
</font> <font face="Verdana, Arial, Helvetica, sans-serif" size="-1">You must
have seen this script working at many places. One that comes to my mind is at
Yahoo / Hotmail for checking or unchecking all the mails that are visible on the
page. There are lots of places where you can use this script, generally when you
want the user to carry out some task on either all or none of the items that you
present to him.<br>
</font> <font face="Verdana, Arial, Helvetica, sans-serif" size="-1"><br>
</font>
<table width="100%" border="0" cellpadding="0" cellspacing="0" bgcolor="#F5F5F5">
 <tr bgcolor="#F5F5F5">
  <td colspan="4"><font face="Verdana, Arial, Helvetica, sans-serif" size="-1">&lt;SCRIPT
   LANGUAGE = &quot;JavaScript&quot;&gt;<br>
   &lt;!--<br>
   </font></td>
 </tr>
 <tr bgcolor="#F5F5F5">
  <td colspan="4"><font face="Verdana, Arial, Helvetica, sans-serif" size="-1">function
   modify_boxes(to_be_checked,total_boxes){</font></td>
 </tr>
 <tr bgcolor="#F5F5F5">
  <td width="3%">&nbsp;</td>
  <td colspan="3"><font face="Verdana, Arial, Helvetica, sans-serif" size="-1">for
   ( i=0 ; i &lt; total_boxes ; i++ ){</font></td>
 </tr>
 <tr bgcolor="#F5F5F5">
  <td width="3%" rowspan="3">&nbsp;</td>
  <td width="2%" rowspan="3">&nbsp;</td>
  <td colspan="2"><font face="Verdana, Arial, Helvetica, sans-serif" size="-1">if
   (to_be_checked){ </font></td>
 </tr>
 <tr>
  <td width="3%">&nbsp;</td>
  <td width="92%"><font face="Verdana, Arial, Helvetica, sans-serif" size="-1">document.forms[0].chkboxarray[i].checked=true;</font></td>
 </tr>
 <tr>
  <td colspan="2"><font face="Verdana, Arial, Helvetica, sans-serif" size="-1">}</font></td>
 </tr>
 <tr bgcolor="#F5F5F5">
  <td width="3%">&nbsp;</td>
  <td width="2%">&nbsp;</td>
  <td colspan="2"><font face="Verdana, Arial, Helvetica, sans-serif" size="-1">else{</font></td>
 </tr>
 <tr bgcolor="#F5F5F5">
  <td width="3%">&nbsp;</td>
  <td width="2%">&nbsp;</td>
  <td width="3%"><font face="Verdana, Arial, Helvetica, sans-serif" size="-1"><br>
   </font></td>
  <td width="92%"><font face="Verdana, Arial, Helvetica, sans-serif" size="-1">document.forms[0].chkboxarray[i].checked=false;</font></td>
 </tr>
 <tr bgcolor="#F5F5F5">
  <td width="3%">&nbsp;</td>
  <td width="2%">&nbsp;</td>
  <td colspan="2"><font face="Verdana, Arial, Helvetica, sans-serif" size="-1">}</font></td>
 </tr>
 <tr bgcolor="#F5F5F5">
  <td width="3%">&nbsp;</td>
  <td width="2%"><font face="Verdana, Arial, Helvetica, sans-serif" size="-1">}</font></td>
  <td colspan="2">&nbsp;</td>
 </tr>
 <tr bgcolor="#F5F5F5">
  <td width="3%"><font face="Verdana, Arial, Helvetica, sans-serif" size="-1">}<br>
   </font></td>
  <td width="2%">&nbsp;</td>
  <td colspan="2">&nbsp;</td>
 </tr>
 <tr bgcolor="#F5F5F5">
  <td colspan="4"><font face="Verdana, Arial, Helvetica, sans-serif" size="-1">--&gt;<br>
   &lt;/SCRIPT&gt;</font> <font face="Verdana, Arial, Helvetica, sans-serif" size="-1"><br>
   <br>
   </font></td>
 </tr>
 <tr bgcolor="#F5F5F5">
  <td colspan="4"><font face="Verdana, Arial, Helvetica, sans-serif" size="-1">&lt;BODY&gt;<br>
   &lt;FORM&gt;<br>
   &lt;INPUT TYPE=checkbox NAME=&quot;chkboxarray&quot; VALUE=&quot;1&quot;&gt;&lt;br&gt;<br>
   &lt;INPUT TYPE=checkbox NAME=&quot;chkboxarray&quot; VALUE=&quot;2&quot;&gt;&lt;br&gt;<br>
   &lt;INPUT TYPE=checkbox NAME=&quot;chkboxarray&quot; VALUE=&quot;3&quot;&gt;&lt;br&gt;<br>
   &lt;INPUT TYPE=button NAME=&quot;CheckAll&quot; VALUE=&quot;Check All Boxes&quot;
   onClick=&quot;modify_boxes(true,3)&quot;&gt;<br>
   &lt;INPUT TYPE=button NAME=&quot;UnCheckAll&quot; VALUE=&quot;UnCheck All
   Boxes&quot; onClick=&quot;modify_boxes(false,3)&quot;&gt;<br>
   &lt;/FORM&gt;<br>
   &lt;/BODY&gt; </font></td>
 </tr>
</table>
<p><font face="Verdana, Arial, Helvetica, sans-serif" size="-1"><b>Note :</b>
 The VALUE tag for the checkboxes seem to have no use. But it is required to
 differentiate between the check boxes when you submit such a form to a server
 side program. You could differentiate between the checked boxed by giving different
 VALUEs to the checkbox.<br>
 <br>
 <br>
 <b>Example 2 : Opening a page (existing as well as dynamic) in a new window
 without bars, buttons, etc.</b><br>
 This script shows how to open a new page inside a new window rather than the
 existing window. You can also remove all the buttons and toolbars that exist
 in the standard browser window so that the entire new window is filled with
 only your content. You could either open an existing page or you could create
 dynamic content inside the new window.<br>
 </font></p>
<table width="100%" border="0" cellpadding="0" cellspacing="0">
 <tr bgcolor="#F5F5F5">
  <td colspan="3"><font face="Verdana, Arial, Helvetica, sans-serif" size="-1">&lt;SCRIPT
   LANGUAGE = &quot;JavaScript&quot;&gt;<br>
   &lt;!--<br>
   <br>
   function open_new_window() {</font></td>
 </tr>
 <tr bgcolor="#F5F5F5">
  <td width="6%">&nbsp;</td>
  <td colspan="2" width="94%"><font face="Verdana, Arial, Helvetica, sans-serif" size="-1">dlg
   = window.open (&quot;newpage.html&quot; ,&quot;NewWindowName&quot; , &quot;width=400,height=400,<br>
   toolbar=no,location=no,directories=no,<br>
   status=no,menubar=no,scrollbars=no,resizable=no&quot;) </font></td>
 </tr>
 <tr bgcolor="#F5F5F5">
  <td colspan="3">
   <p><font face="Verdana, Arial, Helvetica, sans-serif" size="-1">}</font></p>
   <p><font size="-1" face="Verdana, Arial, Helvetica, sans-serif">function
    open_new_window2() { </font></p>
  </td>
 </tr>
 <tr bgcolor="#F5F5F5">
  <td width="6%">&nbsp;</td>
  <td colspan="2" width="94%"><font size="-1" face="Verdana, Arial, Helvetica, sans-serif">dlg
   = window.open (&quot;&quot;,&quot;NewWindowName2&quot;,&quot;width=400,height=400,toolbar=no,location=no,<br>
   directories=no,status=no,menubar=no,scrollbars=no,resizable=no&quot;)<br>
   dlg.document.write (&quot;&lt;BODY bgColor='#FFFFFF'&gt;&quot;)<br>
   dlg.document.write (&quot;&lt;CENTER&gt;This is text that has been added
   on the fly using Javascript.&lt;/CENTER&gt;&quot;)<br>
   dlg.document.write (&quot;&lt;/BODY&gt;&quot;) </font></td>
 </tr>
 <tr bgcolor="#F5F5F5">
  <td colspan="3">
   <p><font size="-1" face="Verdana, Arial, Helvetica, sans-serif">}<br>
    --><br>
    </font><font size="-1" face="Verdana, Arial, Helvetica, sans-serif">&lt;/SCRIPT&gt;<br>
    <br>
    </font><font size="-1" face="Verdana, Arial, Helvetica, sans-serif">&lt;BODY&gt;<br>
    &lt;A onClick='open_new_window()' &gt;Click anywhere on this text to open
    the file newpage.html in a new window&lt;/a&gt;&lt;br&gt;<br>
    <br>
    Or click on the button below to open a dynamically generated html page&lt;br&gt;<br>
    <br>
    &lt;FORM&gt; <br>
    &lt;INPUT type=&quot;button&quot; value=&quot;New Window&quot; onClick
    ='open_new_window2()' &gt; <br>
    &lt;/FORM&gt;<br>
    &lt;/BODY&gt; </font></p>
   </td>
 </tr>
</table>
<p><font face="Verdana, Arial, Helvetica, sans-serif" size="-1"><br>
 <br>
 <b>Example 3 : Multiple submit buttons on a single form (Submitting same form
 to any one of many programs) </b><br>
 This script shows you how to submit the contents of a form to different programs
 depending on which Submit button you press. Additionally it also shows how to
 call two different functions when you press the Submit button. </font></p>
<p><font face="Verdana, Arial, Helvetica, sans-serif" size="-1">When you press
 submit on this script it first sets the variable totalboxes = 2, then it also
 sets the target for the form using the 3 if conditions stated. Then it calls
 the isReady() function and checks to see if atleast one checkbox has been checked.
 If even one is checked then it returns true and this causes the contents to
 be submitted to either program1.jsp or program2.jsp or program3.jsp. If even
 one checkbox wasn't checked you would be notified with a alert dialog box.<br>
 </font></p>
<table width="100%" border="0" cellpadding="0" cellspacing="0">
 <tr bgcolor="#F5F5F5">
  <td colspan="3"><font face="Verdana, Arial, Helvetica, sans-serif" size="-1">&lt;SCRIPT
   LANGUAGE = &quot;JavaScript&quot;&gt;<br>
   &lt;!--<br>
   <br>
   var totalboxes;<br>
   <br>
   function setCount(count, target){<br>
   </font></td>
 </tr>
 <tr bgcolor="#F5F5F5">
  <td width="3%">&nbsp;</td>
  <td colspan="2">
   <p><font face="Verdana, Arial, Helvetica, sans-serif" size="-1">totalboxes=count;</font></p>
   <p><font face="Verdana, Arial, Helvetica, sans-serif" size="-1">// the next
    3 lines are the main lines of this script<br>
    //remember to leave action field blank when defining the form <br>
    if(target == 0) document.myform.action=&quot;program1.jsp&quot;;<br>
    if(target == 1) document.myform.action=&quot;program2.jsp&quot;;<br>
    if(target == 2) document.myform.action=&quot;program3.jsp&quot;; </font></p>
  </td>
 </tr>
 <tr bgcolor="#F5F5F5">
  <td colspan="3">
   <p><font face="Verdana, Arial, Helvetica, sans-serif" size="-1">}<br>
    <br>
    function isReady(form) {<br>
    </font></p>
  </td>
 </tr>
 <tr bgcolor="#F5F5F5">
  <td width="3%" rowspan="3">&nbsp;</td>
  <td bgcolor="#F5F5F5" colspan="2"><font face="Verdana, Arial, Helvetica, sans-serif" size="-1">for(var
   x=0 ; x&lt;totalboxes ; x++){<br>
   </font></td>
 </tr>
 <tr>
  <td width="1%" bgcolor="#F5F5F5"><font face="Verdana, Arial, Helvetica, sans-serif" size="-1"><br>
   </font></td>
  <td width="96%" bgcolor="#F5F5F5"><font face="Verdana, Arial, Helvetica, sans-serif" size="-1">//if
   even one box is checked then return true<br>
   if(myform.boxes[x].checked) return true; </font></td>
 </tr>
 <tr>
  <td width="1%" bgcolor="#F5F5F5"><font face="Verdana, Arial, Helvetica, sans-serif" size="-1">}</font></td>
  <td width="96%" bgcolor="#F5F5F5">&nbsp;</td>
 </tr>
 <tr bgcolor="#F5F5F5">
  <td width="3%">&nbsp;</td>
  <td colspan="2">
   <p><font face="Verdana, Arial, Helvetica, sans-serif" size="-1">//default
    action : When even one was not checked then..<br>
    alert(&quot;Please check at least one checkbox..&quot;);<br>
    return false;</font></p>
   </td>
 </tr>
 <tr bgcolor="#F5F5F5">
  <td colspan="3">
   <p><font face="Verdana, Arial, Helvetica, sans-serif" size="-1">}</font></p>
   <p><font face="Verdana, Arial, Helvetica, sans-serif" size="-1">//--&gt;<br>
    &lt;/SCRIPT&gt;</font></p>
   <p><font face="Verdana, Arial, Helvetica, sans-serif" size="-1">&lt;BODY&gt;</font></p>
   <p><font face="Verdana, Arial, Helvetica, sans-serif" size="-1">&lt;FORM
    onSubmit=&quot;return isReady(this)&quot; METHOD=&quot;post&quot; NAME=&quot;myform&quot;
    ACTION=&quot;&quot;&gt;<br>
    &lt;INPUT TYPE=&quot;checkbox&quot; NAME=&quot;boxes&quot; VALUE=&quot;box1&quot;&gt;Box
    1 &lt;BR&gt; <br>
    &lt;INPUT TYPE=&quot;checkbox&quot; NAME=&quot;boxes&quot; VALUE=&quot;box2&quot;&gt;Box
    2 &lt;BR&gt;<br>
    &lt;INPUT TYPE=&quot;checkbox&quot; NAME=&quot;boxes&quot; VALUE=&quot;box2&quot;&gt;Box
    3 &lt;BR&gt;<br>
    &lt;INPUT TYPE=&quot;checkbox&quot; NAME=&quot;boxes&quot; VALUE=&quot;box2&quot;&gt;Box
    4 &lt;BR&gt;<br>
    &lt;INPUT TYPE=&quot;checkbox&quot; NAME=&quot;boxes&quot; VALUE=&quot;box2&quot;&gt;Box
    5 &lt;BR&gt; <br>
    &lt;/FORM&gt;</font></p>
   <p><font face="Verdana, Arial, Helvetica, sans-serif" size="-1">&lt;INPUT
    TYPE=&quot;image&quot; onClick=&quot;setCount(5,0)&quot; NAME=&quot;Submit1&quot;
    VALUE=&quot;delete&quot; SRC=&quot;delete_icon.jpg&quot;&gt;<br>
    &lt;INPUT TYPE=&quot;image&quot; onClick=&quot;setCount(5,1)&quot; NAME=&quot;Submit2&quot;
    VALUE=&quot;view&quot; SRC=&quot;view_icon.jpg&quot;&gt;<br>
    &lt;INPUT TYPE=&quot;image&quot; onClick=&quot;setCount(5,2)&quot; NAME=&quot;Submit3&quot;
    VALUE=&quot;modify&quot; SRC=&quot;modify_icon.jpg&quot;&gt; </font></p>
   <p><font face="Verdana, Arial, Helvetica, sans-serif" size="-1">&lt;/BODY&gt;
    </font></p>
   </td>
 </tr>
</table>
<p><font face="Verdana, Arial, Helvetica, sans-serif" size="-1">The setCount()
 take 2 parameters, the no of checkboxes and the target program to which the
 contents have to be submitted to.</font></p>
<p><font face="Verdana, Arial, Helvetica, sans-serif" size="-1"><b>Note :</b>
 Sending the variable 5 for no of boxes using the onClick() event is useful in
 case you are not knowing the no. of checkboxes while writing the top part of
 the html page (while writing the script part at the top of the page). This may
 happen in case you are dynamically creating this html page then you may not
 know how many checkboxes would be present in the beginning. Basically this thing
 becomes useful since the dynamic languages such as ASP or JSP would generate
 the page line by line and at that time you would first generate the script part
 and then the actual checkboxes on the page. So you would not be able to set
 the value of totalboxes to <i>a finite number</i> before actually adding all
 the checkboxes to the page. You could use a counter (within ASP/JSP) which keeps
 track of the checkboxes you add to the html page and finally set the value of
 that counter as a parameter to this onClick() function. <br>
 You could avoid this by typing the Script at the bottom of the page, but that
 doesn't work with a few browsers. In case you haven't got the point, its ok..
 Just understand how to submit the form to different programs. You can leave
 the checkbox part... <br>
 <br>
 <br>
 <b>Example 4 : Emulating Browsers Back-Forward buttons</b><br>
 This is a simple script that many programmers know. Most of the users feel that
 this is a waste since the browsers Forward-Back buttons are already present.
 But you would realize that in case you are creating a window without the standard
 toolbars as shown in Example No.3 , then you would find this script to be very
 useful to emulate the Browsers buttons.<br>
 <br>
 I have shown 2 ways.. I prefer the image one, since it looks really neat in
 case you have nice image.<br>
 </font></p>
<table width="100%" border="0">
 <tr bgcolor="#F5F5F5">
  <td><font face="Verdana, Arial, Helvetica, sans-serif" size="-1">&lt;BODY&gt;<br>
   &lt;FORM&gt; <br>
   &lt;INPUT TYPE=&quot;image&quot; SRC=&quot;N.jpg&quot; NAME=&quot;back&quot;
   onClick=&quot;window.history.go(-1)&quot;&gt;<br>
   &lt;INPUT TYPE=&quot;button&quot; VALUE=&quot;Go Back&quot; NAME=&quot;back&quot;
   onClick=&quot;window.history.go(-1)&quot;&gt; <br>
   &lt;INPUT TYPE = &quot;button&quot; VALUE = &quot;GO Forward&quot; onClick
   = &quot;window.history.go(1);&quot;&gt; <br>
   &lt;/FORM&gt; <br>
   &lt;/BODY&gt; </font></td>
 </tr>
</table>
<p><font face="Verdana, Arial, Helvetica, sans-serif" size="-1"><br>
 <b>Example 5 : Making the Output of a program (servlet/cgi program) to appear
 in a new frame</b><br>
 This script is used by most many programmers. I haven't found this script to
 be very helpful, since I try my best to avoid using frames on my website. Frames
 are to be avoided whenever, wherever possible. And I always manage without them.
 <br>
 </font></p>
<table width="100%" border="0">
 <tr bgcolor="#F5F5F5">
  <td><font face="Verdana, Arial, Helvetica, sans-serif" size="-1">&lt;HTML&gt;<br>
   &lt;FRAMESET COLS=&quot;20%,*&quot;&gt;<br>
   &lt;FRAME SRC=&quot;leftindex.html&quot; NAME=&quot;Left frame&quot; &gt;<br>
   &lt;FRAME SRC=&quot;rightindex.html&quot; NAME=&quot;Right frame&quot;&gt;<br>
   &lt;/FRAMESET&gt;<br>
   &lt;/HTML&gt; </font></td>
 </tr>
</table>
<p><font face="Verdana, Arial, Helvetica, sans-serif" size="-1">Below is the source
 of leftindex.html</font></p>
<table width="100%" border="0">
 <tr bgcolor="#F5F5F5">
  <td><font face="Verdana, Arial, Helvetica, sans-serif" size="-1">&lt;HTML&gt;<br>
   &lt;BODY&gt;<br>
   &lt;FORM NAME=&quot;Myform&quot; METHOD=GET<br>
   ACTION=&quot;http://www.kiranpai.com/servlet1&quot; onSubmit=&quot;document.myform.target
   = 'Right frame'&gt;<br>
   &lt;INPUT TYPE=SUBMIT VALUE=&quot;Clicking in left frame but Output in Right
   frame&quot;&gt;<br>
   &lt;/FORM&gt;<br>
   &lt;/BODY&gt;<br>
   &lt;/HEAD&gt; </font></td>
 </tr>
</table>
<br>
<br>
<font face="Verdana, Arial, Helvetica, sans-serif" size="-1"><b>Example 6 : Displaying
a Countdown using Javascript</b><br>
You require 5 images named countdown1.jpg, countdown2.jpg ..so on till countdown5.jpg
each with repective digits on them, in the same directory as the script. When
you load this page, after a delay of 2 seconds the images are displayed in the
reverse order (from 5 down to 1) each after a delay of 1 second. This gives it
a kewl effect of a countdown from 5 to 1 and then when it finishes a new blank
window opens. The opening of a blank window was the simplest thing to use here.
You can replace that with any other command. <br>
<br>
I had used a slightly modified version of this countdown script during a press
release of one of the websites I had developed. After the countdown the website
opened in the new window. Ofcourse it was accompanied with claps and wows from
the crowd present there :-) The effects looked wonderful since I had used 5 animated
gifs, with each of them showing a sort of transformation (morphing) from one digit
to another.<br>
<br>
</font>
<table width="100%" border="0" cellpadding="0" cellspacing="0">
 <tr bgcolor="#F5F5F5">
  <td colspan="2"><font face="Verdana, Arial, Helvetica, sans-serif" size="-1">&lt;SCRIPT
   LANGUAGE = &quot;JavaScript&quot;&gt;<br>
   &lt;!--<br>
   <br>
   x=5;<br>
   var pics= new Array();<br>
   <br>
   for(i=1;i&lt;=x;i++){ </font></td>
 </tr>
 <tr bgcolor="#F5F5F5">
  <td width="3%">&nbsp;</td>
  <td width="97%"><font face="Verdana, Arial, Helvetica, sans-serif" size="-1">pics[i]=new
   Image();<br>
   pics[i].src=&quot;countdown&quot;+i+&quot;.jpg&quot;; </font></td>
 </tr>
 <tr bgcolor="#F5F5F5">
  <td colspan="2"><font face="Verdana, Arial, Helvetica, sans-serif" size="-1">}<br>
   <br>
   function img(){</font></td>
 </tr>
 <tr bgcolor="#F5F5F5">
  <td width="3%">&nbsp;</td>
  <td width="97%"><font face="Verdana, Arial, Helvetica, sans-serif" size="-1">document.images[0].src=pics[x].src;<br>
   x--;<br>
   if(x&gt;0) setTimeout('img()',1000);<br>
   if(x==0) setTimeout(&quot;msg=open('','DisplayWindow')&quot;,1000); </font></td>
 </tr>
 <tr bgcolor="#F5F5F5">
  <td colspan="2">
   <p><font face="Verdana, Arial, Helvetica, sans-serif" size="-1">}<br>
    --&gt; <br>
    &lt;/script&gt;<br>
    <br>
    &lt;BODY onLoad=&quot;setTimeout('img()',2000)&quot;&gt;<br>
    &lt;B&gt;The countdown from 5 to 1 will begin in 2 seconds&lt;/B&gt;<br>
    &lt;/BODY&gt;<br>
    </font></p>
  </td>
 </tr>
</table>
<p><font face="Verdana, Arial, Helvetica, sans-serif" size="-1"><br>
 <b>Example 7 : Changing images with MouseOver and MouseOut events</b> <br>
 This is probably the most common use of Javascript. There are countless ways
 to get this working, but I present one that I use frequently. This script like
 many of my other ones rely on numbered image files. Make images with names such
 as org0.jpg, org1.jpg and org2.jpg. These would be initially displayed. Get
 3 more files named new1.jpg, new2.jpg and 3.jpg which would be the files displayed
 when the mouse is over the original images.<br>
 </font></p>
<table width="100%" border="0" cellpadding="0" cellspacing="0">
 <tr bgcolor="#F5F5F5">
  <td colspan="2"><font face="Verdana, Arial, Helvetica, sans-serif" size="-1">
   &lt;SCRIPT LANGUAGE = &quot;JavaScript&quot;&gt;<br>
   &lt;!--<br>
   <br>
   function new_img(no){ </font></td>
 </tr>
 <tr bgcolor="#F5F5F5">
  <td width="5%">&nbsp;</td>
  <td width="95%"><font face="Verdana, Arial, Helvetica, sans-serif" size="-1">document.images[no].src=&quot;new&quot;+no+&quot;.jpg&quot;;
   </font></td>
 </tr>
 <tr bgcolor="#F5F5F5">
  <td colspan="2"><font face="Verdana, Arial, Helvetica, sans-serif" size="-1">}<br>
   <br>
   function org_img(no){ </font></td>
 </tr>
 <tr bgcolor="#F5F5F5">
  <td>&nbsp;</td>
  <td><font face="Verdana, Arial, Helvetica, sans-serif" size="-1">document.images[no].src=&quot;org&quot;+no+&quot;.jpg&quot;;</font></td>
 </tr>
 <tr bgcolor="#F5F5F5">
  <td colspan="2"><font face="Verdana, Arial, Helvetica, sans-serif" size="-1">}<br>
   --&gt;<br>
   &lt;/SCRIPT&gt;<br>
   <br>
   &lt;BODY&gt;<br>
   &lt;IMG SRC=&quot;org0.jpg&quot; onMouseOver=&quot;new_img(0)&quot; onMouseOut=&quot;org_img(0)&quot;&gt;<br>
   &lt;IMG SRC=&quot;org1.jpg&quot; onMouseOver=&quot;new_img(1)&quot; onMouseOut=&quot;org_img(1)&quot;&gt;<br>
   &lt;IMG SRC=&quot;org2.jpg&quot; onMouseOver=&quot;new_img(2)&quot; onMouseOut=&quot;org_img(2)&quot;&gt;<br>
   &lt;/BODY&gt; </font></td>
 </tr>
</table>
<p><font face="Verdana, Arial, Helvetica, sans-serif" size="-1">Alternatively
 in case you want to change an image when clicked on it use the following script</font></p>
<table width="100%" border="0" cellpadding="0" cellspacing="0">
 <tr bgcolor="#F5F5F5">
  <td colspan="2"><font face="Verdana, Arial, Helvetica, sans-serif" size="-1">&lt;SCRIPT
   LANGUAGE = &quot;JavaScript&quot;&gt;<br>
   &lt;!--<br>
   <br>
   function change_img(index){ </font></td>
 </tr>
 <tr bgcolor="#F5F5F5">
  <td width="5%">&nbsp;</td>
  <td width="95%"><font face="Verdana, Arial, Helvetica, sans-serif" size="-1">document.images[index].src
   = &quot;N.jpg&quot;;</font></td>
 </tr>
 <tr bgcolor="#F5F5F5">
  <td colspan="2">
   <p><font face="Verdana, Arial, Helvetica, sans-serif" size="-1">}<br>
    --&gt; <br>
    &lt;/SCRIPT&gt;</font></p>
   <p><font face="Verdana, Arial, Helvetica, sans-serif" size="-1">&lt;BODY&gt;<br>
    &lt;A HREF=&quot;JavaScript: change_img(0)&quot;&gt;&lt;IMG SRC=&quot;I.jpg&quot;&gt;&lt;/A&gt;<br>
    &lt;/BODY&gt; </font></p>
  </td>
 </tr>
</table>
<p><font face="Verdana, Arial, Helvetica, sans-serif" size="-1"><br>
 </font><font size="-1" face="Verdana, Arial, Helvetica, sans-serif"><b>Example
 8 : Checking the form contents before submitting the form</b><br>
 This is once again an extremely important use of Javascript (this was one of
 the primary uses of Javascript). It reduces the time and resources on the server
 side for checking of online forms. Once again I have found many implementations
 of this script. This is one I find easy to understand.<br>
 </font></p>
<table width="100%" border="0" cellpadding="0" cellspacing="0">
 <tr bgcolor="#F5F5F5">
  <td colspan="3"><font size="-1" face="Verdana, Arial, Helvetica, sans-serif"><br>
   &lt;SCRIPT LANGUAGE = &quot;JavaScript&quot;&gt;<br>
   &lt;!--<br>
   function isReady(recv_form) { </font></td>
 </tr>
 <tr bgcolor="#F5F5F5">
  <td width="4%">&nbsp;</td>
  <td colspan="2"><font size="-1" face="Verdana, Arial, Helvetica, sans-serif">if
   (recv_form.feedback.value != &quot;&quot;)</font></td>
 </tr>
 <tr bgcolor="#F5F5F5">
  <td width="4%">&nbsp;</td>
  <td>&nbsp;</td>
  <td><font size="-1" face="Verdana, Arial, Helvetica, sans-serif"> return true;
   </font></td>
 </tr>
 <tr bgcolor="#F5F5F5">
  <td width="4%">&nbsp;</td>
  <td colspan="2"><font size="-1" face="Verdana, Arial, Helvetica, sans-serif">else
   {</font></td>
 </tr>
 <tr bgcolor="#F5F5F5">
  <td rowspan="2" width="4%">&nbsp;</td>
  <td width="3%">&nbsp;</td>
  <td width="93%"><font size="-1" face="Verdana, Arial, Helvetica, sans-serif">alert(&quot;Please
   include a feedback message.&quot;);<br>
   recv_form.feedback.focus();<br>
   return false; </font></td>
 </tr>
 <tr>
  <td colspan="2" bgcolor="#F5F5F5"><font size="-1" face="Verdana, Arial, Helvetica, sans-serif">}</font></td>
 </tr>
 <tr bgcolor="#F5F5F5">
  <td colspan="3"><font size="-1" face="Verdana, Arial, Helvetica, sans-serif">}<br>
   //--&gt;<br>
   &lt;/SCRIPT&gt;<br>
   <br>
   &lt;BODY&gt;<br>
   &lt;FORM NAME = &quot;myform&quot; onSubmit = &quot;return isReady(this)&quot;
   METHOD=POST ACTION = &quot;http://www.kiranpai.com/servlet1&quot;&gt;<br>
   &lt;TEXTAREA NAME = &quot;feedback&quot;&gt;&lt;/TEXTAREA&gt;&lt;br&gt;<br>
   &lt;INPUT TYPE=&quot;submit&quot; VALUE=&quot;Submit&quot;&gt;<br>
   &lt;/FORM&gt;<br>
   &lt;/BODY&gt;<br>
   </font></td>
 </tr>
</table>
<p><font size="-1" face="Verdana, Arial, Helvetica, sans-serif"><br>
 <b>Example 9 : Filling the values of a dropdown SelectMenu depending on the
 selection in another Menu </b><br>
 If you are developing a professional site for a company you would invariably
 come across a situation where you are expected to do the above. Remember that
 the power of this script becomes evident when you use Javascript along with
 some other dynamic language such as JSP or ASP. You could probably fill the
 arrays used in this script with some data fetched from a database relating to
 the particular user. When he selects an entry in the first dropdown menu, he
 is immediately presented with <i>his relevant data</i> in the second menu, instead
 of making another request to the server to fetch more data. These types of scripts
 are very useful when you have to allow a user select some thing from a general
 level to a more specific level. I mean each successive dropdown menu would be
 more and more specific choice. Read on to understand the entire thing.<br>
 </font></p>
<table width="100%" border="0" cellpadding="0" cellspacing="0">
 <tr bgcolor="#F5F5F5">
  <td colspan="4">
   <p><font face="Verdana, Arial, Helvetica, sans-serif" size="-1"><br>
    &lt;SCRIPT LANGUAGE = &quot;JavaScript&quot;&gt;<br>
    &lt;!--<br>
    <br>
    var tennisplayers= new Array(&quot;Safin&quot;, &quot;Andre Agassi&quot;,
    &quot;Pete Sampras&quot;, &quot;Anna Kournikova&quot;, &quot;Martina Hingis&quot;);<br>
    var cricketplayers = new Array(&quot;Sachin Tendulkar&quot;, &quot;Steve
    Waugh&quot;, &quot;Brian Lara&quot;, &quot;Sir Don Bradman&quot;);</font><br>
    <br>
    <font face="Verdana, Arial, Helvetica, sans-serif" size="-1">function
    set_player() { </font></p>
  </td>
 </tr>
 <tr bgcolor="#F5F5F5">
  <td width="3%">&nbsp;</td>
  <td colspan="3">
   <p><font face="Verdana, Arial, Helvetica, sans-serif" size="-1">var select_sport
    = document.myform.sport;<br>
    var select_player = document.myform.player;<br>
    var selected_sport = select_sport.options[select_sport.selectedIndex].value;</font></p>
   <p><font face="Verdana, Arial, Helvetica, sans-serif" size="-1"> select_player.options.length=0;<br>
    if (selected_sport == &quot;tennis&quot;){ </font></p>
  </td>
 </tr>
 <tr bgcolor="#F5F5F5">
  <td rowspan="2" width="3%">&nbsp;</td>
  <td width="3%">&nbsp;</td>
  <td colspan="2"><font face="Verdana, Arial, Helvetica, sans-serif" size="-1">for(var
   i=0; i&lt;tennisplayers.length; i++) </font></td>
 </tr>
 <tr>
  <td width="3%" bgcolor="#F5F5F5">&nbsp;</td>
  <td width="3%" bgcolor="#F5F5F5">&nbsp;</td>
  <td width="91%" bgcolor="#F5F5F5"><font face="Verdana, Arial, Helvetica, sans-serif" size="-1">select_player.options[select_player.options.length]
   = new Option(tennisplayers[i]);</font></td>
 </tr>
 <tr bgcolor="#F5F5F5">
  <td>&nbsp;</td>
  <td colspan="3"><font face="Verdana, Arial, Helvetica, sans-serif" size="-1">}<br>
   if (selected_sport == &quot;cricket&quot;){<br>
   </font></td>
 </tr>
 <tr bgcolor="#F5F5F5">
  <td>&nbsp;</td>
  <td>&nbsp;</td>
  <td colspan="2"><font face="Verdana, Arial, Helvetica, sans-serif" size="-1">for(var
   i=0; i&lt;cricketplayers.length; i++)</font></td>
 </tr>
 <tr bgcolor="#F5F5F5">
  <td>&nbsp;</td>
  <td>&nbsp;</td>
  <td>&nbsp;</td>
  <td><font face="Verdana, Arial, Helvetica, sans-serif" size="-1">select_player.options[select_player.options.length]
   = new Option(cricketplayers[i]);</font></td>
 </tr>
 <tr bgcolor="#F5F5F5">
  <td>&nbsp;</td>
  <td colspan="3"><font face="Verdana, Arial, Helvetica, sans-serif" size="-1">}</font></td>
 </tr>
 <tr bgcolor="#F5F5F5">
  <td colspan="4">
   <p><font face="Verdana, Arial, Helvetica, sans-serif" size="-1">}<br>
    --&gt; <br>
    &lt;/SCRIPT&gt;<br>
    </font><font face="Verdana, Arial, Helvetica, sans-serif" size="-1"><br>
    &lt;BODY&gt;<br>
    &lt;FORM NAME=&quot;myform&quot; METHOD=&quot;POST&quot;&gt;<br>
    <br>
    Sport<br>
    &lt;SELECT NAME=&quot;sport&quot; onChange=&quot;set_player()&quot;&gt;<br>
    &lt;OPTION VALUE=&quot;tennis&quot;&gt;-------<br>
    &lt;OPTION VALUE=&quot;tennis&quot;&gt;Tennis<br>
    &lt;OPTION VALUE=&quot;cricket&quot;&gt;Cricket<br>
    &lt;/SELECT&gt;<br>
    <br>
    Player<br>
    &lt;SELECT NAME=&quot;player&quot;&gt;<br>
    &lt;OPTION&gt;------<br>
    &lt;/SELECT&gt;<br>
    <br>
    &lt;/FORM&gt;<br>
    &lt;/BODY&gt;<br>
    </font></p>
   </td>
 </tr>
</table>
<p><font face="Verdana, Arial, Helvetica, sans-serif" size="-1">In the above script
 when the user selects either Cricket or Tennis in the first Select Menu, the
 choices in the second Select Menu automatically changes accordingly.<br>
 <br>
 </font><font face="Verdana, Arial, Helvetica, sans-serif" size="-1">Try to understand
 the working of all these scripts properly rather than cut-pasting them. A reference
 book on Javascript is extremely useful since there are many small details that
 you got to take note of while scripting else your scripts won't run. Programming
 in Javascript in conjunction with any other language such as ASP or JSP makes
 it more tough and you have to take great care about the syntax else you end
 up in a mess. Thats all..<br>
 <br>
 Hope you enjoyed these 9 examples. <br>
 <br>
 <br>
 </font></p>
<table width="98%" border="0" bgcolor="#AFAFAF" cellpadding="0" cellspacing="1" name="outside" align="center">
 <tr bgcolor="#FFFFFF">
  <td>
   <table width="100%" border="0" name="inside" cellpadding="3" cellspacing="0" bgcolor="#FFFFFF">
    <tr>
     <td>
      <div align="center"><font face="Verdana, Arial, Helvetica, sans-serif" size="-2">This
       article has been written by Kiran Pai. All comments and feedback
       may be sent to <b>paikiran@yahoo.com</b></font> <font face="Verdana, Arial, Helvetica, sans-serif" size="-2"><br>
       <b><font color="#000000">This article should not be modified in
       any form. In case you want to host a copy of this article on your
       site please request for authors permission before doing so</font></b>
       </font></div>
     </td>
    </tr>
   </table>
  </td>
 </tr>
</table>
<font face="Verdana, Arial, Helvetica, sans-serif" size="-1"> </font>

