[![gitter](https://badges.gitter.im/Join%20Chat.svg)](https://gitter.im/audiojs/audio)

Thank you for taking the time to contribute!  Here are a few things to help you:

### Naming Convention

Package names tend to fall under the following convention:

 - `audio-*`: Packages related to [`audio`](https://github.com/audiojs/audio), [`audio-buffer`](https://github.com/audiojs/audio-buffer), [`audio-oscillator`](https://github.com/audiojs/audio-oscillator) etc. Typically implement functional interface: a constructor, returning a function. Usually utilise [`audio-format`](https://github.com/audiojs/audio-format) to solve common problems related to audio data conversions.
 - `audio-*-stream`: Packages with [node `stream`](https://nodejs.org/api/stream.html) interface, usually wrappers over plain `audio-*` packages, enabling audio processing.
 - `pull-audio-*`: Packages with [pull-stream](https://github.com/pull-stream/pull-stream) interface, usually wrappers over plain `audio-*` packages, enabling audio processing.
 - `web-audio-*`: Packages related to the [Web Audio API](https://developer.mozilla.org/en-US/docs/Web/API/Web_Audio_API).
 - `audio-*-native`: Node addon implementation of audio processing module.
 - `audio-*-wasm`, `audio-*-asm`: WebAssembly implementation of a package.
 
### Workflow

 - Please verify new stream components with [streams convention](https://github.com/audiojs/contributing/wiki/Streams-convention).
 - Audiojs uses very loose code style [.eslintrc.json](https://github.com/audiojs/contributing/wiki/.eslintrc.json), please verify code with at least this rule set, or if you prefer, with stricter versions like [standard](https://www.npmjs.com/package/standard) etc.

### How to Contribute

 1. Fork or branch from the master.
 2. Create commits following the [commit style](#Commit-Style)
 3. Start a pull request to the master branch
 4. Wait for a **@audiojs/core** member to review

### Commit Style

 - Use the present tense ("Add feature" not "Added feature")
 - Use the imperative mood ("Move cursor to..." not "Moves cursor to...")
 - Limit the first line to 72 characters or less
 - Reference issues and pull requests

<sub>(From [electron's commit style](https://github.com/electron/electron/blob/master/CONTRIBUTING.md))</sub>

### Also See
 - [audio-lab](https://github.com/audio-lab): Sound research tools
 - [stability-badges](https://github.com/orangemug/stability-badges): The badges used here to show stability.
