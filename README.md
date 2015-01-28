# Resources
## A list of resources for developers

### Console/Terminal
- nano <filename> => opens nano (terminal's text editor) and creates/edits file in console
- You can put universal Rails configuration options in `~.railsrc`.  I have `--skip-test-unit` (since I use RSpec) and `-d postgresql` (though you can also do `-d mysql2`).

### Sublime text
- command-u => soft undo (undo last action, ie click)

### Image Resources
- Aggregate of open source stock and background photos from other sites: http://www.pexels.com/
- More open source stock and background photos: https://unsplash.com/

### Useful Gems
- [awesome_print](https://github.com/michaeldv/awesome_print): get colorized and well-formatted object output.  If you want to use awesome_print by default in all irb sessions (including `rails c`), `touch ~/.irbrc` and put in it
```ruby
  require "awesome_print"
  AwesomePrint.irb!
```
- [reform](https://github.com/apotonick/reform): abstract your validations and get rid of clunky processing of nested forms
- [bower_rails](https://github.com/42dev/bower-rails): put bower into your Rails asset pipeline by calling `rake bower:install`.  I like to put the `assets_path 'assets/javascripts'` option at the top of my Bowerfile.
- [jquery-turbolinks](https://github.com/kossnocorp/jquery.turbolinks): any JS that depends on document.ready will break if you use Turbolinks (which is enabled by default).  This gem offers a global fix.

### Data Sources
- List of states and abbreviations in various formats: http://statetable.com/
