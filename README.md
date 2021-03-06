Test First Ruby -- RSpec 3 Edition
==========
This is modified version of test-first.org's learn ruby project. See [testfirst's Ruby page](http://testfirst.org/learn_ruby#install) for more information about how this will work. 

### Set up instructions

1. Fork this repo
2. Clone your version of the repo to your local machine
3. On your local machine, `cd` into the root folder of this repo in your terminal
4. run `bundle install` to install all the gems this project needs.

### Getting started with the exercises

To work through the first exercise, follow this process

1. `cd` into `00_hello` from the root folder of this project
2. Run `rake`, to run the tests. It will fail with the following error:
3. Read the failure output carefully and write the code that will make it pass
4. Run the tests again with `rake`
5. This will output that one test has passed and another test failure, write the code to make the next test pass.
4. Continue this process until all tests pass (when they are green) you have now completed the exercise.
5. Do this for all the exercises in this project
5. To get hints and tips about each exercise, view the `index.html` file that is included in each exercise folder


Basically, this is "error-driven development"... you'll keep running tests, hitting error messages, fixing those messages, running more tests...  It is meant to not only test your Ruby skills but also get you comfortable seeing big scary looking stack traces and error messages.  Most of the development you do at first will be just like this.  In fact, most of *all* development is error-driven.  So get comfortable with it!

### Credit

This is forked from [https://github.com/alexch/learn_ruby](https://github.com/alexch/learn_ruby), its original creator.

This is part of [TheOdinProject](http://www.theodinproject.com) introduction to Ruby, RSpec and test driven development in the Web Development 101 track. See [here](http://www.theodinproject.com/courses/web-development-101/lessons/ruby) for more information.
