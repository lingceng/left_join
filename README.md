# left_join

This gem helps you doing `LEFT JOIN`s between your ActiveRecord associations, so
you can do this:

```ruby
Book.left_join(:category)
# SELECT "books".* FROM "books"
# LEFT OUTER JOIN "categories"
# ON "books"."category_id" = "categories"."id"
```

## Why?

See [this blog post](http://nerde.github.io/posts/a-better-left-join-with-active-record/)
for details.

## Installation

Add to your Gemfile:

```ruby
gem 'left_join'
```

Or install it manually

```
gem install left_join
```

## Contributing

* Fork the project.
* Start a feature/bugfix branch.
* Commit and push until you are happy with your contribution.
* Make sure to add tests for it. This is important so I don't break it in a
future version unintentionally.
* Create a pull request.

## Copyright

Copyright (c) 2015 Diego Aguir Selzlein. See LICENSE.txt for further details.
