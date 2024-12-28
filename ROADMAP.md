# Roadmap
## Lib Lase
### Base Functionality
- search files by phrases using TF-IDF
- tagging files, and retrieving files by those tags
- lazily index files 
  - when they are first encounterned and included in the directory which is
    being searched
  - when they are in the directory which is being searched and have changed
    since the last time
- create links/edges between files, directional and undirectional
- view file graphs
- if file is searched all child files must be searched
- except different file types:
  - plain text
  - pdf
  - html
- have programming language support and intelligently searching for concepts in
  the given programming language
- configure which directories should be searched
- be able to have frontends for different languages -> maybe load them via
  shared objects? Would be cool if someone could just write a fronend for a
  given filetype they need to support -> this could then replace the inbuilt
  support for multiple file formats and one could just write a frontend for a
  given language
- support 'headlines' could be literal headlines in articles, could be function
  definitions in programming languages could be anything
## Lase CLI
