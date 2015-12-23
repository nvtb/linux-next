Tegra baseline test results for next-20151223


Here are some basic Tegra test results for Linux next-20151223.
Logs and other details at:

    https://nvtb.github.io//linux-next/test_next-20151223/20151222201533/


Test summary
------------

Build: zImage:
    FAIL: ( 1/ 2): tegra_defconfig
    Pass: ( 1/ 2): multi_v7_defconfig

Build: Image:
    Pass: ( 1/ 1): defconfig

Boot to userspace: defconfig:
    FAIL: ( 1/ 1): qemu-vexpress64

Boot to userspace: multi_v7_defconfig:
    FAIL: ( 4/ 4): tegra114-dalmore-a04, tegra124-jetson-tk1,
		   tegra20-trimslice, tegra30-beaver



-------------------------------------------------------------
Branch: test_next-20151223
Test-Serial: 20151222201533
Commit-ID: 80c75a0f1d81922bf322c0634d1e1a15825a89e6
Test-Target-Board-Count: 5
Test-Boot-Count: 9
