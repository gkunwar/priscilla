# Priscilla

Frock up your console messages. :dancer: :dancer: :dancer:

## Why Priscilla

Because of [Priscilla, Queen of the Desert](http://en.wikipedia.org/wiki/The_Adventures_of_Priscilla,_Queen_of_the_Desert).

**Don't let your console messages drown in a wall of text, make them stand out!**

![Tutorial](images/priscilla.gif)

## Install

Add this line to your application's Gemfile:

    gem 'priscilla'

And then execute:

    $ bundle

Or install it yourself as:

    $ gem install priscilla

## Use

Require the gem:

    require 'priscilla'

Use `pr` to frock up your console messages

    pr "A cock in a frock on a rock"

Result

![Result](images/result.png)

## Decorators

Priscilla supports a lot of different decorators:

**Strings**

![Strings](images/strings.png)

**Colored Strings**

![Colored Strings](images/colored_strings.png)
![Colored Strings, part 2](images/colored_strings_two.png)

**Unicode Emojis**

![Unicode Emojis](images/unicode_emojis.png)

**Text Emojis**

![Text Emojis](images/text_emojis.png)

## Configure

If you're using rails create an initializer in `config/initializers/priscilla.rb`:

```ruby
Priscilla.configure do |c|
  c.width = 80              # default
  c.decorator = ':dancer: ' # default
end
```

## Contribute

1. Fork it ( http://github.com/Arkham/priscilla/fork )
2. Create your feature branch (`git checkout -b my-new-feature`)
3. Commit your changes (`git commit -am 'Add some feature'`)
4. Push to the branch (`git push origin my-new-feature`)
5. Create new Pull Request
