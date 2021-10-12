---
title: Typography
---

<h2 class="features-title"><a href="#">Typography</a></h2>

<!-- Typography
================================================== -->
<section id="typography">

<div class="gantry-width-container">
<div class="gantry-width-block gantry-width-50">
<div class="gantry-left">
  <h2 id="headings">Headings</h2>
  <p>All HTML headings, <code>&lt;h1&gt;</code> through <code>&lt;h6&gt;</code> are available.</p>
  <div class="gantry-example">
    <h1>h1. Heading 1</h1>
    <h2>h2. Heading 2</h2>
    <h3>h3. Heading 3</h3>
    <h4>h4. Heading 4</h4>
    <h5>h5. Heading 5</h5>
    <h6>h6. Heading 6</h6>
  </div>

  <h3>Built with SCSS</h3>
  <p>The typographic scale is based on two SCSS variables in <strong>variables.less</strong>: <code>$base-font-size</code> and <code>$base-line-height</code>. The first is the base font-size used throughout and the second is the base line-height. We use those variables and some simple math to create the margins, paddings, and line-heights of all our type and more.</p>
</div></div>

<div class="gantry-width-block gantry-width-50">
<div class="gantry-right">
  <h2 id="body-copy">Body copy</h2>
  <p>Bootstrap's global default <code>font-size</code> is <strong>14px</strong>, with a <code>line-height</code> of <strong>24px</strong>. This is applied to the <code>&lt;body&gt;</code> and all paragraphs. In addition, <code>&lt;p&gt;</code> (paragraphs) receive a bottom margin of half their line-height (9px by default).</p>
  <div class="gantry-example">
    <p>Nullam quis risus eget urna mollis ornare vel eu leo. Cum sociis natoque penatibus et magnis dis parturient montes, nascetur ridiculus mus. Nullam id dolor id nibh ultricies vehicula.</p>
  </div>
  <pre class="prettyprint">&lt;p&gt;...&lt;/p&gt;</pre>

  <h3>Lead body copy</h3>
  <p>Make a paragraph stand out by adding <code>.lead</code>.</p>
  <div class="gantry-example">
    <p class="lead">Vivamus sagittis lacus vel augue laoreet rutrum faucibus dolor auctor. Duis mollis, est non commodo luctus.</p>
  </div>
  <pre class="prettyprint">&lt;p class=&quot;lead&quot;&gt;...&lt;/p&gt;</pre>


</div></div></div>
<div class="clear"></div>

<br /><!-- SEPARATOR -->


  <h2 id="emphasis">Emphasis</h2>
  <p>Make use of HTML's default emphasis tags with lightweight styles.</p>

<div class="gantry-width-container">
<div class="gantry-width-block gantry-width-50">
<div class="gantry-left">
  <h4><code>&lt;em&gt;</code></h4>
  <p>For emphasizing a snippet of text with <em>stress</em></p>
  <div class="gantry-example">
    <p>The following snippet of text is <em>rendered as italicized text</em>.</p>
  </div>
  <pre class="prettyprint">&lt;em&gt;rendered as italicized text&lt;/em&gt;</pre>

  <h4><code>&lt;strong&gt;</code></h4>
  <p>For emphasizing a snippet of text with <strong>important</strong></p>
  <div class="gantry-example">
    <p>The following snippet of text is <strong>rendered as bold text</strong>.</p>
  </div>
  <pre class="prettyprint">&lt;strong&gt;rendered as bold text&lt;/strong&gt;</pre>
</div></div>

<div class="gantry-width-block gantry-width-50">
<div class="gantry-right">
  <h4><code>&lt;small&gt;</code></h4>
  <p>For de-emphasizing inline or blocks of text, <small>use the small tag.</small></p>
  <div class="gantry-example">
    <p><small>This line of text is meant to be treated as fine print.</small></p>
  </div>
<pre class="prettyprint">&lt;p&gt;
  &lt;small&gt;This line of text is meant to be treated as fine print.&lt;/small&gt;
&lt;/p&gt;</pre><br />

  <p><strong>Note:</strong> Feel free to use <code>&lt;b&gt;</code> and <code>&lt;i&gt;</code> in HTML5. <code>&lt;b&gt;</code> is meant to highlight words or phrases without conveying additional importance while <code>&lt;i&gt;</code> is mostly for voice, technical terms, etc.</p>
</div></div></div>
<div class="clear"></div>

<h3>Notice Styles</h3>

<p>Use the <code>&lt;p&gt;</code> tag with <code>.success</code>, <code>.warning</code>, <code>.info</code> or <code>.error</code> classes.</p>

<div class="gantry-width-container">
<div class="gantry-width-block gantry-width-50">
<div class="gantry-left">
<div class="gantry-example"><p class="success">Nullam quis risus eget urna mollis ornare vel eu leo. Cum sociis natoque penatibus et magnis dis parturient montes, nascetur ridiculus mus.</p></div>
<pre class="prettyprint">&lt;p class=&quot;success&quot;&gt;...&lt;/p&gt;</pre>

<div class="gantry-example"><p class="info">Nullam quis risus eget urna mollis ornare vel eu leo. Cum sociis natoque penatibus et magnis dis parturient montes, nascetur ridiculus mus.</p></div>
<pre class="prettyprint">&lt;p class=&quot;info&quot;&gt;...&lt;/p&gt;</pre>
</div></div>    

<div class="gantry-width-block gantry-width-50">
<div class="gantry-right">
<div class="gantry-example"><p class="warning">Nullam quis risus eget urna mollis ornare vel eu leo. Cum sociis natoque penatibus et magnis dis parturient montes, nascetur ridiculus mus.</p></div>
<pre class="prettyprint">&lt;p class=&quot;warning&quot;&gt;...&lt;/p&gt;</pre>

<div class="gantry-example"><p class="error">Nullam quis risus eget urna mollis ornare vel eu leo. Cum sociis natoque penatibus et magnis dis parturient montes, nascetur ridiculus mus.</p></div>
<pre class="prettyprint">&lt;p class=&quot;error&quot;&gt;...&lt;/p&gt;</pre>
</div></div></div>

<div class="clear"></div>


<br /><!-- SEPARATOR -->

<div class="gantry-width-container">
<div class="gantry-width-block gantry-width-50">
<div class="gantry-left" style="float: none;">
  <h2 id="abbreviations">Abbreviations</h2>
  <p>Stylized implementation of HTML's <code>&lt;abbr&gt;</code> element for abbreviations and acronyms to show the expanded version on hover. Abbreviations with a <code>title</code> attribute have a light dotted bottom border and a help cursor on hover, providing additional context on hover.</p>

  <h4><code>&lt;abbr&gt;</code></h4>
  <p>For expanded text on long hover of an abbreviation, include the <code>title</code> attribute.</p>
  <div class="gantry-example">
    <p>An abbreviation of the word attribute is <abbr title="attribute">attr</abbr>.</p>
  </div>
  <pre class="prettyprint">&lt;abbr title=&quot;attribute&quot;&gt;attr&lt;/abbr&gt;</pre>

  <h4><code>&lt;abbr class="initialism"&gt;</code></h4>
  <p>Add <code>.initialism</code> to an abbreviation for a slightly smaller font-size.</p>
  <div class="gantry-example">
    <p><abbr title="HyperText Markup Language" class="initialism">HTML</abbr> is the best thing since sliced bread.</p>
  </div>
  <pre class="prettyprint">&lt;abbr title=&quot;attribute&quot; class=&quot;initialism&quot;&gt;attr&lt;/abbr&gt;</pre>
</div></div>

<div class="gantry-width-block gantry-width-50">
<div class="gantry-right">
  <h2 id="addresses">Addresses</h2>
  <p>Stylized implementation of HTML's element to present contact information for the nearest ancestor or the entire body of work.</p>

  <h4><code>&lt;address&gt;</code></h4>
  <p>Preserve formatting by ending all lines with <code>&lt;br&gt;</code>.</p>
  <div class="gantry-example">
    <address>
      <strong>Twitter, Inc.</strong><br>
      795 Folsom Ave, Suite 600<br>
      San Francisco, CA 94107<br>
      <abbr title="Phone">P:</abbr> (123) 456-7890
    </address>
    <address>
      <strong>Full Name</strong><br>
      <a href="mailto:#">first.last@gmail.com</a>
    </address>
  </div>
