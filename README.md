# Display-Test-for-Mainline-Linux-on-MediaTek-Chromebook

To ensure the quality, stability, and long-term maintenance of display for Mainline Linux on MediaTek Chromebook, the test would regularly test display function every new released Linux version.

Current test platform include:

1. HP 11a-na0040nr (MT8183 Chromebook kappa)

Platform setup step [1]

Current test include:

1. modetest [2]
2. igt-gpu-tools [3]

After test, generate report for test result. If some test fail, bisect the source code, find out the fail reason, and fix the problem.

[1] 
[2] https://gitlab.freedesktop.org/mesa/libdrm/-/tree/master/tests/modetest
[3] https://drm.pages.freedesktop.org/igt-gpu-tools/
