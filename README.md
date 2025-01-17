Mini Audio Rust Bindings

Bindings to https://github.com/dr-soft/miniaudio

This fork doesn't have safe crate as it target newest miniaudio's source tree.

**
The crate currently lacks documentation, but for the most part the API is very close the the API of the miniaudio C library.
That can be found in the C library's main header file.
**

Building
---
LLVM and clang must be installed in order to generate the bindings.
Installation instructions can be found here: https://rust-lang.github.io/rust-bindgen/requirements.html
