# MoreMarkov

Simple Markov chain generation.

## Installation

Add this line to your application's Gemfile:

```ruby
gem 'more_markov'
```

And then execute:

    $ bundle

Or install it yourself as:

    $ gem install more_markov

## Usage
```ruby
your_generator = MoreMarkov::MarkovChainGenerator.new(source_text_as_string)
your_generator.find_patterns
your_generator.generate_chain(word_count, optional_start_word) #=> Markov chain
```
## License

The gem is available as open source under the terms of the [MIT License](http://opensource.org/licenses/MIT).
