# Display-Test-for-Mainline-Linux-on-MediaTek-Chromebook

To ensure the quality, stability, and long-term maintenance of display for Mainline Linux on MediaTek Chromebook, the test would regularly test display function every new released Linux version.

Current test platform include:

1. HP 11a-na0040nr (MT8183 Chromebook kappa)

Current test include:

1. modetest [1]
2. igt-gpu-tools [2]

After test, generate report for test result. If some test fail, bisect the source code, find out the fail reason, and fix the problem.

[1] https://gitlab.freedesktop.org/mesa/libdrm/-/tree/master/tests/modetest
[2] https://drm.pages.freedesktop.org/igt-gpu-tools/
