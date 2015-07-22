Tegra baseline test results for next-20150716


Here are some basic Tegra test results for Linux next-20150716.
Logs and other details at:

    https://nvtb.github.io//linux-next/test_next-20150716/20150722041533/


Test summary
------------

Build: zImage:
    Pass: ( 2/ 2): multi_v7_defconfig, tegra_defconfig

Build: Image:
    FAIL: ( 1/ 1): defconfig

Boot to userspace: multi_v7_defconfig:
    Pass: ( 4/ 4): tegra114-dalmore-a04, tegra124-jetson-tk1,
		   tegra20-trimslice, tegra30-beaver

Boot to userspace: tegra_defconfig:
    Pass: ( 4/ 4): tegra114-dalmore-a04, tegra124-jetson-tk1,
		   tegra20-trimslice, tegra30-beaver



-------------------------------------------------------------
Branch: test_next-20150716
Test-Serial: 20150722041533
Commit-ID: 6593e2dcdedd0493e1b1fcb419609d2101c4d0be
Test-Target-Board-Count: 5
Test-Boot-Count: 9
