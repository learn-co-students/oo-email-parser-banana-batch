# Object Oriented Email Parser

## Learning Goals

- Practice defining a class and using an `attr_accessor` to create setter and
  getter methods
- Use TDD to write working code

## Description

You will be writing an `EmailAddressParser` class that gets initialized with a string
of emails.

Your job is to parse those email addresses into a useful array using an instance
method, `parse`.

I should be able to do this:

```ruby
email_addresses = "john@doe.com, person@somewhere.org"
parser = EmailAddressParser.new(email_addresses)

parser.parse
# => ["john@doe.com", "person@somewhere.org"]
```

You should be able to initialize with a list of email addresses either separated
with spaces _or_ separated with commas. The `parse` method should, additionally,
only return unique addresses.

## Instructions

This lab is test-driven, so run the test suite to get started and use the test
output to get the program working.

**Hints:**

- How will you control for parsing a list of email addresses that is _either_
  comma separated _or_ separated by a white space?
- Use an `attr_accessor` to set and get the list of email addresses
