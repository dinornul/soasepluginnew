Eclipse extension providing a custom builder/nature for Sins entity files.

# Introduction

The EntityBuilder and EntityNature provides Eclipse extensions for associateing entity files with the custom builder. The EntityBuilder is responsible for validating entity source files against the meta definition. If any errors or warnings are found markers are created and associated with the file and displayed visually as part of the Editor and Problems view.


# Details

Here is an example of the Entity Builder/Nature at work.

  1. Whoops! I didn't increment the instant action count.
  1. I misspelled buffInstantActionType (missing an 'f' in Effect).
  1. The soundID on the first instant action is spelled wrong.

![http://dl.dropbox.com/u/5790092/SinsTools/example_error.jpg](http://dl.dropbox.com/u/5790092/SinsTools/example_error.jpg)