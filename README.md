# Kafkaesque

A JRuby-based event stream processing framework for Kafka.

## Example

```ruby
Kafkaesque::Consumer.new(
  :handler => MyHandler,
  :event => MyEvent,
  :kafka => {
    :host => '10.3.165.11',
    :topics => StatsHandler::GAMES
  }
).start
```

## Contributing to Kafkaesque
 
* Check out the latest master to make sure the feature hasn't been implemented or the bug hasn't been fixed yet
* Check out the issue tracker to make sure someone already hasn't requested it and/or contributed it
* Fork the project
* Start a feature/bugfix branch
* Commit and push until you are happy with your contribution
* Make sure to add tests for it. This is important so I don't break it in a future version unintentionally.
* Please try not to mess with the Rakefile, version, or history. If you want to have your own version, or is otherwise necessary, that is fine, but please isolate to its own commit so I can cherry-pick around it.

## Copyright

Copyright (c) 2011, 2012 Wooga GmbH, Berlin