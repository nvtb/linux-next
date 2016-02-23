Tegra baseline test results for next-20160222


Here are some basic Tegra test results for Linux next-20160222.
Logs and other details at:

    https://nvtb.github.io//linux-next/test_next-20160222/20160223085626/


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

PM: System suspend: multi_v7_defconfig:
    FAIL: ( 1/ 4): tegra114-dalmore-a04
    Pass: ( 3/ 4): tegra124-jetson-tk1, tegra20-trimslice,
		   tegra30-beaver

PM: System suspend: tegra_defconfig:
    FAIL: ( 2/ 4): tegra114-dalmore-a04, tegra124-jetson-tk1
    Pass: ( 2/ 4): tegra20-trimslice, tegra30-beaver


-------------------------------------------------------------
Branch: test_next-20160222
Test-Serial: 20160223085626
Commit-ID: 1615dc93be9d922abce871a9ac589bb079247e0b
Test-Target-Board-Count: 5
Test-Boot-Count: 9
