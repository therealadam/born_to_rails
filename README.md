# Adam Keys' lovely app generator

...because I got tired of remembering the options to `rails new`.

What you get:

* rspec
* pry and friends (via jazzhands), rack-mini-profiler, better_errors, foreman
* Twitter Bootstrap, vendor'd
* Pow setup
* A lovely error message if something went sideways (note: will be obscured by
  `rails new` running `bundle` _after_ the template runs)

## Usage

    $ rails new your_awesome_app -m
    https://github.com/therealadam/born_to_rails/born_to_rails.rb