<pre class="prettyprint linenums">
&lt;address&gt;
  &lt;strong&gt;Twitter, Inc.&lt;/strong&gt;&lt;br&gt;
  795 Folsom Ave, Suite 600&lt;br&gt;
  San Francisco, CA 94107&lt;br&gt;
  &lt;abbr title=&quot;Phone&quot;&gt;P:&lt;/abbr&gt; (123) 456-7890
&lt;/address&gt;
&lt;address&gt;
  &lt;strong&gt;Full Name&lt;/strong&gt;&lt;br&gt;
  &lt;a href=&quot;mailto:#&quot;&gt;first.last&#64;gmail.com&lt;/a&gt;
&lt;/address&gt;
</pre>
</div></div></div>
<div class="clear"></div>

<br /><!-- SEPARATOR -->


  <h2 id="blockquotes">Blockquotes</h2>
  <p>For quoting blocks of content from another source within your document.</p>

  <h3>Default blockquote</h3>
  <p>Wrap <code>&lt;blockquote&gt;</code> around any <abbr title="HyperText Markup Language">HTML</abbr> as the quote. For straight quotes we recommend a <code>&lt;p&gt;</code>.</p>
  <div class="gantry-example">
    <blockquote>
      <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Integer posuere erat a ante.</p>
    </blockquote>
  </div>
<pre class="prettyprint linenums">&lt;blockquote&gt;
  &lt;p&gt;Lorem ipsum dolor sit amet, consectetur adipiscing elit. Integer posuere erat a ante.&lt;/p&gt;
&lt;/blockquote&gt;</pre>

  <h3>Blockquote options</h3>
  <span>Style and content changes for simple variations on a standard blockquote.</span><br />

<div class="gantry-width-container">
<div class="gantry-width-block gantry-width-50">
<div class="gantry-left">
  <h4>Naming a source</h4>
  <p>Add <code>&lt;small&gt;</code> tag for identifying the source. Wrap the name of the source work in <code>&lt;cite&gt;</code>.</p>
  <div class="gantry-example">
    <blockquote>
      <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Integer posuere erat a ante.</p>
      <small>Someone famous in <cite title="Source Title">Source Title</cite></small>
    </blockquote>
  </div>
<pre class="prettyprint linenums">&lt;blockquote&gt;
  &lt;p&gt;Lorem ipsum dolor sit amet, consectetur adipiscing elit. Integer posuere erat a ante.&lt;/p&gt;
  &lt;small&gt;Someone famous &lt;cite title=&quot;Source Title&quot;&gt;Source Title&lt;/cite&gt;&lt;/small&gt;
&lt;/blockquote&gt;</pre>
</div></div>

<div class="gantry-width-block gantry-width-50">
<div class="gantry-right">
  <h4>Alternate displays</h4>
  <p>Use <code>.pull-right</code> for a floated, right-aligned blockquote.</p>
  <div class="gantry-example" style="overflow: hidden;">
    <blockquote class="pull-right">
      <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Integer posuere erat a ante.</p>
      <small>Someone famous in <cite title="Source Title">Source Title</cite></small>
    </blockquote>
  </div>
<pre class="prettyprint linenums">&lt;blockquote class=&quot;pull-right&quot;&gt;
  ...
&lt;/blockquote&gt;</pre>
</div></div></div>
<div class="clear"></div>

<br /><!-- SEPARATOR -->


  <!-- Lists -->
<h2 id="lists" class="nomarginbottom">Lists</h2>
<div class="clear"></div>

<div class="gantry-width-container">
<div class="gantry-width-block gantry-width-33">
<div class="gantry-left">
  <h3>Unordered</h3>
  <p>This will display a list of items in which the order does <em>not</em> explicitly matter.</p>
  <div class="gantry-example">
    <ul>
      <li>Lorem ipsum dolor sit amet</li>
      <li>Nulla volutpat aliquam velit
        <ul>
          <li>Phasellus iaculis neque</li>
          <li>Purus sodales ultricies</li>
          <li>Vestibulum laoreet porttitor sem</li>
          <li>Ac tristique libero volutpat at</li>
        </ul>
      </li>
      <li>Faucibus porta lacus fringilla vel</li>
      <li>Eget porttitor lorem</li>
    </ul>
  </div>
<pre class="prettyprint linenums">&lt;ul&gt;
  &lt;li&gt;...&lt;/li&gt;
&lt;/ul&gt;</pre>
</div></div>

<div class="gantry-width-block gantry-width-33">
<div class="gantry-left">
  <h3>Ordered</h3>
  <p>This will display a list of items in which the order <em>does</em> explicitly matter (numbered list).</p>
  <div class="gantry-example">
    <ol>
      <li>Lorem ipsum dolor sit amet</li>
      <li>Consectetur adipiscing elit</li>
      <li>Integer molestie lorem at massa</li>
      <li>Facilisis in pretium nisl aliquet</li>
      <li>Nulla volutpat aliquam velit</li>
      <li>Faucibus porta lacus fringilla vel</li>
      <li>Aenean sit amet erat nunc</li>
      <li>Eget porttitor lorem</li>
    </ol>
  </div>
<pre class="prettyprint linenums">&lt;ol&gt;
  &lt;li&gt;...&lt;/li&gt;
&lt;/ol&gt;</pre>
</div></div>

<div class="gantry-width-block gantry-width-33">
<div class="gantry-left">
<h3>Unstyled</h3>
<p>This will display a list of items with no <code>list-style</code> or additional left padding.</p>
<div class="gantry-example">
  <ul class="unstyled">
      <li>Lorem ipsum dolor sit amet</li>
      <li>Nulla volutpat aliquam velit
        <ul>
          <li>Phasellus iaculis neque</li>
          <li>Purus sodales ultricies</li>
          <li>Vestibulum laoreet porttitor sem</li>
          <li>Ac tristique libero volutpat at</li>
        </ul>
      </li>
      <li>Faucibus porta lacus fringilla vel</li>
      <li>Eget porttitor lorem</li>
  </ul>
</div>
<pre class="prettyprint linenums">&lt;ul class=&quot;unstyled&quot;&gt;
  &lt;li&gt;...&lt;/li&gt;
&lt;/ul&gt;</pre>
</div></div></div>

<div class="clear"></div>

<div class="gantry-width-container">
<div class="gantry-width-block gantry-width-50">
<div class="gantry-left">
<h3>Description</h3>
<p>A list of terms with their associated descriptions.</p>
<div class="gantry-example">
  <dl>
    <dt>Description lists</dt>
    <dd>A description list is perfect for defining terms.</dd>
    <dt>Euismod</dt>
    <dd>Vestibulum id ligula porta felis euismod semper eget lacinia odio sem nec elit.</dd>
    <dd>Donec id elit non mi porta gravida at eget metus.</dd>
    <dt>Malesuada porta</dt>
    <dd>Etiam porta sem malesuada magna mollis euismod.</dd>
  </dl>
</div>
<pre class="prettyprint linenums">&lt;dl&gt;
  &lt;dt&gt;...&lt;/dt&gt;
  &lt;dd&gt;...&lt;/dd&gt;
&lt;/dl&gt;</pre><br />
<p>
  <strong>Note:</strong>
  Horizontal description lists will truncate terms that are too long to fit in the left column fix <code>text-overflow</code>. In narrower viewports, they will change to the default stacked layout.
</p>
</div></div>

<div class="gantry-width-block gantry-width-50">
<div class="gantry-right">
<h3>Horizontal description</h3>
<p>Make terms and descriptions in <code>&lt;dl&gt;</code> line up side-by-side.</p>
<div class="gantry-example">
  <dl class="dl-horizontal">
    <dt>Description lists</dt>
    <dd>A description list is perfect for defining terms.</dd>
    <dt>Euismod</dt>
    <dd>Vestibulum id ligula porta felis euismod semper eget lacinia odio sem nec elit.</dd>
    <dd>Donec id elit non mi porta gravida at eget metus.</dd>
    <dt>Malesuada porta</dt>
    <dd>Etiam porta sem malesuada magna mollis euismod.</dd>
    <dt>Felis euismod semper eget lacinia</dt>
    <dd>Fusce dapibus, tellus ac cursus commodo, tortor mauris condimentum nibh, ut fermentum massa justo sit amet risus.</dd>
  </dl>
