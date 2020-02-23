# jekyll-theme-onepage

Welcome to jekyll-theme-onepage. You'll find everything you need to built a one page website with a portfolio based on Jekyll. Every posts is a portfolio project instead of a blog post.

This template is based on bootstrap (css, javascript) and use jQuery (javascript).
This theme embed a fully functional website with a few files and code.

Here is what it looks like:

![Screenshot](screenshot.png)

## Installation

Add this line to your Jekyll site's `Gemfile`:

```ruby
gem "jekyll-theme-onepage"
```

And add this line to your Jekyll site's `_config.yml`:

```yaml
theme: jekyll-theme-onepage
```

And then execute:

    $ bundle install

Or install it yourself as:

    $ gem install jekyll-theme-onepage
    
To correctly show a portfolio project, add into the YAML syntax of your post:

```yaml
subtitle: "Give me a subtitle"
poster: "image.jpg"
```
The `poster` attribute will be used to show a thumbnail of the project in the portfolio section. This attribute needs to be the name of a existing image placed in "*assets/img/*".

The `subtitle` is used to show a text below the title of the post.

Some examples can be found in this them in `_example-posts/` folder.

## Usage

There are 2 defaults layouts :

- home, used in the home page only
- post, used for all posts

You can replace the build-in images (`assets/img/`) by your own.

## Development

To set up your environment to develop this theme, run `bundle install`.

Your theme is setup just like a normal Jekyll site! To test your theme, run `bundle exec jekyll serve` and open your browser at `http://localhost:4000`. This starts a Jekyll server using your theme. Add pages, documents, data, etc. like normal to test your theme's contents. As you make modifications to your theme and to your content, your site will regenerate and you should see the changes in the browser after a refresh, just like normal.

When your theme is released, only the files in `_layouts`, `_includes`, `_sass` and `assets` tracked with Git will be bundled.
To add a custom directory to your theme-gem, please edit the regexp in `jekyll-theme-onepage.gemspec` accordingly.

## Contribute

### Release

To create a new version:

- Update version `spec.version` in `jekyll-theme-onepage.gemspec`
- Run `gem build jekyll-theme-onepage.gemspec`
- Run `gem push jekyll-theme-onepage-[version].gem`

## License

The theme is available as open source under the terms of the [MIT License](https://opensource.org/licenses/MIT).

