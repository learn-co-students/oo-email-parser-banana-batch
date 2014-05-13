---
  tags: string parsing, oop, micro, initializers
  languages: ruby
  resources: 2
---

# Object Oriented Email Parser

## Description

You will be writing an `EmailParser` class that gets initialized with a string of emails.
Your job is to parse those emails into a useful array using an instance method,
`parse`.

I should be able to do this:

```ruby
emails = "john@doe.com, person@somewhere.org"
parser = EmailParser.new(emails)

parser.parse
# => ["john@doe.com", "person@somewhere.org"]
```

I should be able to initialize with a list of emails either separated with spaces
or separated with commas. The `parse` method should, additionally, only return
unique emails.

## Instructions

Get all the tests to pass by implementing an "EmailParser" class.

Run the test suite using the `rspec` command.
## Resources
* [Programming Ruby 1.9](http://books.flatironschool.com/books/11) - [String Docs: split](http://books.flatironschool.com/books/11), page 678
* [Programming Ruby 1.9](http://books.flatironschool.com/books/11) - [4.3 Blocks and Iterators](http://books.flatironschool.com/books/11), page 68