</div>
<pre class="prettyprint linenums">&lt;dl class=&quot;dl-horizontal&quot;&gt;
  &lt;dt&gt;...&lt;/dt&gt;
  &lt;dd&gt;...&lt;/dd&gt;
&lt;/dl&gt;</pre>
</div></div></div>
<div class="clear"></div>
</section>



<!-- Code
================================================== -->
<section id="code">
  <div class="page-header">
    <h1>Code</h1>
  </div>
  <div class="gantry-width-container">
<div class="gantry-width-block gantry-width-50">
<div class="gantry-left">
  <h2>Inline</h2>
  <p>Wrap inline snippets of code with <code>&lt;code&gt;</code>.</p>
<div class="gantry-example">
For example, <code>&lt;section&gt;</code> should be wrapped as inline.
</div>
<pre class="prettyprint linenums">For example, &lt;code&gt;&lt;section&gt;&lt;/code&gt; should be wrapped as inline.</pre>
<p><strong>Note:</strong> Be sure to keep code within <code>&lt;pre&gt;</code> tags as close to the left as possible; it will render all tabs.</p>
<p>You may optionally add the <code>.pre-scrollable</code> class which will set a max-height of 350px and provide a y-axis scrollbar.</p>

</div></div>

<div class="gantry-width-block gantry-width-50">
<div class="gantry-right">
  <h2>Basic block</h2>
  <p>Use <code>&lt;pre&gt;</code> for multiple lines of code. Be sure to escape any angle brackets in the code for proper rendering.</p>
<div class="gantry-example">
<pre>&lt;p&gt;Sample text here...&lt;/p&gt;</pre>
</div>
<pre class="prettyprint linenums" style="margin-bottom: 9px;">&lt;pre&gt;
  &amp;lt;p&amp;gt;Sample text here...&amp;lt;/p&amp;gt;
&lt;/pre&gt;</pre>
</div></div></div>
<div class="clear"></div>

<h2>Prettify</h2>
<p>To add colored syntax highlight to the <code>&lt;pre&gt;</code> tag, then use the <code>.prettyprint</code> class or the <code>.prettyprint linenums</code> class.</p>

