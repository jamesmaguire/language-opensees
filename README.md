# language-opensees package

Atom text editor package that provides syntax highlighting and auto-completion for OpenSees tcl scripts.

## Autocompletion
Includes autocompletion support for common OpenSees commands.

<img width="505" alt="pattern-snippets" src="https://cloud.githubusercontent.com/assets/22332883/19871205/ccf60b7c-a018-11e6-8bc8-9c4d1bc94d54.PNG">

<img width="505" alt="uniaxialmaterial-snippets" src="https://cloud.githubusercontent.com/assets/22332883/19871220/df94ac16-a018-11e6-92f8-9208e45095ba.PNG">

Starting a new model from scratch? Use the template snippet to easily get started:

<img width="505" alt="template-snippet-suggestion" src="https://cloud.githubusercontent.com/assets/22332883/19871196/c261f5f4-a018-11e6-9359-f080facf9fec.PNG">

<img width="505" alt="template-snippet-expanded" src="https://cloud.githubusercontent.com/assets/22332883/19871184/b57f1466-a018-11e6-9045-c0c9752ce833.PNG">

Find links to the OpenSees documentation with the Link snippet:

<img width="505" alt="link-snippets" src="https://cloud.githubusercontent.com/assets/22332883/19871141/887abc36-a018-11e6-8094-4d002947422e.PNG">


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
