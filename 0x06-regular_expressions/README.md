0x06 Reguiar expression
Regex
DevOps
 By: Sylvain Kalache
  Weight: 1
   Ongoing second chance project - started Oct 3, 2023 6:00 AM, must end by Oct 7, 2023 6:00 AM
    An auto review will be launched at the deadline
    In a nutshell…
    Auto QA review: 1.0/24 mandatory & 0.0/9 optional
    Altogether:  4.17%
    Mandatory: 4.17%
    Optional: 0.0%
    Calculation:  4.17% + (4.17% * 0.0%)  == 4.17%
    Concepts
    For this project, we expect you to look at this concept:

    Regular Expression
    Background Context
    For this project, you have to build your regular expression using Oniguruma, a regular expression library that which is used by Ruby by default. Note that other regular expression libraries sometimes have different properties.

    Because the focus of this exercise is to play with regular expressions (regex), here is the Ruby code that you should use, just replace the regexp part, meaning the code in between the //:

    sylvain@ubuntu$ cat example.rb
#!/usr/bin/env ruby
    puts ARGV[0].scan(/127.0.0.[0-9]/).join
    sylvain@ubuntu$
    sylvain@ubuntu$ ./example.rb 127.0.0.2
    127.0.0.2
    sylvain@ubuntu$ ./example.rb 127.0.0.1
    127.0.0.1
    sylvain@ubuntu$ ./example.rb 127.0.0.a
    Resources
    Read or watch:

    Regular expressions - basics
    Regular expressions - advanced
    Rubular is your best friend
    Use a regular expression against a problem: now you have 2 problems
    Learn Regular Expressions with simple, interactive exercises
