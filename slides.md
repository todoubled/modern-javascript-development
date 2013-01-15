Modern JavaScript Development

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
- CSS preprocessing - Stylus, Less, Sass
- JS preprocessing - CoffeeScript, ClojureScript, Dart
- Integration testing - Casper.js, Zombie.js, Selenium
- Unit testing - Jasmine.js, Mocha + Chai, QUnit
- Dependency management - Browserify.js, stitch, Require.js
- File watching - watchman, wach, guard
- Test running - Testem, grunt, make
- API mocking - Express.js, sinatra, flatiron
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
