# Catch on npm

This is an unofficial repackaging of the excellent [Catch](https://github.com/philsquared/Catch)
C++ unit test library.

# Using catch via npm

     $ npm init                 # create a package.json
     $ npm i --save-dev catch   # install catch

# Setting include paths in binding.gyp

     "include_dirs": [
       "<!(node -e \"require('catch')\")"
     ]

# Setting include paths in other systems

Add node_modules to your include path

# Using Catch

     #define CATCH_CONFIG_MAIN
     #include "catch/single_include/catch.hpp"

Follow the [tutorial](https://github.com/philsquared/Catch/blob/master/docs/tutorial.md) for more
details.
