<div class="mui-col-md-6 tutorial-content">
<h1>HTML - Basic Tags</h1>
<hr>
<div class="mui-container-fluid button-borders">
<div class="pre-btn">
<a href="/html/html_overview.htm"><i class="fal fa-chevron-circle-left"></i> Previous Page</a>
</div>
<div class="nxt-btn">
<a href="/html/html_elements.htm">Next Page <i class="fal fa-chevron-circle-right"></i>&nbsp;</a>
</div>
</div>
<div class="clearer"></div>
<h2>Heading Tags</h2>
<p>Any document starts with a heading. You can use different sizes for your headings. HTML also has six levels of headings, which use the elements <b>&lt;h1&gt;, &lt;h2&gt;, &lt;h3&gt;, &lt;h4&gt;, &lt;h5&gt;,</b> and <b>&lt;h6&gt;</b>. While displaying any heading, browser adds one line before and one line after that heading.</p>
<h3>Example</h3>
<div class="demo-view">
<a href="http://tpcg.io/Oevfe8" target="_blank" rel="nofollow" class="demo"><i class="fa-external-link"></i> Live Demo</a>
</div>
<pre class="prettyprint notranslate prettyprinted" style=""><span class="dec">&lt;!DOCTYPE html&gt;</span><span class="pln">
</span><span class="tag">&lt;html&gt;</span><span class="pln">

   </span><span class="tag">&lt;head&gt;</span><span class="pln">
      </span><span class="tag">&lt;title&gt;</span><span class="pln">Heading Example</span><span class="tag">&lt;/title&gt;</span><span class="pln">
   </span><span class="tag">&lt;/head&gt;</span><span class="pln">
	
   </span><span class="tag">&lt;body&gt;</span><span class="pln">
      </span><span class="tag">&lt;h1&gt;</span><span class="pln">This is heading 1</span><span class="tag">&lt;/h1&gt;</span><span class="pln">
      </span><span class="tag">&lt;h2&gt;</span><span class="pln">This is heading 2</span><span class="tag">&lt;/h2&gt;</span><span class="pln">
      </span><span class="tag">&lt;h3&gt;</span><span class="pln">This is heading 3</span><span class="tag">&lt;/h3&gt;</span><span class="pln">
      </span><span class="tag">&lt;h4&gt;</span><span class="pln">This is heading 4</span><span class="tag">&lt;/h4&gt;</span><span class="pln">
      </span><span class="tag">&lt;h5&gt;</span><span class="pln">This is heading 5</span><span class="tag">&lt;/h5&gt;</span><span class="pln">
      </span><span class="tag">&lt;h6&gt;</span><span class="pln">This is heading 6</span><span class="tag">&lt;/h6&gt;</span><span class="pln">
   </span><span class="tag">&lt;/body&gt;</span><span class="pln">
	
</span><span class="tag">&lt;/html&gt;</span></pre>
<p>This will produce the following result −</p>
<iframe onload="resizeFrame(this)" class="result" src="/html/src/heading_tag.htm" height="300px" width="660px"></iframe>
<h2>Paragraph Tag</h2>
<p>The <b>&lt;p&gt;</b> tag offers a way to structure your text into different paragraphs. Each paragraph of text should go in between an opening &lt;p&gt; and a closing &lt;/p&gt; tag as shown below in the example −</p>
<h3>Example</h3>
<div class="demo-view">
<a href="http://tpcg.io/Uo5jZe" target="_blank" rel="nofollow" class="demo"><i class="fa-external-link"></i> Live Demo</a>
</div>
<pre class="prettyprint notranslate prettyprinted" style=""><span class="dec">&lt;!DOCTYPE html&gt;</span><span class="pln">
</span><span class="tag">&lt;html&gt;</span><span class="pln">

   </span><span class="tag">&lt;head&gt;</span><span class="pln">
      </span><span class="tag">&lt;title&gt;</span><span class="pln">Paragraph Example</span><span class="tag">&lt;/title&gt;</span><span class="pln">
   </span><span class="tag">&lt;/head&gt;</span><span class="pln">
	
   </span><span class="tag">&lt;body&gt;</span><span class="pln">
      </span><span class="tag">&lt;p&gt;</span><span class="pln">Here is a first paragraph of text.</span><span class="tag">&lt;/p&gt;</span><span class="pln">
      </span><span class="tag">&lt;p&gt;</span><span class="pln">Here is a second paragraph of text.</span><span class="tag">&lt;/p&gt;</span><span class="pln">
      </span><span class="tag">&lt;p&gt;</span><span class="pln">Here is a third paragraph of text.</span><span class="tag">&lt;/p&gt;</span><span class="pln">
   </span><span class="tag">&lt;/body&gt;</span><span class="pln">
	
