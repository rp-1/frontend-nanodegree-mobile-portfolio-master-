
 href="#frontend-nanodegree-mobile-portfolio-master" aria-hidden="true"><span class="octicon octicon-link"></span></a>frontend-nanodegree-mobile-portfolio-master</h1>

<p>This is a project for the Udacity front end nano-degree program designed to teach the theory and techniques behind optimizing
web pages for quick loading.</p>

<p>There are two main goals: First, tweak the main index.html file so that its Page Speed Insight score is higher than 90. 
Second, optimize the pizza.html doc and its assoicated javascript files so that pizza.html operates at a smooth 60 fps.</p>

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

</div>

<a href="#jump-to-line" rel="facebox[.linejump]" data-hotkey="l" style="display:none">Jump to Line</a>
<div id="jump-to-line" style="display:none">
  <form accept-charset="UTF-8" action="" class="js-jump-to-line-form" method="get"><div style="margin:0;padding:0;display:inline"><input name="utf8" type="hidden" value="&#x2713;" /></div>
    <input class="linejump-input js-jump-to-line-field" type="text" placeholder="Jump to line&hellip;" autofocus>
    <button type="submit" class="btn">Go</button>
</form></div>

        </div>

      </div><!-- /.repo-container -->
      <div class="modal-backdrop"></div>
    </div><!-- /.container -->
  </div><!-- /.site -->


    </div><!-- /.wrapper -->

      <div class="container">
  <div class="site-footer" role="contentinfo">
    <ul class="site-footer-links right">
        <li><a href="https://status.github.com/" data-ga-click="Footer, go to status, text:status">Status</a></li>
      <li><a href="https://developer.github.com" data-ga-click="Footer, go to api, text:api">API</a></li>
      <li><a href="https://training.github.com" data-ga-click="Footer, go to training, text:training">Training</a></li>
      <li><a href="https://shop.github.com" data-ga-click="Footer, go to shop, text:shop">Shop</a></li>
        <li><a href="https://github.com/blog" data-ga-click="Footer, go to blog, text:blog">Blog</a></li>
        <li><a href="https://github.com/about" data-ga-click="Footer, go to about, text:about">About</a></li>

    </ul>

    <a href="https://github.com" aria-label="Homepage">
      <span class="mega-octicon octicon-mark-github" title="GitHub"></span>
</a>
    <ul class="site-footer-links">
      <li>&copy; 2015 <span title="0.05897s from github-fe129-cp1-prd.iad.github.net">GitHub</span>, Inc.</li>
        <li><a href="https://github.com/site/terms" data-ga-click="Footer, go to terms, text:terms">Terms</a></li>
        <li><a href="https://github.com/site/privacy" data-ga-click="Footer, go to privacy, text:privacy">Privacy</a></li>
        <li><a href="https://github.com/security" data-ga-click="Footer, go to security, text:security">Security</a></li>
        <li><a href="https://github.com/contact" data-ga-click="Footer, go to contact, text:contact">Contact</a></li>
    </ul>
  </div>
</div>


    <div class="fullscreen-overlay js-fullscreen-overlay" id="fullscreen_overlay">
  <div class="fullscreen-container js-suggester-container">
    <div class="textarea-wrap">
      <textarea name="fullscreen-contents" id="fullscreen-contents" class="fullscreen-contents js-fullscreen-contents" placeholder=""></textarea>
      <div class="suggester-container">
        <div class="suggester fullscreen-suggester js-suggester js-navigation-container"></div>
      </div>
    </div>
  </div>
  <div class="fullscreen-sidebar">
    <a href="#" class="exit-fullscreen js-exit-fullscreen tooltipped tooltipped-w" aria-label="Exit Zen Mode">
      <span class="mega-octicon octicon-screen-normal"></span>
    </a>
    <a href="#" class="theme-switcher js-theme-switcher tooltipped tooltipped-w"
      aria-label="Switch themes">
      <span class="octicon octicon-color-mode"></span>
    </a>
  </div>
</div>



    
    

    <div id="ajax-error-message" class="flash flash-error">
      <span class="octicon octicon-alert"></span>
      <a href="#" class="octicon octicon-x flash-close js-ajax-error-dismiss" aria-label="Dismiss error"></a>
      Something went wrong with that request. Please try again.
    </div>


      <script crossorigin="anonymous" src="https://assets-cdn.github.com/assets/frameworks-2c8ae50712a47d2b83d740cb875d55cdbbb3fdbccf303951cc6b7e63731e0c38.js"></script>
      <script async="async" crossorigin="anonymous" src="https://assets-cdn.github.com/assets/github-6ef28f80a929515cb3e7e424363db63629a966b42acdf1666c433dc4b46de3db.js"></script>
      
      

      <div class="js-socket-channel" data-channel="test:rp-1"></div>

  </body>
</html>