<div class="gantry-example">
<pre class="prettyprint linenums">&lt;?php /** Begin Debug **/ if ($gantry-&gt;countModules(&#x27;debug&#x27;)) : ?&gt;
    &lt;div id=&quot;rt-debug&quot;&gt;
    &lt;div class=&quot;rt-container&quot;&gt;
      &lt;?php echo $gantry-&gt;displayModules(&#x27;debug&#x27;,&#x27;standard&#x27;,&#x27;standard&#x27;); ?&gt;
      &lt;div class=&quot;clear&quot;&gt;&lt;/div&gt;
    &lt;/div&gt;
  &lt;/div&gt;
  &lt;?php /** End Debug **/ endif; ?&gt;</pre>
</div>
<pre class="prettyprint linenums">&lt;pre class=&quot;prettyprint linenums&quot;&gt;&lt;?php /** Begin Debug **/ if ($gantry-&gt;countModules(&#x27;debug&#x27;)) : ?&gt;
  &lt;div id=&quot;rt-debug&quot;&gt;
    &lt;div class=&quot;rt-container&quot;&gt;
      &lt;?php echo $gantry-&gt;displayModules(&#x27;debug&#x27;,&#x27;standard&#x27;,&#x27;standard&#x27;); ?&gt;
      &lt;div class=&quot;clear&quot;&gt;&lt;/div&gt;
    &lt;/div&gt;
  &lt;/div&gt;
  &lt;?php /** End Debug **/ endif; ?&gt;&lt;/pre&gt;</pre>
</section>



<!-- Tables
================================================== -->
<section id="tables">
  <div class="page-header">
    <h1>Tables</h1>
  </div>

  <h2>Default styles</h2>
  <p>For basic styling—light padding and only horizontal dividers—add the base class <code>.table</code> to any <code>&lt;table&gt;</code>.</p>
  <div class="gantry-example">
    <table class="table">
      <thead>
        <tr>
          <th>#</th>
          <th>First Name</th>
          <th>Last Name</th>
          <th>Username</th>
        </tr>
      </thead>
      <tbody>
        <tr>
          <td>1</td>
          <td>Mark</td>
          <td>Otto</td>
          <td>@mdo</td>
        </tr>
        <tr>
          <td>2</td>
          <td>Jacob</td>
          <td>Thornton</td>
          <td>@fat</td>
        </tr>
        <tr>
          <td>3</td>
          <td>Larry</td>
          <td>the Bird</td>
          <td>@twitter</td>
        </tr>
      </tbody>
    </table>
  </div>
<pre class="prettyprint linenums">&lt;table class=&quot;table&quot;&gt;
  &hellip;
&lt;/table&gt;</pre>


<br /><!-- SEPARATOR -->

  <h2>Optional classes</h2>
  <p>Add any of the follow classes to the <code>.table</code> base class.</p>

<div class="gantry-width-container">
<div class="gantry-width-block gantry-width-50">
<div class="gantry-left">
  <h4><code>.table-striped</code></h4>
  <p>Adds zebra-striping to any table row within the <code>&lt;tbody&gt;</code> via the <code>:nth-child</code> CSS selector (not available in IE7-IE8).</p>
  <div class="gantry-example">
    <table class="table table-striped">
      <thead>
        <tr>
          <th>#</th>
          <th>First Name</th>
          <th>Last Name</th>
          <th>Username</th>
        </tr>
      </thead>
      <tbody>
        <tr>
          <td>1</td>
          <td>Mark</td>
          <td>Otto</td>
          <td>@mdo</td>
        </tr>
        <tr>
          <td>2</td>
          <td>Jacob</td>
          <td>Thornton</td>
          <td>@fat</td>
        </tr>
        <tr>
          <td>3</td>
          <td>Larry</td>
          <td>the Bird</td>
          <td>@twitter</td>
        </tr>
      </tbody>
    </table>
  </div>
<pre class="prettyprint linenums" style="margin-bottom: 18px;">&lt;table class=&quot;table table-striped&quot;&gt;
  &hellip;
&lt;/table&gt;</pre>
  <h4><code>.table-hover</code></h4>
  <p>Enable a hover state on table rows within a <code>&lt;tbody&gt;</code>.</p>
  <div class="gantry-example">
    <table class="table table-hover">
      <thead>
        <tr>
          <th>#</th>
          <th>First Name</th>
          <th>Last Name</th>
          <th>Username</th>
        </tr>
      </thead>
      <tbody>
        <tr>
          <td>1</td>
          <td>Mark</td>
          <td>Otto</td>
          <td>@mdo</td>
        </tr>
        <tr>
          <td>2</td>
          <td>Jacob</td>
          <td>Thornton</td>
          <td>@fat</td>
        </tr>
        <tr>
          <td>3</td>
          <td colspan="2">Larry the Bird</td>
          <td>@twitter</td>
        </tr>
      </tbody>
    </table>
  </div>
<pre class="prettyprint linenums" style="margin-bottom: 18px;">&lt;table class=&quot;table table-hover&quot;&gt;
  &hellip;
&lt;/table&gt;</pre>
</div></div>

<div class="gantry-width-block gantry-width-50">
<div class="gantry-right" style="float: none;">
  <h4><code>.table-bordered</code></h4>
  <p>Add borders and rounded corners to the table.</p>
  <div class="gantry-example">
    <table class="table table-bordered">
      <thead>
        <tr>
          <th>#</th>
          <th>First Name</th>
          <th>Last Name</th>
          <th>Username</th>
        </tr>
      </thead>
      <tbody>
        <tr>
          <td rowspan="2">1</td>
          <td>Mark</td>
          <td>Otto</td>
          <td>@mdo</td>
        </tr>
        <tr>
          <td>Mark</td>
          <td>Otto</td>
          <td>@TwBootstrap</td>
        </tr>
        <tr>
          <td>2</td>
          <td>Jacob</td>
          <td>Thornton</td>
          <td>@fat</td>
        </tr>
        <tr>
          <td>3</td>
          <td colspan="2">Larry the Bird</td>
          <td>@twitter</td>
        </tr>
      </tbody>
    </table>
  </div>
<pre class="prettyprint linenums">&lt;table class=&quot;table table-bordered&quot;&gt;
  &hellip;
&lt;/table&gt;</pre>
  <h4><code>.table-condensed</code></h4>
  <p>Makes tables more compact by cutting cell padding in half.</p>
  <div class="gantry-example">
    <table class="table table-condensed">
      <thead>
        <tr>
          <th>#</th>
          <th>First Name</th>
          <th>Last Name</th>
          <th>Username</th>
        </tr>
      </thead>
      <tbody>
        <tr>
          <td>1</td>
          <td>Mark</td>
          <td>Otto</td>
          <td>@mdo</td>
        </tr>
        <tr>
          <td>2</td>
          <td>Jacob</td>
          <td>Thornton</td>
          <td>@fat</td>
        </tr>
        <tr>
          <td>3</td>
          <td colspan="2">Larry the Bird</td>
          <td>@twitter</td>
        </tr>
      </tbody>
    </table>
  </div>
<pre class="prettyprint linenums" style="margin-bottom: 18px;">&lt;table class=&quot;table table-condensed&quot;&gt;
  &hellip;
&lt;/table&gt;</pre>
</div></div></div>
<div class="clear"></div>

<br /><!-- SEPARATOR -->

  <h2>Optional row classes</h2>   
  <p>Use contextual classes to color table rows.</p>
     <table class="table table-bordered table-striped">
        <colgroup>
          <col class="span1">
          <col class="span7">
        </colgroup>
        <thead>
          <tr>
            <th>Class</th>
            <th>Description</th>
          </tr>
        </thead>
        <tbody>
          <tr>
            <td>
              <code>.success</code>
            </td>
            <td>Indicates a successful or positive action.</td>
          </tr>
          <tr>
            <td>
              <code>.error</code>
            </td>
            <td>Indicates a dangerous or potentially negative action.</td>
          </tr>
          <tr>
            <td>
              <code>.warning</code>
            </td>
            <td>Indicates a warning that might need attention.</td>
          </tr>
  <tr>
            <td>
              <code>.info</code>
            </td>
            <td>Used as an alternative to the default styles.</td>
          </tr>
        </tbody>
      </table>

  <div class="gantry-example">
       <table class="table">
         <thead>
           <tr>
             <th>#</th>
             <th>Product</th>
             <th>Payment Taken</th>
             <th>Status</th>
           </tr>
         </thead>
         <tbody>
           <tr class="success">
             <td>1</td>
             <td>TB - Monthly</td>
             <td>01/04/2012</td>
             <td>Approved</td>
           </tr>
           <tr class="error">
             <td>2</td>
             <td>TB - Monthly</td>
             <td>02/04/2012</td>
             <td>Declined</td>
           </tr>
           <tr class="warning">
             <td>3</td>
             <td>TB - Monthly</td>
             <td>03/04/2012</td>
             <td>Pending</td>
           </tr>
           <tr class="info">
             <td>4</td>
             <td>TB - Monthly</td>
             <td>04/04/2012</td>
             <td>Call in to confirm</td>
           </tr>
         </tbody>
       </table>
     </div>
<pre class="prettyprint linenums">...
  &lt;tr class=&quot;success&quot;&gt;
    &lt;td&gt;1&lt;/td&gt;
    &lt;td&gt;TB - Monthly&lt;/td&gt;
    &lt;td&gt;01/04/2012&lt;/td&gt;
    &lt;td&gt;Approved&lt;/td&gt;
  &lt;/tr&gt;
...</pre>

  <h2>Supported table markup</h2>
  <p>List of supported table HTML elements and how they should be used.</p>
  <table class="table table-bordered table-striped">
    <colgroup>
      <col class="span1">
      <col class="span7">
    </colgroup>
    <thead>
      <tr>
        <th>Tag</th>
        <th>Description</th>
      </tr>
    </thead>
    <tbody>
      <tr>
        <td>
          <code>&lt;table&gt;</code>
        </td>
        <td>
          Wrapping element for displaying data in a tabular format
        </td>
      </tr>
      <tr>
        <td>
          <code>&lt;thead&gt;</code>
        </td>
        <td>
          Container element for table header rows (<code>&lt;tr&gt;</code>) to label table columns
        </td>
      </tr>
      <tr>
        <td>
          <code>&lt;tbody&gt;</code>
        </td>
        <td>
          Container element for table rows (<code>&lt;tr&gt;</code>) in the body of the table
        </td>
      </tr>
      <tr>
        <td>
          <code>&lt;tr&gt;</code>
        </td>
        <td>
          Container element for a set of table cells (<code>&lt;td&gt;</code> or <code>&lt;th&gt;</code>) that appears on a single row
        </td>
      </tr>
      <tr>
        <td>
          <code>&lt;td&gt;</code>
        </td>
        <td>
          Default table cell
        </td>
      </tr>
      <tr>
        <td>
          <code>&lt;th&gt;</code>
        </td>
        <td>
          Special table cell for column (or row, depending on scope and placement) labels<br>
          Must be used within a <code>&lt;thead&gt;</code>
        </td>
      </tr>
      <tr>
        <td>
          <code>&lt;caption&gt;</code>
        </td>
        <td>
          Description or summary of what the table holds, especially useful for screen readers
        </td>
      </tr>
    </tbody>
  </table>
<pre class="prettyprint linenums">&lt;table&gt;
  &lt;caption&gt;...&lt;/caption&gt;
  &lt;thead&gt;
    &lt;tr&gt;
      &lt;th&gt;...&lt;/th&gt;
      &lt;th&gt;...&lt;/th&gt;
    &lt;/tr&gt;
  &lt;/thead&gt;
  &lt;tbody&gt;
    &lt;tr&gt;
      &lt;td&gt;...&lt;/td&gt;
      &lt;td&gt;...&lt;/td&gt;
    &lt;/tr&gt;
  &lt;/tbody&gt;
&lt;/table&gt;</pre>

</section>



<!-- Forms
================================================== -->
<section id="forms">
  <div class="page-header">
    <h1>Forms</h1>
  </div>

<div class="gantry-width-container">
<div class="gantry-width-block gantry-width-50">
<div class="gantry-left" style="float: none;">                
  <h2>Default styles</h2>
  <p>Individual form controls receive styling, but without any required base class on the <code>&lt;form&gt;</code> or large changes in markup. Results in stacked, left-aligned labels on top of form controls.</p>

  <form class="gantry-example"><fieldset>
    <legend>Legend</legend>
    <label>Label name</label>
    <input type="text" placeholder="Type something…">
    <span class="help-block">Example block-level help text here.</span>
    <label class="checkbox">
      <input type="checkbox"> Check me out
    </label>
    <button type="submit" class="btn">Submit</button>
  </fieldset></form>

<pre class="prettyprint linenums">&lt;form&gt;
  &lt;legend&gt;Legend&lt;/legend&gt;
  &lt;label&gt;Label name&lt;/label&gt;
  &lt;input type=&quot;text&quot; placeholder=&quot;Type something&hellip;&quot;&gt;
  &lt;span class=&quot;help-block&quot;&gt;Example block-level help text here.&lt;/span&gt;
  &lt;label class=&quot;checkbox&quot;&gt;
    &lt;input type=&quot;checkbox&quot;&gt; Check me out
  &lt;/label&gt;
  &lt;button type=&quot;submit&quot; class=&quot;btn&quot;&gt;Submit&lt;/button&gt;
&lt;/form&gt;</pre><br />

  <h2>Optional layouts</h2>
  <p>Included with Bootstrap are three optional form layouts for common use cases.</p>

  <h3>Search form</h3>
  <p>Add <code>.form-search</code> to the form and <code>.search-query</code> to the <code>&lt;input&gt;</code> for an extra-rounded text input.</p>
  <form class="gantry-example form-search">
    <input type="text" class="input-medium search-query">
    <button type="submit" class="btn">Search</button>
  </form>
<pre class="prettyprint linenums">&lt;form class=&quot;form-search&quot;&gt;
  &lt;input type=&quot;text&quot; class=&quot;input-medium search-query&quot;&gt;
  &lt;button type=&quot;submit&quot; class=&quot;btn&quot;&gt;Search&lt;/button&gt;
&lt;/form&gt;</pre>

  <h3>Inline form</h3>
  <p>Add <code>.form-inline</code> for left-aligned labels and inline-block controls for a compact layout.</p>
  <form class="gantry-example form-inline">
    <input type="text" class="input-small" placeholder="Email">
    <input type="password" class="input-small" placeholder="Password">
    <label class="checkbox">
      <input type="checkbox"> Remember me
    </label>
    <button type="submit" class="btn">Sign in</button>
  </form>
<pre class="prettyprint linenums">&lt;form class=&quot;form-inline&quot;&gt;
  &lt;input type=&quot;text&quot; class=&quot;input-small&quot; placeholder=&quot;Email&quot;&gt;
  &lt;input type=&quot;password&quot; class=&quot;input-small&quot; placeholder=&quot;Password&quot;&gt;
  &lt;label class=&quot;checkbox&quot;&gt;
    &lt;input type=&quot;checkbox&quot;&gt; Remember me
  &lt;/label&gt;
  &lt;button type=&quot;submit&quot; class=&quot;btn&quot;&gt;Sign in&lt;/button&gt;
&lt;/form&gt;</pre>

  <h3>Horizontal form</h3>
  <p>Right align labels and float them to the left to make them appear on the same line as controls. Requires the most markup changes from a default form:</p>
  <ul>
    <li>Add <code>.form-horizontal</code> to the form</li>
    <li>Wrap labels and controls in <code>.control-group</code></li>
    <li>Add <code>.control-label</code> to the label</li>
    <li>Wrap any associated controls in <code>.controls</code> for proper alignment</li>
  </ul>
  <form class="gantry-example form-horizontal"><fieldset class="hidden-tablet">
    <legend>Legend</legend>
    <div class="control-group">
      <label class="control-label" for="inputEmail">Email</label>
      <div class="controls">
        <input type="text" id="inputEmail" placeholder="Email">
      </div>
    </div>
    <div class="control-group">
      <label class="control-label" for="inputPassword">Password</label>
      <div class="controls">
        <input type="password" id="inputPassword" placeholder="Password">
      </div>
    </div>
    <div class="control-group">
      <div class="controls">
        <label class="checkbox">
          <input type="checkbox"> Remember me
        </label>
        <button type="submit" class="btn">Sign in</button>
      </div>
    </div></fieldset>
  </form>
<pre class="prettyprint linenums">&lt;form class=&quot;form-horizontal&quot;&gt;
  &lt;div class=&quot;control-group&quot;&gt;
    &lt;label class=&quot;control-label&quot; for=&quot;inputEmail&quot;&gt;Email&lt;/label&gt;
    &lt;div class=&quot;controls&quot;&gt;
      &lt;input type=&quot;text&quot; id=&quot;inputEmail&quot; placeholder=&quot;Email&quot;&gt;
    &lt;/div&gt;
  &lt;/div&gt;
  &lt;div class=&quot;control-group&quot;&gt;
    &lt;label class=&quot;control-label&quot; for=&quot;inputPassword&quot;&gt;Password&lt;/label&gt;
    &lt;div class=&quot;controls&quot;&gt;
      &lt;input type=&quot;password&quot; id=&quot;inputPassword&quot; placeholder=&quot;Password&quot;&gt;
    &lt;/div&gt;
  &lt;/div&gt;
  &lt;div class=&quot;control-group&quot;&gt;
    &lt;div class=&quot;controls&quot;&gt;
      &lt;label class=&quot;checkbox&quot;&gt;
        &lt;input type=&quot;checkbox&quot;&gt; Remember me
      &lt;/label&gt;
      &lt;button type=&quot;submit&quot; class=&quot;btn&quot;&gt;Sign in&lt;/button&gt;
    &lt;/div&gt;
  &lt;/div&gt;
&lt;/form&gt;</pre>
</div></div>

<div class="gantry-width-block gantry-width-50">
<div class="gantry-right">
  <h2>Supported form controls</h2>
  <p>Examples of standard form controls supported in an example form layout.</p>

  <h3>Inputs</h3>
  <p>Most common form control, text-based input fields. Includes support for all HTML5 types: text, password, datetime, datetime-local, date, month, time, week, number, email, url, search, tel, and color.</p>
  <p>Requires the use of a specified <code>type</code> at all times.</p>
  <form class="gantry-example form-inline">
    <input type="text" placeholder="Text input">
  </form>
<pre class="prettyprint linenums">&lt;input type=&quot;text&quot; placeholder=&quot;Text input&quot;&gt;</pre>

  <h3>Textarea</h3>
  <p>Form control which supports multiple lines of text. Change <code>row</code> attribute as necessary.</p>
  <form class="gantry-example form-inline">
    <textarea rows="3"></textarea>
  </form>
<pre class="prettyprint linenums">&lt;textarea rows=&quot;3&quot;&gt;&lt;/textarea&gt;</pre>

  <h3>Checkboxes and radios</h3>
  <p>Checkboxes are for selecting one or several options in a list while radios are for selecting one option from many.</p>
  <h4>Default (stacked)</h4>
  <form class="gantry-example">
    <label class="checkbox">
      <input type="checkbox" value="">
      Option one is this and that—be sure to include why it's great
    </label>
    <br>
    <label class="radio">
      <input type="radio" name="optionsRadios" id="optionsRadios1" value="option1" checked="">
      Option one is this and that—be sure to include why it's great
    </label>
    <label class="radio">
      <input type="radio" name="optionsRadios" id="optionsRadios2" value="option2">
      Option two can be something else and selecting it will deselect option one
    </label>
  </form>
<pre class="prettyprint linenums">&lt;label class=&quot;checkbox&quot;&gt;
  &lt;input type=&quot;checkbox&quot; value=&quot;&quot;&gt;
  Option one is this and that&mdash;be sure to include why it&#x27;s great
&lt;/label&gt;

&lt;label class=&quot;radio&quot;&gt;
  &lt;input type=&quot;radio&quot; name=&quot;optionsRadios&quot; id=&quot;optionsRadios1&quot; value=&quot;option1&quot; checked&gt;
  Option one is this and that&mdash;be sure to include why it&#x27;s great
&lt;/label&gt;
&lt;label class=&quot;radio&quot;&gt;
  &lt;input type=&quot;radio&quot; name=&quot;optionsRadios&quot; id=&quot;optionsRadios2&quot; value=&quot;option2&quot;&gt;
  Option two can be something else and selecting it will deselect option one
&lt;/label&gt;</pre>

  <h4>Inline checkboxes</h4>
  <p>Add the <code>.inline</code> class to a series of checkboxes or radios for controls appear on the same line.</p>
  <form class="gantry-example">
    <label class="checkbox inline">
      <input type="checkbox" id="inlineCheckbox1" value="option1"> 1
    </label>
    <label class="checkbox inline">
      <input type="checkbox" id="inlineCheckbox2" value="option2"> 2
    </label>
    <label class="checkbox inline">
      <input type="checkbox" id="inlineCheckbox3" value="option3"> 3
    </label>
  </form>
<pre class="prettyprint linenums">&lt;label class=&quot;checkbox inline&quot;&gt;
  &lt;input type=&quot;checkbox&quot; id=&quot;inlineCheckbox1&quot; value=&quot;option1&quot;&gt; 1
&lt;/label&gt;
&lt;label class=&quot;checkbox inline&quot;&gt;
  &lt;input type=&quot;checkbox&quot; id=&quot;inlineCheckbox2&quot; value=&quot;option2&quot;&gt; 2
&lt;/label&gt;
&lt;label class=&quot;checkbox inline&quot;&gt;
  &lt;input type=&quot;checkbox&quot; id=&quot;inlineCheckbox3&quot; value=&quot;option3&quot;&gt; 3
&lt;/label&gt;</pre>

  <h3>Selects</h3>
  <p>Use the default option or specify a <code>multiple="multiple"</code> to show multiple options at once.</p>
  <form class="gantry-example">
    <select>
      <option>1</option>
      <option>2</option>
      <option>3</option>
      <option>4</option>
      <option>5</option>
    </select>
    <br>
    <select multiple="multiple">
      <option>1</option>
      <option>2</option>
      <option>3</option>
      <option>4</option>
      <option>5</option>
    </select>
  </form>
<pre class="prettyprint linenums">&lt;select&gt;
  &lt;option&gt;1&lt;/option&gt;
  &lt;option&gt;2&lt;/option&gt;
  &lt;option&gt;3&lt;/option&gt;
  &lt;option&gt;4&lt;/option&gt;
  &lt;option&gt;5&lt;/option&gt;
&lt;/select&gt;

&lt;select multiple=&quot;multiple&quot;&gt;
  &lt;option&gt;1&lt;/option&gt;
  &lt;option&gt;2&lt;/option&gt;
  &lt;option&gt;3&lt;/option&gt;
  &lt;option&gt;4&lt;/option&gt;
  &lt;option&gt;5&lt;/option&gt;
&lt;/select&gt;</pre>
</div></div></div>

<div class="clear"></div>

<br /><!-- SEPARATOR -->


  <h2>Extending form controls</h2>
  <p>Adding on top of existing browser controls, Bootstrap includes other useful form components.</p>

  <h3>Prepended and appended inputs</h3>
  <span>Add text or buttons before or after any text-based input. Do note that <code>select</code> elements are not supported here.</span><br />

<div class="gantry-width-container">
<div class="gantry-width-block gantry-width-50">
<div class="gantry-left" style="float: none;">
  <h4>Default options</h4>
  <p>Wrap an <code>.add-on</code> and an <code>input</code> with one of two classes to prepend or append text to an input.</p>
  <form class="gantry-example">
    <div class="input-prepend">
      <span class="add-on">@</span>
      <input class="span2" id="prependedInput" size="16" type="text" placeholder="Username">
    </div>
    <br>
    <div class="input-append">
      <input class="span2" id="appendedInput" size="16" type="text">
      <span class="add-on">.00</span>
    </div>
  </form>
<pre class="prettyprint linenums">&lt;div class=&quot;input-prepend&quot;&gt;
  &lt;span class=&quot;add-on&quot;&gt;@&lt;/span&gt;&lt;input class=&quot;span2&quot; id=&quot;prependedInput&quot; size=&quot;16&quot; type=&quot;text&quot; placeholder=&quot;Username&quot;&gt;
&lt;/div&gt;
&lt;div class=&quot;input-append&quot;&gt;
  &lt;input class=&quot;span2&quot; id=&quot;appendedInput&quot; size=&quot;16&quot; type=&quot;text&quot;&gt;&lt;span class=&quot;add-on&quot;&gt;.00&lt;/span&gt;
&lt;/div&gt;</pre>

  <h4>Search form</h4>
  <form class="gantry-example form-search">
    <div class="input-append">
      <input type="text" class="span2 search-query">
      <button type="submit" class="btn">Search</button>
    </div>
    <br /><br /><div class="input-prepend">
      <button type="submit" class="btn">Search</button>
      <input type="text" class="span2 search-query">
    </div>
  </form>
<pre class="prettyprint linenums">&lt;form class=&quot;form-search&quot;&gt;
  &lt;div class=&quot;input-append&quot;&gt;
    &lt;input type=&quot;text&quot; class=&quot;span2 search-query&quot;&gt;
    &lt;button type=&quot;submit&quot; class=&quot;btn&quot;&gt;Search&lt;/button&gt;
  &lt;/div&gt;
  &lt;div class=&quot;input-prepend&quot;&gt;
    &lt;button type=&quot;submit&quot; class=&quot;btn&quot;&gt;Search&lt;/button&gt;
    &lt;input type=&quot;text&quot; class=&quot;span2 search-query&quot;&gt;
  &lt;/div&gt;
&lt;/form&gt;</pre>
</div></div>

<div class="gantry-width-block gantry-width-50">
<div class="gantry-right" style="float: none;">
  <h4>Combined</h4>
  <p>Use both classes and two instances of <code>.add-on</code> to prepend and append an input.</p>
  <form class="gantry-example form-inline">
    <div class="input-prepend input-append">
      <span class="add-on">$</span>
      <input class="span2" id="appendedPrependedInput" size="16" type="text">
      <span class="add-on">.00</span>
    </div>
  </form>
<pre class="prettyprint linenums">&lt;div class=&quot;input-prepend input-append&quot;&gt;
  &lt;span class=&quot;add-on&quot;&gt;$&lt;/span&gt;&lt;input class=&quot;span2&quot; id=&quot;appendedPrependedInput&quot; size=&quot;16&quot; type=&quot;text&quot;&gt;&lt;span class=&quot;add-on&quot;&gt;.00&lt;/span&gt;
&lt;/div&gt;</pre>

  <h4>Buttons instead of text</h4>
  <p>Instead of a <code>&lt;span&gt;</code> with text, use a <code>.btn</code> to attach a button (or two) to an input.</p>
  <form class="gantry-example">
    <div class="input-append">
      <input class="span2" id="appendedInputButton" size="16" type="text">
      <button class="btn" type="button">Go!</button>
    </div>
    <br>
    <div class="input-append">
      <input class="span2" id="appendedInputButtons" size="16" type="text">
      <button class="btn" type="button">Search</button>
      <button class="btn" type="button">Options</button>
    </div>
  </form>
<pre class="prettyprint linenums">&lt;div class=&quot;input-append&quot;&gt;
  &lt;input class=&quot;span2&quot; id=&quot;appendedInputButton&quot; size=&quot;16&quot; type=&quot;text&quot;&gt;&lt;button class=&quot;btn&quot; type=&quot;button&quot;&gt;Go!&lt;/button&gt;
&lt;/div&gt;

&lt;div class=&quot;input-append&quot;&gt;
  &lt;input class=&quot;span2&quot; id=&quot;appendedInputButtons&quot; size=&quot;16&quot; type=&quot;text&quot;&gt;&lt;button class=&quot;btn&quot; type=&quot;button&quot;&gt;Search&lt;/button&gt;&lt;button class=&quot;btn&quot; type=&quot;button&quot;&gt;Options&lt;/button&gt;
&lt;/div&gt;</pre>

</div></div></div>
<div class="clear"></div>

<div class="gantry-width-container">
<div class="gantry-width-block gantry-width-50">
<div class="gantry-left">
  <h3>Form actions</h3>
  <p>End a form with a group of actions (buttons). When placed within a <code>.form-horizontal</code>, the buttons will automatically indent to line up with the form controls.</p>
  <form class="gantry-example">
    <div class="form-actions">
      <button type="submit" class="btn btn-primary">Save changes</button>
      <button type="button" class="btn">Cancel</button>
    </div>
  </form>
<pre class="prettyprint linenums">&lt;div class=&quot;form-actions&quot;&gt;
  &lt;button type=&quot;submit&quot; class=&quot;btn btn-primary&quot;&gt;Save changes&lt;/button&gt;
  &lt;button type=&quot;button&quot; class=&quot;btn&quot;&gt;Cancel&lt;/button&gt;
&lt;/div&gt;</pre>

  <h3>Help text</h3>
  <p>Inline and block level support for help text that appears around form controls.</p>
  <h4>Inline help</h4>
  <form class="gantry-example form-inline">
    <input type="text"> <span class="help-inline">Inline help text</span>
  </form>
<pre class="prettyprint linenums">&lt;input type=&quot;text&quot;&gt;&lt;span class=&quot;help-inline&quot;&gt;Inline help text&lt;/span&gt;</pre>

  <h4>Block help</h4>
  <form class="gantry-example form-inline">
    <input type="text">
    <span class="help-block">A longer block of help text that breaks onto a new line and may extend beyond one line.</span>
  </form>
<pre class="prettyprint linenums">&lt;input type=&quot;text&quot;&gt;&lt;span class=&quot;help-block&quot;&gt;A longer block of help text that breaks onto a new line and may extend beyond one line.&lt;/span&gt;</pre>
</div></div>

<div class="gantry-width-block gantry-width-50">
<div class="gantry-right" style="float: none;">
  <h3>Control sizing</h3>
  <p>Use relative sizing classes like <code>.input-large</code> or match your inputs to the grid column sizes using <code>.span*</code> classes.</p>

  <h4>Relative sizing</h4>
  <form class="gantry-example" style="padding-bottom: 15px;">
    <div class="controls docs-input-sizes">
      <input class="input-mini" type="text" placeholder=".input-mini"><br />
      <input class="input-small" type="text" placeholder=".input-small"><br />
      <input class="input-medium" type="text" placeholder=".input-medium"><br />
      <input class="input-large" type="text" placeholder=".input-large"><br />
      <input class="input-xlarge" type="text" placeholder=".input-xlarge"><br />
      <input class="input-xxlarge" type="text" placeholder=".input-xxlarge">
    </div>
  </form>
<pre class="prettyprint linenums">&lt;input class=&quot;input-mini&quot; type=&quot;text&quot; placeholder=&quot;.input-mini&quot;&gt;
&lt;input class=&quot;input-small&quot; type=&quot;text&quot; placeholder=&quot;.input-small&quot;&gt;
&lt;input class=&quot;input-medium&quot; type=&quot;text&quot; placeholder=&quot;.input-medium&quot;&gt;
&lt;input class=&quot;input-large&quot; type=&quot;text&quot; placeholder=&quot;.input-large&quot;&gt;
&lt;input class=&quot;input-xlarge&quot; type=&quot;text&quot; placeholder=&quot;.input-xlarge&quot;&gt;
&lt;input class=&quot;input-xxlarge&quot; type=&quot;text&quot; placeholder=&quot;.input-xxlarge&quot;&gt;</pre><br />
  <p>
    <strong>Note:</strong> In future versions, we'll be altering the use of these relative input classes to match our button sizes. For example, <code>.input-large</code> will increase the padding and font-size of an input.
  </p>

  <h3>Uneditable inputs</h3>
  <p>Present data in a form that's not editable without using actual form markup.</p>
  <form class="gantry-example">
    <span class="input-xlarge uneditable-input">Some value here</span>
  </form>
<pre class="prettyprint linenums">&lt;span class=&quot;input-xlarge uneditable-input&quot;&gt;Some value here&lt;/span&gt;</pre>
</div></div></div>
<div class="clear"></div>

<br /><!-- SEPARATOR -->


  <h2>Form control states</h2>
  <p>Provide feedback to users or visitors with basic feedback states on form controls and labels.</p>

<div class="gantry-width-container">
<div class="gantry-width-block gantry-width-50">
<div class="gantry-left">
  <h3>Input focus</h3>
  <p>We remove the default <code>outline</code> styles on some form controls and apply a <code>box-shadow</code> in its place for <code>:focus</code>.</p>
  <form class="gantry-example form-inline">
    <input class="input-xlarge focused" id="focusedInput" type="text" value="This is focused...">
  </form>
<pre class="prettyprint linenums">&lt;input class=&quot;input-xlarge&quot; id=&quot;focusedInput&quot; type=&quot;text&quot; value=&quot;This is focused...&quot;&gt;</pre>
</div></div>

<div class="gantry-width-block gantry-width-50">
<div class="gantry-right">
  <h3>Disabled inputs</h3>
  <p>Add the <code>disabled</code> attribute on an input to prevent user input and trigger a slightly different look.</p>
  <form class="gantry-example form-inline">
    <input class="input-xlarge" id="disabledInput" type="text" placeholder="Disabled input here…" disabled="">
  </form>
<pre class="prettyprint linenums">&lt;input class=&quot;input-xlarge&quot; id=&quot;disabledInput&quot; type=&quot;text&quot; placeholder=&quot;Disabled input here...&quot; disabled&gt;</pre>
</div></div></div>
<div class="clear"></div>       

<h3>Validation states</h3>
<p>Bootstrap includes validation styles for error, warning, and success messages. To use, add the appropriate class to the surrounding <code>.control-group</code>.</p>

<form class="gantry-example form-horizontal">
  <div class="control-group warning">
    <label class="control-label" for="inputWarning">Input with warning</label>
    <div class="controls">
      <input type="text" id="inputWarning">
      <span class="help-inline">Something may have gone wrong</span>
    </div>
  </div>
  <div class="control-group error">
    <label class="control-label" for="inputError">Input with error</label>
    <div class="controls">
      <input type="text" id="inputError">
      <span class="help-inline">Please correct the error</span>
    </div>
  </div>
  <div class="control-group info">
    <label class="control-label" for="inputError">Input with info</label>
    <div class="controls">
      <input type="text" id="inputError">
      <span class="help-inline">Username is taken</span>
    </div>
  </div>
  <div class="control-group success">
    <label class="control-label" for="inputSuccess">Input with success</label>
    <div class="controls">
      <input type="text" id="inputSuccess">
      <span class="help-inline">Woohoo!</span>
    </div>
  </div>
</form>   
<pre class="prettyprint linenums">&lt;div class=&quot;control-group warning&quot;&gt;
  &lt;label class=&quot;control-label&quot; for=&quot;inputWarning&quot;&gt;Input with warning&lt;/label&gt;
  &lt;div class=&quot;controls&quot;&gt;
    &lt;input type=&quot;text&quot; id=&quot;inputWarning&quot;&gt;
    &lt;span class=&quot;help-inline&quot;&gt;Something may have gone wrong&lt;/span&gt;
  &lt;/div&gt;
&lt;/div&gt;
&lt;div class=&quot;control-group error&quot;&gt;
  &lt;label class=&quot;control-label&quot; for=&quot;inputError&quot;&gt;Input with error&lt;/label&gt;
  &lt;div class=&quot;controls&quot;&gt;
    &lt;input type=&quot;text&quot; id=&quot;inputError&quot;&gt;
    &lt;span class=&quot;help-inline&quot;&gt;Please correct the error&lt;/span&gt;
  &lt;/div&gt;
&lt;/div&gt;
&lt;div class=&quot;control-group info&quot;&gt;
  &lt;label class=&quot;control-label&quot; for=&quot;inputError&quot;&gt;Input with info&lt;/label&gt;
  &lt;div class=&quot;controls&quot;&gt;
    &lt;input type=&quot;text&quot; id=&quot;inputError&quot;&gt;
    &lt;span class=&quot;help-inline&quot;&gt;Username is taken&lt;/span&gt;
  &lt;/div&gt;
&lt;/div&gt;
&lt;div class=&quot;control-group success&quot;&gt;
  &lt;label class=&quot;control-label&quot; for=&quot;inputSuccess&quot;&gt;Input with success&lt;/label&gt;
  &lt;div class=&quot;controls&quot;&gt;
    &lt;input type=&quot;text&quot; id=&quot;inputSuccess&quot;&gt;
    &lt;span class=&quot;help-inline&quot;&gt;Woohoo!&lt;/span&gt;
  &lt;/div&gt;
&lt;/div&gt;</pre>
</section>



<!-- Buttons
================================================== -->
<section id="buttons">
  <div class="page-header">
    <h1>Buttons</h1>
  </div>

  <h2>Default buttons</h2>
  <p>Button styles can be applied to anything with the <code>.btn</code> class applied. However, typically you'll want to apply these to only <code>&lt;a&gt;</code> and <code>&lt;button&gt;</code> elements for the best rendering.</p>
<table class="table table-bordered table-striped">
  <thead>
    <tr>
      <th>Button</th>
      <th>class=""</th>
      <th>Description</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td><button type="button" class="btn">Default</button></td>
      <td><code>btn</code></td>
      <td>Standard gray button with gradient</td>
    </tr>
    <tr>
      <td><button type="button" class="btn btn-primary">Primary</button></td>
      <td><code>btn btn-primary</code></td>
      <td>Provides extra visual weight and identifies the primary action in a set of buttons</td>
    </tr>
    <tr>
      <td><button type="button" class="btn btn-info">Info</button></td>
      <td><code>btn btn-info</code></td>
      <td>Used as an alternative to the default styles</td>
    </tr>
    <tr>
      <td><button type="button" class="btn btn-success">Success</button></td>
      <td><code>btn btn-success</code></td>
      <td>Indicates a successful or positive action</td>
    </tr>
    <tr>
      <td><button type="button" class="btn btn-warning">Warning</button></td>
      <td><code>btn btn-warning</code></td>
      <td>Indicates caution should be taken with this action</td>
    </tr>
    <tr>
      <td><button type="button" class="btn btn-danger">Danger</button></td>
      <td><code>btn btn-danger</code></td>
      <td>Indicates a dangerous or potentially negative action</td>
    </tr>
    <tr>
      <td><button type="button" class="btn btn-inverse">Inverse</button></td>
      <td><code>btn btn-inverse</code></td>
      <td>Alternate dark gray button, not tied to a semantic action or use</td>
    </tr>
    <tr>
      <td><button type="button" class="btn btn-link">Link</button></td>
      <td><code>btn btn-link</code></td>
      <td>Deemphasize a button by making it look like a link while maintaining button behavior</td>
    </tr>
  </tbody>
</table>

  <h4>Cross browser compatibility</h4>
  <p>IE9 doesn't crop background gradients on rounded corners, so we remove it. Related, IE9 jankifies disabled <code>button</code> elements, rendering text gray with a nasty text-shadow that we cannot fix.</p>


  <h2>Button sizes</h2>
  <p>Fancy larger or smaller buttons? Add <code>.btn-large</code>, <code>.btn-small</code>, or <code>.btn-mini</code> for additional sizes.</p>
  <div class="gantry-example">
    <p>
      <button type="button" class="btn btn-large btn-primary">Large button</button>
      <button type="button" class="btn btn-large">Large button</button>
    </p>
    <p>
      <button type="button" class="btn btn-primary">Default button</button>
      <button type="button" class="btn">Default button</button>
    </p>
    <p>
      <button type="button" class="btn btn-small btn-primary">Small button</button>
      <button type="button" class="btn btn-small">Small button</button>
    </p>
    <p>
      <button type="button" class="btn btn-mini btn-primary">Mini button</button>
      <button type="button" class="btn btn-mini">Mini button</button>
    </p>
  </div>
<pre class="prettyprint linenums">&lt;p&gt;
  &lt;button class=&quot;btn btn-large btn-primary&quot; type=&quot;button&quot;&gt;Large button&lt;/button&gt;
  &lt;button class=&quot;btn btn-large&quot; type=&quot;button&quot;&gt;Large button&lt;/button&gt;
&lt;/p&gt;
&lt;p&gt;
  &lt;button class=&quot;btn btn-primary&quot; type=&quot;button&quot;&gt;Default button&lt;/button&gt;
  &lt;button class=&quot;btn&quot; type=&quot;button&quot;&gt;Default button&lt;/button&gt;
&lt;/p&gt;
&lt;p&gt;
  &lt;button class=&quot;btn btn-small btn-primary&quot; type=&quot;button&quot;&gt;Small button&lt;/button&gt;
  &lt;button class=&quot;btn btn-small&quot; type=&quot;button&quot;&gt;Small button&lt;/button&gt;
&lt;/p&gt;
&lt;p&gt;
  &lt;button class=&quot;btn btn-mini btn-primary&quot; type=&quot;button&quot;&gt;Mini button&lt;/button&gt;
  &lt;button class=&quot;btn btn-mini&quot; type=&quot;button&quot;&gt;Mini button&lt;/button&gt;
&lt;/p&gt;</pre>
<p>Create block level buttons—those that span the full width of a parent— by adding <code>.btn-block</code>.</p>
<div class="gantry-example">
  <div class="well" style="max-width: 400px; margin: 0 auto 10px;">
    <button type="button" class="btn btn-large btn-block btn-primary">Block level button</button>
    <button type="button" class="btn btn-large btn-block">Block level button</button>
  </div>
</div>
<pre class="prettyprint linenums">&lt;button class=&quot;btn btn-large btn-block btn-primary&quot; type=&quot;button&quot;&gt;Block level button&lt;/button&gt;
&lt;button class=&quot;btn btn-large btn-block&quot; type=&quot;button&quot;&gt;Block level button&lt;/button&gt;</pre>
  
  <h2>Disabled state</h2>
  <p>Make buttons look unclickable by fading them back 50%.</p>

<div class="gantry-width-container">
<div class="gantry-width-block gantry-width-50">
<div class="gantry-left">
  <h3>Anchor element</h3>
  <p>Add the <code>.disabled</code> class to <code>&lt;a&gt;</code> buttons.</p>
  <p class="gantry-example">
    <a href="#" class="btn btn-large btn-primary disabled">Primary link</a>
    <a href="#" class="btn btn-large disabled">Link</a>
  </p>
<pre class="prettyprint linenums">&lt;a href=&quot;#&quot; class=&quot;btn btn-large btn-primary disabled&quot;&gt;Primary link&lt;/a&gt;
&lt;a href=&quot;#&quot; class=&quot;btn btn-large disabled&quot;&gt;Link&lt;/a&gt;</pre><br />
  <p>
    <strong>Note:</strong>
    We use <code>.disabled</code> as a utility class here, similar to the common <code>.active</code> class, so no prefix is required.
  </p>
</div></div>

<div class="gantry-width-block gantry-width-50">
<div class="gantry-right">
  <h3>Button element</h3>
  <p>Add the <code>disabled</code> attribute to <code>&lt;button&gt;</code> buttons.</p>
  <p class="gantry-example">
    <button type="button" class="btn btn-large btn-primary disabled" disabled="disabled">Primary button</button>
    <button type="button" class="btn btn-large" disabled="">Button</button>
  </p>
<pre class="prettyprint linenums">&lt;button type=&quot;button&quot; class=&quot;btn btn-large btn-primary disabled&quot; disabled=&quot;disabled&quot;&gt;Primary button&lt;/button&gt;
&lt;button type=&quot;button&quot; class=&quot;btn btn-large&quot; disabled&gt;Button&lt;/button&gt;</pre>
</div></div></div>
<div class="clear"></div>


  <h2>One class, multiple tags</h2>
  <p>Use the <code>.btn</code> class on an <code>&lt;a&gt;</code>, <code>&lt;button&gt;</code>, or <code>&lt;input&gt;</code> element.</p>
  <form class="gantry-example">
    <a class="btn" href="">Link</a>
    <button class="btn" type="submit">Button</button>
    <input class="btn" type="button" value="Input">
    <input class="btn" type="submit" value="Submit">
  </form>
<pre class="prettyprint linenums">&lt;a class=&quot;btn&quot; href=&quot;&quot;&gt;Link&lt;/a&gt;
&lt;button class=&quot;btn&quot; type=&quot;submit&quot;&gt;Button&lt;/button&gt;
&lt;input class=&quot;btn&quot; type=&quot;button&quot; value=&quot;Input&quot;&gt;
&lt;input class=&quot;btn&quot; type=&quot;submit&quot; value=&quot;Submit&quot;&gt;</pre><br />
  <p>As a best practice, try to match the element for your context to ensure matching cross-browser rendering. If you have an <code>input</code>, use an <code>&lt;input type="submit"&gt;</code> for your button.</p>

</section>

<!-- Icons
================================================== -->
<h1>Icons</h1>
<h2>Font Awesome (v.4+)</h2>

<p>Font Awesome is a pictographic language of web-related actions which delivers over 300 icons. The Font Awesome webfont is created by <a href="http://twitter.com/davegandy">Dave Gandy</a> and licensed under <a href="http://scripts.sil.org/OFL">SIL OFL 1.1</a>. The code is licensed under <a href="http://opensource.org/licenses/mit-license.html">MIT License</a>.</p>

<p>Add <code>fa fa-ICON_NAME</code> to any element.</p>

<div class="gantry-example">
  <i class="fa fa-download"></i> Download
</div>		
<pre class="prettyprint linenums">&lt;i class="fa fa-ICON_NAME"&gt;&lt;/i&gt; ...
&lt;i class="fa fa-download"&gt;&lt;/i&gt; Download
</pre>

You can find the full examples of usage at <a href="http://fontawesome.io/icons/">Font Awesome - http://fontawesome.io/icons/</a>.