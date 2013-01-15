Modern JavaScript Development

<small>@toddjlarsen</small>

<small>[http://github.com/todoubled](http://github.com/todoubled/modern-javascript-development)</small>

<small>Groupon</small>

---


# Respect
- `<script src="/hairball.js"></script>`
- JavaScript sprinkles
- "Tools"
---


# Changing Times
- Biz logic moving towards client
- 1st Class Citizen
- Multiple global platforms
---


# New Perspective
- Guest App vs. Host App
- Input vs. Output
- Embedded Client Apps
---


# Why untangle client and server?
- Upfront thought about data input/output
- Reusability & rigor
- Embeddable on any host app/platform
---


# We need new tools
- Feature parity+
- No compromises
- Reasonable maturity
---


# What tools exist?
- CSS preprocessing - [Stylus](http://learnboost.github.com/stylus/), [Less](http://lesscss.org/), [Sass](http://sass-lang.com/)
- JS preprocessing - [CoffeeScript](http://coffeescript.org/), [ClojureScript](https://github.com/clojure/clojurescript), [Dart](http://www.dartlang.org/)
- Integration testing - [Casper.js](http://casperjs.org/), [Zombie.js](http://zombie.labnotes.org/), [Selenium](http://seleniumhq.org/)
- Unit testing - [Jasmine.js](http://pivotal.github.com/jasmine/), [Mocha](http://visionmedia.github.com/mocha/) + [Chai](http://chaijs.com/), [QUnit](http://qunitjs.com/)
- Dependency management - [Browserify.js](http://browserify.org/), [stitch](https://github.com/sstephenson/stitch), [Require.js](http://requirejs.org/)
- File watching - [watchman](https://github.com/dfjones/watchman), [wach](https://github.com/quackingduck/wach), [guard](https://github.com/guard/guard)
- Test running - [Testem](https://github.com/airportyh/testem), [grunt](http://gruntjs.com/), make
- API mocking - [Express.js](http://expressjs.com/), [sinatra](http://www.sinatrarb.com/), [flatiron](http://flatironjs.org/)
---


# What tools do we need?
- Task System
- Testing
- Templating & Asset compilation
- Documentation
- Deployment
- Mocks
- Concatenation/minification
---


# What tools do we want?
- Dependency management
- Auto compiling build
- Auto running tests
- Auto refreshing browser
- Support for multiple versions of runtime dependencies
- Easy A/B testing
---


# JIFASNIF
- 1 scripting language for tools & product
- Unix philosophy
- Rich community
---


# Harness
- Tools for building JavaScript apps
- Production tested
- Pick and choose
---


# Philosophy
- Unix
- Principle of Least Surprise
- Get Things Done
---


# Features
- `make` task system
- Auto-compiling build on file change
- Auto-running Jasmine unit tests in all browsers
- Auto-refreshing browser on file change
- Headless integration tests with Casper.js
- Mustache.js templating
- CoffeeScript and Stylus preprocessing
---


# More Features
- `groc` documentation
- Filesystem deployment
- Express.js mock API server
- CommonJS dependency management with `browserify`
- Support multiple versions of runtime deps via query string
- Test A/B variants via query string
---


# HTML?
- Vanilla + mustache
- Tiny markup sets
- Attr-less + presenters

<script src="https://gist.github.com/4536762.js?file=html.mustache"></script>
---


# CSS?
- Stylus modules
- Whitespace significant
- Gradual adoption

<script src="https://gist.github.com/4536762.js?file=css.styl"></script>
---


# JS?
- CommonJS modules
- Explicit public interface
- Explicit dependency graph

<script src="https://gist.github.com/4536762.js?file=search-error.coffee"></script>
<script src="https://gist.github.com/4536762.js?file=callbacks.coffee"></script>
---

# Try Harness
##[http://github.com/todoubled/harness](http://github.com/todoubled/harness)
##[http://toddjlarsen.com/harness](http://toddjlarsen.com/harness)

@toddjlarsen

github.com/todoubled