</span><span class="tag">&lt;/html&gt;</span></pre>
<p>This will produce the following result −</p>
<iframe onload="resizeFrame(this)" class="result" src="/html/src/paragraph_tag.htm" height="150px" width="660px"></iframe>
<h2>Line Break Tag</h2>
<p>Whenever you use the <b>&lt;br /&gt;</b> element, anything following it starts from the next line. This tag is an example of an <b>empty</b> element, where you do not need opening and closing tags, as there is nothing to go in between them.</p>
<p>The &lt;br /&gt; tag has a space between the characters <b>br</b> and the forward slash. If you omit this space, older browsers will have trouble rendering the line break, while if you miss the forward slash character and just use &lt;br&gt; it is not valid in XHTML.</p>
<h3>Example</h3>
<div class="demo-view">
<a href="http://tpcg.io/aWg5PG" target="_blank" rel="nofollow" class="demo"><i class="fa-external-link"></i> Live Demo</a>
</div>
<pre class="prettyprint notranslate prettyprinted" style=""><span class="dec">&lt;!DOCTYPE html&gt;</span><span class="pln">
</span><span class="tag">&lt;html&gt;</span><span class="pln">

   </span><span class="tag">&lt;head&gt;</span><span class="pln">
      </span><span class="tag">&lt;title&gt;</span><span class="pln">Line Break  Example</span><span class="tag">&lt;/title&gt;</span><span class="pln">
   </span><span class="tag">&lt;/head&gt;</span><span class="pln">
	
   </span><span class="tag">&lt;body&gt;</span><span class="pln">
      </span><span class="tag">&lt;p&gt;</span><span class="pln">Hello</span><span class="tag">&lt;br</span><span class="pln"> </span><span class="tag">/&gt;</span><span class="pln">
         You delivered your assignment ontime.</span><span class="tag">&lt;br</span><span class="pln"> </span><span class="tag">/&gt;</span><span class="pln">
         Thanks</span><span class="tag">&lt;br</span><span class="pln"> </span><span class="tag">/&gt;</span><span class="pln">
         Mahnaz</span><span class="tag">&lt;/p&gt;</span><span class="pln">
   </span><span class="tag">&lt;/body&gt;</span><span class="pln">
	
