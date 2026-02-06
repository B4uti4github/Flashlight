# 🛠 Roadmap / TODO

Core tasks and components to be implemented (referencing the [Flare Animate](https://github.com/Flare-Animate/Flare/tree/master/flare/sources/common/flash) structure):

- [ ] **AVM2 Compatibility** For Compatibility with ActionScript.
- [ ] **FCT Implementation:** Porting the core Flash Conversion Tool logic.
- [ ] **FDT Integration:** Implementing Flash Data Types and all related code dependencies.
- [ ] **XFL-Parser:** Developing the parser to read uncompressed or Compressed(If is an FLA file) Flash project structures.
- [ ] **Core Architecture:** Implement `Loader.js` in the root directory.
- [ ] **TFlash/ToonzFlash Port:** Porting parsing logic to JavaScript. 
    *   *Note: Original Flash API from TFlash methods are being replaced with [OpenFL API](https://api.openfl.org/) equivalents.*
- [ ] **Web Bundler:** Create the logic to reconstruct `.FLA` files into a portable **Web ZIP Source Code** (ready for browser deployment).

> **Note for contributors:** Please use the `/src` directory for new files and refer to the [Flare repository](https://github.com/Flare-Animate/Flare/tree/master/flare/sources/common/flash) for architectural guidance.
