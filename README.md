# travis_qmake_gcc_cpp14_oclint_sfml

[![Travis CI logo](TravisCI.png)](https://travis-ci.org)

[![Build Status](https://travis-ci.org/richelbilderbeek/travis_qmake_gcc_cpp14_oclint_sfml.svg?branch=master)](https://travis-ci.org/richelbilderbeek/travis_qmake_gcc_cpp14_oclint_sfml)

This GitHub is part of [the Travis C++ Tutorial](https://github.com/richelbilderbeek/travis_cpp_tutorial).

The goal of this project is to have a clean Travis CI build, with specs:
 * Build system: `qmake`
 * C++ compiler: `gcc`
 * C++ version: `C++14`
 * Libraries: `STL` and `SFML`
 * Code coverage: none
 * Static code checking: `OCLint`
 * Source: one single file, `main.cpp`

More complex builds:
 * Add `gcov`: [travis_qmake_gcc_cpp14_gcov_oclint_sfml](https://www.github.com/richelbilderbeek/travis_qmake_gcc_cpp14_gcov_oclint_sfml)

Less complex builds:
 * No `OCLint`: [travis_qmake_gcc_cpp14_sfml](https://www.github.com/richelbilderbeek/travis_qmake_gcc_cpp14_sfml)
 * No `SFML`: [travis_qmake_gcc_cpp14_oclint](https://www.github.com/richelbilderbeek/travis_qmake_gcc_cpp14_oclint)
 * C++11: [travis_qmake_gcc_cpp11_oclint_sfml](https://www.github.com/richelbilderbeek/travis_qmake_gcc_cpp98_oclint_sfml)
 * C++98: [travis_qmake_gcc_cpp98_oclint_sfml](https://www.github.com/richelbilderbeek/travis_qmake_gcc_cpp11_oclint_sfml)