</span><span class="tag">&lt;/html&gt;</span></pre>
<p>This will produce the following result −</p>
<iframe onload="resizeFrame(this)" class="result" src="/html/src/line_break_tag.htm" height="150px" width="660px"></iframe>
<h2>Centering Content</h2>
<p>You can use <b>&lt;center&gt;</b> tag to put any content in the center of the page or any table cell.</p>
<h3>Example</h3>
<div class="demo-view">
<a href="http://tpcg.io/mVrRPS" target="_blank" rel="nofollow" class="demo"><i class="fa-external-link"></i> Live Demo</a>
</div>
<pre class="prettyprint notranslate prettyprinted" style=""><span class="dec">&lt;!DOCTYPE html&gt;</span><span class="pln">
</span><span class="tag">&lt;html&gt;</span><span class="pln">

   </span><span class="tag">&lt;head&gt;</span><span class="pln">
      </span><span class="tag">&lt;title&gt;</span><span class="pln">Centring Content Example</span><span class="tag">&lt;/title&gt;</span><span class="pln">
   </span><span class="tag">&lt;/head&gt;</span><span class="pln">
	
   </span><span class="tag">&lt;body&gt;</span><span class="pln">
      </span><span class="tag">&lt;p&gt;</span><span class="pln">This text is not in the center.</span><span class="tag">&lt;/p&gt;</span><span class="pln">
      
      </span><span class="tag">&lt;center&gt;</span><span class="pln">
         </span><span class="tag">&lt;p&gt;</span><span class="pln">This text is in the center.</span><span class="tag">&lt;/p&gt;</span><span class="pln">
      </span><span class="tag">&lt;/center&gt;</span><span class="pln">
   </span><span class="tag">&lt;/body&gt;</span><span class="pln">
	
</span><span class="tag">&lt;/html&gt;</span></pre>
<p>This will produce following result −</p>
<iframe onload="resizeFrame(this)" class="result" src="/html/src/centering_content.htm" height="100px" width="660px"></iframe>
<h2>Horizontal Lines</h2>
<p>Horizontal lines are used to visually break-up sections of a document. The <b>&lt;hr&gt;</b> tag creates a line from the current position in the document to the right margin and breaks the line accordingly.</p>
<p>For example, you may want to give a line between two paragraphs as in the given example below −</p>
<h3>Example</h3>
<div class="demo-view">
<a href="http://tpcg.io/4iAnXc" target="_blank" rel="nofollow" class="demo"><i class="fa-external-link"></i> Live Demo</a>
</div>
<pre class="prettyprint notranslate prettyprinted" style=""><span class="dec">&lt;!DOCTYPE html&gt;</span><span class="pln">
</span><span class="tag">&lt;html&gt;</span><span class="pln">

   </span><span class="tag">&lt;head&gt;</span><span class="pln">
      </span><span class="tag">&lt;title&gt;</span><span class="pln">Horizontal Line Example</span><span class="tag">&lt;/title&gt;</span><span class="pln">
   </span><span class="tag">&lt;/head&gt;</span><span class="pln">
	
   </span><span class="tag">&lt;body&gt;</span><span class="pln">
      </span><span class="tag">&lt;p&gt;</span><span class="pln">This is paragraph one and should be on top</span><span class="tag">&lt;/p&gt;</span><span class="pln">
      </span><span class="tag">&lt;hr</span><span class="pln"> </span><span class="tag">/&gt;</span><span class="pln">
      </span><span class="tag">&lt;p&gt;</span><span class="pln">This is paragraph two and should be at bottom</span><span class="tag">&lt;/p&gt;</span><span class="pln">
   </span><span class="tag">&lt;/body&gt;</span><span class="pln">
	
