## 🛠 Roadmap / TODO

Core tasks and components to be implemented (referencing the [Flare Animate](https://github.com/Flare-Animate/Flare/tree/master/flare/sources/common/flash) structure):

- [ ] **FCT Implementation:** Porting the core Flash Conversion Tool logic.
- [ ] **FDT Integration:** Implementing Flash Data Types and all related code dependencies.
- [ ] **XFL/FLA Parser:** Developing the parser to read both uncompressed (XFL) and compressed (FLA) project structures.
- [ ] **Core Architecture:** Implement `Loader.js` in the root directory.
- [ ] **TFlash/ToonzFlash Port:** Porting parsing logic to JavaScript.
- [ ] **Web Bundler:** Create the logic to reconstruct `.FLA` files into a portable **Web ZIP Source Code** (ready for browser deployment).

And for more later...
- [ ] **AVM2 Compatibility:** Support for ActionScript 3.0 execution logic. 
    *   *Note: Original Flash API methods from TFlash are being replaced with [OpenFL API](https://api.openfl.org/) equivalents.*
