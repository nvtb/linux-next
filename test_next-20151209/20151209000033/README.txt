Tegra baseline test results for next-20151209


Here are some basic Tegra test results for Linux next-20151209.
Logs and other details at:

    https://nvtb.github.io//linux-next/test_next-20151209/20151209000033/


Test summary
------------

Build: zImage:
    Pass: ( 2/ 2): multi_v7_defconfig, tegra_defconfig

Build: Image:
    FAIL: ( 1/ 1): defconfig

Boot to userspace: multi_v7_defconfig:
    FAIL: ( 4/ 4): tegra114-dalmore-a04, tegra124-jetson-tk1,
		   tegra20-trimslice, tegra30-beaver

Boot to userspace: tegra_defconfig:
    FAIL: ( 4/ 4): tegra114-dalmore-a04, tegra124-jetson-tk1,
		   tegra20-trimslice, tegra30-beaver



-------------------------------------------------------------
Branch: test_next-20151209
Test-Serial: 20151209000033
Commit-ID: cd1bfb776710ceffca2ca09df029f136318c5a10
Test-Target-Board-Count: 5
Test-Boot-Count: 9
