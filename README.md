# kickstrap_rails for Rails 3.1+

Just a little gem that packages up [kickstrap](http://ajkochanowicz.github.com/Kickstrap/index.html) as a gem so you can easily add it to your Rails apps using the asset pipeline.

## Installing

Add to your `Gemfile`:

    gem "kickstrap_rails", :git => "https://github.com/bharthur/kickstrap_rails.git"

Add to your `application.js`:

    //= require kickstrap

Add to your `application.css`:

    *= require kickstrap

Also you can select theme:

    *= require kickstrap/themes/simplex
    
To include responsive design, add to your `application.css`:

		*= require responsive

Then just [use kickstrap as normal](http://ajkochanowicz.github.com/Kickstrap/index.html).
