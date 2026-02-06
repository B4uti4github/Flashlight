# 🔦 Flashlight

Flash as a platform may have "died," but its legacy—the art, the games, and the creativity—is a part of our collective memory. **Flashlights** is the bridge that keeps that light from being extinguished. 

By converting **FLA into pure, eternal source code**, we are making sure those "flashes" of creativity are preserved in the "sky" of the open web.

## 🛠 Features
*   **Legacy Preservation:** Converts FLA files into modern, open-source formats.
*   **Open Web Standards:** Ensures content remains accessible without proprietary plugins.
*   **Robust Engine:** Built using industry-standard animation source code.

## ⚖️ Disclaimer
This repository utilizes source code from [OpenToonz](https://opentoonz.github.io), specifically the [**Flare Animate**](https://github.com/Flare-Animate/Flare/tree/master) fork by the Flare Contributors. It also integrates the [OpenFL API](https://api.openfl.org/) and, where applicable, open-source AVM2 reimplementations for JavaScript.

The project incorporates specialized animation middleware components to handle file conversion, ensuring compliance with the **BSD License** requirements of the original source code.

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


> **Note for contributors:** Please use the `/src` directory for new files and refer to the [Flare repository](https://github.com/Flare-Animate/Flare/tree/master/flare/sources/common/flash) for architectural guidance.
# License
This is free and unencumbered software released into the public domain.

Anyone is free to copy, modify, publish, use, compile, sell, or
distribute this software, either in source code form or as a compiled
binary, for any purpose, commercial or non-commercial, and by any
means.

In jurisdictions that recognize copyright laws, the author or authors
of this software dedicate any and all copyright interest in the
software to the public domain. We make this dedication for the benefit
of the public at large and to the detriment of our heirs and
successors. We intend this dedication to be an overt act of
relinquishment in perpetuity of all present and future rights to this
software under copyright law.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND,
EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF
MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT.
IN NO EVENT SHALL THE AUTHORS BE LIABLE FOR ANY CLAIM, DAMAGES OR
OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE,
ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR
OTHER DEALINGS IN THE SOFTWARE.

For more information, please refer to <https://unlicense.org/>