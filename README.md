# Python Markdown Generator

Python library for creating HTML sanitized Markdown documents.

This library aims to bring modular approach for dynamically building Markdown documents with pure Python.
Documents can be built with such a way, that they consist multiple reusable components and can contain automatically generated table of contents etc.

[![CircleCI](https://img.shields.io/circleci/build/github/Nicceboy/python-markdown-generator?label=CircleCI&logo=circleci)](https://circleci.com/gh/Nicceboy/python-markdown-generator)
[![codecov](https://codecov.io/gh/Nicceboy/python-markdown-generator/branch/master/graph/badge.svg)](https://codecov.io/gh/Nicceboy/python-markdown-generator)
[![License](https://img.shields.io/badge/License-Apache%202.0-blue.svg)](https://opensource.org/licenses/Apache-2.0)

## But why?

In most cases, Markdown is finally converted into HTML syntax, and there are already multiple existing libraries for generating HTML output dynamically.
Markdown was originally created as a lightweight, user-friendly, user-written text formatting markup language to produce rich text format by using plain text editor, and existence of this kind of library is against the original purpose of language.

However, there are couple of rare use cases, where you might want to generate Markdown *instead* of direct HTML.  
  * Some documents can be ideally generated by machine, but they might be edited by some user later on.
  * There might be need to generate some Markdown templates, which are finally filled by end-user
  * Also, there are some external systems, where HTML rendering is not supported, but you can input Markdown into them, and you might integrate something automatically into these systems

The original need for this kind of library came from the need to generate different kind of reports automatically into git repositories.

At the time of starting of making this library, not complete existing similar library was found.

> This is **not** yet-another-Markdown-to-HTML conversion tool.


## Licence

Copyright &#169; 2019 Niklas Saari

Licensed under the Apache License, Version 2.0 (the "License");
you may not use this file except in compliance with the License.
You may obtain a copy of the License at

    http://www.apache.org/licenses/LICENSE-2.0

Unless required by applicable law or agreed to in writing, software
distributed under the License is distributed on an "AS IS" BASIS,
WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
See the License for the specific language governing permissions and
limitations under the License.The project is under Apache License, Version 2.0.

