# Most-gulp-use
List of most useful plugins for Gulp
<p>##HTML&amp;CSS
<a href="https://github.com/postcss/autoprefixer">autoprefixer</a> - parse CSS and add vendor prefixes to rules by Can I Use.</p>
<p><a href="https://github.com/BrowserSync/gulp-browser-sync">gulp-browser-sync</a> - keep multiple browsers &amp; devices in sync when building websites.</p>
<p><a href="https://github.com/jonkemp/gulp-useref">gulp-useref</a> - parse build blocks in HTML files to replace references to non-optimized scripts or stylesheets.</p>
<p><a href="https://github.com/alexshk/gulp-email-design">gulp-email-design</a> - a workflow for designing and testing HTML email templates.</p>
<p><a href="https://github.com/ben-eb/gulp-uncss">gulp-uncss</a> - remove unused CSS from your projects.</p>
<p><a href="https://github.com/ben-eb/gulp-csso">gulp-csso</a> - very cool CSS minificator. In addition, there are many CSS optimizers and <a href="http://goalsmashers.github.io/css-minification-benchmark/" rel="nofollow">benchmark tests</a> (<a href="https://github.com/GoalSmashers/css-minification-benchmark">GitHub</a>) for them. But recently I saw most powerful <a href="https://github.com/frankmarineau/shorthand">Shorthand</a> utility and <a href="https://github.com/kevva/gulp-shorthand">gulp-shorthand</a>, which does folowing:</p>
<pre><code>a {
	font-family: Arial;
	font-style: italic;
	font-size: 14px;
	line-height: 18px;
	font-weight: bold;
	background-image: url('example.png');
	background-color: red;
	background-size: cover;
	background-repeat: no-repeat;
}

=&gt;

