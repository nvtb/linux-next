Tegra baseline test results for next-20160304


Here are some basic Tegra test results for Linux next-20160304.
Logs and other details at:

    https://nvtb.github.io//linux-next/test_next-20160304/20160304004534/


Test summary
------------

Build: zImage:
    FAIL: ( 1/ 2): tegra_defconfig
    Pass: ( 1/ 2): multi_v7_defconfig

Build: Image:
    Pass: ( 1/ 1): defconfig

Boot to userspace: defconfig:
    FAIL: ( 1/ 3): qemu-vexpress64
    Pass: ( 2/ 3): tegra132-norrin, tegra210-p2371-0000

Boot to userspace: multi_v7_defconfig:
    Pass: ( 4/ 4): tegra114-dalmore-a04, tegra124-jetson-tk1,
		   tegra20-trimslice, tegra30-beaver

PM: System suspend: multi_v7_defconfig:
    FAIL: ( 1/ 4): tegra114-dalmore-a04
    Pass: ( 3/ 4): tegra124-jetson-tk1, tegra20-trimslice,
		   tegra30-beaver


-------------------------------------------------------------
Branch: test_next-20160304
Test-Serial: 20160304004534
Commit-ID: d10bf08fe16c324a992e5d6318e62844d7c4312f
Test-Target-Board-Count: 5
Test-Boot-Count: 9
