<ol dir="auto">
<li> First of all, you need to buy the theme from <a href="https://www.buymeacoffee.com/itztxs/e/133988?from_page=home" rel="nofollow">purchase page</a>
</li><li> Then first restore the <strong>blank.xml</strong>. <br>
A sample blank.xml is provided here.
<div class="snippet-clipboard-content notranslate position-relative overflow-auto"><pre class="notranslate"><code>
&lt;?xml version="1.0" encoding="UTF-8" ?&gt;
&lt;!DOCTYPE html&gt;
&lt;html b:css='false' b:js='false' b:defaultwidgetversion='2' b:layoutsVersion='3'&gt;
&lt;b:attr name='xmlns' value=''/&gt;
&lt;b:attr name='xmlns:b' value=''/&gt;
&lt;b:attr name='xmlns:expr' value=''/&gt;
&lt;b:attr name='xmlns:data' value=''/&gt;
&lt;head&gt;
&lt;title&gt;&lt;data:blog.pageTitle/&gt;&lt;/title&gt;
&lt;b:skin/&gt;
&lt;/head&gt;
&lt;body&gt;
&lt;b:section id='1'/&gt;
&lt;/body&gt;
&lt;/html&gt;
</code></pre><div class="zeroclipboard-container position-absolute right-0 top-0">
    <clipboard-copy aria-label="Copy" class="ClipboardButton btn js-clipboard-copy m-2 p-0 tooltipped-no-delay" data-copy-feedback="Copied!" data-tooltip-direction="w" value="
<?xml version=&quot;1.0&quot; encoding=&quot;UTF-8&quot; ?>
<!DOCTYPE html>
<html b:css='false' b:js='false' b:defaultwidgetversion='2' b:layoutsVersion='3'>
<b:attr name='xmlns' value=''/>
<b:attr name='xmlns:b' value=''/>
<b:attr name='xmlns:expr' value=''/>
<b:attr name='xmlns:data' value=''/>
<head>
<title><data:blog.pageTitle/></title>
<b:skin/>
</head>
<body>
<b:section id='1'/>
</body>
</html>" tabindex="0" role="button">
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-copy js-clipboard-copy-icon m-2">
    <path d="M0 6.75C0 5.784.784 5 1.75 5h1.5a.75.75 0 0 1 0 1.5h-1.5a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-1.5a.75.75 0 0 1 1.5 0v1.5A1.75 1.75 0 0 1 9.25 16h-7.5A1.75 1.75 0 0 1 0 14.25Z"></path><path d="M5 1.75C5 .784 5.784 0 6.75 0h7.5C15.216 0 16 .784 16 1.75v7.5A1.75 1.75 0 0 1 14.25 11h-7.5A1.75 1.75 0 0 1 5 9.25Zm1.75-.25a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-7.5a.25.25 0 0 0-.25-.25Z"></path>
</svg>
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-check js-clipboard-check-icon color-fg-success d-none m-2">
    <path d="M13.78 4.22a.75.75 0 0 1 0 1.06l-7.25 7.25a.75.75 0 0 1-1.06 0L2.22 9.28a.751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018L6 10.94l6.72-6.72a.75.75 0 0 1 1.06 0Z"></path>
</svg>
    </clipboard-copy>
  </div></div>
</li><li> Then apply the base theme. <br>
  A sample of the stats is given below of (Royal ui 3.7) <br> <br>
  <a target="_blank" rel="noopener noreferrer nofollow" href="https://camo.githubusercontent.com/2009fa8c765ca09bdd92cb2d01978ba8e4ba911ad85added6fcf8f26a142d02b/68747470733a2f2f67726170682e6f72672f66696c652f3066643233373138303863653137643535313035612e6a7067"><img src="https://camo.githubusercontent.com/2009fa8c765ca09bdd92cb2d01978ba8e4ba911ad85added6fcf8f26a142d02b/68747470733a2f2f67726170682e6f72672f66696c652f3066643233373138303863653137643535313035612e6a7067" alt="lantro_ui" data-canonical-src="https://graph.org/file/0fd2371808ce17d55105a.jpg" style="max-width: 100%;"></a>
<h3 tabindex="-1" dir="auto"><a id="user-content-documentations" class="anchor" aria-hidden="true" href="#documentations"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a>Documentations</h3>
<p dir="auto">According to DMCA guidelines, Royal ui strictly uses its own code and encrypts them as per the rules. <br>
The FAQs regarding the theme are listed well at <a href="https://www.buymeacoffee.com/itztxs/e/133988?from_page=home" rel="nofollow">FAQ SECTION</a> <br></p>
<h3 tabindex="-1" dir="auto"><a id="user-content-changelogs" class="anchor" aria-hidden="true" href="#changelogs"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a>Changelogs</h3>
<p dir="auto">A view on changelogs has been updated <a href="docs.royal-ui.xyz" rel="nofollow">here</a></p>
<h3 tabindex="-1" dir="auto"><a id="user-content-purchase" class="anchor" aria-hidden="true" href="#purchase"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a>Purchase</h3>
<p dir="auto"><a href="https://www.buymeacoffee.com/itztxs/e/133988?from_page=home" rel="nofollow">Purchase Page</a></p>
<div align="right" dir="auto">
<table><tbody><tr><td>
<a href="#start-of-content">↥ Scroll To Top</a>
</td></tr></tbody></table>
</div>
</li></ol>
