gcc-arm-cmake
=============

Ubuntu/Debian base image with GNU Arm Embedded Toolchain and cmake installed.

Debian version also has clang-tidy.

# Environment Variables

* **$DEBIAN_VERSION**<br>
  The debian version used in image, e.g. `"buster"`.

* **$UBUNTU_VERSION**<br>
  The ubuntu version used in image, e.g. `"18.04"`.

* **$GCC_VERSION**<br>
  The installed version of the GNU Arm Embedded Toolchain in image, e.g. `"7-2018q2"`.


# Getting the image
```
docker pull bintel-se/gcc-arm-cmake
```
