# jekyll-theme-bootstrap

Welcome to your new jekyll-theme-bootstrap based. You'll find everything you need in order to built a website with a portfolio with Jekyll.

This template is based on bootstrap (ccs, javascript) and use jQuery (javascript).
This theme embed a fully functional website with a few files and code.

To experiment with this code, add some sample content and run `bundle exec jekyll serve` – this directory is setup just like a Jekyll site!

## Installation

Add this line to your Jekyll site's `Gemfile`:

```ruby
gem "jekyll-theme-bootstrap"
```

And add this line to your Jekyll site's `_config.yml`:

```yaml
theme: jekyll-theme-bootstrap
```

And then execute:

    $ bundle

Or install it yourself as:

    $ gem install jekyll-theme-bootstrap

## Usage

There are 2 defaults layouts :

- home, used in the home page only
- post, used for all posts

You can replace the build-in images (`assets/img/`) by your own.

## Development

To set up your environment to develop this theme, run `bundle install`.

Your theme is setup just like a normal Jekyll site! To test your theme, run `bundle exec jekyll serve` and open your browser at `http://localhost:4000`. This starts a Jekyll server using your theme. Add pages, documents, data, etc. like normal to test your theme's contents. As you make modifications to your theme and to your content, your site will regenerate and you should see the changes in the browser after a refresh, just like normal.

When your theme is released, only the files in `_layouts`, `_includes`, `_sass` and `assets` tracked with Git will be bundled.
To add a custom directory to your theme-gem, please edit the regexp in `jekyll-theme-bootstrap.gemspec` accordingly.

## License

The theme is available as open source under the terms of the [MIT License](https://opensource.org/licenses/MIT).

