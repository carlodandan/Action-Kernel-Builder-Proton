### Action Kernel Builder | Proton
Compile your first custom kernel using [proton-clang](https://github.com/kdrag0n/proton-clang).

### Toolchain/Compiler Version
* Clang+LLVM (v13.0.0, as of commit [b4fd512c](https://github.com/llvm/llvm-project/commit/b4fd512c36ca344a3ff69350219e8b0a67e9472a))
* Binutils (v2.36.1, trimmed)

### Builder Notes
* The last proton-clang release is the current branch, `master`. If you want to build with much older release, choose your own tag.
* To change invocations for make command, just edit make.txt, change it how ever you want.
* Builder uses osm0sis' AnyKernel3 template but with modified (just a bit) anykernel.sh - device checking were set to 0. Flash at your own risk.
