# minitest-docker

A simple image with [Minitest](https://github.com/seattlerb/minitest) installed.

## Developing

It's recommended to have [`rbenv`](https://github.com/rbenv/rbenv) installed for development:

```
brew install rbenv
```

After installing `rbenv`, the shell will pick up `.ruby-version` file.

```
which ruby # /path/to/home/.rbenv/shims/ruby
```

Then install [`bundler`](http://bundler.io/) with:

```
gem install bundler
```

And then install project dependencies with:

```
bundle install
```
