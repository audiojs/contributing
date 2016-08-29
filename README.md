[![gitter](https://badges.gitter.im/Join%20Chat.svg)](https://gitter.im/audiojs/audio)

Thank you for taking the time to contribute!  Here are a few things to help you:

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

### Package Style

 - `audio-*`: Packages related to [`audio`](https://github.com/audiojs/audio), [`audio-buffer`](https://github.com/audiojs/audio-buffer), or other audio components.  Typically is a [Node `stream`](https://nodejs.org/api/stream.html) interface, except the base components.
 - `web-audio-*`: Packages related to the [Web Audio API](https://developer.mozilla.org/en-US/docs/Web/API/Web_Audio_API)
 - `*-util`: Packages that provide multiple helpful functions. (like [`pcm-util`](https://github.com/audiojs/pcm-util))
 - [Package exports convention](https://github.com/audiojs/contributing/wiki/Streams-convention).

### Also See
 - [audio-lab](https://github.com/audio-lab): Sound research tools
 - [stability-badges](https://github.com/orangemug/stability-badges): The badges used here to show stability.
