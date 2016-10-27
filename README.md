# language-opensees package

Atom text editor package that provides syntax highlighting and auto-completion for OpenSees tcl scripts.

## OpenSees commands
This is a list of the currently supported OpenSees functions for syntax highlighting. Most of these also have snippets for autocompletion.

### Modelling commands
- model
- node
- element
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
