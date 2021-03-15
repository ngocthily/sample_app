# Ruby on Rails Tutorial sample application

This is the sample application for
[*Ruby on Rails Tutorial:
Learn Web Development with Rails*](https://www.railstutorial.org/)
(6th Edition)
by [Michael Hartl](https://www.michaelhartl.com/).

To view on Heroku: [Click here](https://gentle-eyrie-90936.herokuapp.com/)

#### Quick routes
* ```/``` or ```/static_pages/home``` -> view home page
* ```/static_pages/help``` -> view help page
* ```/static_pages/about``` -> view about page
* ```/static_pages/contact``` -> view contact page
## License

All source code in the [Ruby on Rails Tutorial](https://www.railstutorial.org/)
is available jointly under the MIT License and the Beerware License. See
[LICENSE.md](LICENSE.md) for details.

## Getting started

To get started with the app, clone the repo and then install the needed gems:

```
$ gem install bundler -v 2.2.13
$ bundle _2.2.13_ config set --local without 'production'
$ bundle _2.2.13_ install
```

Next, migrate the database (not needed at the moment):

```
$ rails db:migrate
```

Finally, run the test suite to verify that everything is working correctly:

```
$ rails test
```

If the test suite passes, you'll be ready to run the app in a local server:

```
$ rails server
```

For more information, see the
[*Ruby on Rails Tutorial* book](https://www.railstutorial.org/book).