a {
  font: italic bold 14px/18px Arial;
  background: red url('example.png') no-repeat / cover;
}
</code></pre>
<p><a href="https://github.com/jonschlinkert/gulp-htmlmin">gulp-htmlmin</a> - neat HTML minificator.</p>
<p><a href="https://github.com/koistya/gulp-csscomb">gulp-csscomb</a> - refines the structure of your CSS.</p>
<p><a href="https://www.npmjs.com/package/gulp-csslint" rel="nofollow">gulp-csslint</a> - CSS linter.</p>
<p><a href="https://github.com/bezoerb/gulp-htmlhint">gulp-htmlhint</a> - HTML validator using <a href="https://github.com/yaniswang/HTMLHint">htmlhint</a></p>
<p><a href="https://github.com/yvanavermaet/gulp-htmllint">gulp-htmllint</a> - HTML validator using <a href="https://github.com/htmllint/htmllint/">htmllint</a></p>
<p><a href="https://www.npmjs.com/package/gulp-processhtml" rel="nofollow">gulp-processhtml</a> - Process html files at build time to modify them as you wish.</p>
<p><a href="https://github.com/sindresorhus/gulp-myth">gulp-myth</a> - Postprocessor that polyfills CSS</p>
<p>##JavaScript
<a href="https://github.com/azproduction/gulp-autopolyfiller">gulp-autopolyfiller</a> - precise polyfills. This is like Autoprefixer, but for JavaScript polyfills.</p>
<p><a href="https://github.com/babel/gulp-babel">gulp-babel</a> - transpiler for writing next generation JavaScript.</p>
<p><a href="https://www.npmjs.com/package/gulp-jsfmt" rel="nofollow">gulp-jsfmt</a> - for formatting, searching, and rewriting JavaScript.</p>
<p><a href="https://github.com/jscs-dev/gulp-jscs">gulp-jscs</a> - Check JavaScript code style with <a href="https://github.com/jscs-dev/node-jscs">jscs</a>.</p>
<p><a href="https://github.com/doctyper/gulp-modernizr">gulp-modernizr</a> - build out a lean, mean Modernizr machine.</p>
<p><a href="https://github.com/gimm/gulp-express">gulp-express</a> — start (and supervise) an Express.js web server using, works well with socket.io</p>
<p><a href="https://github.com/robinthrift/gulp-requirejs">gulp-requirejs</a> and <a href="https://github.com/deepak1556/gulp-browserify">gulp-browserify</a> - optimize the work with RequireJS and Browserify respectively.</p>
<p><a href="https://github.com/sindresorhus/gulp-plato">gulp-plato</a> - generate static analysis reports.</p>
<p><a href="https://github.com/alexeyraspopov/gulp-complexity">gulp-complexity</a> - evaluates code maintainability using Halstead and Cyclomatic metrics.</p>
<p><a href="https://github.com/kirjs/gulp-fixmyjs">fixmyjs</a> - automatically fix silly lint errors with help of <a href="http://jshint.com/" rel="nofollow">JSHint</a> (<a href="https://github.com/spalger/gulp-jshint">gulp-jshint</a>).</p>
<p><a href="https://github.com/yannickcr/gulp-jscpd">gulp-jscpd</a> — copy/paste detector for programming source code.</p>
<p><a href="https://github.com/Semigradsky/gulp-buddy.js">gulp-buddy.js</a> - magic number detection for javascript.</p>
<p><a href="https://github.com/rogeriopvl/gulp-jsonlint">gulp-jsonlint</a>  - JSON validator.</p>
<p><a href="https://github.com/terinjokes/gulp-uglify">gulp-uglify</a> - JavaScript compressor.</p>
<p><a href="https://github.com/wearefractal/gulp-concat">gulp-concat</a> - concatenate files.</p>
<p><a href="https://github.com/emgeee/gulp-standard">gulp-standard</a> - Check JavaScript code style with <a href="https://github.com/feross/standard">Standard</a>.</p>
<p>###Unit Tests</p>
<ul>
<li><a href="https://github.com/kjvalencik/gulp-nodeunit">gulp-nodeunit</a></li>
<li><a href="https://github.com/sindresorhus/gulp-jasmine">gulp-jasmine</a></li>
<li><a href="https://github.com/jonkemp/gulp-qunit">gulp-qunit</a></li>
<li><a href="https://github.com/sindresorhus/gulp-mocha">gulp-mocha</a></li>
<li><a href="https://github.com/karma-runner/gulp-karma">gulp-karma</a></li>
</ul>
<p>##Graphics
<a href="https://github.com/wakayama-io/gulpicon/">gulpicon</a> - mystical CSS icon solution.</p>
<p><a href="https://github.com/nfroidure/gulp-iconfont">gulp-iconfont</a> - SVG to webfont converter.</p>
<p><a href="https://github.com/mahnunchik/gulp-responsive">gulp-responsive</a> - produce images at different sizes for responsive websites.</p>
<p><a href="https://github.com/rizalp/gulp-sharp">gulp-sharp</a> - fastest module for work JPEG, PNG, WebP and TIFF images.</p>
<p><a href="https://github.com/w0rm/gulp-svgstore">gulp-svgstore</a> - merge SVGs from a folder.</p>
<p><a href="https://github.com/akoenig/imacss">gulp-imacss</a> - application and library that transforms image files to data URIs.</p>
<p><a href="https://github.com/sindresorhus/gulp-imagemin">gulp-imagemin</a> и <a href="https://github.com/creativeaura/gulp-tinypng">gulp-tinypng</a> or fimage compression.</p>
<p><a href="https://github.com/otouto/gulp-spritesmith">gulp-spritesmith</a> - converting a set of images into a spritesheet and corresponding CSS variables.</p>
<p>##Others</p>
<p><a href="https://github.com/gratimax/gulp-grunt">gulp-grunt</a> - able to run Grunt tasks from Gulp.</p>
<p><a href="https://github.com/floatdrop/gulp-watch">gulp-watch</a> — run tasks whenever watched files change.</p>
<p><a href="https://github.com/mikaelbr/gulp-notify">gulp-notify</a> - automatic error messages in system notifications center when Gulp tasks fail.</p>
<p><a href="https://github.com/stevelacy/gulp-git">gulp-git</a> - able to use Git commands.</p>
<p><a href="https://github.com/jsBoot/gulp-jsdoc">gulp-jsdoc</a> - generate JavaScript documentation by running JSDoc3.</p>
<p><a href="https://github.com/sindresorhus/gulp-rev">gulp-rev</a> - static file asset revisioning through content hashing.</p>
<p><a href="https://github.com/stevelacy/gulp-bump">gulp-bump</a> - increments versions in package JSON and <a href="https://github.com/tounano/gulp-update">gulp-update</a>, which automatically updates packages.</p>
<p><a href="https://github.com/ck86/main-bower-files">main-bower-files</a> - inject Bower packages.</p>
<p><a href="https://github.com/hemanth/gulp-removelogs">gulp-removelogs</a> - remove console logging statements.</p>
<p><a href="https://github.com/jas/gulp-preprocess">gulp-preprocess</a> - preprocess files based off environment configuration.</p>
<p><a href="https://github.com/hughsk/gulp-duration">gulp-duration</a> — displays the elapsed execution time of Gulp tasks.</p>
<p><a href="https://github.com/sindresorhus/gulp-changed">gulp-changed</a> and <a href="https://www.npmjs.com/package/gulp-newer" rel="nofollow">gulp-newer</a> — run Gulp tasks with only those source files modified since the last successful run.</p>
<p><a href="https://github.com/avevlad/gulp-connect">gulp-connect</a> - simple static web server.</p>
<p><a href="https://github.com/sun-zheng-an/gulp-shell">gulp-shell</a> - run Shell commands.</p>
<p><a href="https://github.com/teambition/gulp-ssh">gulp-ssh</a> - provides the ability to connect via SSH and SFTP.</p>
<p><a href="https://www.npmjs.com/package/gulp-zip" rel="nofollow">gulp-zip</a> - compress files and folders..</p>
<p><a href="https://github.com/peter-vilja/gulp-clean">gulp-clean</a> and <a href="https://github.com/klaascuvelier/gulp-copy">gulp-copy</a> - respectively remove and copy sources.</p>
<p><a href="https://www.npmjs.com/package/gulp-replace" rel="nofollow">gulp-replace</a> - Search and replace strings in text files.</p>
<p><a href="https://github.com/Metrime/gulp-filesize">gulp-filesize</a> - displays sizes of files in a readable format.</p>
<p><a href="https://github.com/gulpjs/gulp-util">gulp-util</a> - utilities for developing Gulp plugins.</p>
<p><a href="https://github.com/floatdrop/gulp-plumber">gulp-plumber</a> - prevents pipe breaking caused by errors from gulp plugins</p>
<p><a href="https://github.com/colynb/gulp-data">gulp-data</a> - Generate a data object from a variety of sources: json, front-matter, database, anything. Compatible with many plugins including <code>gulp-jade</code> and <code>gulp-swig</code></p>
<p><a href="https://github.com/crissdev/gulp-props">gulp-props</a> - Convert Java <code>.properties</code> files to JSON</p>
<p><a href="https://github.com/pgilad/gulp-todo">gulp-todo</a> - Generate a TODO.md from todos &amp; fixmes in your code</p>
<p><a href="https://github.com/sindresorhus/gulp-markdown">gulp-markdown</a> - Markdown to HTML with <a href="https://github.com/chjj/marked">marked</a></p>
<p><a href="https://github.com/shinnn/gulp-gh-pages">gulp-gh-pages</a> - Publish contents to <a href="https://pages.github.com/">Github pages</a></p>
<p><a href="https://github.com/jackfranklin/gulp-load-plugins">gulp-load-plugins</a> - Automatically load any gulp plugins in your package.json</p>
<p><a href="https://github.com/floridoo/gulp-sourcemaps">gulp-sourcemaps</a> - Source map support</p>
<p>##Compilers</p>
<ul>
<li><a href="https://github.com/plus3network/gulp-less">gulp-less</a> - LESS in CSS.</li>
<li><a href="https://github.com/dlmanning/gulp-sass">gulp-sass</a> - SASS/SCSS in СSS.</li>
<li><a href="https://github.com/appleboy/gulp-compass">gulp-compass</a> - SASS with Compass in CSS.</li>
<li><a href="https://github.com/LearnBoost/stylus">gulp-stylus</a> - Stylus in CSS.</li>
<li><a href="https://github.com/wearefractal/gulp-coffee">gulp-coffee</a> - CoffeeScript in JavaScript.</li>
<li><a href="https://github.com/ivogabe/gulp-typescript">gulp-typescript</a> - TypeScript in JavaScript.</li>
<li><a href="https://github.com/phated/gulp-jade">gulp-jade</a> - Jade in HTML.</li>
<li><a href="https://github.com/lazd/gulp-handlebars">gulp-handlebars</a> - Handlebars templates in JST.</li>
<li><a href="https://github.com/rdmurphy/gulp-jst">gulp-jst</a> - Underscore templates in JST.</li>
<li><a href="https://github.com/sindresorhus/gulp-react">gulp-react</a> - Facebook React's JSX templates in JST.</li>
<li><a href="https://github.com/sindresorhus/gulp-nunjucks">gulp-nunjucks</a> - Nunjucks templates in JST.</li>
<li><a href="https://github.com/sindresorhus/gulp-dust">gulp-dustjs</a> - Dust templates in JST.</li>
<li><a href="https://github.com/miickel/gulp-angular-templatecache">gulp-angular-templatecache</a> - AngularJS templates in JST.</li>
<li><a href="https://github.com/e-jigsaw/gulp-riot">gulp-riot</a> - RiotJS templates in JavaScript.</li>
<li><a href="https://github.com/colynb/gulp-swig">gulp-swig</a> - Compile swig templates.</li>
</ul>
<p>##Finally</p>
<ul>
<li><a href="https://github.com/addyosmani/psi">psi</a> - PageSpeed Insights with reporting.</li>
<li><a href="https://github.com/addyosmani/tmi">tmi</a> -  TMI (Too Many Images) - discover your image weight on the web.</li>
<li><a href="https://ngrok.com/" rel="nofollow">ngrok</a> - Introspected tunnels to localhost.</li>
<li><a href="https://github.com/sindresorhus/pageres">pageres</a> - responsive website screenshots.</li>
<li><a href="https://github.com/tkellen/node-matchdep">matchdep</a> -  filter npm module dependencies.</li>
<li>Maybe some automatization methods you want to use directly in the editor, so look at the <a href="http://ipestov.com/the-best-plugins-for-sublime-text/" rel="nofollow">The Best Plugins for Sublime Text</a>.</li>
</ul>
