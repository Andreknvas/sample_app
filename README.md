# Ruby on Rails Tutorial Sample App

This is the sample application for
["Ruby on Rails Tutorial:
Learn Web Development with Rails"](https://www.railstutorial.org/)
by [Michael Hartl](https://www.michaelhartl.com/).


## License

All source code in the [Ruby on Rails Tutorial](https://www.railstutorial.org/)
is available jointly for use under the MIT License or under a modified BSD License.
See [LICENSE.md](LICENSE.md) for details.

## Getting started

To get started with the app, clone the repo and then install the needed gems:

```
gem install bundler -v 2.3.14
bundle _2.3.14_ config set --local without 'production'
bundle _2.3.14_ install

```

Next, migrate the database:

```
rails db:migrate
```

Finally, run the test suite to verify that everything is working correctly:

```
rails test
```

If the test suite passes, you'll be ready to run the app in a local server:

```
rails server
```

To stop the server, you can press `Ctrl-C` in the terminal where it's running.
