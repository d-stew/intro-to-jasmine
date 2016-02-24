Initializing Jasmine

  jasmine init

spec -- Where you should put all your test files.

  spec/leap_year_spec.js

lib -- Where your file to test lives

  lib/leap_year.js

You should always give your spec file the same name as your .js file, but with a spec appended to it.

miles-spec.js:

  var miles = require('../lib/miles');

  describe('Miles', function(){
    it('is our master plan')
  })

miles.js

  module.exports = {

  }