</span><span class="tag">&lt;/html&gt;</span></pre>
<p>This will produce the following result −</p>
<iframe onload="resizeFrame(this)" class="result" src="/html/src/horizontal_lines.htm" height="150px" width="660px"></iframe>
<p>Again <b>&lt;hr /&gt;</b> tag is an example of the <b>empty</b> element, where you do not need opening and closing tags, as there is nothing to go in between them.</p>
<p>The <b>&lt;hr /&gt;</b> element has a space between the characters <b>hr</b> and the forward slash. If you omit this space, older browsers will have trouble rendering the horizontal line, while if you miss the forward slash character and just use <b>&lt;hr&gt;</b> it is not valid in XHTML</p>
<h2>Preserve Formatting</h2>
<p>Sometimes, you want your text to follow the exact format of how it is written in the HTML document. In these cases, you can use the preformatted tag <b>&lt;pre&gt;</b>.</p>
<p>Any text between the opening <b>&lt;pre&gt;</b> tag and the closing <b>&lt;/pre&gt;</b> tag will preserve the formatting of the source document.</p>
<h3>Example</h3>
<div class="demo-view">
<a href="http://tpcg.io/e3k3sG" target="_blank" rel="nofollow" class="demo"><i class="fa-external-link"></i> Live Demo</a>
</div>
<pre class="prettyprint notranslate prettyprinted" style=""><span class="dec">&lt;!DOCTYPE html&gt;</span><span class="pln">
</span><span class="tag">&lt;html&gt;</span><span class="pln">

   </span><span class="tag">&lt;head&gt;</span><span class="pln">
      </span><span class="tag">&lt;title&gt;</span><span class="pln">Preserve Formatting Example</span><span class="tag">&lt;/title&gt;</span><span class="pln">
   </span><span class="tag">&lt;/head&gt;</span><span class="pln">
	
   </span><span class="tag">&lt;body&gt;</span><span class="pln">
      </span><span class="tag">&lt;pre&gt;</span><span class="pln">
         function testFunction( strText ){
            alert (strText)
         }
      </span><span class="tag">&lt;/pre&gt;</span><span class="pln">
   </span><span class="tag">&lt;/body&gt;</span><span class="pln">
	
</span><span class="tag">&lt;/html&gt;</span></pre>
<p>This will produce the following result −</p>
<iframe onload="resizeFrame(this)" class="result" src="/html/src/preserve_formatting.htm" height="100px" width="660px"></iframe>
<p>Try using the same code without keeping it inside <b>&lt;pre&gt;...&lt;/pre&gt;</b> tags</p>
<h2>Nonbreaking Spaces</h2>
<p>Suppose you want to use the phrase "12 Angry Men." Here, you would not want a browser to split the "12, Angry" and "Men" across two lines −</p>
<pre class="result notranslate">An example of this technique appears in the movie "12 Angry Men."
</pre>
<p>In cases, where you do not want the client browser to break text, you should use a nonbreaking space entity <b>&amp;nbsp;</b> instead of a normal space. For example, when coding the "12 Angry Men" in a paragraph, you should use something similar to the following code −</p>
<h3>Example</h3>
<div class="demo-view">
<a href="http://tpcg.io/OhhfWR" target="_blank" rel="nofollow" class="demo"><i class="fa-external-link"></i> Live Demo</a>
</div>
<pre class="prettyprint notranslate prettyprinted" style=""><span class="dec">&lt;!DOCTYPE html&gt;</span><span class="pln">
</span><span class="tag">&lt;html&gt;</span><span class="pln">

   </span><span class="tag">&lt;head&gt;</span><span class="pln">
      </span><span class="tag">&lt;title&gt;</span><span class="pln">Nonbreaking Spaces Example</span><span class="tag">&lt;/title&gt;</span><span class="pln">
   </span><span class="tag">&lt;/head&gt;</span><span class="pln">
	
   </span><span class="tag">&lt;body&gt;</span><span class="pln">
      </span><span class="tag">&lt;p&gt;</span><span class="pln">An example of this technique appears in the movie "12&amp;nbsp;Angry&amp;nbsp;Men."</span><span class="tag">&lt;/p&gt;</span><span class="pln">
   </span><span class="tag">&lt;/body&gt;</span><span class="pln">
	
</span><span class="tag">&lt;/html&gt;</span></pre>

<div class="mui-container-fluid button-borders show">
<div class="pre-btn">
<a href="/html/html_overview.htm"><i class="fal fa-chevron-circle-left"></i> Previous Page</a>
<a class="hide-on-mobile" href="javascript:printPage();"><i class="fa fa-print"></i> Print Page</a>
</div>
<div class="nxt-btn">
<a href="/html/html_elements.htm">Next Page <i class="fal fa-chevron-circle-right"></i>&nbsp;</a>
</div>
</div>
<div class="google-bottom-ads">
<div class="space-bottom"></div>
</div>
</div>
