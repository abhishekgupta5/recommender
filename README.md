# Recommender
Recommendation system based out of last.fm API

## Geting started

To get started, clone the repo and install the needed gems:

```
$ bundle install --without production
```

Next, migrate the database:

```
$ rails db:migrate
```

Finally, run the test suite to verify that everything is working correctly:

```
$ rails test
```

If the test suite passes, you'll be ready to run the app in local server:

```
$ rails server
```
