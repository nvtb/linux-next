Tegra baseline test results for next-20151222


Here are some basic Tegra test results for Linux next-20151222.
Logs and other details at:

    https://nvtb.github.io//linux-next/test_next-20151222/20151221214533/


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
Branch: test_next-20151222
Test-Serial: 20151221214533
Commit-ID: 3248efff60b83f93dad704e98d80657285aa0780
Test-Target-Board-Count: 5
Test-Boot-Count: 9
