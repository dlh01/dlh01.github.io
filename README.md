

# Setup

* Clone this repository
* Install the [GitHub Pages Gem](https://github.com/github/pages-gem) to ensure the local environment matches production
    * `gem install bundler`
    * `bundle install`
* Initialize submodules to get Inuit


# Other requirements

* Ruby 1.9.3
* Sass 3.2.10


# Running the server locally

* `bundle exec jekyll serve` for an auto-regenerating server
* `cd css/` and `./watch` for auto-generating styles. The `watch` script comes from the [inuit.css web template](https://github.com/csswizardry/inuit.css-web-template).


# Keeping dependencies up to date

* `bundle update`
* `git submodule foreach git pull origin master`


# Notes

* The included Modernizr is a custom build, not the HTML5 Boilerplate default build
* An encoded version of the contact email address is in `_includes/email_address.html`

# References

* <https://help.github.com/articles/using-jekyll-with-pages>
