# Ruby Study

Use your favorite search engine and the provided readings to research and
respond to the following questions.

In your responses, be sure to cite any relevant sources you consulted in your
search. We ask you to write responses in your own words in order to see how you
process what you've read. Please do not respond with direct quotes from source
material. Instead, digest what you've read and repeat it in your own voice.

## Required Readings

-   [Ruby Tutorial - Try Ruby](http://tryruby.org/)
-   [Ruby in Twenty Minutes](https://www.ruby-lang.org/en/documentation/quickstart/)
-   Code School (Only the free levels. **Do not pay for Code School unless you want to.**
    -   [Ruby Bits](https://www.codeschool.com/courses/ruby-bits)
    -   [Ruby Bits Part 2](https://www.codeschool.com/courses/ruby-bits-part-2)
-   [% Notation](https://en.wikibooks.org/wiki/Ruby_Programming/Syntax/Literals#The_.25_Notation)

## Additional Resources: Optional

-   [RubyMonk - Interactive Ruby tutorials](https://rubymonk.com/)
-   [Why's (Poignant) Guide to Ruby](http://poignant.guide/)
-   [Learn Ruby - With the Edge Case Ruby Koans](http://rubykoans.com/)

## Type Conversion

Write the Ruby code that takes the integer `700` and returns the string `"007"`.

```ruby

(700.to.s).reverse

(not sure about this one)

(stack overflow)

```

## Array Manipulation

Write the Ruby code that takes the following array, `[23, 56, 3, 7]`, and
manipulates it by sorting it and then reversing it in place (i.e., modifying the
reference to the original).

```ruby

a = [23, 56, 3, 7]
a.sort { |x,y| y <=> x }

(ruby-doc.org)

```

## Class#method!

What does an exclamation point after a method usually signify?  e.g.,
`my_string.capitalize!`

```md
It usually signifies that whatever method it follow is acting on the object itself.
These methods followed by ! usually perform a permanent or potentially dangerous change.
"The bang is used to distinguish the "more surprising" version of the method from the "less surprising" one."

(Answer found on Stack Overflow)
```

## Instantiation
How do you create an instance of a class in Ruby?

```ruby
you type the word "class" followed by the name you want to give it, and then
following the name you can give it various methods.
```

## Class Modification

If a class in Ruby gets modified while there are existing instances of it, then
will those instances also have those modifications?

```md

ruby-lang says:
"In Ruby, you can open a class up again and modify it. The changes will be present
in any new objects you create and even available in existing objects of that class."
It looks like the answer to this question is yes, but I can't tell if there's a
distinction here that I'm missing.

https://www.ruby-lang.org/en/documentation/quickstart/3/
```

## Iteration

Write an example of iteration in Ruby.

```ruby

i=1
while i < 11
  print "#{i} "
  i+=1
end

This is a While loop that prints out the numbers from 1 to 10.^^

(skorks.com)
```
