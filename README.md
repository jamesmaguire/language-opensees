# language-opensees package

Atom text editor package that provides syntax highlighting and auto-completion for OpenSees tcl scripts.

## Autocompletion
Includes autocompletion support for common OpenSees commands.

![pattern snippets](https://github.com/JamesMaj/language-opensees/tree/master/screenshots/pattern-snippets.png)

Starting a new model from scratch? Use the template snippet to easily get started:

![template snippet suggestion](https://github.com/JamesMaj/language-opensees/tree/master/screenshots/template-snippet-suggestion.png)

![template snippet expanded](https://github.com/JamesMaj/language-opensees/tree/master/screenshots/template-snippet-expanded.png)

You can find links to the OpenSees documentation with the Link snippet:
![link snippets](https://github.com/JamesMaj/language-opensees/tree/master/screenshots/link-snippets.png)


## Supported OpenSees commands
This is a list of the currently supported OpenSees functions for syntax highlighting. Most of these also have snippets for autocompletion.

### Modelling commands
- model
- node
- element
- uniaxialMaterial
- fix, fixX, fixY, fixZ
- equalDOF
- rigidDiaphragm
- rigidLink
- timeSeries
- pattern
  - load
  - eleLoad
  - sp
  - groundMotion
  - imposedMotion
- section
  - fiber
  - patch
  - layer

### Analysis commands
- constraints
- numberer
- system
- test
- algorithm
- integrator
- analysis
- eigen
- analyze

### Output commands
- eleNodes
- eleResponse
- getEleTags
- getNodeTags
- getTime
- logFile
- nodeAccel
- nodeBounds
- nodeCoord
- nodeDisp
- nodeEigenvector
- nodeVel
- print
- print
- printA
- recorder, record


### Misc commands
- exit
- loadConst
- remove
- reset
- setMaxOpenFiles
- setTime
- testIter
- testNorms
- wipe
- wipeAnalysis
