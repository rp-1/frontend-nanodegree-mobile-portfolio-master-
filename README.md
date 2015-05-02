<h1>frontend-nanodegree-mobile-portfolio-master</h1>

<p>This is a project for the Udacity front end nano-degree program designed to teach the theory and techniques behind optimizing
web pages for quick loading.</p>

<p>There are two main goals: First, tweak the main index.html file so that its Page Speed Insight score is higher than 90. 
Second, optimize the pizza.html doc and its assoicated javascript files so that pizza.html operates at a smooth 60 fps.</p>

<p>To view project, first load index.html. Then click the pizzeria link, which will take you to pizza.html, where you will see the optimized page live.<p>

<h1>
<a id="user-content-indexhtml-changes" class="anchor" href="#indexhtml-changes" aria-hidden="true"><span class="octicon octicon-link"></span></a>Index.html changes</h1>

<p>The following changes were made to Index.html, which resulted in a Page Speed score of 94 mobil, 95 desktop.</p>

<h4>
<a id="user-content-1-minified-stylecss" class="anchor" href="#1-minified-stylecss" aria-hidden="true"><span class="octicon octicon-link"></span></a>1) Minified style.css</h4>

<h4>
<a id="user-content-2-inlined-stylecss" class="anchor" href="#2-inlined-stylecss" aria-hidden="true"><span class="octicon octicon-link"></span></a>2) Inlined style.css</h4>

<h4>
<a id="user-content-3-made-google-analytics-script-async-so-it-would-not-block-parsing-and-rendering" class="anchor" href="#3-made-google-analytics-script-async-so-it-would-not-block-parsing-and-rendering" aria-hidden="true"><span class="octicon octicon-link"></span></a>3) Made google analytics script async so it would not block parsing and rendering</h4>

<h4>
<a id="user-content-4-reduced-24-mb-thumbnail-pic-to-under-20k-in-photoshop-made-file-local" class="anchor" href="#4-reduced-24-mb-thumbnail-pic-to-under-20k-in-photoshop-made-file-local" aria-hidden="true"><span class="octicon octicon-link"></span></a>4) Reduced 2.4 mb thumbnail pic to under 20k in photoshop. Made file local.</h4>

<h4>
<a id="user-content-5-removed-call-to-remote-google-font-not-worth-the-speed-hit" class="anchor" href="#5-removed-call-to-remote-google-font-not-worth-the-speed-hit" aria-hidden="true"><span class="octicon octicon-link"></span></a>5) Removed call to remote google font. Not worth the speed hit.</h4>

<h4>
<a id="user-content-6-constrained-the-include-of-printcss-with-mediaprint-since-that-file-is-unnecessary-here" class="anchor" href="#6-constrained-the-include-of-printcss-with-mediaprint-since-that-file-is-unnecessary-here" aria-hidden="true"><span class="octicon octicon-link"></span></a>6) Constrained the include of print.css with media="print" since that file is unnecessary here</h4>

<h1>
<a id="user-content-main-pizza-page----pizzahtml" class="anchor" href="#main-pizza-page----pizzahtml" aria-hidden="true"><span class="octicon octicon-link"></span></a>Main pizza page -- pizza.html</h1>

<h4>
<a id="user-content-1-optimized-main-image-as-well-as-main-pizza-illustration-graphic-for-faster-load" class="anchor" href="#1-optimized-main-image-as-well-as-main-pizza-illustration-graphic-for-faster-load" aria-hidden="true"><span class="octicon octicon-link"></span></a>1) Optimized main image, as well as main pizza illustration graphic for faster load</h4>

<h1>
<a id="user-content-mainjs" class="anchor" href="#mainjs" aria-hidden="true"><span class="octicon octicon-link"></span></a>main.js</h1>

<h4>
<a id="user-content-1-removed-routines-and-statements-from-for-loops-that-could-accomplish-same-thing-outside-loop-huge-performance-bump-this-technique-was-used-in-both-the-main-update-routine-called-when-a-scroll-event-occurred-and-also-when-pizza-size-slider-called-for-a-refresh-with-new-pizza-sizes" class="anchor" href="#1-removed-routines-and-statements-from-for-loops-that-could-accomplish-same-thing-outside-loop-huge-performance-bump-this-technique-was-used-in-both-the-main-update-routine-called-when-a-scroll-event-occurred-and-also-when-pizza-size-slider-called-for-a-refresh-with-new-pizza-sizes" aria-hidden="true"><span class="octicon octicon-link"></span></a>1) Removed routines and statements from for loops that could accomplish same thing OUTSIDE loop. Huge performance bump. This technique was used in both the main update routine (called when a scroll event occurred) and also when pizza size slider called for a refresh with new pizza sizes.</h4>

<h4>
<a id="user-content-2-greatly-reduced-number-of-pizzas-created-by-creating-only-the-number-that-would-be-appearing-on-screen-now-we-use-the-browser-window-to-determine-just-how-many-pizzas-will-be-displayed" class="anchor" href="#2-greatly-reduced-number-of-pizzas-created-by-creating-only-the-number-that-would-be-appearing-on-screen-now-we-use-the-browser-window-to-determine-just-how-many-pizzas-will-be-displayed" aria-hidden="true"><span class="octicon octicon-link"></span></a>2) Greatly reduced number of pizzas created by creating only the number that would be appearing on screen. Now, we use the browser window to determine just how many pizzas will be displayed.</h4>

<h4>
<a id="user-content-3-further-enhanced-speedy-loading-by-replacing-slower-calls-like-queryselectorall-with-faster-calls-like-getelementsbyclassname" class="anchor" href="#3-further-enhanced-speedy-loading-by-replacing-slower-calls-like-queryselectorall-with-faster-calls-like-getelementsbyclassname" aria-hidden="true"><span class="octicon octicon-link"></span></a>3) Further enhanced speedy loading by replacing slower calls like querySelectorAll with faster calls like getElementsByClassName</h4>
</article>
  </div>
