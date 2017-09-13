# SlideFrom by lepola
Easy slide library for javascript.

Slide / fade element when it's scrolled into view.

# Require
JQuery and JQuery UI

&#60;script src="//code.jquery.com/jquery-1.12.4.js"&#62;&#60;/script&#62;

&#60;script src="//ajax.googleapis.com/ajax/libs/jqueryui/1.11.3/jquery-ui.min.js"&#62;&#60;/script&#62;

# Usage

Enable in javascript with:

<code>slideFrom.enable = 1</code>

Set attribute *'slidefrom'* to element, and give parameters;

<b>*slidefrom="slide, FROM, DURATION"*</b> 

or 

<b>*slidefrom="fade, DURATION"*</b>

<b>Example:</b>
  
<code>
  
&#60;article slidefrom="slide,left,800"&#62;
  
  &#60;p&#62; Hello my friend! &#60;/p&#62;
  
&#60;/article&#62;

</code>

<b>Example2:</b>
  
<code>
  
&#60;article slidefrom="fade,800"&#62;
  
  &#60;p&#62; Hello my friend! &#60;/p&#62;
  
&#60;/article&#62;

</code>
