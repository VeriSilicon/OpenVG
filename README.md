# OpenVG

OpenVG build steps:
1. Edit the `build_linux.sh` script and update the `KERNEL_DIR` and `VG_LITE_SDK` paths if needed.
2. Run the script to build OpenVG for your target. FPGA example:
```
./build_linux.sh PCIE-GEN6
```
3. The libraries are generated in the `build` directory. The VGLite dependencies are also copied to the same location.
