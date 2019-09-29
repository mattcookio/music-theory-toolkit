[music-theory-toolkit](README.md) › [Globals](globals.md)

# music-theory-toolkit

# Music Theory Toolkit

This is a toolkit for note/chord/set parsing, transposition, and enumeration.

This repository is under active development. Help is welcome!

# Installation and Setup

In your node or JavaScript project using NPM ( run `npm init` in a new directory, and follow the prompts ):

```bash
npm i music-theory-toolkit
```

All methods can be used statically from these imported objects - there is currently no need to instantiate them:

```javascript
import { Note, Chord, Set, Scale } from 'music-theory-toolkit';

const note = Note.numNoteToAlpha(10, '#');
```

# Usage

There are currently 4 primary classes available - Note, Chord, Set, and Scale - some sharing common functionality.

# Testing and Development

Testing libraries: Mocha & Chai

    npm test
