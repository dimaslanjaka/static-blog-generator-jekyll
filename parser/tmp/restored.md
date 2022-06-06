<h2 id="shortcode-css" tabindex="-1"><a class="header-anchor" href="#shortcode-css">Shortcode CSS</a></h2>
<p>From Local Directory</p>
<pre><code class="language-html">&lt;style&gt;/*STYLE CSS SHORTCODES*/
.just-test {
  display: block;
}&lt;/style&gt;
</code></pre>
<p>From Root/cwd Directory</p>
<pre><code class="language-html">&lt;style&gt;/*STYLE CSS SHORTCODES*/
.just-test {
  display: block;
}&lt;/style&gt;
</code></pre>
<h2 id="shortcode-js" tabindex="-1"><a class="header-anchor" href="#shortcode-js">Shortcode JS</a></h2>
<p>From Local Directory</p>
<pre><code class="language-html">&lt;script&gt;/* script js shortcode */
console.log('hello world');
&lt;/script&gt;
</code></pre>
<p>From Root/cwd Directory</p>
<pre><code class="language-html">&lt;script&gt;/* script js shortcode */
console.log('hello world');
&lt;/script&gt;
</code></pre>
<h2 id="shortcode-include" tabindex="-1"><a class="header-anchor" href="#shortcode-include">Shortcode Include</a></h2>
<p>From Local Directory</p>
<pre><code class="language-html">&lt;p&gt;included html&lt;/p&gt;
</code></pre>
<p>From Root/cwd Directory</p>
<pre><code class="language-html">&lt;p&gt;included html&lt;/p&gt;
</code></pre>
<h2 id="shortcode-extract-text" tabindex="-1"><a class="header-anchor" href="#shortcode-extract-text">Shortcode extract-text</a></h2>
<p>From Local Directory</p>
<pre><code class="language-html">include extract text
</code></pre>
<p>From Root/cwd Directory</p>
<pre><code class="language-html">include extract text
</code></pre>
<h2 id="shortcode-youtube" tabindex="-1"><a class="header-anchor" href="#shortcode-youtube">Shortcode Youtube</a></h2>
<p>By default youtube tag will output video</p>
<pre><code class="language-html">&lt;div class=&quot;video-container&quot;&gt;
  &lt;iframe src=&quot;https://www.youtube.com/embed/4_oXjfgQ2G4&quot; frameborder=&quot;0&quot; allow=&quot;accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture&quot; loading=&quot;lazy&quot; allowfullscreen=&quot;true&quot;&gt;&lt;/iframe&gt;
&lt;/div&gt;
</code></pre>
<p>Manually set type <code>video</code></p>
<pre><code class="language-html">&lt;div class=&quot;video-container&quot;&gt;
  &lt;iframe src=&quot;https://www.youtube.com/embed/4_oXjfgQ2G4&quot; frameborder=&quot;0&quot; allow=&quot;accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture&quot; loading=&quot;lazy&quot; allowfullscreen=&quot;true&quot;&gt;&lt;/iframe&gt;
&lt;/div&gt;
</code></pre>
<p>Manually set type <code>playlist</code></p>
<pre><code class="language-html">&lt;div class=&quot;video-container&quot;&gt;
  &lt;iframe src=&quot;https://www.youtube.com/embed/videoseries?list=RDGMEMQ1dJ7wXfLlqCjwV0xfSNbA&quot; frameborder=&quot;0&quot; allow=&quot;accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture&quot; loading=&quot;lazy&quot; allowfullscreen=&quot;true&quot;&gt;&lt;/iframe&gt;
&lt;/div&gt;
</code></pre>
<h2 id="shortcode-now" tabindex="-1"><a class="header-anchor" href="#shortcode-now">Shortcode now()</a></h2>
<pre><code class="language-html">6/6/2022, 8:01:40 AM
</code></pre>
