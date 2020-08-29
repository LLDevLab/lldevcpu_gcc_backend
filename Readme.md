# How to apply a patch
- Download and unzip gcc-releases-gcc-8.zip file from [here](https://github.com/gcc-mirror/gcc.git) (releases/gcc-8 branch).
- Download a patch file (lldevcpu_200829-src.patch) to the directory, where gcc-releases-gcc-8.zip was unzipped.
- Execute "patch -s -p0 < lldevcpu_200829-src.patch" command to patch a soucre code.
- Compile gcc for lldevcpu.